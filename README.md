# gradle-test-exception-npe
Public repro of a Gradle NullPointerException obscuring a test error

To repro, run: `./gradlew test --stacktrace`

Oddly, the NPE doesn't happen when `--info` is used.
