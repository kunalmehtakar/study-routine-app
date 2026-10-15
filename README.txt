STUDY ROUTINE — FINAL PROJECT PACKAGE

Features:
- Home dashboard and six-hour study plan
- Six subjects: History, Geography, Polity, Physics, Chemistry, Biology
- Add, rename, mark complete, revision mark and delete chapters
- Manually create multiple-choice quizzes with four options and correct answer
- Score, answered count and quiz history
- Subject-wise progress
- Local data persistence and JSON backup import/export
- PDF upload and PDF-based quiz controls are not included
- GitHub Actions workflow builds a debug APK

IMPORTANT LIMITATIONS:
- Data is stored locally on the device; there is no cloud sync/login.
- Quiz questions must be entered manually; no automatic PDF/OCR question extraction.
- The GitHub workflow must be run in your repository. This package is not itself an APK.
- A debug APK is for testing. Google Play publishing needs a signed release bundle and Play Console account.

BUILD WITHOUT TERMUX:
1. Extract ZIP and upload all contents (including hidden .github folder) to a GitHub repository root.
2. Open Actions tab -> Build Study Routine APK -> Run workflow.
3. Wait for green success. Open completed workflow run -> Artifacts -> study-routine-debug-apk.
4. Download and extract the artifact ZIP to get app-debug.apk.
