## QrCodeScanner

###How to import?

1. Root level

```groovy
allprojects {
    repositories {
    ...
    maven {
        url "https://jitpack.io"
    }
    ...
```

2. App level

```groovy
dependencies {
    ...
    // Scanner (view)
    implementation 'com.github.NikitaGordia.QrCodeScanner:qrscanner:1.2.4'
    
    // Bitmap generator
    implementation 'com.github.NikitaGordia.QrCodeScanner:qrgenerator:1.2.4'
    ...
}
```
