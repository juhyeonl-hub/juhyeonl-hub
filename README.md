# Hi, I'm JuHyeon Lee

[![Email](https://img.shields.io/badge/Email-xx.juon%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:xx.juon@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-juhyeon--lee-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juhyeon-lee-54aa1a223)
[![Location](https://img.shields.io/badge/Location-Vantaa%2C%20Finland-green?style=flat)](https://www.google.com/maps/place/Vantaa,+Finland)

---

I worked for about 2 years as a backend developer in **South Korea's financial sector**. At Hyundai Capital & Hyundai Commercial, I handled AML system ESB integration and B2B mobile office platform development. At the Korean National Police Agency, I led a full rebuild of the identity verification platform. My main stack was **Java / Spring Boot / Oracle**, with some frontend work in React and Node.js.

In November 2024, I moved to Finland to study **C/C++ systems programming** from the ground up at **Hive Helsinki (42 Network)**. I've completed system-level projects including a Unix shell, a threading simulation, a raycasting program, and more — all built from scratch without frameworks.

Currently based in Helsinki, looking for backend developer opportunities.

---

## Projects

### [minishell](https://github.com/juhyeonl-hub/minishell)
A Unix shell implemented in C.
- Supports pipes, redirections, heredoc, and signal handling
- Handles process creation and execution using `fork`, `execve`, and `wait`
- Uses tokenizing and an AST-based structure to control command flow

---

### [cub3d](https://github.com/juhyeonl-hub/cub3d)
A raycasting program inspired by *Wolfenstein 3D*.
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

### [PEER](https://github.com/juhyeonl-hub/PEER)
A side project — all-in-one developer platform with Scheduler, Algorithm Peer Review, and Community.
- Built with **Spring Boot 3 + Java 21** (backend) and **Next.js 16** (frontend)
- Google OAuth 2.0 + JWT authentication with role-based access
- Deployed on local infrastructure via **Cloudflare Tunnel**

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | C, C++, Java, JavaScript/TypeScript |
| **Backend** | Spring Boot, JPA/Hibernate, PostgreSQL, Redis |
| **Frontend** | Next.js, React, TailwindCSS |
| **DevOps** | Nginx, Cloudflare Tunnel, Flyway, Maven |
| **Tools** | Git, Valgrind, GDB, ThreadSanitizer |
