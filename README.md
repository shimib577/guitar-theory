# 🎸 Liran's Guitar Theory Master

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![PWA](https://img.shields.io/badge/PWA-enabled-orange.svg)

**כלי לימוד גיטרה מקצועי ואינטראקטיבי** עם אקורדים, סולמות, פרוגרסיות, מטרונום ו-Tonnetz.

נבנה על ידי **Liran Lin** 🎸

---

## ✨ תכונות

### 🎸 אקורדים
- **120+ אקורדים** - כל 12 התווים × 10+ סוגים
- **4 פוזיציות** שונות לכל אקורד
- **ניגון תווים** - לחץ על כל נקודה
- **דיאגרמות מקצועיות** עם צבעי אצבעות
- **מספרי שריגים** ברורים
- **הצגה על צוואר הגיטרה**

### 🎵 סולמות
- **15+ סולמות**:
  - בסיסי: Major, Minor, Harmonic, Melodic
  - פנטטוני: Major, Minor, Blues
  - Modes: Dorian, Phrygian, Lydian, Mixolydian
  - אקזוטי: Spanish, Gypsy, Arabic, Japanese
- **ניגון תווים** על כל הצוואר
- **הדגשת תו יסוד**

### ⭕ מעגל חמישיות
- **12 תווים** באינטרפייס אינטראקטיבי
- **ניגון תווים** בלחיצה
- **הסבר מפורט** על קשרים הרמוניים

### 🎼 פרוגרסיות אקורדים
- **5 פרוגרסיות נפוצות**
- **דינמיות** - משתנות לפי תו היסוד שנבחר
- I-IV-V (בלוז/רוק)
- I-V-vi-IV (פופ - הפופולרית ביותר!)
- ii-V-I (ג'אז)
- I-vi-IV-V (50s דו-ווּפ)
- vi-IV-I-V (רוק מודרני)

### 🥁 מטרונום מקצועי
- **BPM:** 40-240
- **Tap Tempo** - הקש 4 פעמים לחישוב BPM
- **ויזואליזציה** - 4 אינדיקטורים מהבהבים
- **סאונד מדויק** - Web Audio API

### 🔷 Tonnetz
- **רשת קשרים הרמוניים** הקסגונלית
- **הדגשת אקורד** נוכחי
- **ניגון תווים** בלחיצה
- **הסבר מלא** על המבנה המתמטי

### 🌙 Dark Mode
- **מצב כהה מושלם** (ברירת מחדל)
- **מצב בהיר** - החלפה בכפתור אחד
- **צבעים מותאמים** לכל מצב

### 📱 PWA - Progressive Web App
- **התקנה כאפליקציה** - עובד כמו אפליקציה אמיתית
- **עבודה אופליין** - אחרי התקנה ראשונה
- **מהיר** - ללא טעינות
- **רספונסיבי 100%** - מובייל, טאבלט, מחשב

---

## 🚀 התקנה והפעלה

### אפשרות 1: שימוש ישיר
1. פתח את `guitar-final.html` בדפדפן
2. זהו! האפליקציה עובדת מיידית

### אפשרות 2: GitHub Pages (מומלץ!)

#### שלבים:
1. **Fork** את הריפוזיטורי
2. לך ל-**Settings** → **Pages**
3. בחר **Source**: `Deploy from a branch`
4. בחר **Branch**: `main` (או `master`)
5. לחץ **Save**
6. אחרי דקה תקבל קישור:
   ```
   https://[username].github.io/[repository-name]/guitar-final.html
   ```

#### התקנה כאפליקציה באנדרויד:
1. פתח את הקישור ב-**Chrome** בטלפון
2. תקפוץ הודעה: **"📱 התקן כאפליקציה"**
3. לחץ עליה!
4. האפליקציה תותקן בטלפון 🎉

### אפשרות 3: Netlify / Vercel (חינם)

#### Netlify:
1. לך ל-[netlify.com](https://netlify.com)
2. גרור את התיקייה
3. קבל קישור מיידי!

#### Vercel:
1. לך ל-[vercel.com](https://vercel.com)
2. חבר GitHub
3. Deploy!

---

## 📂 מבנה הקבצים

```
📁 guitar-theory-master/
├── 📄 guitar-final.html    # האפליקציה הראשית
├── 📄 manifest.json         # הגדרות PWA
├── 📄 sw.js                 # Service Worker
├── 📄 README.md             # מדריך זה
└── 🖼️ icons/                # אייקונים (אופציונלי)
```

---

## 🎯 דרישות

### דפדפנים נתמכים:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Chrome Android 90+
- ✅ Safari iOS 14+

### דרישות מערכת:
- ❌ **אין!** עובד ישירות בדפדפן
- ❌ לא צריך התקנה
- ❌ לא צריך Node.js / npm
- ❌ לא צריך שרת

---

## 📱 התקנה באנדרויד - מדריך מפורט

### שיטה 1: PWA (מומלץ!)

1. **העלה ל-GitHub Pages**
   ```bash
   git clone [your-repo]
   cd guitar-theory-master
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **הפעל GitHub Pages**
   - Settings → Pages → Source → main
   - חכה דקה
   - קבל קישור

3. **התקן בטלפון**
   - פתח ב-Chrome בטלפון
   - לחץ על כפתור "התקן"
   - תופיע אייקון באפליקציות!

### שיטה 2: APK Builder

אתרים שהופכים HTML ל-APK:
- [AppsGeyser](https://appsgeyser.com) - חינם
- [WebIntoApp](https://webintoapp.com)
- [Gonative](https://gonative.io)

---

## 🎓 איך להשתמש

### לימוד אקורד:
1. בחר תו יסוד (למשל C)
2. בחר סוג אקורד (Major)
3. הזז סליידר לראות 4 פוזיציות
4. לחץ על נקודות כדי לשמוע תווים

### לימוד סולם:
1. בחר "🎵 סולמות"
2. בחר תו וסולם
3. ראה על כל הצוואר
4. לחץ על תווים לניגון

### תרגול עם מטרונום:
1. בחר "🥁 מטרונום"
2. הזז ל-BPM רצוי
3. לחץ "התחל"
4. תרגל!

---

## 🛠️ טכנולוגיות

- **HTML5** - מבנה
- **CSS3** - עיצוב ואנימציות
- **JavaScript (ES6+)** - לוגיקה
- **Web Audio API** - סאונד
- **Service Workers** - PWA
- **LocalStorage** - שמירת העדפות

---

## 📊 מה בקרוב?

- [ ] אימון אוזן (Ear Training)
- [ ] ספריית שירים
- [ ] הקלטת לופים
- [ ] תמיכה ב-MIDI
- [ ] שיתוף פרוגרסיות
- [ ] רשימת מועדפים

---

## 🤝 תרומה

רוצה לתרום? מעולה!

1. Fork את הפרויקט
2. צור branch חדש (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add some AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. פתח Pull Request

---

## 📝 רישיון

MIT License - חופשי לשימוש, שינוי והפצה.

---

## 👨‍💻 יוצר

**Liran Lin**

נבנה ב-❤️ עבור למדני גיטרה בכל העולם 🎸🌍

---

## 📞 צור קשר

יש שאלות? רעיונות? באגים?

פתח **Issue** בגיטהאב!

---

## ⭐ תמיכה

אהבת את הפרויקט? תן ⭐ בגיטהאב!

---

**🎸 Happy Playing! 🎸**
