# Turayev Lazizbek — Mobile Developer Portfolio

Senior Mobile Application Engineer (iOS & Android) portfoliosi. Ushbu loyiha App Store va Google Play do'konlarida faol bo'lgan 8 ta ishlab chiqarish (production) ilovalarini zamonaviy, interaktiv va ta'sirchan tarzda namoyish etadi.

## 📂 Loyiha Tarkibi

```bash
mobile-developer-portfolio/
├── index.html                  # Asosiy interaktiv portfolio veb-sayti
├── GITHUB_PROFILE_README.md    # GitHub bosh sahifasi (Profile README) uchun tayyor andoza
├── LINKEDIN_AND_RESUME_GUIDE.md# LinkedIn va Rezyume (CV) uchun O'zbek va Inglizcha tavsiflar
└── README.md                   # Ushbu qo'llanma
```

---

## 🚀 1. Saytni Kompyuterda Ko'rish (Lokal sinov)

Saytni ko'rish uchun hech qanday qo'shimcha paketlar o'rnatish shart emas. Shunchaki:

```bash
cd /Users/macbookpro/.gemini/antigravity/scratch/mobile-developer-portfolio
python3 -m http.server 8000
```
So'ng brauzerda oching: **`http://localhost:8000`**

---

## 🌐 2. Saytni Bepul Internetga Joylash (Deployment)

### Variant A: GitHub Pages orqali (Tavsiya etiladi)

1. GitHub'da yangi repozitoriy yarating (masalan, `portfolio` yoki `username.github.io`).
2. Loyiha papkasida terminalni ochib, quyidagi buyruqlarni bajaring:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/Lazizbek6766/portfolio.git
   git push -u origin main
   ```
3. GitHub repozitoriyangiz sahifasida:
   - **Settings** bo'limiga o'ting.
   - Chap tomondagi **Pages** tugmasini bosing.
   - **Branch:** `main` va papka sifatida `/(root)` ni tanlab **Save** tugmasini bosing.
4. 1 daqiqadan so'ng saytingiz jonli efirda bo'ladi: `https://Lazizbek6766.github.io/portfolio/`

---

### Variant B: Vercel orqali (1 daqiqada)

1. [vercel.com](https://vercel.com) saytiga GitHub orqali kiring.
2. **Add New...** -> **Project** tugmasini bosing.
3. Yangi ochilgan GitHub repozitoriyangizni tanlang va **Deploy** tugmasini bosing.
4. Vercel sizga darhol bepul `.vercel.app` domenini beradi.

---

### Variant C: Netlify orqali

1. [netlify.com](https://netlify.com) saytiga kiring.
2. Ushbu `mobile-developer-portfolio` papkasini Netlify saytidagi **"Drag and drop your site folder here"** maydoniga tashlang.
3. Sayt soniyalar ichida jonli ishlay boshlaydi!

---

## 📝 3. Shaxsiy Ma'lumotlarni Sozlash

`index.html` faylida quyidagi joylarni o'zingizning aniq manzillaringiz bilan yangilashingiz mumkin:
- Telegram linki (`https://t.me/your_username`)
- LinkedIn linki (`https://linkedin.com/in/your_profile`)
- GitHub linki (`https://github.com/Lazizbek6766`)
- Email manzili (`lazizbek.developer@example.com`)
