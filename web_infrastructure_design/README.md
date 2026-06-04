# Web Infrastructure Design

A series of progressively more robust web infrastructure designs, from a simple single-server stack to a fully secured and monitored distributed architecture.

Each file contains a whiteboard-style diagram, a walk-through of every component's role, and an honest analysis of the design's limitations.

---

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | [0-simple_web_stack](./0-simple_web_stack) | Single server — LAMP stack (Nginx + App Server + MySQL) behind one IP |

---

## Concepts covered

- DNS records (A, CNAME, NS, MX)
- Role of a web server vs. an application server
- Relational databases (MySQL)
- HTTP/HTTPS and TCP/IP communication
- Infrastructure weaknesses: SPOF, maintenance downtime, scalability limits

---

## Repository structure

```
holbertonschool-system_engineering-devops/
└── web_infrastructure_design/
    ├── README.md               ← this file
    └── 0-simple_web_stack      ← task 0
```

---

## Author

Project completed as part of the Holberton School curriculum — System Engineering & DevOps track.
