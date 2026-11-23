GTA VI ANDROID MOCK-UP — SIMPLE BUILD GUIDE

This project makes an unofficial GTA VI-inspired Android mock-up screen.
It is not the official GTA VI game and contains no gameplay.

IMPORTANT: Upload the CONTENTS of this ZIP to the ROOT of your GitHub repository.
Do not upload the outer GTA-VI-Android-Fixed folder itself.

Your repository root must contain:
- .github/workflows/build.yml
- app/
- build.gradle
- settings.gradle
- gradle.properties

BUILD:
1. Extract this ZIP on your phone.
2. Open your GitHub repository in your browser.
3. Upload all files and folders inside the extracted folder to the repository root.
4. Make sure the hidden .github folder is included. If it is difficult to upload, create
   .github/workflows/build.yml directly on GitHub and paste the workflow from that file.
5. Commit the files.
6. Open Actions and select "Build GTA VI APK".
7. Tap Run workflow.
8. When the run succeeds, open it and download the GTA-VI-Android artifact.
9. Extract the artifact ZIP. It contains app-debug.apk.

If the build fails, open the failed step and share a screenshot of the error.
