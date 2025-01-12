# Android-Dependencies
Some dependencies which is needed more often than i thought, keeping all those in a single place

# Here
```gradle

//glide
implementation("com.github.bumptech.glide:glide:4.16.0")

//dagger-hilt
implementation("com.google.dagger:hilt-android:2.51")
kapt("com.google.dagger:hilt-compiler:2.44")
kapt("androidx.hilt:hilt-compiler:1.2.0")
implementation("androidx.hilt:hilt-navigation-compose:1.2.0")

plugins {
    kotlin("kapt")
    id("com.google.dagger.hilt.android")
}

kapt {
    correctErrorTypes = true
}

//in project level gradle
id("com.google.dagger.hilt.android") version "2.51" apply false


//retrofit
implementation("com.squareup.retrofit2:retrofit:2.9.0")
implementation("com.squareup.retrofit2:converter-gson:2.9.0")
implementation("com.google.code.gson:gson:2.10.1")
implementation("com.squareup.okhttp3:okhttp:4.11.0")
implementation("com.squareup.okhttp3:logging-interceptor:4.10.0")

//room
implementation("androidx.room:room-runtime:2.6.1")
kapt("androidx.room:room-compiler:2.6.1")
implementation("androidx.room:room-ktx:2.6.1")

//viewmodel
implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0")
implementation("androidx.lifecycle:lifecycle-livedata-ktx:2.7.0")
implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.7.0")

//coroutines
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3")
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.3")

implementation("androidx.activity:activity-ktx:1.8.2")

// System ui controller
implementation ("com.google.accompanist:accompanist-systemuicontroller:0.27.0")

// Fragment Navigation
implementation("androidx.navigation:navigation-fragment-ktx:2.7.7")
implementation("androidx.navigation:navigation-ui-ktx:2.7.7")

// navigation safe args
id("androidx.navigation.safeargs.kotlin") version "2.8.5" apply false
id("androidx.navigation.safeargs.kotlin")

implementation("com.facebook.shimmer:shimmer:0.5.0")

implementation("androidx.core:core-splashscreen:1.0.1")


```
