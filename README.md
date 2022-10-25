# Unreal-Android-Manifest-Fix-Plugin

Here is a small fix for Android 12 (API 31). Plugin simply modifies AndroidManifest.xml, so it meets new Google Play requirements.

https://developer.android.com/about/versions/12/behavior-changes-12#exported

## Install

1. Clone repository or download zip archive.
2. Create 'Android12GooglePlayFix' folder in Plugins folder of your project and place everything there. Path should look like this: Project/Plugins/Android12GooglePlayFix/Android12GooglePlayFix.uplugin.
3. Regenerate project's files and compile it.
4. Plugin enables automatically. But if don't, open editor, and enable it via Plugins manager window.
5. Build your project for Android with target API level of 31 (ProjectSettings > Android)
