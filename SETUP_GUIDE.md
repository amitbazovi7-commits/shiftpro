# 📱 ShiftPro — מדריך הגדרה ב-GitHub Pages

## מה תקבל בסוף?
אפליקציית PWA מלאה שרצה מהאינטרנט, ניתנת להתקנה על iPhone/Android כאפליקציית מסך הבית, עם שמירת נתונים מקומית ותמיכה אופליין.

---

## שלב 1 — יצירת חשבון GitHub (חינם)

1. גש ל-[github.com](https://github.com)
2. לחץ **Sign Up**
3. הירשם עם מייל וסיסמה (חינמי לחלוטין)

---

## שלב 2 — יצירת Repository חדש

1. לאחר הכניסה, לחץ **＋ → New repository**
2. **Repository name:** `shiftpro` (חשוב: אותיות קטנות)
3. **Public** ✅ (חייב להיות Public עבור GitHub Pages חינמי)
4. אל תסמן שום דבר אחר
5. לחץ **Create repository**

---

## שלב 3 — העלאת הקבצים

### דרך א' — ממשק אינטרנט (הכי קל)

1. בדף ה-repository החדש, לחץ **uploading an existing file**
2. גרור את כל הקבצים הבאים:
   ```
   📄 index.html
   📄 manifest.json
   📄 sw.js
   📁 icons/
       📄 icon-192.svg
       📄 icon-512.svg
   ```
3. בתחתית הדף, לחץ **Commit changes**

---

## שלב 4 — הפעלת GitHub Pages

1. בדף ה-repository, לחץ **Settings** (גלגל שיניים)
2. בתפריט הצד, לחץ **Pages**
3. תחת **Source**, בחר **Deploy from a branch**
4. תחת **Branch**, בחר **main** (או **master**)
5. לחץ **Save**

⏳ **המתן 2-3 דקות**

---

## שלב 5 — קבלת הקישור

לאחר כמה דקות, ב-Settings → Pages תראה:

```
✅ Your site is live at:
https://YOUR_USERNAME.github.io/shiftpro/
```

**זה הקישור לאפליקציה שלך!**

---

## שלב 6 — התקנה על iPhone 📱

1. פתח **Safari** (חשוב — לא Chrome!)
2. גש לכתובת: `https://YOUR_USERNAME.github.io/shiftpro/`
3. לחץ על כפתור **שתף** ⬆️ (בתחתית המסך)
4. גלול מטה ולחץ **"הוסף למסך הבית"**
5. תן שם (ShiftPro) ולחץ **הוסף**

✅ האפליקציה תופיע על מסך הבית שלך כאייקון רגיל!

---

## שלב 7 — עדכון הנתונים

כל הנתונים (משמרות, שכר, הגדרות) נשמרים **על המכשיר שלך** ב-localStorage.
הנתונים **לא** נשמרים ב-GitHub ולא נשלחים לשרת.

אם תרצה לגבות — השתמש בייצוא Excel בתוך האפליקציה.

---

## שאלות נפוצות

**האם זה בטוח?**
כן. כל הנתונים נשמרים רק על המכשיר שלך.

**האם האפליקציה עובדת ללא אינטרנט?**
כן! לאחר ביקור ראשון, כל הקבצים נשמרים במכשיר (Service Worker).

**האם ניתן להשתמש ממספר מכשירים?**
הנתונים נשמרים בכל מכשיר בנפרד. לסינכרון בין מכשירים נדרש פיתוח נוסף.

**כמה עולה?**
אפס. GitHub Pages חינמי לחלוטין.

---

## קישורים מהירים

- GitHub: [github.com](https://github.com)
- GitHub Pages Docs: [pages.github.com](https://pages.github.com)
