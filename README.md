# opencv-android

[![](https://jitpack.io/v/ars-nomura/opencv-android.svg)](https://jitpack.io/#ars-nomura/opencv-android)

--- 

See the [project website][opencv] for documentation and APIs.

## Usage

### Groovy DSL:

#### 1. Add the JitPack repository in your `settings.gradle` at the end of repositories

```groovy
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' } // add this line
    }
}
```

##### If using obsolete gradle

add this in your root `build.gradle`

```groovy
allprojects {
    repositories {
        google()
        mavenCentral()
        maven { url "https://www.jitpack.io" }
    }
}
```


#### 2. then, add the library to your module `build.gradle`

```groovy
implementation 'com.github.ars-nomura:opencv-android:4.8.0'
```

### Kotlin DSL:

#### 1. Add the JitPack repository to your `settings.gradle.kts` at the end of repositories

```kotlin
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url = uri("https://jitpack.io") } // add this line
    }
}
```

#### 2. then, add the library to your module `build.gradle.kts`

```kotlin
implementation("com.github.ars-nomura:opencv-android:4.8.0")
```

[opencv]: https://opencv.org/