# state management in jetpack compose

## why it's important

[![Maven Central](https://img.shields.io/maven-central/v/it.czerwinski.android.room/room-extensions)][room-extensions-release]
[![Sonatype Nexus (Snapshots)](https://img.shields.io/nexus/s/it.czerwinski.android.room/room-extensions?server=https%3A%2F%2Foss.sonatype.org)][room-extensions-snapshot]

Artifact `it.czerwinski.android.room:room-extensions` aggregates artifacts:
- `room-database`,
- `room-database-sql`.

You can either use `state extensions` or any combination of the other artifacts, whateve suits your project.

<details>
  <summary>Kotlin</summary>

  ```kotlin
  dependencies {
      implementation("androidx.room:room-runtime:2.4.2")
      implementation("it.czerwinski.android.room:room-extensions:[VERSION]")
  }
  ```
</details>
