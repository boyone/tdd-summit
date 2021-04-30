# Mockito

## pom.xml

Add mockito to dependencies

```xml
<dependencies>
    <dependency>
        <groupId>org.mockito</groupId>
        <artifactId>mockito-junit-jupiter</artifactId>
        <version>3.9.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>
```

## Annotation

- @ExtendWith(MockitoExtension.class)
- @Mock

```java
@ExtendWith(MockitoExtension.class)
public class ClasUnderTest {
    @Mock
    DependencyClass mockClass;
}
```

## Method

- when
- thenReturn
- thenThrow
- verify
- times

Setting behavior of dependencies `when` call with `get(0)`, `then return "first"`.

```java
when(mockedClass.get(0)).thenReturn("first");
```

Setting behavior of dependencies `when` call with `get(0)`, `then throw IndexOutOfBoundsException`.

```java
when(mockedClass.get(0)).thenThrow(new IndexOutOfBoundsException());
```

Verify behavior of dependencies it should be called with method `add` and value `"one"`.

```java
verify(mockedClass).add("one");
```

Verify behavior of dependencies it should be called with method `add`, value `"one"`, and only 1 time.

```java
verify(mockedClass, times(1)).add("one");
```

## Reference
- [https://javadoc.io/doc/org.mockito/mockito-core/latest/org/mockito/Mockito.html](https://javadoc.io/doc/org.mockito/mockito-core/latest/org/mockito/Mockito.html)