# Remarks

| Tool                          |
| ----------------------------- |
| [IntelliJ](#IntelliJ)         |
| [Java](#Java)                 |
| [JUnit](#junit)               |
| [Kubernetes](#Kubernetes)     |
| [Maven](#Maven)               |
| [...](#...)                   |

# IntelliJ
## Shortcuts
Code → Optimize Imports...

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>O</kbd>


# Java
## Enum in switch statement

```java
public class C_EnumTest {
    public enum MethodType {
        DOUBLE,LIST,STRING,ARRAYLIST,FLOAT,LONG;
    }
    public static void main( String[] args ) {
        String value = "DOUBLE";
        switch( MethodType.valueOf( value ) ) {
        case DOUBLE:
            System.out.println( "It's a double" );
            break;
        case LIST:
            System.out.println( "It's a list" );
            break;
        }
    }
}
```
Source: https://stackoverflow.com/questions/2836286/enums-use-in-switch-case

## Serialization and Deserialization

-------- serialization ----->

OBJECT..................STREAM

<------ deserialization -----

    

## JUnit

In JUnit 5, the tags `@BeforeEach` and `@BeforeAll` are the equivalents of `@Before` and `@BeforeClass` in JUnit 4.


# Kubernetes

Creating a secret manually: https://kubernetes.io/docs/concepts/configuration/secret/


# Maven

## Maven CLI Options Reference

![alt text](https://i.stack.imgur.com/wqati.png "Maven CLI Options Reference")

Source: http://maven.apache.org/ref/3.1.0/maven-embedder/cli.html


![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
