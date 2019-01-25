# Cordova-Plugin-Asset-Manifest

This Cordova plugin for Android generates the cdvasset.manifest File.
Solves the problem if multiple plugins use postBuildExtras and the manifest file is not generated.
I developed the plugin because of the following problem with the code push plugin from Microsoft:

'[CodePush] Could not get binary hash.Error: Could not get binary hash.'

# Installation

```
cordova plugin add cordova-plugin-asset-manifest
```