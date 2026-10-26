# Educational Processing Examples

A small Java project for exploring graphics, animation, and user interaction with [Processing](https://processing.org/).

## Bouncing circle

The [`Main.java`](src/main/java/com/javiergs/processing/Main.java) example extends `PApplet` and demonstrates:

- Drawing and animating a circle.
- Bouncing off window boundaries.
- Changing the circle's color with the **spacebar**.
- Detecting mouse clicks on the circle.

## Run

Requires **JDK 17+** and Maven.

```sh
mvn compile exec:java
```

The example was adapted from the `spiderworld` package in the original [teaching-library](https://github.com/javiergs/teaching-library) repository.
