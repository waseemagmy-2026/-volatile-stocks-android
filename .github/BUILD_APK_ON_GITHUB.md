# Build APK on GitHub

## Fastest way
1. Create a new GitHub repository.
2. Upload all files from this project.
3. Push to `main`.
4. Open **Actions** in GitHub.
5. Run **Build Android APK**.
6. When the workflow finishes, open the run and download the artifact named **app-debug-apk**.
7. Copy the APK to your Android phone and install it.

## Notes
- This project includes `.github/workflows/build-apk.yml` so GitHub Actions can build the APK automatically.
- The generated file is a **debug APK** suitable for testing and installation on your phone.
- For public distribution, prefer a signed release APK or Android App Bundle.
