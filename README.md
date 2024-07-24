# TmdbAppCompose
A Jetpack Compose-based Android application that utilizes the TMDB API to showcase the latest popular, currently playing, upcoming, and top-rated movies. It also provides detailed information and trailers for each movie.

## Prerequisites
Insert your [TMDB](https://www.themoviedb.org/) API key into the `local.properties` file:
```
TMDB_API_KEY="YOUR_API_KEY"
```

## Screenshots
<img src="https://user-images.githubusercontent.com/48273411/210358426-4d34cf3e-67ba-4bcd-b13e-26b353e26ea4.png" width="250" /> <img src="https://user-images.githubusercontent.com/48273411/210358652-aaf94cfc-9c6d-43de-bf54-be6c2bc05661.png" width="250" /> <img src="https://user-images.githubusercontent.com/48273411/210358837-288db934-7dce-478a-b16d-1677ccc109e0.png" width="250" />

## Technology Stack 🛠
- [Jetpack Compose](https://developer.android.com/jetpack/compose/) - Android’s modern toolkit for creating native UIs, making UI development faster and more efficient with concise code, robust tools, and intuitive Kotlin APIs.
- [Kotlin](https://kotlinlang.org/) - The official programming language for Android development.
- [MVVM Architecture](https://developer.android.com/topic/architecture) - A design pattern that reduces tight coupling between components, ensuring that child components reference the parent through observables rather than direct references.
- [Hilt](https://dagger.dev/hilt/) - Integrates Dagger dependency injection into Android applications in a standard way.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous programming.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Libraries that assist in designing robust, testable, and maintainable apps.
- [Flows](https://developer.android.com/kotlin/flow) - Built on top of coroutines, providing multiple values and functioning as an asynchronous stream of data.
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Retains UI-related data across UI changes.
- [Navigation](https://developer.android.com/jetpack/compose/navigation) - Manages navigation between composables.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
- [GSON](https://github.com/square/gson) - A JSON parser.
- [Retrofit](https://github.com/square/retrofit) - A type-safe HTTP client for Android and Java.
- [OkHttp Logging Interceptor](https://github.com/square/okhttp/blob/master/okhttp-logging-interceptor/README.md) - Logs HTTP request and response data.
- [Lottie Files for Compose](https://github.com/airbnb/lottie) - Parses Adobe After Effects animations exported as JSON with Bodymovin and renders them natively on mobile and web platforms.
- [Compose Pagination](https://developer.android.com/jetpack/androidx/releases/paging) - Helps in gradually and efficiently loading data within your app.

Note: The application supports Android version 5.0 (Lollipop) or higher.

Supported SDK levels
--------------------
- Minimum SDK: 21
- Target SDK: 33
