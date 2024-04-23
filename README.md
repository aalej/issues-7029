# Repro for issue 7029

## Versions

firebase-tools: v13.7.3<br>
platform: macOS Sonoma 14.4.1

## Steps to reproduce issue

1. In `firebase.json` replace `PROJECT_ID` with an actual project ID (3 instances)
1. Run `ng deploy` or `firebase deploy`
