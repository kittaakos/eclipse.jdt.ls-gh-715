# eclipse.jdt.ls-gh-715
Customized Java LS with semantic highlighting capabilities

### Building a new version of the LS from eclipse.jdt.ls:
 - Execute the following in the root of the eclipe.jdt.ls
```
./mvnw clean verify && cd org.eclipse.jdt.ls.product/target/repository/ && tar -czf ../../../jdt-language-server-latest.tar.gz ./config_linux/ ./config_mac/ ./config_win/ ./plugins/ ./features/ && cd ../../..
```
 - Copy the arhive here.
 - Push.
