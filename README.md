# Service84.IO Download Dependencies Gradle Plugin

## License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Usage
This plugin adds a task to download all dependencies in a gradle project.  This is to support docker builds by creating a layer that only needs to change when the build.gradle file changes.

    plugin {
      id 'io.service84.downloaddependencies' version '0.5.0-SNAPSHOT'
    }

To download the dependencies run the following task

    gradle downloadDependencies

### Availability
This library is available from Maven Central with more information at
https://mvnrepository.com/artifact/io.service84.downloaddependencies/io.service84.downloaddependencies.gradle.plugin

TODO make this available on the Gradle Plugin Portal

## Build
This is a Java 11 project that builds best with Gradle 6.3

## Versioning
This project makes a best effort to comply with [SemVer](https://semver.org/)
