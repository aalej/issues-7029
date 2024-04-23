# Repro for issue 7029

## Versions

firebase-tools: v13.7.3<br>
platform: macOS Sonoma 14.4.1

## Steps to reproduce issue

1. In `firebase.json` replace `PROJECT_ID` with an actual project ID (3 instances)
1. Run `ng deploy` or `firebase deploy`
   - Error

```
Build at: 2024-04-23T14:02:09.639Z - Hash: 6d713757861e6b44 - Time: 6926ms

   Thank you for trying our early preview of Angular support on Firebase Hosting.
   During the preview, support is best-effort and breaking changes can be expected. Proceed with caution.

   Documentation: https://firebase.google.com/docs/hosting/frameworks/angular
   File a bug: https://github.com/firebase/firebase-tools/issues/new?template=bug_report.md
   Submit a feature request: https://github.com/firebase/firebase-tools/issues/new?template=feature_request.md

   We'd love to learn from you. Express your interest in helping us shape the future of Firebase Hosting: https://goo.gle/41enW5X

Error when trying to deploy:
@angular-devkit/build-angular:browser (app:build:production) is not a recognized builder. Please check your angular.json
```
