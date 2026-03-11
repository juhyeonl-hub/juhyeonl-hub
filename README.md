# Hi, I'm JuHyeon Lee

![Email](https://img.shields.io/badge/Email-xx.juon%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)
![LinkedIn](https://img.shields.io/badge/LinkedIn-juhyeon--lee-0A66C2?style=flat&logo=linkedin&logoColor=white)
![Location](https://img.shields.io/badge/Location-Vantaa%2C%20Finland-green?style=flat)

---

Backend-oriented developer with hands-on experience in **system programming** and **networked applications**.

I graduated from **Hive Helsinki (42 Network)** in 2025, where I worked on project-based software development focused on operating systems, networking, and low-level problem solving. Most of my experience comes from building and debugging real programs in **C/C++**, and gradually extending that knowledge to **backend web systems**.

I'm particularly interested in how programs behave at runtime — process execution, resource management, and communication between components — and how those fundamentals translate into reliable backend services.

---

## What I'm Working On

- Exploring **network programming** and real-time communication systems
- Building a developer productivity platform ([PEER](https://github.com/juhyeonl-hub/PEER)) with Spring Boot + Next.js
- Interested in **concurrent systems** and how event-driven architectures can support scalable network services
- Curious about **embedded systems** and MCU-based applications — planning small experiments with C/C++ and sensors

---

## Selected Projects

### [minishell](https://github.com/juhyeonl-hub/minishell)
A Unix shell implemented in C.
- Supports pipes, redirections, heredoc, and signal handling
- Handles process creation and execution using `fork`, `execve`, and `wait`
- Uses tokenizing and an AST-based structure to control command flow

---

### [PEER](https://github.com/juhyeonl-hub/PEER)
An all-in-one developer platform — Scheduler + Algorithm Peer Review + Community.
- Built with **Spring Boot 3 + Java 21** (backend) and **Next.js 16** (frontend)
- Google OAuth 2.0 + JWT authentication with role-based access
- Deployed on local infrastructure via **Cloudflare Tunnel**

---

### [cub3d](https://github.com/juhyeonl-hub/cub3d)
A 3D game engine inspired by *Wolfenstein 3D*.
- Implemented in C using **DDA raycasting** algorithm
- Renders a 3D environment from a 2D map with textured walls
- Handles player movement, collision detection, and a basic game loop

---

### [philosophers](https://github.com/juhyeonl-hub/philo)
The Dining Philosophers Problem — concurrency with threads and mutexes.
- Each philosopher is a **thread**, each fork is a **mutex**
- Deadlock prevention via asymmetric fork ordering
- Millisecond-precision timing with busy-wait polling

---

### [push_swap](https://github.com/juhyeonl-hub/push_swap)
A sorting algorithm using two stacks and a limited set of operations.
- **Chunk-based sorting** optimized for minimum moves
- 100 elements in ~580 ops, 500 elements in ~5200 ops

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | C, C++, Java, JavaScript/TypeScript |
| **Backend** | Spring Boot, JPA/Hibernate, PostgreSQL, Redis |
| **Frontend** | Next.js, React, TailwindCSS |
| **DevOps** | Nginx, Cloudflare Tunnel, Flyway, Maven |
| **Tools** | Git, Valgrind, GDB, ThreadSanitizer |
