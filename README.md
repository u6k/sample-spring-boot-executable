# sample-spring-boot-executable

Spring BootのExecutable JARのサンプルコードです。

## 確認したいこと

* Executable JARを作成して、`java -jar`で起動すること。
* Linuxサービスに登録して、OS起動時に起動すること。
    * `.conf`が読み込まれること。

* Mavenプロジェクトを作成

```
mvn -B archetype:generate \
    -DarchetypeGroupId=org.apache.maven.archetypes \
    -DgroupId=me.u6k.sample \
    -DartifactId=sample-spring-boot-executable
```

[Maven – Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/)
