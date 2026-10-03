# Resume Builder in Java

A desktop **Resume Builder** application developed in Java Swing. The project provides a graphical interface for entering personal information, skills, qualifications, and work experience, with supporting login/sign-up flows and resume file generation.

## Features

- Java Swing desktop user interface
- Resume information entry through structured forms
- Personal information, skills, qualifications, and work-experience sections
- Login and sign-up screens
- Resume data written to a text file
- File browsing support
- UML documentation for the application design

## Tech Stack

- **Java**
- **Java Swing / AWT**
- **Object-Oriented Programming**
- **File I/O**
- **UML**

## Project Structure

The original project is organized under `Resume-Builder-Java-master/`.

```text
Resume-Builder-Java-master/
├── Resume Builder/
│   └── src/
│       ├── ResumeUI.java
│       ├── Login.java
│       ├── LoginPage.java
│       ├── SignUp.java
│       ├── SignUpDb.java
│       ├── NotSignedUp.java
│       ├── FileBrowser.java
│       └── FileWriterInput.java
├── resumebuilder.uml
├── UML-OOPS.png
└── res.jar
```

## Main Components

| Component | Purpose |
|---|---|
| `ResumeUI` | Main resume data-entry interface |
| `Login` / `LoginPage` | User login flow |
| `SignUp` / `SignUpDb` | Registration and user-data handling |
| `FileWriterInput` | Writes submitted resume information to a file |
| `FileBrowser` | File-selection/browsing functionality |

## Running the Project

### Option 1 — Run the provided JAR

```bash
java -jar res.jar
```

### Option 2 — Run from source

Open the project in an IDE such as IntelliJ IDEA or Eclipse, configure a compatible JDK, and run the appropriate Java entry point.

> The repository contains the original IDE-oriented project layout, so paths may need to be adjusted depending on the IDE.

## UML

The repository includes `resumebuilder.uml` and `UML-OOPS.png` for understanding the class relationships and application design.

## Notes

This is a desktop Java project created to demonstrate GUI development, object-oriented design, and file-based resume generation.

## Future Improvements

- Replace file-based credential storage with a database and secure password hashing
- Add PDF resume generation
- Improve validation and error handling
- Add multiple resume templates
- Introduce a cleaner Maven/Gradle build structure
- Add automated tests

## Author

**Prathamesh Tadas**

GitHub: https://github.com/prathameshtadas
