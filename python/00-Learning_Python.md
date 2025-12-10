
## Python Learning Guide  
*A roadmap from “Hello, World!” to architect‑level proficiency*  

> **TL;DR** –  
> 1️⃣ *Beginner* – 4 weeks (core syntax, first scripts, debugging)  
> 2️⃣ *Intermediate* – 8 weeks (OOP, libraries, projects)  
> 3️⃣ *Advanced* – 12 + weeks (async, performance, system design, frameworks)  

Feel free to bend the timeline to match your pace; the most important thing is *consistent practice* and *building projects*.

---

### 1. Pre‑course Checklist

| Item | Why it matters | How to set it up |
|------|----------------|------------------|
| **Python 3.12+** (latest stable) | Future‑proof, latest syntax | `pyenv install 3.12.3` or `brew install python` |
| **VS Code / PyCharm** | Good IDE, integrated terminal, debugger | VS Code + Python extension |
| **Git + GitHub** | Version control, collaboration | `git init`, create repo, push |
| **Virtualenv / venv** | Isolate project deps | `python -m venv venv && source venv/bin/activate` |
| **Linters & Formatters** | Clean code, PEP 8 | `pip install flake8 black mypy` |
| **Testing framework** | Write tests early | `pip install pytest` |
| **Basic command line** | Run scripts, pip, Git | Terminal fundamentals |

> **Tip** – Keep a running “Project Ideas” file; we’ll fill it in later.

---

## 2. Beginner Level (Weeks 1‑4)

| Week | Focus | Deliverable | Resources |
|------|-------|-------------|-----------|
| **1** | Syntax & Basics | Write a script that prints “Hello, Python!” and asks for user input | *Automate the Boring Stuff* – ch. 1‑2; [Real Python – Intro](https://realpython.com/python-first-steps/) |
| **2** | Data types & control flow | Create a simple calculator, a “guess the number” game | *Python Crash Course* – ch. 4‑6; practice on **Exercism** (Python track) |
| **3** | Functions & modules | Build a reusable library of utility functions (e.g., string helpers) | *Python for Everybody* – ch. 7‑8; [docs](https://docs.python.org/3/tutorial/modules.html) |
| **4** | Error handling & file I/O | Read a CSV, compute statistics, write results to a file | *Fluent Python* – ch. 1; **Practice**: read `pandas_tips.csv` from a repo |

### Mini‑Project: “Contact Book”  
- CLI app storing name, phone, email.  
- Save/load from a JSON file.  
- Bonus: use `argparse` for command‑line options.

---

## 3. Intermediate Level (Weeks 5‑12)

| Week | Focus | Deliverable | Resources |
|------|-------|-------------|-----------|
| **5** | Object‑Oriented Programming | Model a `BankAccount` class with methods, inheritance, polymorphism | *Python Crash Course* – ch. 10‑11; **Exercise**: `Vehicle` base class, `Car`/`Bike` subclasses |
| **6** | File & Data Persistence | Pickle, shelve, SQLite via `sqlite3` | *Python for Data Analysis* – ch. 6 |
| **7** | Decorators, generators | Write a timing decorator; use a generator to stream file lines | *Fluent Python* – ch. 5; *Effective Python* – Item 20 |
| **8** | Context managers & the `with` statement | Create a custom context manager that logs entry/exit | *Real Python – Context Managers* |
| **9** | Concurrency basics | Threading vs. Multiprocessing; a producer‑consumer demo | *Python 3: The Complete Guide* – ch. 24 |
| **10** | Async/Await | Build a simple async web scraper with `aiohttp` | *Asyncio Recipes* – ch. 3 |
| **11** | Testing & CI | Unit tests with `pytest`, coverage, GitHub Actions | *Test-Driven Development with Python* – ch. 3 |
| **12** | Packaging & Distribution | Create a `setup.py`, publish to TestPyPI | *Python Packaging Authority* guide |

### Mini‑Project: “Flask API + Frontend”  
- RESTful CRUD API for a to‑do list.  
- Frontend with vanilla JS or React.  
- Deploy locally; later containerize with Docker.

---

## 4. Advanced Level (Weeks 13‑+)

| Phase | Focus | Deliverable | Resources |
|-------|-------|-------------|-----------|
| **13‑15** | Performance & Profiling | Use `cProfile`, `memory_profiler`, write a Cython extension | *Python Performance* – ch. 2‑3 |
| **16‑18** | Metaprogramming & Design Patterns | Create decorators that register functions; use `abc` and `typing` | *Fluent Python* – ch. 11; *Design Patterns* (Python) |
| **19‑21** | Microservices & Docker | Build two services, orchestrate with Docker Compose | *Docker for Python Developers* |
| **22‑24** | Cloud & DevOps | Deploy to AWS Lambda / GCP Cloud Functions; CI/CD pipeline | *Serverless Framework* docs |
| **25‑27** | Advanced Async | FastAPI with WebSockets, background tasks, async DB with `asyncpg` | *FastAPI Docs* |
| **28‑30** | Testing in Production | Property‑based testing (`hypothesis`), contract testing | *Testing in Production* by TestDriven.io |
| **31‑36** | Open‑Source Contribution | Pick a repo, read CONTRIBUTING.md, submit a PR | GitHub Explore, `bug bounty` |

### Capstone: “Real‑World System”  
- Choose a domain: **Web scraping**, **Chatbot**, **Data pipeline**, **Game**.  
- Architecture diagram (components, data flow).  
- Implement with production‑ready patterns (dependency injection, logging, monitoring).  
- Document & publish on GitHub; optionally deploy on Heroku/Render.

---

## 5. Continuous Learning & Mastery

| Topic | Why it matters | How to deepen |
|-------|----------------|---------------|
| **Type Hints & Static Analysis** | Reduce runtime bugs, better IDE support | `mypy`, `pyright`; *Typed Python* |
| **Reactive Programming** | Data streams, event‑driven apps | `RxPY` |
| **GraphQL** | API flexibility | `graphene` |
| **Data Science** | Data manipulation, ML | `pandas`, `scikit‑learn`, `torch` |
| **Systems Programming** | Networking, OS APIs | `asyncio`, `socket`, `subprocess` |
| **Security** | OWASP guidelines, penetration testing | `bandit`, `sqlmap` |
| **Performance Tuning** | CPU‑bound, memory‑bound | `numpy`, `numba` |

> **Learning Habit** – Allocate **30 min/day** to reading docs or tutorials.  
> **Project Habit** – Finish **one small feature** every week.  

---

## 6. Recommended Reading & Resources

| Category | Title / Site | Why |
|----------|--------------|-----|
| **Books** | *Automate the Boring Stuff* | Intro to scripting. |
| | *Python Crash Course* | Hands‑on projects. |
| | *Fluent Python* | Deep dive into language quirks. |
| | *Effective Python* | 59 specific practices. |
| | *Python Cookbook* | Recipes for seasoned devs. |
| | *Python Data Science Handbook* | For analytics. |
| | *Design Patterns in Python* | Architecture. |
| **Online Courses** | *Real Python* | Curated tutorials. |
| | *freeCodeCamp Python* | 4‑hour full‑stack crash‑course. |
| | *Coursera – Python for Everybody* | University‑level. |
| | *Udemy – Automate with Python* | Projects. |
| **Practice** | [LeetCode](https://leetcode.com) | Algorithms. |
| | [HackerRank](https://hackerrank.com) | Coding challenges. |
| | [Exercism](https://exercism.io) | Mentored exercises. |
| | [Project Euler](https://projecteuler.net) | Problem solving. |
| **Docs** | [Python Official Docs](https://docs.python.org/3) | Reference. |
| | [PEP 8](https://peps.python.org/pep-0008/) | Style guide. |
| | [PEP 484](https://peps.python.org/pep-0484/) | Type hints. |
| **Community** | [Python Discord](https://discord.com/invite/python) | Real‑time help. |
| | [r/Python](https://reddit.com/r/Python) | Discussion. |
| | [Stack Overflow](https://stackoverflow.com/questions/tagged/python) | Q&A. |
| | [Python Weekly](https://www.pythonweekly.com) | Newsletters. |

---

## 7. Quick Reference Cheat‑Sheet (Beginner to Advanced)

| Feature | Syntax | Example |
|---------|--------|---------|
| **Variables** | `x = 10` | |
| **Strings** | `"Hello\nWorld"` | |
| **Lists** | `lst = [1, 2, 3]` | |
| **Dicts** | `d = {'a': 1}` | |
| **Loops** | `for i in range(5):` | |
| **Conditionals** | `if x > 0:` | |
| **Functions** | `def foo(a, b=1):` | |
| **Classes** | `class Person:` | |
| **Inherit** | `class Student(Person):` | |
| **Decorators** | `@staticmethod` | |
| **Generators** | `yield` | |
| **Context Managers** | `with open(...) as f:` | |
| **Exceptions** | `try/except` | |
| **Modules** | `import math` | |
| **Packages** | `from . import utils` | |
| **Virtualenv** | `python -m venv venv` | |
| **Testing** | `def test_add():` | |
| **Async** | `async def foo():` | |
| **Await** | `await bar()` | |
| **Docker** | `docker build .` | |

---

## 8. Sample Roadmap (4‑Month Sprint)

| Week | Milestone |
|------|-----------|
| 1–4 | **Foundations** – Syntax, data types, scripts. |
| 5–8 | **Intermediate** – OOP, modules, testing, simple web app. |
| 9–12 | **Advanced** – Async, containers, micro‑services, capstone. |
| 13+ | **Specialization** – Data Science, Web, DevOps, or Security. |

---

## 9. Final Words

1. **Code Every Day** – Consistency beats marathon sessions.  
2. **Read Code** – Browse GitHub projects; understand idioms.  
3. **Ask for Feedback** – Open source PRs, code reviews, mentors.  
4. **Teach** – Write a blog post or tutorial; teaching consolidates knowledge.  
5. **Enjoy the Journey** – Python is vast; pick domains that excite you.

> **You’re ready** – Grab a coffee, open VS Code, and start the first script.  
> Remember: *the best way to learn Python is to build something useful (or just something fun).* Happy coding!
