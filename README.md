# Disk Scanner

## 📝 Description
**Disk Scanner** is a web application designed for monitoring and analyzing changes in the file system on your disk. Built using the Spring Framework, this tool helps you track the evolution of your directories over time.

### Key Features:
* **Snapshots:** Take comprehensive snapshots of file structures and attributes on your disk.
* **Comparison Engine:** Detect new files, deleted files, and modified file sizes between snapshots.
* **Integrity Control:** Track file consistency using **SHA checksums** to spot hidden changes.
* **Change Log:** View a detailed history and log of all file system events.

---

## 🛠️ Technologies
* **Java 8 SE** (Optionals, Streams API, LocalDateTime)
* **Spring Boot** (Automatic configuration and rapid application launching)
* **Spring MVC** (Clean separation of concerns using the Model-View-Controller pattern)
* **Thymeleaf** (Server-side HTML templating engine)
* **Maven** (Project management and build automation)

---

## 🚀 Getting Started

### Prerequisites
* Java JDK 8 or higher
* Maven 3.6+

### Installation & Launch
1. Clone the repository:
   ```bash
   git clone https://github.com/kharisovruslan/disk-scanner
   ```
2. Navigate to the project root:
   ```bash
   cd disk-scanner
   ```
3. Build and run the application using Maven:
   ```bash
   mvn spring-boot:run
   ```
4. Open your browser and navigate to `http://localhost:8080`.