# GooglePackages
A Git UPM (Unity Package Manager) version of Google's package.

Just unzip from https://developers.google.com/unity/archive.
Also to avoid confused with official version SDK package, the package name is all renamed from "com.google" into "com.macacagames"

This repository replicates the licence terms of his original distribution location. For more information check https://firebase.google.com/terms and https://firebase.google.com/support/release-notes/unity


# Usage
 
## Important : Since UPM didn't support dependencies resolve with git package. Manually manage the dependencies is required!!!

See [Here](https://developers.google.com/unity/archive) to understand which package's dependencies eachother

Add followo item in your manifest.json

```json
// To add External Dependency Manager: 
{
    "com.macacagames.external-dependency-manager": "https://github.com/MacacaGames/GooglePackages.git?path=/External Dependency Manager",
}

// To add Firebase App (Core): 
{
    "com.macacagames.firebase.app": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase App"
}

// To add Cloud Firestore for Firebase: 
{
    "com.macacagames.firebase.firestore": "https://github.com/MacacaGames/GooglePackages.git?path=/Cloud Firestore for Firebase"
}

// To add Cloud Functions for Firebase: 
{
    "com.macacagames.firebase.functions": "https://github.com/MacacaGames/GooglePackages.git?path=/Cloud Functions for Firebase"
}

// To add Cloud Storage for Firebase: 
{
    "com.macacagames.firebase.storage": "https://github.com/MacacaGames/GooglePackages.git?path=/Cloud Storage for Firebase"
}

// To add Firebase Authentication: 
{
    "com.macacagames.firebase.auth": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Authentication"
}

// To add Firebase Cloud Messaging: 
{
    "com.macacagames.firebase.messaging": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Cloud Messaging"
}

// To add Firebase Crashlytics: 
{
    "com.macacagames.firebase.crashlytics": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Crashlytics"
}

// To add Firebase Dynamic Links: 
{
    "com.macacagames.firebase.dynamic-links": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Dynamic Links"
}

// To add Firebase Installations: 
{
    "com.macacagames.firebase.installations": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Installations"
}

// To add Firebase Instance ID: 
{
    "com.macacagames.firebase.instance-id": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Instance ID"
}

// To add Firebase Realtime Database: 
{
    "com.macacagames.firebase.database": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Realtime Database"
}

// To add Firebase Remote Config: 
{
    "com.macacagames.firebase.remote-config": "https://github.com/MacacaGames/GooglePackages.git?path=/Firebase Remote Config"
}

// To add Google Analytics for Firebase: 
{
    "com.macacagames.firebase.analytics": "https://github.com/MacacaGames/GooglePackages.git?path=/Google Analytics for Firebase"
}

```
