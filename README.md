Updater  
[![Build Status](https://ci.dustplanet.de/job/updater/badge/icon)](https://ci.dustplanet.de/job/updater/)
[![Known Vulnerabilities](https://snyk.io/test/github/timbru31/updater/badge.svg)](https://snyk.io/test/github/timbru31/updater)
===

Updater - Easy, Safe, and Policy-Compliant auto-updating for your plugins

This is a fork of gravitylow's awesome Updater project that's been around for years.  
Thanks a bunch for originally making this!

## Usage 

#### The old usage guide of gravitylow is worth a read, too! It's available on Bukkit: https://bukkit.org/threads/96681

### Releases (stable)

Add the following repo to your `pom.xml`:

```xml
    <repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
    </repositories>

   <dependencies>
        <dependency>
            <groupId>com.github.timbru31</groupId>
            <artifactId>updater</artifactId>
            <version>updater-4.0.0</version> <!-- Or other releases -->
        </dependency>
    </dependencies>
```

### Development (**unstable**)

Add the following repo to your `pom.xml`:

```xml
    <repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
    </repositories>

   <dependencies>
        <dependency>
            <groupId>com.github.timbru31</groupId>
            <artifactId>updater</artifactId>
            <version>master-SNAPSHOT</version>
        </dependency>
    </dependencies>
```

## JavaDocs

The JavaDocs can be found here: https://ci.dustplanet.de/job/updater/javadoc/

---
Built by (c) Tim Brust and contributors. Released under the MIT license.
