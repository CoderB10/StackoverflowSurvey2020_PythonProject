
<img width="3017" height="1543" alt="Dashboard" src="https://github.com/user-attachments/assets/7b5aafec-8b02-48b3-81bb-363f1b9c698b" />


🧠 StackOverflow 2020 Developer Survey Analysis 📊
Welcome to my data analysis project based on the 2020 StackOverflow Developer Survey a global survey with responses from 64,000+ developers! This project dives deep into the demographics, experiences, and preferences of developers worldwide using tools like Pandas, NumPy, Matplotlib, and Seaborn. 🐍📈

📂 Dataset Overview
The dataset was obtained from StackOverflow's 2020 Developer Survey, one of the largest annual surveys targeting developers globally.

* 🔢 21 Questions asked per respondent

* 👥 64,000+ Respondents

* 🌍 Covers diverse aspects such as:

* Country of residence

* Age (current & when they started coding)

* Coding experience (total and professional)

* Most used & preferred programming languages

* Most dreaded programming languages

* Current job roles

* Educational background

🧠 Key Insights from the Survey
🌐 Community & Demographics
* The survey is somewhat representative of the global programming community.

* ⚠️ However, there's a noticeable underrepresentation of:

* Programmers from non-English speaking countries

* Women and non-binary individuals

💡 Diversity & Inclusion
* The programming community is not as diverse as it can be.

* Improvements are visible, but:

   * We should support underrepresented groups more proactively — be it by age, gender, race, or geography.

🎓 Education & Career Path
* Most developers have a college degree, though:

* A large number did not major in Computer Science.

  * ✅ A CS degree isn't mandatory to become a developer!

* Many work as freelancers or part-timers, which can be a great entry point into tech careers.

💻 Programming Languages

✅ Most Used in 2020
* 🥇 JavaScript

* 🥈 HTML/CSS

* 🥉 SQL & Python

💚 Most Loved Languages
* 🧡 Rust

* 💙 TypeScript

* 💚 Python (close third, despite already being mainstream)

🚫 Most Dreaded Languages
* These are languages developers currently use but don’t want to continue using in the future:

* ❌ VBA and Objective-C:  dreaded by nearly 80% of users 😬

* ❌ Perl and Assembly: dreaded by approximately 71% of users 😓

💭 Most Wanted/Favoured
* Python leads, likely due to its ease of learning and broad applicability across domains like web dev, data science, automation, and more.

---

📊 Correlation & Regression: Age First Coded vs. Professional Experience
* To explore whether starting to code early leads to a longer professional coding career, I conducted both a Pearson Correlation test and a Linear Regression analysis between 2 columns:

* Age1stCode (age when the respondent first coded)
* YearsCodePro (years of professional coding experience)

This was done separately for:
🧑‍💻 Hobbyists (those who started coding as a hobby) AND 👔 Non-Hobbyists

🧠 Interpretation:
* The negative correlation is weak in both groups, and the R² values are very low, meaning:

> 🗨️ The age you start coding has little to no effect on how long you code professionally.

This leads to four clear behavioral quadrants among developers:

| Quadrant          | Behavior                                                                                  |
| ----------------- | ----------------------------------------------------------------------------------------- |
| 🟩 **Quadrant 1** | Started young (e.g., age 10) and coded professionally for a long time (e.g., till age 50) |
| 🟨 **Quadrant 2** | Started late (e.g., age 40) and still managed a long professional career (e.g., till 80)  |
| 🟦 **Quadrant 3** | Started young but didn't continue for long professionally                                 |
| 🟥 **Quadrant 4** | Started late and coded professionally for a short span                                    |

> 📌 Moral of the story: It’s never too early or too late to start coding, what matters more is your consistency and passion 💪

⏱️ Work Habits
* Developers typically work ~40 hours per week, with some regional variation.

👶👴 Age & Coding
* People from a wide range of age groups code.
* It's never too late (or too early!) to start coding — even as a hobby.

---

## 🛠️ Tech Stack Used

* `Python`
* `Pandas`
* `NumPy`
* `Matplotlib`
* `Seaborn`

---

## 📌 Conclusion

This analysis paints a broad picture of the global coding community as of 2020. While we celebrate the growth and enthusiasm in the field, there's a **clear call to action** for making programming **more accessible and inclusive** for all. And maybe... drop that VBA code 😅. Also, don't worry about when you start coding, just start. 🚀

---
