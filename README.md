# Compilation and Execution Guide

To run this project, ensure you have JDK 6 or higher installed on your system. The latest JDK version is not recommended due to incompatibility.

## 1. Compilation
This project uses Apache Ant with the `build.xml` file. To compile the emulator:

1. Open your terminal in the root directory.

2. Run the command: `ant` (or use your IDE to run the build.xml file).

3. Once compilation is complete, you must manually move the resulting .jar file to the `/lib` folder of your project so it can locate the necessary dependencies.

## Execution
Once the .jar file is in the /lib folder, initialize the emulator by running the batch file:

On Windows: Double-click init.bat or run it from the terminal.

Note: If you experience runtime issues, verify that your JAVA_HOME environment variable is correctly set to point to your JDK 6 or later installation.

---

## Credits
* Based on the original work of [jps2].

* Based on components from `pcsx2` and `jpcsp`.
