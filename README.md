# Android-Checklist

Check if the Google API keys are publicly accessible or not.

Check if the APK has set the android:usesCleartextTraffic to true.

Check if the APK has set the android:networkSecurityConfig to a custom configuration file.

Check if the APK is using any hardcoded credentials or sensitive information.

Check if the APK is using any third-party libraries with known security vulnerabilities.

Check if the APK has set the android:allowBackup attribute to true and is backing up sensitive information.

Check if the APK has set the android:exported attribute to true for any component which should not be publicly accessible.

Check if the APK is using any insecure communication protocols such as HTTP instead of HTTPS.

Check if the APK has set the android:permission attribute to a custom permission that grants access to sensitive resources.

Check if the APK is using any insecure encryption algorithms or not using encryption at all.

Check if the APK is using any obfuscation techniques to hide sensitive information from attackers.

Check if the APK is using any reflection or dynamic code loading which could be used to bypass security measures.
