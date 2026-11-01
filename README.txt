English fun — העלאה לאתר ציבורי וגוגל
========================================

בתיקייה הזאת:
  index.html    — האתר (קובץ ראשי)
  icon512.png   — הלוגו
  robots.txt    — מרשה לגוגל לסרוק
  sitemap.xml   — מפת האתר לגוגל

שלב 1 — להעלות לאירוח חינמי (בוחרים אחד):

  Netlify Drop (הכי קל):
   1. נכנסים ל-  https://app.netlify.com/drop
   2. גוררים את כל התיקייה הזאת לתוך הדף
   3. מקבלים כתובת ציבורית, למשל  english-fun.netlify.app

  GitHub Pages:
   1. פותחים repository חדש וציבורי ב-GitHub
   2. מעלים את ארבעת הקבצים
   3. Settings → Pages → Branch: main → Save
   4. הכתובת תהיה  https://<שם-משתמש>.github.io/<שם-repo>/

שלב 2 — לעדכן את הכתובת בקבצים:
   בקבצים index.html, robots.txt, sitemap.xml יש שלוש פעמים
   את הטקסט  REPLACE-WITH-YOUR-URL
   מחליפים אותו בכתובת האמיתית שקיבלתם בשלב 1, ומעלים שוב.

שלב 3 — להגיש לגוגל:
   1. נכנסים ל-  https://search.google.com/search-console
   2. מוסיפים את הכתובת (URL prefix)
   3. מאמתים בעלות (לרוב בהעלאת קובץ קטן שגוגל נותן)
   4. Sitemaps → מגישים  sitemap.xml
   5. URL Inspection → Request indexing

אחרי כמה ימים עד שבועות גוגל יסרוק, והאתר יהיה ניתן למציאה בחיפוש.
