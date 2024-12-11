# apache-cordova-framework-v7
This is repository containing build (.pom, .aar) of the outdated Cordova framework removed from open repositories.
Files were copied from https://artifactory.appodeal.com/appodeal-public/org/apache/cordova/framework/7.0.0/

## Add to ~/.gradle/init.gradle

```bash
allprojects {
    repositories {
        google()
        mavenCentral()
        maven {
            url uri("${System.properties['user.home']}/.m2/repository")
        }
    }
}
```
