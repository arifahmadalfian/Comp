## Test

[![](https://jitpack.io/v/arifahmadalfian/Comp.svg)](https://jitpack.io/#arifahmadalfian/Comp/1.0.0)
[![arifahmadalfian](https://circleci.com/gh/arifahmadalfian/Comp.svg?style=shield)](https://circleci.com/gh/arifahmadalfian/Comp)
## Installation
**Step 1.** Add the [JitPack](https://jitpack.io/#arifahmadalfian/Comp/1.0.0) 
repository to your build file. Add it in your root `/build.gradle` at the end of repositories:
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
**or** Add it in your root `/settings.gradle` at the end of repositories:
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
**Step 2.** Add the dependency in `/app/build.gradle` :

```
dependencies {
    ...
    implementation 'com.github.arifahmadalfian:Comp:1.0.1'
}
```