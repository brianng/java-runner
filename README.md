# Java Runner

Simple setup for running Java code in a terminal.

### Install

```
git clone git@github.com:brianng/java-runner.git
```

### Workflow

Make sure you’re in the `java-runner` directory.

```
cd java-runner
```

##### Write some code

Add your code to `Runner.java` so instead of looking like:

```
public class Runner {
  public static void main(String[] args) {
    System.out.println("Running...");

    // Your code goes here
  }
}
```

...it looks like:

```
public class Runner {
  public static void main(String[] args) {
    System.out.println("Running...");

    String awesomeString = "This is awesome!";
    System.out.println(awesomeString);
  }
}
```

##### Compile

```
javac -d classes Runner.java
```

##### Run

```
java -cp classes Runner
```

