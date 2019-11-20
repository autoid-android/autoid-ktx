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
  implementation 'com.autoid:autoid-ktx:2.0.1'
```

## Tree:

```
    .
    ├── activities
    │   └── BaseActivity.kt
    ├── Application.kt
    ├── net
    │   └── BaseRequest.kt
    ├── utils
    │   ├── CoroutinesHelper.kt
    │   ├── LogUtil.kt
    │   ├── MainThread.kt
    │   └── Messager.kt
    └── views

```
