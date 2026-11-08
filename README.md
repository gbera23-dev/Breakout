# Breakout

A Java implementation of the classic **Breakout** arcade game, built on the ACM Java Task Force graphics library.

## Contents

| File | Description |
|---|---|
| `Breakout.java` | Standard single-player game: a paddle, a ball and a wall of bricks (400×600 window). |
| `Breakoutextension.java` | Two-player extension: two paddles, two balls and two "worlds" separated by a wall of bricks. Each player has three lives and loses one when their *own* ball enters their territory. If all bricks are destroyed, a showdown phase with smaller paddles decides the winner. |

## Requirements

- Java (JDK 8+ recommended)
- The ACM Java library (`acm.jar`, packages `acm.graphics`, `acm.program`, `acm.util`) on the classpath. It is not bundled in this repo.

## Run

```bash
javac -cp acm.jar Breakout.java
java  -cp .:acm.jar Breakout
```

Replace `Breakout` with `Breakoutextension` to play the two-player version.

## Notes

Written as a university programming-methodology assignment by Giga Beradze.
