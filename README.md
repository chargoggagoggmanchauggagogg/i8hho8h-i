# Quick Quiz

Math and ELA practice, grades K to College, with parent controls.

## Get an iOS app (IPA)
1. Create a new GitHub repo and upload everything in this folder (keep the .github folder).
2. Edit `capacitor.config.json` and change `appId` to something unique, like `com.yourname.quickquiz`.
3. Go to the Actions tab, pick "Build iOS (unsigned IPA)", and click Run workflow.
4. When it finishes, download `QuickQuiz-unsigned-ipa` from the run page and unzip it to get `QuickQuiz-unsigned.ipa`.
5. The IPA is unsigned. To install it on your iPhone, sign it with a tool like Sideloadly or AltStore using your Apple ID (free accounts expire after 7 days), or use a paid Apple Developer account and TestFlight.

## Web version
Turn on Settings > Pages > Source: GitHub Actions. The "Deploy web version" workflow publishes `www/` to a public link you can add to your home screen.
