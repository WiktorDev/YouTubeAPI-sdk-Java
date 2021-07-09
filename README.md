# YouTubeAPI-sdk-java

### Library installation
Maven
```xml
<dependency>
    <groupId>ga.wiktor.dev</groupId>
    <artifactId>YTAPI</artifactId>
    <version>1.0</version>
</dependency>
```
```xml
<repository>
    <id>api</id>
    <name>ytapi</name>
    <url>https://maven.ycode.xyz/releases</url>
</repository>
```
### Creating an instance

```java
YTAPI api = new YTAPI("your_api_key");
```
### Example

```java
package your.package;

import ga.wiktor.dev.yt.api.YTAPI;

public class Main {
    public static void main(String[] args) {
        YTAPI api = new YTAPI("your_api_key");
        System.out.println(api.getChannel("https://www.youtube.com/channel/UCY9W5kdyCi45cT68CBSZQAQ"));
    }
}

```
##Kiedys skoncze dokumentacje 
