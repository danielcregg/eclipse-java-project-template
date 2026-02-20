# Eclipse Java Project Template

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipse&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/danielcregg/eclipse-java-project-template?style=flat-square)

A starter template for Java projects using the Eclipse IDE. Provides a pre-configured project structure with a sample `Main` class, a `.classpath` configuration, and a comprehensive `.gitignore` for Eclipse and Java artifacts.

## Overview

This repository serves as a ready-to-use project template for Java development in Eclipse IDE. It eliminates the repetitive setup steps when starting a new Java project by providing a clean directory layout, an entry-point class, and sensible default configurations for version control.

## Features

- Pre-configured Eclipse `.classpath` for immediate import into the IDE
- Sample `Main.java` entry point with a standard `main` method
- Comprehensive `.gitignore` covering Eclipse metadata, compiled classes, and OS-specific files
- Organized package structure following Java naming conventions (`ie.gmit.testpackage`)

## Prerequisites

- [Java JDK](https://www.oracle.com/java/technologies/downloads/) 8 or higher
- [Eclipse IDE for Java Developers](https://www.eclipse.org/downloads/)

## Getting Started

### Installation

1. **Use this template** or clone the repository:

   ```bash
   git clone https://github.com/danielcregg/eclipse-java-project-template.git
   ```

2. **Import into Eclipse:**
   - Open Eclipse IDE
   - Go to `File` > `Import...`
   - Select `General` > `Existing Projects into Workspace`
   - Browse to the cloned directory and click `Finish`

### Usage

1. Right-click `Main.java` in the Package Explorer
2. Select `Run As` > `Java Application`

Modify the `Main.java` file or add new classes under the `src/` directory to build your own Java application. The template uses the package structure `ie.gmit.testpackage`, which you can rename to suit your project.

```
eclipse-java-project-template/
├── src/
│   └── ie/gmit/testpackage/
│       └── Main.java          # Entry point with sample main method
├── .classpath                 # Eclipse classpath configuration
└── .gitignore                 # Ignore rules for Eclipse and Java files
```

## Tech Stack

| Category | Technology                                             |
|----------|--------------------------------------------------------|
| Language | [Java](https://www.oracle.com/java/)                   |
| IDE      | [Eclipse](https://www.eclipse.org/)                    |
| Build    | Eclipse built-in compiler                              |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
