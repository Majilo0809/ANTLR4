# ANTLR4-CALCULADORA
## Requerimientos
Tener instalado:
  Java JDK 17 o superior.
  ANTLR 4.13.x configurado en el sistema.

Generación del parser y visitor mediante:

antlr4 -no-listener -visitor Expr.g4

Compilación:
javac *.java

Ejecución:

java Calc archivo.expr

La actividad contiene:

- Archivo de gramática (Expr.g4)
- Clases generadas por ANTLR
-  Clase EvalVisitor para evaluación
-  Clase Calc como punto de entrada
-  Archivos de prueba (.expr)
