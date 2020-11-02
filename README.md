# jacoco4sbt - Code Coverage via JaCoCo in sbt

This is a direct clone of sbt-jacoco updated for jacoco 0.8.6, sbt 1.3.4, Scala 2.12.x, and newer jvms.
One additional feature is that Scala 3's .tasty files are copied into the instrumented code area.  This is essential for test code
that requires reading the .tasty files.

The sbt-jacoco project seems a bit stagnant right now, but if it revivies and gets updated this project may no longer be needed.
