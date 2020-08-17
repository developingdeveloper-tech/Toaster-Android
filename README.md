# Toaster-Android

![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/5AbhishekSaxena/Toaster-Android?include_prereleases)
![GitHub](https://img.shields.io/github/license/5AbhishekSaxena/Toaster-Android)
![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/5AbhishekSaxena/toaster-Android)

Toaster-Android is a simple open source library to customize toast messages in adnroid applications.
It has some predefined templates for common use-cases like warning, error and success messages.

# Download

#### Step 1
Add the JitPack repository to your `build.gradle(project)`.
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
 ```
 #### Step 2
 Add the dependency to your `build.gradle(Module: app)`.
 
 ```
 dependencies {
	        implementation 'com.github.5AbhishekSaxena:Toaster-Android:0.1.0-beta02'
	}
  ```
