# testJavaSMT
#JavaSMT and SMT Solvers

This is a demo of how to use java-smt based on the template and tutorial from
[sosy-lab/java-smt](https://github.com/sosy-lab/java-smt/blob/master/doc/Getting-started.md).
i use a pure Java-based SMT solver. please refer to the above tutorial.
First, we show how to encode and solve a simple emoji math puzzle in class [EmojiSolver]
(src/main/java/de/buw/fm4se/java_smt/EmojiSolver.java). This example only uses integer arithmetic.

Second, we show how to encode a PC configuration problem in class
[PCConfigSolver](src/main/java/de/buw/fm4se/java_smt/PCConfigSolver.java).
This example combines propositional logic and simple integer arithmetic
