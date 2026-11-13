<div dir="rtl">

# MultiPic

**סדר בספריית התמונות שלך: מוצאת תמונות וסרטונים כפולים, תמונות דומות ומיותרות, ומאפשרת לפנות מקום בבטחה.**

**[⬇ הורדת MultiPic (חינם, ל-Windows)](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe)**

> 🔒 **עובדת בלי אינטרנט.** התמונות שלך לא יוצאות מהמחשב, ושום מידע לא נשלח לשום מקום.
>
> 🧮 **בלי בינה מלאכותית (AI).** כל השוואה, סינון והמלצה מבוססים על חישובים קבועים ושקופים: השוואה של תוכן הקבצים והפיקסלים, תאריך, מיקום, גודל וחדות. אין "ניחושים" של מודל, ואותה תיקייה תיתן תמיד את אותן תוצאות.
>
> 🗑 **שום דבר לא נמחק בלי אישור שלך.** והמחיקה היא לסל המיחזור, כך שאפשר להתחרט.
>
> 🪟 **נפתחת בחלון משלה,** כמו כל תוכנה רגילה, ולא בדפדפן.

> [!WARNING]
> **⚠ חשוב: לפני שמוחקים, שים לב**
>
> - **בדוק היטב מה מסומן למחיקה לפני כל אישור.** התוכנה מציעה, אבל ההחלטה והאחריות שלך. היא בוחרת איזה עותק לשמור לפי כללים טכניים (רזולוציה, גודל, נתיב), ולא יודעת איזו תיקייה חשובה לך.
> - **אל תמחק את העותקים שבתיקיות המסודרות ותשאיר את התמונות בתפזורת.** אם אותה תמונה נמצאת גם באלבום מסודר וגם בתיקייה כמו "הורדות", ודא שהעותק שנמחק הוא זה שבתפזורת.
> - **אל תמחק תיקיית גיבוי שאתה רוצה לשמור כגיבוי.** מבחינת התוכנה, עותק בגיבוי הוא כפילות כמו כל כפילות אחרת. הדרך הבטוחה ביותר היא לא לסרוק את תיקיית הגיבוי בכלל.
> - **השימוש בתוכנה הוא על אחריות המשתמש בלבד.** היוצר לא אחראי לשום נזק, כולל אובדן קבצים, שייגרם מהשימוש בה. מומלץ לגבות את התמונות לפני מחיקה בכמות גדולה.

## למי זה מתאים

לכל מי שיש לו במחשב הרבה תמונות שהצטברו עם השנים: גיבויים שהועתקו פעמיים, תמונות מהטלפון שהורדו כמה פעמים, אותה תמונה בגדלים שונים, ותיקיות שכבר לא ברור מה יש בהן. לא צריך ידע טכני.

## איך זה עובד

1. **בוחרים תיקייה** (למשל "תמונות") ולוחצים "סרוק". התוכנה רק קוראת את הקבצים ולא משנה בהם כלום.
2. **עוברים על מה שהיא מצאה.** כל התוצאות מוצגות עם תמונות ממוזערות, כדי שתראה בעיניים מה מוצע.
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

### תיקיות כפולות
מוצאת תיקיות שהתמונות שבהן כבר קיימות בתיקייה אחרת, למשל גיבוי ישן. אפשר לנקות תיקייה כזאת בלחיצה: נמחקות רק תמונות שיש להן עותק זהה בתיקייה השנייה, ותמונות שאין להן עותק נשארות (או מועברות לתיקייה השנייה, אם תבחר בכך).

### תמונות מיותרות
רשימות לבדיקה: תמונות **מטושטשות**, **צילומי מסך**, ותמונות **קטנות מאוד**. שום דבר לא מסומן מראש.

### קבצים פגומים
מראה תמונות שלא נפתחות או נפתחות רק בחלקן, וכשאפשר מציעה עותק תקין שלהן.

### גלריה
כל התמונות במקום אחד, ובלשונית נפרדת כל הסרטונים, ממוינים לפי תאריך הצילום מהחדש לישן. אפשר לסנן לפי **שנה וחודש**, **טווח תאריכים**, **מדינה ועיר** (לפי מיקום הצילום) ו**תיקייה**. אפשר לסמן תמונות וסרטונים (גם טווח שלם עם Shift) ולמחוק אותם, או להעביר ולהעתיק אותם לתיקייה, למשל כדי ליצור אלבום. סרטון אפשר גם לנגן ישר מהגלריה.

- **תאריך ומקום של סרטונים:** נקראים מתוך קובצי MP4, MOV, M4V ו-3GP, כמו שהם נשמרים בטלפוני אנדרואיד ובאייפון. כשאין בסרטון תאריך צילום, מוצג תאריך הקובץ, מסומן ב-~.
- **סרטונים מוואטסאפ:** וואטסאפ מוחקת מהסרטון את תאריך הצילום ואת המיקום, ולכן התאריך שלו הוא בדרך כלל מועד השליחה, ואין לו מקום.
- **בלי תאריך:** לתמונות ולסרטונים שאין להם תאריך יש אפשרות משלהם בסינון, "ללא תאריך".

### ועוד
- **יומן מחיקות:** כל מה שנמחק נרשם, עם המקום שבו הוא היה והעותק שנשאר. אפשר לייצא לאקסל (CSV).
- **סריקה חוזרת מהירה:** בפעם הבאה נבדקים רק קבצים חדשים או כאלה שהשתנו.
- **עברית ואנגלית.**
- **בוחרים מה לסרוק:** תמונות וסרטונים, רק תמונות, או רק סרטונים.
- סוגי קבצים: תמונות JPG, PNG, HEIC (אייפון), WEBP, GIF, BMP, TIFF. סרטונים MP4, MOV, M4V, AVI, MKV, WMV, 3GP, MTS, M2TS, MPG, MPEG, WEBM.

## בטיחות

- **תמיד נשאר עותק אחד לפחות** מכל תמונה או סרטון כפולים.
- רגע לפני מחיקה, התוכנה בודקת שוב שהקובץ לא השתנה ושהעותק שנשאר באמת קיים. אם משהו לא תואם, הקובץ לא נמחק.
- בכונן שאין בו סל מיחזור (למשל דיסק-און-קי או כונן רשת) התוכנה עוצרת ושואלת מה לעשות.
- התוכנה לא כותבת שום דבר לתיקיית התמונות שלך. המידע שלה נשמר בנפרד, בתיקיית הנתונים שלה.

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
- ⚠ התוכנה ניתנת "כמות שהיא", בלי אחריות. **השימוש בה הוא על אחריות המשתמש בלבד**, והיוצר לא אחראי לשום נזק שייגרם מהשימוש בה, כולל אובדן קבצים. לפני מחיקה בכמות גדולה, מומלץ לגבות את התמונות.

הנוסח המלא: [LICENSE.txt](LICENSE.txt). התוכנה כוללת רכיבי קוד פתוח, ורישיונותיהם מצורפים לתוכנה (בתיקייה `licenses` שבתיקיית ההתקנה).

## יצירת קשר

© 2026 אבינעם הולצר. כל הזכויות שמורות.
abh2015@gmail.com

</div>

---

# MultiPic (English)

**Tidy up your photo library: MultiPic finds duplicate photos and videos, similar and unneeded photos, and helps you free up space safely.**

**[⬇ Download MultiPic (free, for Windows)](https://github.com/avi-rav/multipic-releases/releases/latest/download/MultiPic-Setup.exe)**

> 🔒 **Works offline.** Your photos never leave your computer, and no data is sent anywhere.
>
> 🧮 **No artificial intelligence (AI).** Every comparison, filter and recommendation is based on fixed, transparent calculations: comparing file contents and pixels, date, place, size and sharpness. No model guesses anything, and the same folder always gives the same results.
>
> 🗑 **Nothing is deleted without your approval.** Deleted files go to the Recycle Bin, so you can change your mind.
>
> 🪟 **Opens in a window of its own,** like any other program, not in your browser.

> [!WARNING]
> **⚠ Important: before you delete**
>
> - **Check carefully what is selected before every confirmation.** MultiPic suggests, but the decision and the responsibility are yours. It picks which copy to keep by technical rules (resolution, size, path) and does not know which folder matters to you.
> - **Do not delete the copies in your organised folders and keep the loose ones.** If the same photo is both in an organised album and in a folder like "Downloads", make sure the copy being deleted is the loose one.
> - **Do not delete a backup folder you want to keep as a backup.** To MultiPic, a copy in a backup is a duplicate like any other. The safest way is not to scan the backup folder at all.
> - **You use the program entirely at your own risk.** The author is not liable for any damage, including loss of files, resulting from its use. Back up your photos before deleting many files.

## Who it is for

Anyone with lots of photos built up over the years: backups copied twice, phone photos downloaded more than once, the same photo in different sizes, folders nobody remembers. No technical knowledge needed.

## How it works

1. **Pick a folder** (for example "Pictures") and click "Scan". MultiPic only reads the files and never changes them.
2. **Look through what it found.** Every result is shown with thumbnails, so you see exactly what is suggested.
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

### Duplicate folders
Finds folders whose photos already exist in another folder, such as an old backup. Cleaning one takes a click: only photos with an identical copy in the other folder are deleted, and photos without a copy stay (or move to the other folder, if you choose).

### Unneeded photos
Lists to review: **blurry** photos, **screenshots**, and **very small** images. Nothing is selected in advance.

### Damaged files
Shows photos that will not open, or open only partly, and offers a good copy when there is one.

### Gallery
All your photos in one place, and on a separate tab all your videos, sorted by the date taken, newest first. Filter by **year and month**, **date range**, **country and city** (from where it was taken) and **folder**. Select photos and videos (a whole range with Shift) to delete them, or move or copy them into a folder, for example to make an album. Videos can also be played right in the gallery.

- **When and where a video was taken:** read from MP4, MOV, M4V and 3GP files, as Android phones and iPhones record them. When a video has no date taken, the file date is shown, marked with ~.
- **Videos from WhatsApp:** WhatsApp removes the date taken and the location, so such a video's date is usually when it was sent, and it has no place.
- **No date:** photos and videos without a date have their own choice in the filter, "No date".

### And more
- **Deletion log:** everything deleted is recorded, with where it was and which copy stayed. Export it to Excel (CSV).
- **Fast rescans:** next time, only new or changed files are checked.
- **Hebrew and English.**
- **Choose what to scan:** photos and videos, photos only, or videos only.
- File types: photos JPG, PNG, HEIC (iPhone), WEBP, GIF, BMP, TIFF; videos MP4, MOV, M4V, AVI, MKV, WMV, 3GP, MTS, M2TS, MPG, MPEG, WEBM.

## Safety

- **At least one copy always stays** of every duplicate photo or video.
- Right before deleting, MultiPic checks again that the file has not changed and that the copy being kept really exists. If anything does not match, the file is not deleted.
- On a drive with no Recycle Bin (a USB stick or network drive) it stops and asks what to do.
- MultiPic writes nothing into your photo folder. Its own data is kept separately, in its data folder.

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
- ⚠ It is provided "as is", without warranty. **You use it entirely at your own risk**, and the author is not liable for any damage resulting from its use, including loss of files. Back up your photos before deleting many files.

Full text: [LICENSE.txt](LICENSE.txt). The program includes open-source components, whose licences come with it (in the `licenses` folder of the installation folder).

## Contact

© 2026 Avinoam Holzer. All rights reserved.
abh2015@gmail.com
