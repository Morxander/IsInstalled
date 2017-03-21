# IsInstalled
[![GPL](https://img.shields.io/aur/license/yaourt.svg)]() [![Maintenance](https://img.shields.io/maintenance/yes/2017.svg)]()

The library allows you to check if a specific application is installed or not by its `package name`. Also you have a helper which provides the packagenames of the most popular applications.


### Download

Download via Gradle:

```gradle
compile 'morxander.isinstalled:IsInstalled:1.0.0'
```

### Usage
#### Check if an App exists

```java
IsInstalled.isIntalled(this, com.android.chrome); // returns boolean
```

#### Using the library helper to get packagenames of more than 30 popular Apps

```java
AppsPackNames.YOUTUBE;
AppsPackNames.CHROME;
AppsPackNames.FACEBOOK;
AppsPackNames.FACEBOOK_MESSENGER;
AppsPackNames.WHATSAPP;
AppsPackNames.GOOGLE_MAPS;
AppsPackNames.VIBER;
AppsPackNames.GOOGLE_DOCS;
```

### License 
GNU GENERAL PUBLIC LICENSE 3

