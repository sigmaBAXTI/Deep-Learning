# 🔁 RNN bilan vaqt qatorlarini tahlil qilish

## 📘 Loyihaning maqsadi
Ushbu loyiha **Rekurrent Neyron Tarmoq (RNN)** yordamida **vaqt qatorlari (Time Series)** ma’lumotlarini tahlil qilish va bashorat qilishga qaratilgan.  
Model vaqt bo‘yicha ketma-ket ma’lumotlardan o‘rganib, kelajakdagi qiymatlarni oldindan taxmin qiladi.

---

## 🧩 Asosiy bosqichlar
1. **Ma’lumotlarni tayyorlash**  
   - Time Series (vaqt qatori) ma’lumotlarini yuklash  
   - Normalizatsiya (MinMaxScaler yoki StandartScaler)  
   - Ketma-ketliklarga bo‘lish (X, y juftliklari)

2. **Model yaratish**  
   - PyTorch yordamida **RNN (Recurrent Neural Network)** arxitekturasi  
   - `nn.RNN` yoki `nn.LSTM` qatlamlaridan foydalanish  
   - Faollashtirish funksiyasi sifatida **tanh** yoki **ReLU**  
   - Chiqish qatlamida regression natija (bashorat) olish

3. **Modelni o‘qitish**  
   - Yo‘qotish funksiyasi: `MSELoss()`  
   - Optimallashtiruvchi: `Adam`  
   - Epoch davomida `loss` qiymatini kuzatish

4. **Natijalarni tahlil qilish**  
   - Real qiymatlar va bashorat qilingan qiymatlarni chizish  
   - `matplotlib` yordamida vizual tahlil  
   - Modelning bashorat aniqligini baholash

---

## 🧰 Foydalanilgan texnologiyalar
| Texnologiya | Tavsif |
|--------------|--------|
| **Python 3.10+** | Asosiy dasturlash muhiti |
| **PyTorch** | Modelni qurish va o‘qitish uchun |
| **NumPy** | Ma’lumotlar ustida hisoblashlar uchun |
| **Matplotlib** | Grafik vizualizatsiya uchun |
| **scikit-learn** | Normalizatsiya va baholash uchun |

---

## 🚀 O‘rnatish va ishga tushirish

### 1. Repository’ni klonlash
```bash
git clone https://github.com/yourusername/RNN-TimeSeries.git
cd RNN-TimeSeries
