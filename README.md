# DpToUnit

1. Add next lines in your **projects build.gradle** file:
```
allprojects {
    repositories {
        maven { url "http://dl.bintray.com/psycoder0001/AndroidLibs" }
    }
}
```

2. Add next line in modules build.gradle file:
```
    implementation 'com.deepdroid.dptounit:dptounit:1.0.1'
```
