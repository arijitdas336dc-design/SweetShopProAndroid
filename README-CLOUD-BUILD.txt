BUILD SWEET SHOP PRO APK WITHOUT INSTALLING ANDROID STUDIO

This project includes a GitHub Actions workflow at:
.github/workflows/build-apk.yml

You can run the build from a phone using GitHub's website:
1. Sign in to GitHub (create a free account if needed).
2. Create a NEW PRIVATE repository named SweetShopProAndroid.
3. Upload the CONTENTS of this project folder to the repository, keeping folder structure. The .github/workflows/build-apk.yml file must be included. If using GitHub's web uploader, ensure hidden .github folder is included; if the web uploader hides it, use GitHub's web editor to create the workflow file at .github/workflows/build-apk.yml and paste its contents from this project.
4. Open the repository's Actions tab.
5. Select "Build Sweet Shop Pro APK" and press "Run workflow".
6. Wait for the workflow to finish successfully.
7. Open that completed run, scroll to Artifacts, and download "SweetShopPro-debug-APK".
8. Extract the downloaded artifact ZIP on your Android phone, tap app-debug.apk, and follow Android's install prompts.

The GitHub Actions build uses a temporary cloud runner. No Android Studio is needed on your own device.

IMPORTANT:
- This produces a debug APK for personal testing, not a Play Store release.
- The project has not been device-tested here. Test all features and calculations before using for live accounts.
- App data is stored locally on the phone. Back up regularly; uninstalling/clearing app data can erase it.
- Do not upload real shop/customer/employee data to the source repository.
