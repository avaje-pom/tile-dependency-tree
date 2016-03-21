# tile-dependency-tree
Includes the dependency tree and list in the build of an artifact

## Example use

In your project pom under build / plugins add the tiles-maven-plugin with the following configuration. Note that this example also brings in the java-compile tile.

```xml
      <!-- maven build / plugins -->

      <plugin>
        <groupId>io.repaint.maven</groupId>
        <artifactId>tiles-maven-plugin</artifactId>
        <version>2.8</version>
        <extensions>true</extensions>
        <configuration>
          <tiles>
            <tile>org.avaje.tile:dependency-tree:1.1</tile>
          </tiles>
        </configuration>
      </plugin>

```
