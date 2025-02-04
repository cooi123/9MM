## Running Game

### Generation

```
javac -d ./build ./Core/*.java ./Game/*.java ./UI/*.java ./PlayerPawn/*.java
```

in the src directory of the code in order to build the files.

You then change directories into the build folder

```
cd build
```

Then you run the following command

```
jar cvfe game.jar Game.Main Core/*.class Game/*.class UI/*.class ./PlayerPawn/*.class
```

in order to build the jar file.

Otherwise one can be generated using a specific IDE such as [IntelliJ](https://www.jetbrains.com/help/idea/compiling-applications.html#package_into_jar) or [Eclipse](https://help.eclipse.org/latest/index.jsp?topic=%2Forg.eclipse.jdt.doc.user%2Ftasks%2Ftasks-37.htm).

Afterwards the game can be run using the same command as in Download:

```
java -jar jar_name.jar
```
