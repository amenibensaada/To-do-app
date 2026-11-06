# Android task list

A small Kotlin/Android learning app: add a task, mark it complete and remove completed tasks. The UI uses RecyclerView and an in-memory list.

Earlier mobile development work · [Current software engineering portfolio](https://amenibensaadaportfolio.netlify.app/?utm_source=github&utm_medium=profile&utm_campaign=personal_brand).

## Explore and run

Open the project in Android Studio with an Android SDK/JDK compatible with its historical Gradle configuration, sync dependencies and run on an emulator or device. See `app/build.gradle` for the original SDK settings.

- `MainActivity.kt`: task input and add/delete actions.
- `Todo.kt`: task data.
- `TodoAdapter.kt`: RecyclerView binding and completion state.

The task list is process-local; persistent storage, accounts and synchronization are not implemented. Existing unit/instrumentation files are the Android template examples, not a comprehensive application test suite. Gradle/Android dependencies have not been modernized in this documentation cleanup.
