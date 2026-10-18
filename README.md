# Nice-too-meet-you-Android

A minimal beginner Android app demonstrating explicit `Intent` navigation between two screens.

## What it does

1. The main screen shows the text **"很高兴认识你！"** and a button.
2. Tapping the button launches a second Activity that shows **"Nice to meet you！"**.

## Concepts covered

- `Activity` lifecycle (`onCreate`)
- Finding views with `findViewById` and setting text / click listeners
- Screen-to-screen navigation with an explicit `Intent` (`intent.setClass(...)` + `startActivity`)
- Edge-to-edge display via `EdgeToEdge.enable(this)`

## Run

Open the project in Android Studio and run the **app** module on an emulator or device.

## Project structure

| File | Role |
| --- | --- |
| [MainActivity.java](app/src/main/java/com/example/myapplication2java/MainActivity.java) | First screen: greeting text + button that starts `MainActivity2` |
| [MainActivity2.java](app/src/main/java/com/example/myapplication2java/MainActivity2.java) | Second screen |
| [activity_main.xml](app/src/main/res/layout/activity_main.xml) / [activity_main2.xml](app/src/main/res/layout/activity_main2.xml) | Layouts for the two screens |
