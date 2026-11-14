SWEET SHOP PRO - ANDROID STUDIO PROJECT

This is an Android WebView wrapper around an offline-first shop accounting app.
Features: dashboard, sales, expenses, employee register, attendance, payroll, preliminary monthly P&L, JSON backup/restore.

BUILD APK (Windows):
1. Install Android Studio (stable release) from https://developer.android.com/studio
2. Extract this ZIP to a normal folder, e.g. C:\SweetShopProAndroid
3. Open Android Studio > Open > select the extracted SweetShopProAndroid folder.
4. Allow Gradle sync and install the requested Android SDK Platform 35 if prompted.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When build completes, click 'locate' in the notification. APK is normally at app\build\outputs\apk\debug\app-debug.apk.
7. Transfer app-debug.apk to your Android phone, tap it, allow 'Install unknown apps' for the file manager/browser if Android asks, then install.

For a shareable production APK, use Build > Generate Signed Bundle / APK and create/store a private signing key safely.

DATA & ACCOUNTING NOTES:
- Records are stored locally on this phone only; there is no cloud sync or automatic online backup.
- Export JSON backups regularly. Reinstalling or clearing app data may erase records.
- The P&L is preliminary, not statutory accounting or formal net profit. It does not calculate inventory valuation/COGS, GST, depreciation, receivables/payables or full payroll accruals.
- This project has not been compiled or device-tested in this environment. Verify all calculations and backup/restore before relying on it for business accounts.
