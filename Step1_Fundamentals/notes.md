# Step 1 - DevOps/DevSecOps Fundamentals

---

## 📌 What is DevOps?

### Definition
- DevOps = Development + Operations.
- Goal: Break silos between developers and operations teams.
- Focus on:
    - Collaboration & Communication
    - Automation
    - Continuous Delivery (CD)
    - Continuous Improvement via Feedback

### Core Principles
| Principle | Explanation |
|--|--|
| Collaboration | Dev & Ops work together from day one |
| Automation | Automate everything: testing, deployment, infra |
| CI/CD | Continuously test & deliver code |
| Feedback Loops | Monitor, collect feedback, improve continuously |

---

## 📌 What is DevSecOps?

### Definition
- DevSecOps = DevOps + Security.
- Goal: Shift security **left** — apply security practices **early** in development.

### Key DevSecOps Practices
| Practice | Explanation |
|--|--|
| Secure Coding | Train devs to write secure code from the start |
| Automated Security Scans | Use tools like SonarQube, Snyk in CI/CD |
| Security Gates | Block builds if critical vulnerabilities exist |
| Compliance as Code | Automate compliance checks (e.g., policies, encryption rules) |

---

## 📌 Key Concepts to Remember

| Concept | Explanation |
|--|--|
| Collaboration Culture | Break silos, cross-team ownership |
| Automation | Reduce manual errors, save time |
| Continuous Integration | Merge & test code frequently |
| Continuous Delivery | Always deploy ready |
| Monitoring & Feedback | Detect issues fast, learn, improve |

---

## 📌 DevOps Lifecycle Diagram (example)

```text
[Plan] -> [Develop] -> [Build] -> [Test] -> [Release] -> [Deploy] -> [Operate] -> [Monitor]
                          ↑----------------Feedback Loop---------------------↓
