## Hi, I'm Kam 

I'm an Economics major at Northwestern University ('27) with minors in Artificial Intelligence, Mathematics, and Legal Studies. I code for research, and I've also been working on personal projects, for fun, since high school! Below you can find some of my projects. I particularly love working on AI... both analyzing its impact on the world, and creating it myself!

📫 [kamrabizadeh@gmail.com](mailto:kamrabizadeh@gmail.com) · [LinkedIn](https://www.linkedin.com/in/kameron-rabizadeh/)
<!-- Add the OPI website here or on the OPI card once it's live. -->

---

## Research

### 📊 Occupational Power Index (OPI)

A composite index of structural power across **831 U.S. occupations**, used to map who is protected, and who is exposed, as AI reshapes work.

- **Method:** the geometric mean of an autonomy index (esoteric knowledge, accountability, task discretion) and a political-power index (licensing, lobbying, union coverage, employment size).
- **Robustness:** in 99.99% of 173,050 alternative weighting scenarios, the rankings kept a Spearman ρ of 0.90 or higher with the baseline results.
- **Applications:** Cross-analysis with AI exposure measures identifies occupations with the greatest/least power to respond to jurisdictional and wage threats posed by AI. Regressions against demographic groups identify the most exposed employees by race, age, gender, education. 

![Code release: coming soon](https://img.shields.io/badge/code%20release-coming%20soon-orange)

→ [Project page](https://github.com/occupational-power)

---

## Personal projects

### 🔤 Scrabble AI

A Scrabble engine that finds every legal move on the board and ranks them with a neural network trained by self-play.

- **Move generation:** the dictionary is compiled into a GADDAG, which lets the solver list every legal play for a rack, blanks included, in one pass.
- **Move ranking:** a hybrid CNN + MLP network in PyTorch predicts each move's score margin for the rest of the game, then a one-step expectiminimax lookahead over possible opponent racks refines the top picks.
- **Training:** distributed self-play on a CPU cluster. The final model wins 55–65% of games against a greedy player that always takes the highest-scoring move.

→ [Repo](https://github.com/kam-rab/Scrabble-AI)

<!--
Card template for more personal projects:

### <emoji> <Project name>

<One-line summary.>

- **<Label>:** <detail>
- **<Label>:** <detail>

→ [Repo](https://github.com/kam-rab/<repo>)
-->
