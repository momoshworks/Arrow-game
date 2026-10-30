# 🏹 Arrow Master - 2D Archer Physics Game

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Physics](https://img.shields.io/badge/Physics-2D%20Projectile-blue?style=for-the-badge)
![Web Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Android%20WebView-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p align="center">
  <b>لعبة رماية أسهم ثنائية الأبعاد (2D Archery Game) تفاعلية وسلسة، مبنية بمحرك فيزيائي خفيف الوزن (Kinematics & Gravity) وتأثيرات صوتية ديناميكية عبر Web Audio API مع دعم اللمس لشاشات الهواتف وأجهزة أندرويد.</b>
</p>

</div>

---

## 🎯 Game Overview | نظرة عامة

**Arrow Master** هي لعبة تصويب خفيفة وسريعة، تختبر دقة وسرعة بديهة اللاعب في إصابة الأهداف المتحركة. تعتمد اللعبة على حساب زاوية وسرعة انطلاق السهم وتأثير الجاذبية الأرضية (Projectile Trajectory). تم تصميمها لتعمل بسلاسة فائقة داخل المتصفحات أو كـ Web Game مدمجة داخل تطبيقات الأندرويد (WebView / PWA).

---

## ✨ Features | المميزات الأساسية

- 🏹 **Realistic 2D Projectile Physics:** محاكاة دقيقة لحركة المقذوفات وزاوية الانحناء وتأثير قوة الشد والجاذبية.
- 🎯 **Dynamic Moving Targets:** أهداف متحركة عشوائية السرعة والاتجاه مع احتساب النقاط بناءً على حجم الهدف ودقة الإصابة.
- 📱 **Cross-Platform Touch & Mouse Controls:** دعم كامل للسحب والإطلاق عبر اللمس لشاشات الهواتف والماوس للحواسيب.
- 🔊 **Zero-Asset Web Audio Engine:** أصوات إطلاق وإصابة ونهاية اللعبة مولدة كودياً بالكامل عبر `Web Audio API` دون الحاجة لتحميل ملفات صوتية خارجية.
- 💥 **Particle Spark FX:** نظام جزيئات ديناميكي عند إصابة الأهداف لتعزيز المتعة البصرية.
- 🏆 **Local High-Score System:** حفظ أعلى رقم قياسي محلياً عبر `localStorage`.

---

## 🕹 Controls & How to Play | طريقة اللعب

1. **الشد والتصويب (Aim & Pull):** انقر مع السحب للخلف من القوس لتحديد زاوية وقوة الإطلاق.
2. **الإطلاق (Release to Shoot):** ارفع إصبعك أو زر الماوس لتحرير السهم نحو الهدف.
3. **الأهداف (Scoring):** أصب الأهداف المتحركة بأقل عدد من الأسهم لتحقيق أعلى رقم قياسي.

---

## 🛠 Tech Stack | التقنيات المستخدمة

- **Graphics:** HTML5 Canvas 2D Context (High-FPS Render Loop with `requestAnimationFrame`).
- **Logic:** Vanilla JavaScript ES6+ (Object-Oriented Entities, Particle System, Vector Math).
- **Sound:** Synthesized Web Audio API (OscillatorNode & GainNode).
- **Styling:** CSS3 Flexbox & Backdrop Filter Glassmorphism HUD.

---

## 📂 Project Structure | هيكل المشروع

```plaintext
Arrow-game/
├── index.html        # اللعبة كاملة (Canvas + Physics Engine + Audio + Controls)
├── .gitignore        # استبعاد الملفات المؤقتة
└── README.md         # التوثيق الشامل للمشروع
```

---

## 🚀 How to Run | تشغيل اللعبة

### تشغيل فوري:
افتح ملف `index.html` في أي متصفح، أو استضف المستودع مباشرة عبر **GitHub Pages**.

### تضمين داخل تطبيق Android:
يمكنك تضمين اللعبة داخل أي تطبيق أندرويد بسهولة عبر `WebView`:
```kotlin
val myWebView: WebView = findViewById(R.id.webview)
myWebView.settings.javaScriptEnabled = true
myWebView.loadUrl("file:///android_asset/index.html")
```

---

## 👨‍💻 Developer & Author

Developed with care by **[Mohamed Shaaban (momoshworks)](https://github.com/momoshworks)**.

---

## 📄 License
This project is licensed under the MIT License.
