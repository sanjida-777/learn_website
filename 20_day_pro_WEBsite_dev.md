---

## 📅 **রোডম্যাপ: ২০ দিনে ভিডিও স্ট্রিমিং সাইট**  
🔧 **লক্ষ্য:** Flask দিয়ে বানানো নিজের ভিডিও স্ট্রিমিং ওয়েবসাইট, যেখানে ইউজার ভিডিও দেখতে ও আপলোড করতে পারবে।

---

## ✅ **দিন ১-৩: Web Basics (HTML + CSS + JS)**  
🧠 **টপিক:**
- **HTML:** structure, headings, paragraph, list, image, link, video, form  
- **CSS:** color, font, spacing, layout (flexbox), responsive design  
- **JS (Basic):** variables, functions, events, DOM  

🎯 **লক্ষ্য:** একটা সুন্দর ভিডিও প্লেয়ার পেইজ বানাতে পারো

📚 **রিসোর্স:**  
- 🔗 [HTML Bangla Tutorial – Learn with Sumit](https://www.youtube.com/watch?v=ESnrn1kAD4E)  
- 🔗 [CSS Bangla Crash Course – Coder Dost](https://www.youtube.com/watch?v=Edsxf_NBFrw)  
- 🔗 [JavaScript Bangla – Anisul Islam](https://www.youtube.com/playlist?list=PLgH5QX0i9K3rG5Hu6TRuRW0meTSQW6kz-)  
- 🔗 [Flexbox Playground (Live Practice)](https://flexboxfroggy.com/)

🛠️ **প্র্যাকটিস টাস্ক:**
- ভিডিও প্লেয়ার বানাও (HTML `<video>` tag দিয়ে)
- প্লে/পজ বাটন তৈরি করো (JS দিয়ে)
- ভিডিওর নিচে টাইটেল + description দেখাও

---

## ✅ **দিন ৪-৬: Flask (Python Web Framework)**  
🧠 **টপিক:**
- Flask Setup
- Route তৈরি করা
- Template rendering (HTML ফাইল লোড)
- Static files (CSS, JS, ছবি)

📚 **রিসোর্স:**
- 🔗 [Flask Bangla Tutorial – Learn with Sumit](https://www.youtube.com/playlist?list=PLHiZ4m8vCp9PHnOIT7gd30PCBoYCpGoQM)  
- 🔗 [Official Flask Docs (for reference)](https://flask.palletsprojects.com/en/2.2.x/)

🛠️ **প্র্যাকটিস টাস্ক:**
- `/` route এ home পেইজ দেখাও
- `/watch/<video_id>` route এ ভিডিও দেখাও
- Jinja2 দিয়ে HTML-এর মধ্যে Python ডেটা দেখাও

---

## ✅ **দিন ৭-৯: Database (SQLite) শেখা ও ব্যবহার**  
🧠 **টপিক:**
- SQLite কি?
- Flask + SQLite Integration
- টেবিল তৈরি করা (videos)
- নতুন ভিডিও ইনসার্ট, ভিডিও লিস্ট বের করা

📚 **রিসোর্স:**
- 🔗 [SQLite Bangla Tutorial – Stack Learner](https://www.youtube.com/watch?v=lPtM7EJYFys)
- 🔗 [Flask SQLite Tutorial – Tech With Tim](https://www.youtube.com/watch?v=cYWiDiIUxQc)

🛠️ **প্র্যাকটিস টাস্ক:**
- ভিডিও লিস্ট DB তে রাখো (title, filename, description)
- Home পেইজে DB থেকে ভিডিও লিস্ট দেখাও
- ভিডিও page DB থেকে ডেটা লোড করে দেখাও

---

## ✅ **দিন ১০-১২: ভিডিও আপলোড + স্ট্রিমিং (Core Part)**  
🧠 **টপিক:**
- Flask দিয়ে ফাইল আপলোড করা
- আপলোড করা ভিডিও DB তে যোগ করা
- ভিডিও স্ট্রিমিং (byte range support দিয়ে)

📚 **রিসোর্স:**
- 🔗 [Flask File Upload – Corey Schafer](https://www.youtube.com/watch?v=GqHLztqy0PU)
- 🔗 [Flask Video Streaming Example – GitHub Code](https://github.com/miguelgrinberg/flask-video-streaming)

🛠️ **প্র্যাকটিস টাস্ক:**
- `/upload` route বানাও
- ফাইল আপলোড করলে ভিডিও ফোল্ডারে সেভ করো
- নতুন route বানাও `/stream/<filename>` — এখান থেকে ভিডিও stream করো (Content-Range header সহ)

---

## ✅ **দিন ১৩-১৫: UI + Extra ফিচার**  
🧠 **টপিক:**
- Bootstrap দিয়ে UI সুন্দর করা
- Responsive বানানো
- Like, View Count, Category (optional)

📚 **রিসোর্স:**
- 🔗 [Bootstrap Bangla Tutorial – Learn With Sumit](https://www.youtube.com/watch?v=gqOEoUR5RHg)
- 🔗 [Font Awesome Icons](https://fontawesome.com/)

🛠️ **প্র্যাকটিস টাস্ক:**
- Home page: থাম্বনেইল + ভিডিও নাম + বাটন
- Watch page: বড় ভিডিও + views + description
- Upload page: simple form + submit button

---

## ✅ **দিন ১৬-২০: প্রজেক্ট ফিনিশিং + হোস্টিং**  
🧠 **টপিক:**
- Bug fixing
- Code cleanup
- Hosting on shared hosting or PythonAnywhere
- Final Demo

📚 **রিসোর্স:**
- 🔗 [Deploy Flask on PythonAnywhere](https://help.pythonanywhere.com/pages/Flask/)
- 🔗 [Deploy Flask on cPanel Shared Hosting (YouTube)](https://www.youtube.com/watch?v=6rh1m5Vgk5U)

🛠️ **টাস্ক:**
- সব পেইজ টেস্ট করো
- Responsive কিনা দেখো
- ৩টা ডেমো ভিডিও দিয়ে চালিয়ে দেখো
- ফাইনালি হোস্ট করো

---

## 📦 **বোনাস ফিচার আইডিয়া (সময় থাকলে)**
- ইউজার লগইন/সাইনআপ
- ভিডিও ফিল্টার (by tag/category)
- কমেন্ট সিস্টেম
- Dark Mode

---

## 💡 পরামর্শ:
- প্রতিদিন ৫-৬ ঘণ্টা দিলে এই প্ল্যান ফলো করা সম্ভব
- যেটা শেখো সেটা দিয়ে সাথে সাথে কিছু বানাও
- দরকার হলে আমি তোমার জন্য **প্রতিদিনের কোড স্নিপেট + টাস্ক লিস্ট** বানিয়ে দিতে পারি

---
