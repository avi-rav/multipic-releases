<div dir="rtl">

# MultiPic

**סדר בספריית התמונות, הסרטונים והמוזיקה שלך: מוצאת קבצים כפולים, תמונות דומות ומיותרות, ומאפשרת לפנות מקום בבטחה.**

**[⬇ הורדת MultiPic (חינם, ל-Windows)](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe)**

> 🔒 **עובדת בלי אינטרנט.** הקבצים שלך לא יוצאים מהמחשב, ושום מידע לא נשלח לשום מקום.
>
> 🧮 **איתור כפילויות בלי בינה מלאכותית (AI).** כל השוואה, סינון והמלצה מבוססים על חישובים קבועים ושקופים: השוואה של תוכן הקבצים, הפיקסלים והצליל, תאריך, מיקום, גודל וחדות. אין "ניחושים" של מודל, ואותה תיקייה תיתן תמיד את אותן תוצאות. החריג היחיד הוא סינון הגלריה לפי אדם: הוא מפעיל במחשב שלך שני מודלים קטנים של זיהוי פנים, ורק כשתבקש.
>
> 🗑 **שום דבר לא נמחק בלי אישור שלך.** והמחיקה היא לסל המיחזור, כך שאפשר להתחרט.
>
> 🪟 **נפתחת בחלון משלה,** כמו כל תוכנה רגילה, ולא בדפדפן.

> [!WARNING]
> **⚠ חשוב: לפני שמוחקים, שים לב**
>
> - **בדוק היטב מה מסומן למחיקה לפני כל אישור.** התוכנה מציעה, אבל ההחלטה והאחריות שלך. היא בוחרת איזה עותק לשמור לפי כללים טכניים (רזולוציה, איכות, גודל, נתיב), ולא יודעת איזו תיקייה חשובה לך.
> - **אל תמחק את העותקים שבתיקיות המסודרות ותשאיר את הקבצים בתפזורת.** אם אותה תמונה נמצאת גם באלבום מסודר וגם בתיקייה כמו "הורדות", ודא שהעותק שנמחק הוא זה שבתפזורת.
> - **אל תמחק תיקיית גיבוי שאתה רוצה לשמור כגיבוי.** מבחינת התוכנה, עותק בגיבוי הוא כפילות כמו כל כפילות אחרת. הדרך הבטוחה ביותר היא לא לסרוק את תיקיית הגיבוי בכלל.
> - **השימוש בתוכנה הוא על אחריות המשתמש בלבד.** היוצר לא אחראי לשום נזק, כולל אובדן קבצים, שייגרם מהשימוש בה. מומלץ לגבות את הקבצים לפני מחיקה בכמות גדולה.

## למי זה מתאים

לכל מי שיש לו במחשב הרבה תמונות, סרטונים ושירים שהצטברו עם השנים: גיבויים שהועתקו פעמיים, קבצים מהטלפון שהורדו כמה פעמים, אותה תמונה בגדלים שונים, אותו סרטון שנשלח שוב בוואטסאפ, אותו שיר ב-MP3 וב-FLAC, ותיקיות שכבר לא ברור מה יש בהן. לא צריך ידע טכני.

## איך זה עובד

1. **בוחרים תיקייה** (למשל "תמונות" או כל התיקייה האישית), מסמנים מה לסרוק (תמונות, סרטונים, מוזיקה) ולוחצים "סרוק". התוכנה רק קוראת את הקבצים ולא משנה בהם כלום.
2. **עוברים על מה שהיא מצאה.** לכל סוג יש לשונית משלו: תמונות, סרטונים ומוזיקה. כל התוצאות מוצגות עם תמונות ממוזערות, ואפשר לצפות בסרטונים ולהאזין לשירים, כדי שתראה ותשמע מה מוצע.
3. **מאשרים** מה למחוק. רק אז הקבצים עוברים לסל המיחזור.

## מה התוכנה יודעת לעשות

### תמונות כפולות
מוצאת את אותה תמונה גם כשהיא בשם אחר או בתיקייה אחרת. ההתאמות מחולקות לפי רמת ודאות:

| רמה | מה זה | מה התוכנה עושה |
|---|---|---|
| **זהות** | אותו קובץ בדיוק | מסמנת את העותקים המיותרים, ומשאירה את הטוב ביותר |
| **אותה תמונה, פרטים שונים** | אותה תמונה בדיוק, אבל עם תאריך, מיקום או פורמט אחר | כנ"ל |
| **כמעט זהות** | אותה תמונה בגודל או באיכות אחרת | מציגה, ואתה מחליט |
| **דומות** | למשל כמה צילומים ברצף של אותו רגע | מציגה להשוואה בלבד |

בכל קבוצה התוכנה ממליצה איזה עותק לשמור (הגדול והאיכותי ביותר), ואפשר לבחור אחר.

### סרטונים כפולים
מוצאת את אותו סרטון גם בשם אחר, בתיקייה אחרת או בקידוד אחר:

| רמה | מה זה | לפי מה משווים | מה התוכנה עושה |
|---|---|---|---|
| **זהים** | אותו קובץ בדיוק | טביעת אצבע (SHA-256) של כל תוכן הקובץ. רגע לפני מחיקה הקובץ מושווה שוב, בית אחר בית, לעותק שנשאר | מסמנת את העותקים המיותרים, ומשאירה את הטוב ביותר |
| **אותו סרטון, קידוד שונה** | אותו סרטון ברזולוציה, דחיסה או פורמט אחר, למשל עותק שנשלח בוואטסאפ | 20 תמונות שנדגמות לאורך הסרטון ומושוות חזותית, וגם אורך הסרטון ויחס הגובה-רוחב | מציגה, ואתה מחליט. שום דבר לא מסומן מראש |

ברמה "אותו סרטון", שני סרטונים נחשבים אותו סרטון רק כשכל התנאים מתקיימים: האורך שונה בשנייה לכל היותר (או ב-1% בסרטון ארוך), יחס הגובה-רוחב כמעט זהה, ולפחות 80% מהתמונות שנדגמו תואמות. תמונות שחורות או אחידות, כמו מעבר בין סצנות, לא נספרות. אפשר לצפות בכל העותקים זה לצד זה, והפרמטרים המלאים מופיעים בתוכנה, בהגדרות > פרטים טכניים.

> ⚠ **ברמה "אותו סרטון" כדאי לצפות בסרטונים לפני מחיקה.** הפסקול לא נבדק, וגם לא מה שבין התמונות שנדגמו. לכן סרטון עם דיבוב או מוזיקה אחרים, או סרטון שהוחלף בו קטע קצר, עלול להיראות כמו אותו סרטון.

### מוזיקה כפולה
מוצאת את אותו שיר גם בשם אחר, בתיקייה אחרת, עם תגיות אחרות או בפורמט אחר:

| רמה | מה זה | לפי מה משווים | מה התוכנה עושה |
|---|---|---|---|
| **זהים** | אותו קובץ בדיוק | טביעת אצבע (SHA-256) של כל תוכן הקובץ. רגע לפני מחיקה הקובץ מושווה שוב, בית אחר בית, לעותק שנשאר | מסמנת את העותקים המיותרים, ומשאירה את הטוב ביותר |
| **אותו שמע, תגיות שונות** | הצליל זהה לחלוטין, ורק שם השיר, האמן, העטיפה או שם הקובץ שונים | טביעת אצבע של נתוני השמע בלבד, בלי התגיות והעטיפה. רגע לפני מחיקה היא מחושבת שוב לשני הקבצים | מסמנת, וממליצה לשמור את העותק שהתגיות שלו מלאות יותר |
| **אותו שיר** | אותו שיר בפורמט, באיכות או בקידוד אחר | אותו אמן ואותו שם שיר והפרש אורך של עד 2 שניות. לקובץ בלי תגיות: אותו שם קובץ והפרש של עד שנייה | מציגה, ואתה מחליט. שום דבר לא מסומן מראש |

בכל קבוצה התוכנה ממליצה איזה עותק לשמור: קודם קובץ ללא אובדן (FLAC, WAV), אחר כך קצב הסיביות הגבוה יותר. שיר שמופיע ביותר מאלבום אחד מסומן, כדי שמחיקה לא תשאיר אלבום חסר. הפרמטרים המלאים מופיעים בתוכנה, בהגדרות > פרטים טכניים.

> ⚠ **ברמה "אותו שיר" כדאי להאזין לפני מחיקה.** ההשוואה היא לפי התגיות והאורך, והצליל עצמו לא נבדק. לכן הקלטה אחרת של אותו שיר (הופעה חיה או רימאסטר) באורך כמעט זהה עלולה להיראות כמו אותו שיר.

### תיקיות כפולות
מוצאת תיקיות שהתמונות שבהן כבר קיימות בתיקייה אחרת, למשל גיבוי ישן. אפשר לנקות תיקייה כזאת בלחיצה: נמחקות רק תמונות שיש להן עותק זהה בתיקייה השנייה, ותמונות שאין להן עותק נשארות (או מועברות לתיקייה השנייה, אם תבחר בכך).

### תמונות מיותרות
רשימות לבדיקה: תמונות **מטושטשות**, **צילומי מסך**, ותמונות **קטנות מאוד**. שום דבר לא מסומן מראש.

### קבצים פגומים
לכל סוג רשימה משלו: תמונות שלא נפתחות או נפתחות רק בחלקן (וכשאפשר, הצעה של עותק תקין שלהן), סרטונים שלא ניתן היה לנתח, וקובצי מוזיקה שלא ניתן היה לקרוא.

### גלריה
כל התמונות במקום אחד, ובלשונית נפרדת כל הסרטונים, ממוינים לפי תאריך הצילום מהחדש לישן. אפשר לסנן לפי **שנה וחודש**, **טווח תאריכים**, **מדינה ועיר** (לפי מיקום הצילום) ו**תיקייה**. אפשר לסמן תמונות וסרטונים (גם טווח שלם עם Shift) ולמחוק אותם, או להעביר ולהעתיק אותם לתיקייה, למשל כדי ליצור אלבום. סרטון אפשר גם לנגן ישר מהגלריה.

- **תאריך ומקום של סרטונים:** נקראים מתוך קובצי MP4, MOV, M4V ו-3GP, כמו שהם נשמרים בטלפוני אנדרואיד ובאייפון. כשאין בסרטון תאריך צילום, מוצג תאריך הקובץ, מסומן ב-~.
- **סרטונים מוואטסאפ:** וואטסאפ מוחקת מהסרטון את תאריך הצילום ואת המיקום, ולכן התאריך שלו הוא בדרך כלל מועד השליחה, ואין לו מקום.
- **בלי תאריך:** לתמונות ולסרטונים שאין להם תאריך יש אפשרות משלהם בסינון, "ללא תאריך".

### אנשים בתמונות
אפשר לסנן את גלריית התמונות לפי **אדם**. בחלון "אנשים…" לוחצים "חפש פנים בתמונות": התוכנה מוצאת את הפנים בתמונות ומקבצת פנים דומות לאדם אחד. החיפוש עובר על כל התמונות ולכן לוקח זמן, ואפשר לעצור אותו ולהמשיך אחר כך.

- **הכול במחשב שלך:** הזיהוי נעשה בשני מודלים קטנים שמותקנים עם התוכנה, בלי אינטרנט. הוא רץ רק כשמבקשים, ואפשר למחוק את כל נתוני הפנים בכל עת.
- **שמות ומיזוג:** נותנים שם לכל אדם, ואם אותו אדם זוהה כשני אנשים, ממזגים אותם. בשדה "אדם" בגלריה אפשר גם להקליד כדי לחפש.
- **תיקון טעויות:** מעבירים פנים לאדם אחר, לאדם חדש, או לאדם חדש בשם שמקלידים במקום. מה שזוהה ואינו פנים כלל אפשר להסיר. תמונה שמופיעה אצל אדם שלא נמצא בה מתקנים ישר מהגלריה, ומסגרת מסמנת על אילו פנים מדובר.
- **אפשר לבטל:** אחרי כל תיקון יש כפתור "בטל", ופנים שהוסרו בטעות אפשר להחזיר אחר כך.

> ⚠ **הקיבוץ לאנשים הוא הערכה.** כדאי לעבור על הרשימה, לתת שמות ולמזג. זיהוי הפנים אף פעם לא משנה או מוחק תמונות.

### ספריית מוזיקה
כל השירים ברשימה אחת, עם חיפוש לפי שם שיר, אמן, אלבום או שם קובץ, וסינון לפי **אמן**, **אלבום**, **ז'אנר**, **שנה**, **פורמט**, **איכות**, **אורך** ו**תיקייה**. לחיצה על שיר מנגנת אותו בנגן שבתחתית החלון, והנגן ממשיך לנגן גם כשעוברים ללשונית אחרת. אפשר לסמן שירים ולמחוק אותם, או להעביר ולהעתיק אותם לתיקייה. שירים בלי תגיות אפשר להציג לבד, כדי לסדר אותם.

### ועוד
- **יומן מחיקות:** כל מה שנמחק נרשם, עם המקום שבו הוא היה והעותק שנשאר. אפשר לייצא לאקסל (CSV).
- **סריקה חוזרת מהירה:** בפעם הבאה נבדקים רק קבצים חדשים או כאלה שהשתנו.
- **עברית ואנגלית.**
- **בוחרים מה לסרוק:** תמונות, סרטונים ומוזיקה, בכל צירוף.
- סוגי קבצים: תמונות JPG, PNG, HEIC (אייפון), WEBP, GIF, BMP, TIFF. סרטונים MP4, MOV, M4V, AVI, MKV, WMV, 3GP, MTS, M2TS, MPG, MPEG, WEBM. מוזיקה MP3, FLAC, M4A, AAC, WAV, OGG, OPUS, WMA, AIFF.

## בטיחות

- **תמיד נשאר עותק אחד לפחות** מכל קובץ כפול.
- רגע לפני מחיקה, התוכנה בודקת שוב שהקובץ לא השתנה ושהעותק שנשאר באמת קיים. אם משהו לא תואם, הקובץ לא נמחק.
- בכונן שאין בו סל מיחזור (למשל דיסק-און-קי או כונן רשת) התוכנה עוצרת ושואלת מה לעשות.
- **קבצים של תוכנות לא נסרקים.** תיקיות של Windows ושל תוכנות (כמו AppData ו-Program Files), תיקיות מוסתרות, תיקיות שמותקנת בהן תוכנה ופרויקטים של קוד לא נסרקים, כדי שלא יוצעו למחיקה צלילים, סמלים ותמונות שתוכנות צריכות. גם תיקיות זמניות (Temp) לא נסרקות, אלא אם תבקש. בסוף הסריקה מוצגת רשימה של מה שלא נסרק.
- **קבצים שנמצאים רק בענן** (OneDrive, Dropbox, iCloud): סריקה שלהם מורידה אותם למחשב, ולכן התוכנה עוצרת ושואלת קודם, ומראה כמה מקום הם יתפסו. גם תמונה ממוזערת לא נוצרת מקובץ כזה, כדי לא להוריד אותו.
- התוכנה לא כותבת שום דבר לתיקיות שלך. המידע שלה נשמר בנפרד, בתיקיית הנתונים שלה.

## התקנה

1. מורידים את [`MultiPic-Setup.exe`](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe) ומפעילים. לא נדרשות הרשאות מנהל.
2. אם מופיעה אזהרה של Windows ("Windows protected your PC"), לוחצים **More info** ואז **Run anyway**. האזהרה מופיעה כי התוכנה לא חתומה דיגיטלית.
3. התוכנה נפתחת בחלון משלה (לא בדפדפן) ומופיעה בתפריט התחל. סגירת החלון סוגרת את התוכנה.

גרסה חדשה מותקנת מעל הקודמת, וכל המידע נשמר. רשימת השינויים בכל גרסה: [דף הגרסאות](https://github.com/avi-rav/multipic-releases/releases).
דרישות: Windows 10 או 11, 64 ביט.

## רישיון

MultiPic היא **תוכנה חינמית (Freeware)**: חינם לשימוש, אבל הקוד שלה לא פתוח.

- ✅ מותר להשתמש בחינם, בכל מספר מחשבים, בבית וגם בעסק.
- ✅ מותר להעביר לאחרים את קובץ ההתקנה המקורי, בחינם, או לשלוח קישור לדף הזה.
- ❌ אסור למכור את התוכנה, לשנות אותה או לפרק אותה.
- ⚠ התוכנה ניתנת "כמות שהיא", בלי אחריות. **השימוש בה הוא על אחריות המשתמש בלבד**, והיוצר לא אחראי לשום נזק שייגרם מהשימוש בה, כולל אובדן קבצים. לפני מחיקה בכמות גדולה, מומלץ לגבות את הקבצים.

הנוסח המלא: [LICENSE.txt](LICENSE.txt). התוכנה כוללת רכיבי קוד פתוח, ורישיונותיהם מצורפים לתוכנה (בתיקייה `licenses` שבתיקיית ההתקנה).

## יצירת קשר

© 2026 אבינעם הולצר. כל הזכויות שמורות.
abh2015@gmail.com

</div>

---

# MultiPic (English)

**Tidy up your photos, videos and music: MultiPic finds duplicate files, similar and unneeded photos, and helps you free up space safely.**

**[⬇ Download MultiPic (free, for Windows)](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe)**

> 🔒 **Works offline.** Your files never leave your computer, and no data is sent anywhere.
>
> 🧮 **Finding duplicates uses no artificial intelligence (AI).** Every comparison, filter and recommendation is based on fixed, transparent calculations: comparing file contents, pixels and sound, date, place, size and sharpness. No model guesses anything, and the same folder always gives the same results. The only exception is filtering the gallery by person: it runs two small face-recognition models on your computer, and only when you ask.
>
> 🗑 **Nothing is deleted without your approval.** Deleted files go to the Recycle Bin, so you can change your mind.
>
> 🪟 **Opens in a window of its own,** like any other program, not in your browser.

> [!WARNING]
> **⚠ Important: before you delete**
>
> - **Check carefully what is selected before every confirmation.** MultiPic suggests, but the decision and the responsibility are yours. It picks which copy to keep by technical rules (resolution, quality, size, path) and does not know which folder matters to you.
> - **Do not delete the copies in your organised folders and keep the loose ones.** If the same photo is both in an organised album and in a folder like "Downloads", make sure the copy being deleted is the loose one.
> - **Do not delete a backup folder you want to keep as a backup.** To MultiPic, a copy in a backup is a duplicate like any other. The safest way is not to scan the backup folder at all.
> - **You use the program entirely at your own risk.** The author is not liable for any damage, including loss of files, resulting from its use. Back up your files before deleting many of them.

## Who it is for

Anyone with lots of photos, videos and songs built up over the years: backups copied twice, phone files downloaded more than once, the same photo in different sizes, the same video sent again on WhatsApp, the same song as MP3 and FLAC, folders nobody remembers. No technical knowledge needed.

## How it works

1. **Pick a folder** (for example "Pictures", or your whole user folder), tick what to scan (photos, videos, music) and click "Scan". MultiPic only reads the files and never changes them.
2. **Look through what it found.** Each kind has a tab of its own: Photos, Videos and Music. Every result is shown with thumbnails, and you can watch the videos and listen to the songs, so you see and hear exactly what is suggested.
3. **Confirm** what to delete. Only then do the files go to the Recycle Bin.

## What it does

### Duplicate photos
Finds the same photo even under another name or in another folder, grouped by how certain the match is:

| Level | What it means | What MultiPic does |
|---|---|---|
| **Identical** | Exactly the same file | Marks the extra copies and keeps the best one |
| **Same photo, different details** | Exactly the same picture, but another date, place or format | Same as above |
| **Near-identical** | The same photo in another size or quality | Shows them; you decide |
| **Similar** | For example a burst of shots of the same moment | Shows them for comparison only |

In every group MultiPic recommends which copy to keep (the largest, best-quality one), and you can pick another.

### Duplicate videos
Finds the same video even under another name, in another folder or in another encoding:

| Level | What it means | How it is compared | What MultiPic does |
|---|---|---|---|
| **Identical** | Exactly the same file | A fingerprint (SHA-256) of the whole file content. Right before deleting, the file is compared again, byte for byte, with the copy being kept | Marks the extra copies and keeps the best one |
| **Same video, different encoding** | The same video in another resolution, compression or format, for example a copy sent over WhatsApp | 20 frames sampled along the video and compared visually, plus the video's length and aspect ratio | Shows them; you decide. Nothing is selected in advance |

At the "same video" level, two videos count as the same only when every condition holds: their lengths differ by at most one second (or 1% for a long video), their aspect ratios are nearly the same, and at least 80% of the sampled frames match. Black or uniform frames, such as a fade between scenes, are not counted. All copies can be watched side by side, and the full parameters are listed in the program, under Settings > Technical details.

> ⚠ **At the "same video" level, watch the videos before deleting.** The soundtrack is not checked, and neither is anything between the sampled frames. So a video with different dubbing or music, or one where a short section was replaced, may look like the same video.

### Duplicate music
Finds the same song even under another name, in another folder, with other tags or in another format:

| Level | What it means | How it is compared | What MultiPic does |
|---|---|---|---|
| **Identical** | Exactly the same file | A fingerprint (SHA-256) of the whole file content. Right before deleting, the file is compared again, byte for byte, with the copy being kept | Marks the extra copies and keeps the best one |
| **Same audio, other tags** | Exactly the same sound; only the title, artist, cover or file name differ | A fingerprint of the audio data alone, without the tags and the cover. Right before deleting, it is worked out again for both files | Marks them, and recommends keeping the copy with the fuller tags |
| **Same song** | The same song in another format, quality or encoding | The same artist and title, and lengths at most 2 seconds apart. For a file without tags: the same file name, and at most a second apart | Shows them; you decide. Nothing is selected in advance |

In every group MultiPic recommends which copy to keep: lossless first (FLAC, WAV), then the higher bit rate. A song that appears on more than one album is flagged, so that deleting it does not leave an album incomplete. The full parameters are listed in the program, under Settings > Technical details.

> ⚠ **At the "same song" level, listen before deleting.** The comparison is by the tags and the length, and the sound itself is not checked. So another recording of the same song (a live version or a remaster) of almost the same length may look like the same song.

### Duplicate folders
Finds folders whose photos already exist in another folder, such as an old backup. Cleaning one takes a click: only photos with an identical copy in the other folder are deleted, and photos without a copy stay (or move to the other folder, if you choose).

### Unneeded photos
Lists to review: **blurry** photos, **screenshots**, and **very small** images. Nothing is selected in advance.

### Damaged files
A list for each kind: photos that will not open or open only partly (with a good copy offered when there is one), videos that could not be analysed, and music files that could not be read.

### Gallery
All your photos in one place, and on a separate tab all your videos, sorted by the date taken, newest first. Filter by **year and month**, **date range**, **country and city** (from where it was taken) and **folder**. Select photos and videos (a whole range with Shift) to delete them, or move or copy them into a folder, for example to make an album. Videos can also be played right in the gallery.

- **When and where a video was taken:** read from MP4, MOV, M4V and 3GP files, as Android phones and iPhones record them. When a video has no date taken, the file date is shown, marked with ~.
- **Videos from WhatsApp:** WhatsApp removes the date taken and the location, so such a video's date is usually when it was sent, and it has no place.
- **No date:** photos and videos without a date have their own choice in the filter, "No date".

### People in photos
The photo gallery can be filtered by **person**. In "People…", click "Search photos for faces": MultiPic finds the faces in your photos and groups similar ones as one person. The search goes through all the photos, so it takes a while, and it can be stopped and resumed later.

- **Everything stays on your computer:** recognition uses two small models installed with the program, with no internet. It runs only when you ask, and all face data can be deleted at any time.
- **Names and merging:** name each person, and if one person was recognised as two, merge them. In the gallery's "Person" field you can also type to search.
- **Fixing mistakes:** move faces to another person, to a new person, or to a new person named on the spot. Anything recognised that is not a face can be removed. A photo shown under someone who is not in it is fixed right from the gallery, with a frame marking which face is meant.
- **Undo:** every fix can be undone, and faces removed by mistake can be restored later.

> ⚠ **Grouping into people is an estimate.** Review the list, add names and merge where needed. Face recognition never changes or deletes your photos.

### Music library
All your songs in one list, searched by title, artist, album or file name, and filtered by **artist**, **album**, **genre**, **year**, **format**, **quality**, **length** and **folder**. Clicking a song plays it in the player at the bottom of the window, which keeps playing when you move to another tab. Select songs to delete them, or move or copy them into a folder. Songs without tags can be shown on their own, to tidy them up.

### And more
- **Deletion log:** everything deleted is recorded, with where it was and which copy stayed. Export it to Excel (CSV).
- **Fast rescans:** next time, only new or changed files are checked.
- **Hebrew and English.**
- **Choose what to scan:** photos, videos and music, in any combination.
- File types: photos JPG, PNG, HEIC (iPhone), WEBP, GIF, BMP, TIFF; videos MP4, MOV, M4V, AVI, MKV, WMV, 3GP, MTS, M2TS, MPG, MPEG, WEBM; music MP3, FLAC, M4A, AAC, WAV, OGG, OPUS, WMA, AIFF.

## Safety

- **At least one copy always stays** of every duplicate file.
- Right before deleting, MultiPic checks again that the file has not changed and that the copy being kept really exists. If anything does not match, the file is not deleted.
- On a drive with no Recycle Bin (a USB stick or network drive) it stops and asks what to do.
- **Files of programs are not scanned.** Folders of Windows and of programs (such as AppData and Program Files), hidden folders, folders where a program is installed and code projects are not scanned, so that sounds, icons and pictures that programs need are never suggested for deletion. Temporary folders (Temp) are not scanned either, unless you ask. At the end of the scan a list of what was not scanned is shown.
- **Files kept only in the cloud** (OneDrive, Dropbox, iCloud): scanning them downloads them, so MultiPic stops and asks first, and shows how much space they would take. No thumbnail is made from such a file either, so as not to download it.
- MultiPic writes nothing into your folders. Its own data is kept separately, in its data folder.

## Installation

1. Download [`MultiPic-Setup.exe`](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe) and run it. No administrator rights are needed.
2. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**. The warning appears because the program is not digitally signed.
3. MultiPic opens in a window of its own (not in your browser) and is added to the Start menu. Closing the window closes the program.

A new version installs over the old one and keeps your data. What changed in each version: [Releases](https://github.com/avi-rav/multipic-releases/releases).
Requirements: Windows 10 or 11, 64-bit.

## Licence

MultiPic is **freeware**: free to use, but its code is not open.

- ✅ Use it free of charge, on any number of computers, at home or at work.
- ✅ Give others the original installer, free of charge, or send them a link to this page.
- ❌ Do not sell, modify or decompile it.
- ⚠ It is provided "as is", without warranty. **You use it entirely at your own risk**, and the author is not liable for any damage resulting from its use, including loss of files. Back up your files before deleting many of them.

Full text: [LICENSE.txt](LICENSE.txt). The program includes open-source components, whose licences come with it (in the `licenses` folder of the installation folder).

## Contact

© 2026 Avinoam Holzer. All rights reserved.
abh2015@gmail.com
