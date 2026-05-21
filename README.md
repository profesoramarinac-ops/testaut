javac -cp "lib/junit-platform-console-standalone-1.10.0.jar" -source 1.8 -target 1.8 -d bin src/Calculadora.java test/CalculadoraTest.java

javac -cp "lib/junit-platform-console-standalone-1.10.0.jar" -source 1.8 -target 1.8 -d bin src/*.java test/*.java

-----------------------

java -jar lib/junit-platform-console-standalone-1.10.0.jar --class-path bin --select-class CalculadoraTest

java -jar lib/junit-platform-console-standalone-1.10.0.jar --class-path bin --scan-class-path