http://www.gradle.org/downloads
gradle -version
gradle wrapper (в папці з майбутнім проектом)
gradlew init

новіверсії пакетів в версії ставити +


---
settings.gradle.kts і src в  папку visual_core

rootProject.name = "IIGame"

include ("visual_core")

./gradlew visual_core:run

якщо 
./gradlew run то запустить тільки той модуль де є 
plugins {
  
    application

`java-library`  для бібліотеки

}


https://github.com/openjfx/openjfx-docs/issues/55

```
val fileContent = Main::class.java.getResource("main.fxml").readText()
```