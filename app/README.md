# Android Samples in Kotlin

This repository holds sample apps for Android in Kotlin.
Maintained by Android Studio Chipmunk | 2021.2.1

## Introduction

Each sample app is located in its own subdirectory.
One should be able to get hold on them individually somehow.

## Available samples

### TakePhoto
Use AndroidX Activity Result API i.e.
- call registerForActivityResult() with ActivityResultContracts.TakePicture() contract
- launch the camera with returned ActivityResultLauncher's launch() method