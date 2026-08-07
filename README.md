<div align="center">

<img src="img/header.png" width="100%" alt="Flavia Gaglio — Computer Engineering Graduate, M.Sc. Student AI & Cybersecurity" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=18&duration=2800&pause=1100&color=50FF40&background=222623&center=true&vCenter=true&width=680&height=48&lines=%3E+building+things+that+work...;%3E+and+figuring+out+exactly+why+they+might+not." alt="building things that work, and figuring out why they might not" />

<br/><br/>

<a href="https://flaviagaglio.github.io"><img src="https://img.shields.io/badge/PORTFOLIO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/flavia-gaglio-4a30b0335/"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/flaviagaglio"><img src="https://img.shields.io/badge/GITHUB-1a1a1a?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.instagram.com/flaviagaglio/"><img src="https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:flaviagaglio9@gmail.com"><img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<br/>

<img src="img/label-about.png" height="46" alt="01 / About" />

<br/><br/>

Two things pull at me at the same time: making a system do exactly what it's supposed to, and poking at it until it doesn't. That tension is basically my degree. I'm a Computer Engineering graduate now working toward an M.Sc. in Artificial Intelligence & Cybersecurity, and most of what I build sits at that intersection — machine learning systems, and the security questions that come with putting them in front of real inputs.

Biometrics is where that shows up most: not just training a classifier that works on clean data, but asking what happens when someone tries to fool it. My thesis on vulnerability analysis in biometric systems started that habit, and it hasn't worn off — anti-spoofing, anomaly detection and authentication design are the topics I keep coming back to outside of coursework too.

Outside of a code editor, I'm usually in front of a different kind of interface — guitar, piano, bass or a synth, mixing in Logic Pro. Two of the projects below (`keys`, `mode-finder`) are what happens when those two worlds bleed into each other.

<br/>

<img src="img/label-education.png" height="46" alt="02 / Education" />

<br/><br/>

**M.Sc., Artificial Intelligence & Cybersecurity** — *in progress*
Machine learning and security research, with biometric anti-spoofing as a running thread.

**B.Eng., Computer Engineering** — *completed*
Algorithms, systems, databases, networking — and a thesis that turned into a lasting interest in attacking the systems I build.

<br/>

<img src="img/label-skills.png" height="46" alt="03 / Skills" />

<br/><br/>

<img src="img/skills-panel.png" width="100%" alt="AI & Security: Machine Learning, Cybersecurity, Biometrics. Programming: Python, C, Java, SQL, TypeScript, Git, UNIX/Linux. Music Production: Logic Pro, Luna, UA Plugins" />

<br/><br/>

<img src="img/label-projects.png" height="46" alt="04 / Featured Projects" />

<br/><br/>

Full write-ups, architecture notes and honest limits for every project are on the portfolio. These seven are the ones I'd point you to first.

<table width="100%">

<tr>
<td width="45%" valign="middle">

**🗺️ Cartographer**
Client-side Music Information Retrieval tool — extracts timbral features (MFCC, centroid, energy) from dropped audio files and projects them into a 2D acoustic map via UMAP, so acoustically similar sounds cluster together. No server, no upload: decoding, analysis and projection all run in the browser.

`JavaScript` `Web Audio API` `UMAP`

<a href="https://flaviagaglio.github.io/cartographer/"><img src="https://img.shields.io/badge/LIVE_DEMO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Live Demo"/></a>
<a href="https://github.com/flaviagaglio/cartographer"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
<td width="55%">
<a href="https://flaviagaglio.github.io/cartographer/"><img src="img/cartographer.png" width="100%" alt="Cartographer screenshot" /></a>
</td>
</tr>

<tr>
<td width="55%">
<a href="https://flaviagaglio.github.io/kepler0/"><img src="img/kepler0.png" width="100%" alt="Kepler0 screenshot" /></a>
</td>
<td width="45%" valign="middle">

**🪐 Kepler0**
Real-time N-body gravitational simulator: every body attracts every other body under Newtonian gravity, integrated frame by frame, with a softening factor that keeps close encounters numerically stable instead of ejecting bodies at infinite velocity. Inject mass and watch orbits and chaos emerge live.

`JavaScript` `HTML5 Canvas` `Numerical Simulation`

<a href="https://flaviagaglio.github.io/kepler0/"><img src="https://img.shields.io/badge/LIVE_DEMO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Live Demo"/></a>
<a href="https://github.com/flaviagaglio/kepler0"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
</tr>

<tr>
<td width="45%" valign="middle">

**🩺 Male Infertility Prediction**
Classifying Controls vs. Infertile subjects from clinical andrology data: 13 tuned model configurations across Decision Trees, MLP, SVM and gradient-boosting ensembles, validated with repeated/nested cross-validation and statistical significance testing rather than a single accuracy number.

`Python` `scikit-learn` `XGBoost` `SHAP`

<a href="https://github.com/flaviagaglio/male-infertility-prediction-ml"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
<td width="55%">
<img src="img/stat-infertility.png" width="100%" alt="13 configs across 6 model families, best F1 0.740 held-out, SHAP and permutation explainability" />
</td>
</tr>

<tr>
<td width="55%">
<img src="img/stat-nlp.png" width="100%" alt="Italian BERT (dbmdz) fine-tune, best Pearson r 0.71 on Valence, single- vs multi-target comparison" />
</td>
<td width="45%" valign="middle">

**💬 Emotion Detection in Italian Text**
Fine-tuned Italian BERT for VAD emotion regression (Valence, Arousal, Dominance) on the EmoITA dataset — three single-target models compared head-to-head against one joint multi-target model, rather than assuming one approach wins.

`Python` `PyTorch` `BERT` `NLP`

<a href="https://github.com/flaviagaglio/EmotivITA-BERT-VAD"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
</tr>

<tr>
<td width="45%" valign="middle">

**🎹 Keys**
Instant key signature finder built on real circle-of-fifths math: pick a tonic, get the exact number and letter names of its sharps or flats, computed algorithmically rather than looked up from a table.

`JavaScript` `Music Theory`

<a href="https://flaviagaglio.github.io/keys/"><img src="https://img.shields.io/badge/LIVE_DEMO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Live Demo"/></a>
<a href="https://github.com/flaviagaglio/keys"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
<td width="55%">
<a href="https://flaviagaglio.github.io/keys/"><img src="img/keys.png" width="100%" alt="Keys screenshot" /></a>
</td>
</tr>

<tr>
<td width="55%">
<a href="https://flaviagaglio.github.io/mode-finder/"><img src="img/mode-finder.png" width="100%" alt="Mode Finder screenshot" /></a>
</td>
<td width="45%" valign="middle">

**🎼 Mode Finder**
All seven modes of the major scale on any root note, spelled correctly: the algorithm steps through the musical alphabet one letter per degree — never repeating or skipping one — and picks whichever enharmonic spelling needs the fewest accidentals for each mode independently.

`JavaScript` `Music Theory`

<a href="https://flaviagaglio.github.io/mode-finder/"><img src="https://img.shields.io/badge/LIVE_DEMO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Live Demo"/></a>
<a href="https://github.com/flaviagaglio/mode-finder"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
</tr>

<tr>
<td width="45%" valign="middle">

**🔐 Passwords**
Password generator built on a cryptographically secure RNG (Web Crypto API with rejection sampling to avoid modulo bias, not `Math.random()`), with a strength meter that shows real Shannon entropy in bits instead of an arbitrary score.

`JavaScript` `Web Crypto API`

<a href="https://flaviagaglio.github.io/passwords/"><img src="https://img.shields.io/badge/LIVE_DEMO-FF4400?style=for-the-badge&logoColor=1a1a1a" alt="Live Demo"/></a>
<a href="https://github.com/flaviagaglio/passwords"><img src="https://img.shields.io/badge/CODE-1a1a1a?style=for-the-badge&logo=github&logoColor=FF4400" alt="Code"/></a>

</td>
<td width="55%">
<a href="https://flaviagaglio.github.io/passwords/"><img src="img/passwords.png" width="100%" alt="Passwords screenshot" /></a>
</td>
</tr>

</table>

<p align="center">
  <a href="https://flaviagaglio.github.io/projects"><img src="https://img.shields.io/badge/SEE_ALL_PROJECTS_→-1a1a1a?style=for-the-badge&logoColor=FF4400" alt="See all projects"/></a>
</p>

<br/>

<img src="img/label-activity.png" height="46" alt="05 / GitHub Activity" />

<br/><br/>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=flaviagaglio&background=222623&border=1a1a1a&ring=50FF40&fire=FF4400&currStreakLabel=50FF40&sideLabels=cccccc&currStreakNum=50FF40&sideNums=eeeeee&dates=888888&hide_border=false" alt="GitHub streak stats" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=flaviagaglio&bg_color=222623&color=50FF40&line=50FF40&point=F2EFE6&area_color=1a1a1a&title_color=FF4400&hide_border=false&border_color=1a1a1a" alt="GitHub activity graph" width="100%" />
</p>

<br/>

<img src="img/label-snake.png" height="46" alt="06 / Contribution Snake" />

<br/><br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/flaviagaglio/flaviagaglio/output/snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/flaviagaglio/flaviagaglio/output/snake-light.svg">
    <img alt="contribution snake animation" src="https://raw.githubusercontent.com/flaviagaglio/flaviagaglio/output/snake-dark.svg" width="100%" />
  </picture>
</div>

<br/>

<img src="img/label-contact.png" height="46" alt="07 / Contact" />

<br/><br/>

<p align="center">
  <a href="mailto:flaviagaglio9@gmail.com"><img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/flavia-gaglio-4a30b0335/"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.instagram.com/flaviagaglio/"><img src="https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

<p align="center">
  <sub><img src="https://komarev.com/ghpvc/?username=flaviagaglio&style=flat-square&color=ff4400" alt="Profile views" /></sub>
</p>

<br/>

<img src="img/footer.png" width="100%" alt="" />

