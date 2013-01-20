# Git Dependencies Plugin for Gradle
The Git dependencies plugin provides java source code dependencies via git to your project using seamless gradle syntax.
It relies on Gradle 

## Usage
To use the git-dependencies plugin, include in your build script:

```groovy
apply plugin: 'git-dependencies'

buildscript {
    repositories {
        mavenCentral()
    }
    dependencies {
        classpath 'org.batcha.gradle.plugins:gradle-plugin-git-dependencies:0.1'
    }
}
```
You can also do
```  
apply from: 
```

To declare a Dependency,
``` 
dependencies {
    // work in progress...
    gradle-git  
    
}
```