# 🎓 UVPCE Splash Screen Animation

https://github.com/user-attachments/assets/d0d66041-1098-4cca-a689-e75e3b1d27e4

An Android application that demonstrates a **custom animated Splash Screen** using **Kotlin and XML animations**.

This project was created as part of **Mobile Application Development (MAD) Practical-6**.

## 📱 Project Overview

When the application starts, a custom splash screen is displayed with the **UVPCE logo animation**. The animation uses multiple image frames along with XML animations such as:

- 🔄 Rotate Animation
- ↔️ Translate Animation
- 🔍 Scale Animation
- 🎞️ Frame-by-Frame Animation
- 🌈 Gradient Background

After the animation finishes, the application automatically navigates to the `MainActivity`.

## ✨ Features

- Custom Splash Screen
- UVPCE Logo Frame Animation
- Rotate Animation
- Translate Animation
- Scale Animation
- Gradient Background
- Automatic Navigation to MainActivity
- Built using Kotlin and XML

## 🛠️ Technologies Used

- **Kotlin**
- **Android Studio**
- **XML**
- **Android AnimationDrawable**
- **ConstraintLayout**

## 📂 Project Structure

```text
app/
└── src/
    └── main/
        ├── java/
        │   └── com/example/a24012021096_mad_pr6/
        │       ├── MainActivity.kt
        │       └── SplashActivity.kt
        │
        └── res/
            ├── anim/
            │   └── twinkanimation.xml
            │
            ├── drawable/
            │   ├── rectangle.xml
            │   ├── uvpce_animation_list.xml
            │   ├── uvpce_logo.png
            │   ├── uvpce_logo_1.png
            │   ├── uvpce_logo_2.png
            │   ├── uvpce_logo_3.png
            │   ├── uvpce_logo_4.png
            │   ├── uvpce_logo_5.png
            │   ├── uvpce_logo_6.png
            │   └── uvpce_logo_7.png
            │
            └── layout/
                ├── activity_main.xml
                └── activity_splash.xml
