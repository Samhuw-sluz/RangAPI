# Instalation (Maven):
## Step1:
Add the JitPack repository to your build file:
```xml
<repository>
  <id>jitpack.io</id>
  <url>https://jitpack.io</url>
</repository>
```

## Step2:
Add the dependency
```xml
<dependency>
	    <groupId>com.github.Samhuwsluz</groupId>
	    <artifactId>RangAPI</artifactId>
	    <version>Tag</version>
	</dependency>
```

# Usage
## Importing the API
```java
import  ch.ksrminecraft.rangAPI.RangAPI;
```

## Add RangAPI as Bukkit dependency (plugin.yml)
```yaml
softdepend: ['RangAPI']
```

## Loading Plugin instance
```java
 RangAPI api = (RangAPI) this.getServer().getPluginManager().getPlugin("RangAPI");
```