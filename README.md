### **Recommended level:**
- Junior / Middle

### **Topics:**
- JVM utilities to monitor and troubleshoot Java applications
- Common mistakes in Java programs and how to identify them: OutOfMemory, deadlocks, etc.

### **Required time for the course:**
- **Lectures:** ~5h
- **Homework:** ~8h

### **Lectures:**
- [About JVM Performance Tuning](https://docs.oracle.com/cd/E13222_01/wls/docs103/perform/JVMTuning.html#wp1131630)
- [About JVM Performance Tuning at Twitter](https://www.youtube.com/watch?v=8wHx31mvSLY)
- [Troubleshooting Memory Problems in Java Applications](https://www.youtube.com/watch?v=iixQAYnBnJw)

Here are two main articles you need to go through before jumping into the homework:
- [Monitoring Tools](https://docs.oracle.com/en/java/javase/21/management/overview-java-se-monitoring-and-management.html#GUID-EA3CFF69-F0D3-47AB-9AED-EF1CBF7F2B24)
- [Latency and Throughput](https://www.linkedin.com/learning/java-concurrency-troubleshooting-latency-and-throughput/welcome-to-high-performing-java-applications?u=2113185)

Also, please feel free to visit these references to get more familiar with the tools:
- [Java 21 Troubleshoot Guide](https://docs.oracle.com/en/java/javase/21/troubleshoot/general-java-troubleshooting.html)

### **Prerequisites**
| JDK  | 21.x | [Java 21](https://docs.oracle.com/en/java/javase/21/install/overview-jdk-installation.html)   |
|------|------|---------------------------------------------------------------------------------------------|
| Maven| 3.9.x| [Apache Maven](http://maven.apache.org/download.cgi)                                          |

#### Webinar script for presenter:
- We will work with Java 21 tutorials.
- We use only tools provided in JDK. In most cases, they are enough to have.

### **Java Flight Recorder**
Java Flight Recorder (JFR) is a monitoring tool that collects information about the events in a JVM during the execution of Java applications.

JFR is designed to affect the performance of a running application as little as possible.

JFR saves data about the events in a single output file, `flight.jfr`.

### **References**
- [Troubleshooting Guide](https://docs.oracle.com/en/java/javase/21/troubleshoot/general-java-troubleshooting.html)
- [JVM Tool Interface (JVM TI)](https://docs.oracle.com/en/java/javase/21/docs/specs/jvmti.html)
- [VisualVM Standalone](https://visualvm.github.io/)
- [Analyzing a Heap Dump Using OQL](https://visualvm.github.io/documentation.html)
- [Java Mission Control](https://github.com/openjdk/jmc)
- [Creating and Analyzing Java Heap Dumps](https://reflectoring.io/create-analyze-heapdump/)
- [Java Heap Dump Analyzer](https://dzone.com/articles/java-heap-dump-analyzer-1)
- [Understanding Memory Leaks in Java](https://www.baeldung.com/java-memory-leaks)

### **Self-paced**
- [Monitoring and Troubleshooting](https://learn.epam.com/detailsPage?id=19bdc071-ebc7-4c64-bb1b-035e398fbd86&source=EXTERNAL_COURSE)
