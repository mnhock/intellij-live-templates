# JUnit

## @Test annotated method

```java
@org.junit.jupiter.api.Test
void test$methodName$() {
    $code$
}
```

### General configuration
- Abbreviation: *test*
- Scope: Java - declaration
- Options enabled: Reformat according to style, Use static import if possible, Shorten FQ names

## @BeforeEach and @AfterEach annotated methods

```java
@org.junit.jupiter.api.BeforeEach
void beforeEach() {
    $code$
}
```

```java
@org.junit.jupiter.api.AfterEach
void afterEach() {
    $code$
}
```

### General configuration
- Abbreviation: *beforeEach*, *afterEach*
- Scope: Java - declaration
- Options enabled: Reformat according to style, Use static import if possible, Shorten FQ names

## @BeforeAll and @AfterAll annotated methods

```java
@org.junit.jupiter.api.BeforeAll
static void beforeAll() {
    $code$
}
```

```java
@org.junit.jupiter.api.AfterAll
static void afterAll() {
    $code$
}
```

### General configuration
- Abbreviation: *beforeAll*, *afterAll*
- Scope: Java - declaration
- Options enabled: Reformat according to style, Use static import if possible, Shorten FQ names

## assertAll Assertion

```java
org.junit.jupiter.api.Assertions.assertAll(
    () -> org.junit.jupiter.api.Assertions.assertEquals("",  $code$),
    () -> org.junit.jupiter.api.Assertions.assertEquals("", "")
);
```

### General configuration
- Abbreviation: *assertAll*
- Scope: Java - declaration
- Options enabled: Reformat according to style, Use static import if possible, Shorten FQ names