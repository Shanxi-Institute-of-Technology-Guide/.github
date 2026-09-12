<div align="center">

# Undergraduate Coursework Archive

### 本科课程实验与课程作业归档

Course labs, programming exercises, and coursework completed during my undergraduate studies.

本科阶段完成的课程实验、编程练习与课程作业。

![Coursework](https://img.shields.io/badge/Content-Coursework%20%26%20Labs-2f6f9f)
![Languages](https://img.shields.io/badge/Languages-C%20%7C%20C%2B%2B%20%7C%20Java%20%7C%20SQL-f08a24)
![Status](https://img.shields.io/badge/Status-Learning%20Archive-4c956c)

</div>

---

## About | 关于仓库

This repository archives solutions created for undergraduate course labs, assignments, and course projects. Each top-level directory corresponds to a distinct course topic or coursework project and includes English and Chinese documentation.

本仓库归档本科阶段完成的课程实验、作业与课程项目解决方案。每个一级目录对应一门课程主题或课程项目，并提供中英文说明文档。

These projects are learning records. They may reflect the tools, coding style, and engineering experience available at the time they were completed rather than production-ready standards.

这些项目是学习过程的记录，体现完成当时所掌握的工具、编码风格与工程经验，并不都以生产环境标准为目标。

---

## Coursework Map | 课程项目索引

| Directory | Course Topic | Main Technologies | Contents |
| --- | --- | --- | --- |
| `C-Program` | C Programming | C | Basic syntax, calculations, strings, arrays, sorting, and number exercises |
| `CPP-Program` | C++ Programming | C++ | Functions, classes, inheritance, polymorphism, and calculation exercises |
| `Data-struct-and-Algorithm` | Data Structures and Algorithms | C | AVL trees, Huffman coding, linked lists, expression evaluation, graphs, and sorting |
| `Operating-System` | Operating Systems | C | Banker's algorithm, CPU scheduling, synchronization, and storage management |
| `Java-Program` | Java Programming | Java | Console programs, objects, BMI, sorting, and Fibonacci exercises |
| `JavaEE-Program` | Java EE | Java, Maven, JDBC | JavaBean, database access, and transaction practice modules |
| `SQL-Develop` | Database Systems | SQL | DDL, integrity constraints, indexes, queries, nested queries, and triggers |
| `Student-information-manager` | Course Project | C++, CMake | Console-based student accounts, course selection, and grade management |
| `Gomoku` | Course Project | Java Swing | Desktop Gomoku with local accounts, score persistence, undo, and AI mode |
| `Academic_Map` | Course Project | Spring Boot, Vue 3, MySQL | Full-stack academic information application |
| `From_SXIT_to_World.github.io` | Course Project | Astro, Starlight, TypeScript | Student life and academic development guide site |

---

## Repository Structure | 仓库结构

```text
.
├── .github/
│   └── profile/                    # GitHub profile README
├── .vscode/                        # VS Code workspace settings
├── Academic_Map/
│   ├── Academic_Map/               # Spring Boot backend
│   ├── frontend/                   # Vue 3 frontend
│   └── sql/                        # Database initialization script
├── C-Program/                      # C programming exercises
├── CPP-Program/                    # C++ programming exercises
├── Data-struct-and-Algorithm/      # Data structures and algorithms
├── From_SXIT_to_World.github.io/   # Astro documentation-site course project
├── Gomoku/                         # Java Swing Gomoku course project
├── Java-Program/                   # Java programming exercises
├── JavaEE-Program/                 # Java EE practice modules
├── Operating-System/               # Operating system exercises
├── SQL-Develop/                    # Database and SQL exercises
├── Student-information-manager/
│   ├── include/                    # C++ header files
│   ├── src/                        # C++ implementation files
│   └── test/                       # CMake test files
└── .clang-format                   # Shared C and C++ formatting rules
```

Each project directory contains:

- `README.md`: English project overview and build or run instructions
- `README_CN.md`: Chinese project overview and build or run instructions
- Source code, configurations, and supporting files for that course exercise or project

---

## Technologies | 技术栈

The coursework uses the following languages and tools:

- **Languages:** C, C++, Java, SQL, JavaScript, TypeScript
- **Build tools:** GCC, G++, CMake, Maven, npm, Vite
- **Frameworks:** Spring Boot, Vue 3, Java Swing, Astro, Starlight
- **Data:** MySQL, H2, local text or database files

---

## Running Projects | 运行项目

Most C and C++ exercise files are standalone programs and should be compiled individually. For example:

```powershell
gcc -std=c17 -Wall -Wextra -o exercise source.c
.\exercise.exe
```

```powershell
g++ -std=c++20 -Wall -Wextra -o exercise source.cpp
.\exercise.exe
```

Projects with a build system provide project-specific instructions in their own README files. Common commands include:

```powershell
# CMake course project
cmake -S . -B build
cmake --build build

# Maven module
mvn clean package

# Java program
javac -d out *.java

# Frontend or documentation site
npm install
npm run dev
```

---

## Academic Integrity | 学术诚信

This repository is provided for learning, reference, and archival purposes. Do not submit its code as your own work for an active assignment, laboratory, or course project.

本仓库仅用于学习、参考与归档。请勿将其中代码作为正在进行的课程作业、实验或课程项目的个人提交内容。

Use the materials to understand ideas, reproduce results independently, and improve your own implementation.

请以理解思路、独立复现结果和改进个人实现为目的使用这些资料。

---

## License | 许可

Unless a subproject states otherwise, the included work is intended for educational and reference use. Consult the `LICENSE` file in an individual project before reuse.

除非子项目另有说明，仓库内容用于教育与参考。复用前请查看各项目中的 `LICENSE` 文件。
