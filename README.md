# 22-01-03 Cannot set Main Class

A way to reproduce:
```
./gradlew jar
java -jar build/libs/shadow-jar.jar
```

Getting error message:
```
no main manifest attribute, in build/libs/shadow-jar.jar
```