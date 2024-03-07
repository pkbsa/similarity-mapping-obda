# similarity-mapping-obda# Mapping Service

![Java](https://img.shields.io/badge/Java-8%2B-blue.svg)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-3.0%2B-green.svg)
![Gradle](https://img.shields.io/badge/Gradle-7.0%2B-blue.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

The Mapping Service is a Java-based web application that allows users to add new mappings to an existing mapping file based on a similarity file and a user-defined threshold value. This service is built using Java, Thymeleaf, and Gradle.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Adding Mappings](#adding-mappings)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- Load mapping files in a user-friendly interface.
- Upload similarity files and set a threshold for adding new mappings.
- View the original mapping and the result with added mappings.
- Download the updated mapping.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java 8 or higher installed.
- Gradle 7.0 or higher installed.
- A modern web browser (Chrome, Firefox, Edge, etc.).

#### Install Gradle 

- On Mac OS X
  - `brew install gradle`
- On Windows
  - Download from Gradle site.

  - Unzip the Gradle download to the folder to which you would like to install Gradle, eg. “C:\Program Files”. The subdirectory gradle-x.x will be created from the archive, where x.x is the version.

  - Add location of your Gradle “bin” folder to your path. Open the system properties (WinKey + Pause), select the “Advanced” tab, and the “Environment Variables” button, then add “C:\Program Files\gradle-x.x\bin” (or wherever you unzipped Gradle) to the end of your “Path” variable under System Properties. Be sure to omit any quotation marks around the path even if it contains spaces. Also make sure you separated from previous PATH entries with a semicolon “;”.

  - In the same dialog, make sure that JAVA_HOME exists in your user variables or in the system variables and it is set to the location of your JDK, e.g. C:\Program Files\Java\jdk1.7.0_06 and that %JAVA_HOME%\bin is in your Path environment variable.

  - Open a new command prompt (type cmd in Start menu) and run gradle –version to verify that it is correctly installed.

### Installation

1. Clone this repository:
`git clone https://github.com/realearn-jaist/sim-preference-elh.git`

2. Change to the project directory:
`cd vkg-sim-elh` 

3. Build the project
`gradle build` 

4. Run the project
`gradle bootRun`

4. Open your web browser and navigate to `http://localhost:8080` to access the Mapping Service.

## Usage

### Adding Mappings

1. Click the "Load Mapping File (.obda)" button to upload your existing mapping file.

2. Click the "Load Similarity File" button to upload your similarity file. The similarity file used in this project is based on the [Sim-Preference-ELH](https://github.com/realearn-jaist/sim-preference-elh.git) project.

3. Set the threshold value. Only mappings with a similarity degree greater than this value will be added.

4. Click the "Perform Mapping" button to add new mappings based on the similarity file and threshold.

5. View the original mapping and the result with added mappings.

6. Click the "Download Mapping" link to download the updated mapping.

## Contributing

Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to thank the open-source community for their contributions and support. Additionally, we acknowledge the following projects and resources for their valuable contributions:

- Ontop-VKG: Ontop-VKG is a project that provides a Virtual Knowledge Graph (VKG) system based on the Ontop framework.
- Ontop API Examples: The Ontop API Examples repository offers a collection of examples demonstrating the usage of the Ontop API for interacting with Virtual Knowledge Graphs programmatically.

These resources have been instrumental in the development and enhancement of the Mapping Service.

## Reference

