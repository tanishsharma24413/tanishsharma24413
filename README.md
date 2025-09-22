# Hi there 👋, I'm Tanish Badyal

💻 Passionate about problem-solving, coding, and building cool projects.  
Currently sharpening my **DSA & competitive programming** skills through **LeetCode**.

---

## 🚀 LeetCode Stats

<p align="center">
  <!-- This will auto-update via GitHub Action -->
  <img src="https://leetcard.jacoblin.cool/tanish24413?theme=dark&font=baloo&ext=contest" alt="LeetCode Stats" />
</p>

---

## 🏆 Badges

<p align="center">
  <!-- 50 Days Badge GIF from LeetCode -->
  <img src="https://assets.leetcode.com/static_assets/marketing/2024-50.gif" alt="50 Days Badge" width="140" height="140"/>
</p>

---

## 📈 My Profile

| Stats | Details |
|---|---|
| **Username** | `tanish24413` |
| **Institution** | Panipat Institute of Engineering & Technology |
| **Problems Solved (Java)** | 136 |
| **Problems Solved (C++)** | 26 |
| **Problems Solved (MySQL)** | 2 |
| **Recent Badge** | “50 Days Badge 2025” |

---

## 🔗 Connect with Me

<p align="left">
  <a href="https://leetcode.com/u/tanish24413/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="https://www.linkedin.com/in/tanish-badyal-1099ab228" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:tanisharma2465@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## ⚡ Skills & Topics

- **Advanced**: Dynamic Programming, Backtracking, Divide and Conquer  
- **Intermediate**: Math, Hash Table, Greedy  
- **Fundamental**: Array, String, Matrix  

---

## 🌱 Currently Learning

- More contest participation  
- Graph Algorithms & Segment Trees  
- Performance & optimization in solutions  

---

## 🛠️ Languages & Tools

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)  
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

✨ Consistency is the key. Keep coding, keep growing! ✨

---

### GitHub Action Workflow (Auto-update LeetCode stats)

Place this file as `.github/workflows/leetcode-stats.yml`:

```yaml
name: Update LeetCode Stats

on:
  schedule:
    - cron: '0 0 * * *' # Runs daily at midnight UTC
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repository
        uses: actions/checkout@v3

      - name: Generate LeetCode Stats
        uses: jagrosh/leetcard-action@v1
        with:
          username: tanish24413
          output: README.md
          theme: dark
          font: baloo
          ext: contest
          badges: true

      - name: Commit & Push changes
        uses: EndBug/add-and-commit@v9
        with:
          author_name: 'github-actions[bot]'
          author_email: 'github-actions[bot]@users.noreply.github.com'
          message: 'Update LeetCode stats'
