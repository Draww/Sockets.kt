# Sockets

### Use it

- Gradle: add this to your build.gradle

      repositories {
          maven { url 'https://mymavenrepo.com/repo/NIp3fBk55f5oF6VI1Wso/' }
      }

      dependencies {
          compile 'fr.rhaz:sockets:3.0'
      }


- Maven: add this to your pom.xml

      <repositories>
        <repository>
            <id>rhazdev</id>
            <url>https://mymavenrepo.com/repo/NIp3fBk55f5oF6VI1Wso/</url>
        </repository>
      </repositories>

      <dependencies>
        <dependency>
            <groupId>fr.rhaz</groupId>
            <artifactId>sockets</artifactId>
            <version>3.0</version>
            <scope>compile</scope>
        </dependency>
      </dependencies>
