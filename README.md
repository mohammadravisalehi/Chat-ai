<! DOCTYPE html>
<شبنم lang="fa">
<سر>
 <متا charset="UTF-8"> 
     <عنوان>چت با هوش مصنوعی</عنوان> 
     <سبک> 
 بدن { پس-رنگ: #1212; رنگ: #ffffff; font-family: Arial, sans-serif; متن-align: مرکز; } 
 .chat-box { عرض: ۸۰٪؛ max-width: 600px; ارتفاع: 400px; مرز: 1px جامد #333; padding: 10px; overflow-y: خودکار؛ پس-رنگ: #222; حاشیه: خودرو؛ خط خط: مرز-radius: 5px; } 
 #user-input { عرض: 70%; padding: 10px; مرز: 1px جامد #555; پس-رنگ: #222; رنگ: #fff; مرز-radius: 5px; } 
 دکمه { pading: 10px؛ مرز: نه؛ پس زمینه-رنگ: #6200ea؛ رنگ: #ffffff؛ cursor: pointer؛ مرز-radius: 5px; } 
 button:در حال پرواز   { background-color: #3700b3; } 
 .message { پس-رنگ: #333; padding: 8px; حاشیه: 5px 0; مرز-radius: 5px; عرض: مناسب، max-width: 80%; } 
 .ai-message { پیشینه-رنگ: #057e7; متن-align: چپ; } 
     </سبک> 
</سر>
<بدن>

    <h2>چت با هوش مصنوعی</h2>
    <div class="chat-box" id="chat-box"></div>
    <input type="text" id="user-input" placeholder="پیام خود را بنویسید...">
    <button onclick="sendMessage()">ارسال</button>

    <script>
     تابع ارسال پیام () { 
     const ورودی = سند.getElementById('user-input); 
     const ChatBox = document.getElementById('chat-box); 

     اگر (input.value.trim() { 
     به صورت userMessage = سند.createElement('div"; 
     userMessage.classList.add('message) ; 
     userMessage.textContent = input.value; 
     ChatBox.appendChild (userMessage); 

     setTimeout(() => { 
     const aiMessage = document.createElement('div) ; 
     aiMessage.classList.add('message" ، "ai-message"; 
     aiMessage.textContent = "پاسخ هوش مصنوعی: " + generateAIResponse (input.value); 
     ChatBox.appendChild (aiMessage); 
     chatBox.scrollTop = chatBox.scrollHeight; 
                 }, 1000); 

     ورودی.ارزش = ; 
             } 
         } 

     عملکرد generateAIResponse (userText) { 
              const responses = ["سلام! چطور می‌توانم کمک کنم؟", "جالب است! بیشتر توضیح بدهید.", "به نظر موضوع مهمی می‌آید."];  
     پاسخ های بازگشت (Math.floor (Math.random() * پاسخ.طول)); 
         } 
    </script>

</بدن>
#  چت-ای
