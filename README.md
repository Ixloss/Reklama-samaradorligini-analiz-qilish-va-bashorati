# Reklama-samaradorligini-analiz-qilish-va-bashorati
# Reklama Samaradorligini Bashorat Qilish va Analitika Dashboardi

Ushbu loyiha turli reklama kanallari (TV, Radio, Gazeta) uchun ajratilgan budjetlarning umumiy savdo hajmini (Sales) oshirishdagi samaradorligini tahlil qilish va chiziqli regressiya (Linear Regression) modeli yordamida kelgusi sotuvlarni bashorat qilish uchun ishlab chiqilgan.

---

## 📊 Loyiha Haqida Dynamic Dashboard

<img width="1589" height="1145" alt="Dashboard.png" src="https://github.com/user-attachments/assets/43487f26-3dcd-49c6-9ef4-b9bfafaff1ab" />


Dashboard o'z ichiga quyidagi muhim biznes va texnik tahlillarni oladi:
1. Belgilar orasidagi korrelatsiya (Correlation Matrix): Qaysi reklama kanali savdoga eng kuchli ta'sir qilayotganini aniqlash.
2. TV xarajatlari va Sotuv (Sales) munosabati: Haqiqiy ma'lumotlar va model chizgan Regressiya chizig'ining o'zaro mosligi.
3. Qoldiqlar tahlili (Residuals Plot): Model xatoliklarining taqsimoti va barqarorligini tekshirish.

---

## 🛠 Ishlatilgan Texnologiyalar va Kutubxonalar

*   Python — Asosiy dasturlash tili
*   Pandas & NumPy — Ma'lumotlarni tozalash va tahlil qilish (Data Wrangling)
*   Scikit-Learn — Chiziqli regressiya modelini qurish va baholash
*   Matplotlib & Seaborn — Professional analitik vizualizatsiya va grafiklar

---

## 📈 Biznes Xulosalar (Actionable Insights)

*   TV Reklama Ustunligi: TV reklama xarajatlari sotuvga eng yuqori ijobiy ta'sir ko'rsatuvchi omil hisoblanadi (Korrelatsiya koeffitsiyenti: $r = 0.901$). Marketing budjetini optimallashtirishda asosiy e'tiborni TV kanallariga qaratish tavsiya etiladi.
*   Radio va Gazeta samaradorligi: Radio ($r = 0.350$) va Gazeta ($r = 0.158$) kanallarining sotuvga ta'sir darajasi ancha past. Ushbu kanallarga ajratilayotgan budjet qayta ko'rib chiqilishi kerak.

---

## 🔬 Model Metriklari va Baholash

Model ma'lumotlarni o'rganib, quyidagi aniqlik ko'rsatkichlarini qayd etdi:

*   Mean Absolute Error (MAE): 1.9503 (Model o'rtacha ~1.95 birlik xatolik bilan ishlamoqda)
*   Root Mean Squared Error (RMSE): 2.4700

---

## 🚀 Loyihani Ishga Tushirish

1. Repozitoriyani yuklab oling:
   `bash
   git clone [https://github.com/SizningProfile/repo-nomi.git](https://github.com/Ixloss/Reklama-samaradorligi-analizi-va-bashorati.git)
