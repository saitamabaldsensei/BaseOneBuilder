# BaseOneBuilder

> A community guild for beginner programmers — learn the fundamentals, build your base, and grow together.

---

## 🧱 What is BaseOneBuilder?

**BaseOneBuilder** is a programming guild designed for those who are just starting out.
Whether you're writing your first line of code or looking to solidify core concepts,
this is the place to build your foundation — one block at a time.

---

## 🎯 Guild Goals

- Help beginners understand core programming concepts
- Build a supportive coding community
- Provide hands-on practice through small projects
- Track member progress through a **Stake Base** system

---

## 🪙 Stake Base System

The **Stake Base** is our guild progress tracker.
Members earn "stakes" by completing coding challenges, contributing code, or helping others.

### Example: Stake Base in Python

```python
class Member:
    def __init__(self, name):
        self.name = name
        self.stakes = 0

    def earn_stake(self, amount):
        self.stakes += amount
        print(f"{self.name} earned {amount} stake(s). Total: {self.stakes}")

    def get_rank(self):
        if self.stakes >= 100:
            return "Master Builder"
        elif self.stakes >= 50:
            return "Senior Coder"
        elif self.stakes >= 20:
            return "Junior Coder"
        else:
            return "Rookie"


# Example usage
member = Member("Alice")
member.earn_stake(10)
member.earn_stake(15)
print(f"Rank: {member.get_rank()}")
```

### Stake Rank Table

| Stakes     | Rank           |
|------------|----------------|
| 0 – 19     | 🪨 Rookie       |
| 20 – 49    | 🔧 Junior Coder |
| 50 – 99    | 💻 Senior Coder |
| 100+       | 🏆 Master Builder |

---

## 🚀 Getting Started

1. **Fork** this repository
2. **Clone** it to your local machine
```bash
   git clone https://github.com/saitamabaldsensei/BaseOneBuilder.git
```
3. Start with the `/beginner` folder
4. Complete a challenge and **submit a Pull Request**
5. Earn your first stake! 🎉

---

## 🤝 Contributing

All skill levels are welcome. Please read `CONTRIBUTING.md` before submitting.

---

## 📄 License

MIT License — free to use, learn, and share.
