# Bomhoff Israel TV routing configuration

קובץ ניתוב ציבורי עבור אפליקציית Bomhoff Israel TV.

המאגר מכיל רק כתובות ציבוריות של שידורים וקטלוגים. הוא אינו מכיל קוד מקור של האפליקציה, APK, סיסמאות, אסימוני גישה או מפתחות חתימה.

האפליקציה מאמתת את מבנה הקובץ, דורשת HTTPS ומאפשרת רק דומיינים שהוגדרו מראש. אם הקובץ אינו זמין או אינו תקין, היא ממשיכה עם העותק התקין האחרון או עם ההגדרות המובנות ב-APK.

## File

- `live-routing.json`: versioned routing configuration with primary and backup sources.

## Updating

Increase `configVersion` for every routing change. Keep `schemaVersion` at `1` unless the application is updated to support a new schema.
