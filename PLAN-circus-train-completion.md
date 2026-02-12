# Circus Train Kickstart Challenge – Completion Plan

> Initial plan before starting. Adjust as you progress.
> Related: [CircusTrainKickstartChallenge.md](CircusTrainKickstartChallenge.md)

---

## 1. Assignment Summary

**What it asks for:** Build a program that distributes circus animals into wagons safely and optimally.

- **Input:** Different animal types (diet: carnivore/herbivore; size: small/medium/large)
- **Output:** Wagon distribution that minimizes wagons used
- **Rules:** Carnivores eat equal/smaller animals; wagons max 10 points; optional 4 experimental wagons with separators
- **Must have:** Unit tests proving the algorithm works

**Two paths:** Option 1 (Full Sprint: analysis → design → impl → test → delivery) or Option 2 (Code-first: focus on clean code, algorithms, reflection).

---

## 2. Learning Outcomes Addressed

| LO | Name | How this assignment shows it |
|----|------|-----------------------------|
| 1 | Analysis | Use cases, domain model *(Option 1 only)* |
| 2 | Design | Class diagrams, architecture *(Option 1 only)* |
| 3 | Implementation | Clean code, OOP, algorithm |
| 4 | Managing | Unit tests, version control, iteration |
| 5 | Professional | Documentation, progress discussion |
| 6 | Personal Leadership | Reflection, feedback-seeking |

---

## 3. Breakdown – Concrete Steps

### Phase A: Setup & Path Choice (Day 1)

- [ ] Decide Option 1 (Sprint) or Option 2 (Code-first) with teacher
- [ ] Create C# console project (or ASP.NET if doing Option 1 delivery)
- [ ] Initialize Git, first commit
- [ ] Record choice and reasoning in [CLAUDE.md](CLAUDE.md)

### Phase B: Core Algorithm ( Days 2–4)

- [ ] Define `Animal` model (Diet enum, Size enum, points)
- [ ] Define `Wagon` model (capacity 10, animal list)
- [ ] Implement safety rule: carnivores cannot share with equal/smaller animals
- [ ] Implement greedy/packing algorithm to minimize wagons
- [ ] Handle experimental wagons (optional, adds complexity)

### Phase C: Input & Output (Day 5)

- [ ] Accept animal input (e.g. command-line or simple menu)
- [ ] Parse input into `Animal` instances
- [ ] Output wagon distribution clearly

### Phase D: Testing (Day 6)

- [ ] Add unit test project (xUnit or NUnit)
- [ ] Tests: safety rules, point capacity, wagon count
- [ ] Edge cases: all herbivores, all carnivores, mixed

### Phase E: Option 1 Extras (If Sprint)

- [ ] Use cases + domain model
- [ ] Class diagram
- [ ] Reflection / deployment notes

### Phase F: Polish & Reflection (Day 7)

- [ ] Code review (clean, readable)
- [ ] Commit history tidy
- [ ] Short reflection: what went well, what to improve

---

## 4. Requirements You Might Overlook

- **Experimental wagons:** Up to 4 wagons can hold 2 small/medium carnivores OR 1 carnivore + 1 herbivore (both small/medium). Easy to forget.
- **Unit tests are mandatory** – the assignment explicitly requires them.
- **Teacher consultation** – you must discuss which option fits your level.
- **Portfolio evidence** – document progress and reflection for later use.

---

## 5. Project and Portfolio

- **Project repo:** `circus-train-challenge-1st-week-orienting` (this folder)
- **Portfolio evidence:** Code, tests, (optionally) use cases/diagrams, reflection
- **Timeline:** First 2–3 weeks of semester (Jumpstart)

---

## 6. Tech Choices

| Decision | Suggestion | Rationale |
|----------|------------|-----------|
| Language | C# | S2 SDE tech stack |
| Project type | Console app | Simple I/O, focus on algorithm |
| Test framework | xUnit or NUnit | Common in .NET |
| Experimental wagons | Implement last | Add after core works |

---

## 7. Status Overview

| Phase | Status | Notes |
|-------|--------|-------|
| A. Setup | Not started | |
| B. Core algorithm | Not started | |
| C. I/O | Not started | |
| D. Testing | Not started | |
| E. Option 1 extras | N/A or not started | |
| F. Polish | Not started | |

*Update this table as you progress.*
