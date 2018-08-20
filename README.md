# Remarks

| Tool                           | Command   |
| ----------------------------- |:---------:|
| [JUnit](#junit)               |           |
| [...](#...)                   | `...`     |


## Java
# Enum in switch statement

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

## JUnit

In JUnit 5, the tags `@BeforeEach` and `@BeforeAll` are the equivalents of `@Before` and `@BeforeClass` in JUnit 4.