# Bus Scheduler Composed

This app is part of the [Android Basics in Compose] course from Google, see [Unit 6] [Pathway 2] 
and the [Practice Build Bus Schedule app] Codelab.

The Bus Scheduler app displays a list of bus stops and arrival times. Tapping a bus stop on the 
first screen will display a list of all arrival times for that particular stop.

The bus stops are stored in a Room database. Schedule items are represented by the `Schedule` class
and queries on the data table are made by the `ScheduleDao` class. The app includes a view model to
access the `ScheduleDao` and format data to be display in a list.

[Android Basics in Compose]: https://developer.android.com/courses/android-basics-compose/course
[Unit 6]: https://developer.android.com/courses/android-basics-compose/unit-6
[Pathway 2]: https://developer.android.com/courses/pathways/android-basics-compose-unit-6-pathway-2
[Practice Build Bus Schedule app]: https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-bus-schedule-app

---

Environment

- Kotlin 1.8.20
- Android Studio Flamingo 2022.2.1
- Compose Bom 2023.04.01
- Gradle Plugin 8.0.0

---

```
language: kotlin
repo: busschedule_composed
status: active
updated: 2023-05-03
```