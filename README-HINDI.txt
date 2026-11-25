J.K. SELF STUDY HUB - FIXED GITHUB APK PROJECT

Is project ko apne GitHub repository ke root mein upload karein.
IMPORTANT:
1. Purane .github/workflows/android.yml ko is ZIP wale naye android.yml se REPLACE karein.
2. Root par maujood build-apk.yml ko delete kar sakte hain; workflow hamesha .github/workflows/ ke andar hona chahiye.
3. app folder aur uske andar ka poora structure upload karein.
4. GitHub Actions tab mein Build J.K. Self Study Hub APK workflow run hoga.
5. Successful run > Artifacts > JK-Self-Study-Hub-debug-apk download karein.

Is workflow mein gradlew wrapper ki zaroorat nahi hai. GitHub runner par Gradle 8.7 setup karke build chalaya jata hai.

App URL is the Google Apps Script URL provided by the user.
NOTE: Google sign-in/OAuth screens may be restricted in Android WebView by Google. If the site redirects to blocked login, a native browser/custom tab flow may be needed.
