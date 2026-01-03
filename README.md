### Compile jlox
    javac java/com/craftinginterpreters/lox/*.java

### Run jlox
    java -cp java com.craftinginterpreters.lox.Lox

### Run jlox with source code file
    java -cp java com.craftinginterpreters.lox.Lox script_01.lox

# Generating classes in chap 5
### compile
    javac java/com/craftinginterpreters/tool/GenerateAst.java

### run
    java -cp java com.craftinginterpreters.tool.GenerateAst java/com/craftinginterpreters/lox

