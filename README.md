# Resume Pro – Java Swing + iText

A simple **Java Swing** application to create resumes and export them as **PDF** using the **iText** library.

##  Features
- Clean Swing GUI to enter details (name, email, phone, summary, education, skills, experience)
- One-click **PDF generation**
- Minimal code and easy setup
- Works fully offline

##  Requirements
- Java 8+ (JDK)
- iText 5.5.13.x (placed in `lib/`)

##  How to Run
#Windows
javac -cp "lib/*" src/Main.java
java  -cp "lib/*;src" Main

#macOS/Linux
javac -cp "lib/*" src/Main.java
java  -cp "lib/*:src" Main
