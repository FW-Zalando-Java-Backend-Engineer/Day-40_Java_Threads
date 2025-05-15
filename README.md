# 📚 Java Threads - Day 40 Recap

Welcome to **Day 40** of our Java Backend Bootcamp! Today was all about **Java Threads**, one of the most powerful tools in a developer’s toolbox for writing efficient, concurrent applications. Below you’ll find everything we covered, complete with links to code, exercises, recordings, and reading materials.

---

## 🧵 What We Covered Today

### ✅ Topics
- What is a Java Thread?
- Why we use Threads – Benefits of Concurrency
- How to create threads using `Runnable` and `Thread`
- Understanding the Thread Lifecycle
- Methods: `start()`, `run()`, `sleep()`, `join()`, `isAlive()`
- Real-world project: Email Notification System using Threads
- Unit testing threaded logic with JUnit 5
- Best practices when using threads

---

## 💻 Live Coding Demo

📎 **GitHub Repo (Main Project Code)**  
👉 [Email Notification System](https://github.com/FW-Zalando-Java-Backend-Engineer/email_notification_system)

---

## 📹 Session Recording

🎥 **Zoom Recording of Day 40**  
👉 [COMMING SOON: ZOOM RECORDING LINK HERE]

---
## 📂 Live Boards
[Day 40: Agenda](https://docs.zoom.us/doc/SGXAP2KsRk2AowaH7RwRRA)
[Can a thread go from Blocked or Waiting directly to Running?](https://zoom.us/wb/doc/8i4ylghiTBSY6k-On_EsNg)
[Thread Lifecycle Diagram (Excalidraw)](https://media.geeksforgeeks.org/wp-content/uploads/20240318155846/Lifecycle-and-States-of-a-Thread-in-Java-1.png)

---

## 🧪 Practice Exercises

🧰 **Exercise GitHub Repo**  
Includes:
- Practice on creating multiple threads
- Simulating concurrent tasks
- Thread-safe data access
- Testing concurrency

👉 [Logging / Audit Trail Writer (Simulation)](https://github.com/FW-Zalando-Java-Backend-Engineer/Logging-Audit-Trail-Writer)

---

## 📂 Project Summary: Email Notification System

We built a Java app to simulate sending emails concurrently using Threads. Key highlights:
- Implemented `Runnable` to define thread logic
- Created multiple threads with `Thread`
- Used `start()` and `join()` to control execution
- Wrote unit tests using JUnit 5

📄 Classes:
- `EmailSender`: Runnable task to simulate sending an email
- `EmailNotificationApp`: Main class to create and start threads
- `EmailSenderTest`: Unit tests

---

## 🧪 Unit Tests We Wrote

- Validated thread execution using `assertDoesNotThrow`
- Used `join()` to ensure thread completion
- Tested concurrent execution using `AtomicInteger`
- Validated exception handling with `UncaughtExceptionHandler`
- Used JUnit 5’s `@Timeout` for long-running threads

---

## 🧠 Concepts to Remember

| Concept | Description |
|--------|-------------|
| Thread | A lightweight subprocess |
| Runnable | Interface to define the task to be run by a thread |
| start() | Begins the thread execution |
| run() | Contains the logic for the thread |
| join() | Waits for the thread to finish |
| sleep() | Pauses execution temporarily |
| isAlive() | Checks if the thread is still running |

---

## 📚 References & Further Reading

- [Java Thread Lifecycle - Baeldung](https://www.baeldung.com/java-thread-lifecycle)
- [Thread Class - JavaDocs](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html)
- [GeeksForGeeks - Thread Basics](https://www.geeksforgeeks.org/java-threads/)
- [Java Thread Join Explained - Baeldung](https://www.baeldung.com/java-thread-join)
- [Java Threads Overview - W3Schools](https://www.w3schools.com/java/java_threads.asp)

---

## 🔁 Next Steps

In the next session (Day 41), we’ll move into:
- **Thread Synchronization**
- **Executors and Thread Pools**
- **Callable, Future, and Scheduled Tasks**

Until then, try completing the exercises and revisit today’s code. And remember...

> "Thread responsibly – unless you want a surprise deadlock at midnight." 😄



