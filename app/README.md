# Android Samples in Kotlin

This repository holds sample apps for Android in Kotlin.
Maintained by Android Studio Chipmunk | 2021.2.1

## Introduction

Each sample app is located in its own subdirectory.
One should be able to get hold on them individually somehow.

## Available samples

### TakePhoto
Take a photo using AndroidX Activity Result API i.e.
- call registerForActivityResult() with ActivityResultContracts.TakePicture() contract
- launch the camera with returned ActivityResultLauncher's launch() method
- take a shot with camera
- Once returned from camera app shot taken is displayed on imageview.

Created this sample app as wasn't able to find one when porting deprecated startActivityForResult()  / onActivityResult() way of doing this in one of my apps.