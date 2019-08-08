# autoid-ktx
## Usage:
### project.gradle:

```java
  allprojects {
      repositories {
          maven { url "https://raw.githubusercontent.com/autoid-android/autoid-ktx/master" }
      }
  }
```

### app.gradle

```java
  implementation 'com.autoid:autoid-ktx:1.0.2'
```

## Tree:

```
    .
    ├── MainThread.kt
    └── Messager.kt
```