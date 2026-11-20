<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d12,50:0891b2,100:22e5ff&height=230&section=header&text=Kavya%20Aggarwal&fontSize=58&fontColor=f3f6f8&animation=fadeIn&fontAlignY=42&desc=I%20measure%20whether%20the%20number%20means%20anything&descAlignY=62&descSize=18" width="100%" alt="Kavya Aggarwal" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=22E5FF&center=true&vCenter=true&width=760&lines=Agentic+AI+%E2%80%A2+adaptive+learning+%E2%80%A2+audio+ML;Independent+researcher+%E2%80%A2+measurement+validity;Every+number+here+has+a+measurement+behind+it" alt="Typing SVG" />
</a>

<p>
  <a href="https://aggarwalkavya.web.app">
    <img src="https://img.shields.io/badge/Portfolio-22e5ff?style=for-the-badge&logo=google-chrome&logoColor=0a0d12" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/aggarwalkavya/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:aggarwalkaavya23@gmail.com">
    <img src="https://img.shields.io/badge/Email-0a0d12?style=for-the-badge&logo=gmail&logoColor=22e5ff" alt="Email"/>
  </a>
  <a href="https://leetcode.com/u/OmegaKavya/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="https://www.codechef.com/users/OmegaKavya">
    <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/>
  </a>
  <a href="https://www.hackerrank.com/profile/OmegaKavya">
    <img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="HackerRank"/>
  </a>
</p>

<p>
  <a href="https://www.credly.com/users/omega-kavya">
    <img src="https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly"/>
  </a>
  <a href="https://credentials.databricks.com/profile/omegakavya/wallet">
    <img src="https://img.shields.io/badge/Databricks%20Credentials-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks credentials"/>
  </a>
  <a href="https://www.salesforce.com/trailblazer/aggarwalkavya">
    <img src="https://img.shields.io/badge/Trailblazer-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce Trailblazer"/>
  </a>
</p>

</div>

---

## About

Data analyst working on **agentic AI**: building and testing custom agents end to
end, plus Salesforce automation. Independent researcher in Hyderabad, India.
B.Tech Computer Science, 2026, CGPA 9.32.

What I actually do, across every project below, is check whether a reported
number measures what it claims. It is how a 66% accuracy turned out to be
hiding seven languages scored at zero, how four named customer segments turned
out to be a partition of noise, and how a significant result of my own turned
out to be confounded and was withdrawn.

- Methodology paper written on a confound in simulated evaluations of adaptive difficulty, being prepared for submission
- **Salesforce Agentforce** and **Databricks Data Engineer Associate** certified
- Cricket vice-captain, swimming gold medallist, competitive programmer

---

## Featured work

### CogniLoop · adaptive tutoring, and the measurement problem underneath it

IRT-grounded Bayesian Knowledge Tracing with parameters fitted by a from-scratch
Baum-Welch, Thompson Sampling difficulty routing, and transcript-grounded quiz
generation over open-domain video.

The research contribution is a negative result. Fitting BKT per skill, generating
responses from a latent state and reporting the posterior as the outcome cannot
distinguish a policy that teaches better from one that merely asks harder
questions. The three difficulty tiers sit at mastery levels of 0.846, 0.929 and
1.000, compressed into the top of the scale, so over the range learners occupy no
adaptive policy beats the best fixed one. An earlier significant result of my own
was produced by exactly that construction, and it is withdrawn.

`Python` `Flask` `ChromaDB` `scikit-learn` · **362 tests** · [Live](https://cogniloop-2svo.onrender.com) · [Code](https://github.com/OmegaKavya/CogniLoop)

### CineInfinity · full-stack film and anime platform

React front end, Express and MongoDB behind it, Firebase authentication, deployed
across Firebase Hosting and Render. Reviews, ratings, watchlists and search over
TMDb, OMDb and AniList.

Two things a review site does not usually have. A **watch-order resolver** runs a
topological sort over a franchise's prequel and sequel edges, so a series is
ordered by its story rather than its release dates, with recaps and side stories
classified and ranked separately. And **Your Signal** reads your ratings back
against the crowd: the distribution across all ten points, where you diverge, and
Wilson score intervals rather than raw averages, so it says the sample is too
small instead of drawing confident bars over nothing.

AniList is proxied through the server rather than called from the browser,
because the API rate-limits per client IP and returns the refusal without CORS
headers, so from the browser a rate limit arrives as an opaque failure. Proxied,
it is one budget, cached across every visitor, and a 429 the interface can
explain.

`React` `Node.js` `Express` `MongoDB` `Firebase Auth` · **209 tests** · [Live](https://cineinfinity.web.app) · [Code](https://github.com/OmegaKavya/CineInfinity)

### MelodAI · what a network can and cannot hear in a Hindi film song

Predicts energy at **26 of 26** on held-out songs and shows the evidence: the
per-window energy curve drawn over the spectrogram it came from, the AudioSet
classes the network assigns, nearest songs in embedding space, and the corpus map.

Measured that arousal is recoverable from this audio and valence is not: 85.2%
against 44.7% on a k-NN probe, silhouette 0.073. Serving carries no TensorFlow,
which took the install from 2.1 GB to 441 MB and made a 512 MB host viable.

`TensorFlow` `YAMNet` `TFLite` `Librosa` `FastAPI` `React` · [Live](https://melodai.web.app) · [Code](https://github.com/OmegaKavya/MelodAI)

### Which Language Is This · seventeen languages, in your browser

The reported 66% was concealing seven languages scored at exactly **0%**, because
the cleaning step kept only ASCII and deleted every non-Latin script. Fixed end to
end: worst language 0% to 96.5%, overall 99.1%.

The model is exported and runs client side with no backend, reproducing
scikit-learn on all 2,053 held-out rows to **1.9e-7**.

`scikit-learn` `NumPy` `React` · **24 tests** · [Live](https://whichlanguage.web.app) · [Code](https://github.com/OmegaKavya/Language-Detection)

### Are These Clusters Real? · a validity test for clustering

Four named customer segments that behaved identically, on data whose columns are
independent. Rebuilt as the test that establishes it: a permutation null, the gap
statistic, bootstrap stability, and three clustering algorithms, **all four
agreeing** in both directions.

Runs entirely in a Web Worker. The Python reference and the JavaScript port share
one deterministic generator, so they are compared as numbers: 104 values, worst
relative difference **2e-14**.

`NumPy` `scikit-learn` `React` `Web Workers` · [Live](https://are-these-clusters-real.web.app) · [Code](https://github.com/OmegaKavya/user-segmentation-app)

### BrainBuddy · Smart India Hackathon 2024, third place

A gamified study companion built with my team Ignited Minds. 25 self-contained
pages of plain HTML, CSS and JavaScript with no build step, which is the right
trade when the clock is the constraint.

`HTML` `CSS` `JavaScript` · [Live](https://omegakavya.github.io/BrainBuddy_SIH2024/) · [Code](https://github.com/OmegaKavya/BrainBuddy_SIH2024)

---

## Tech

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Librosa-FF6B6B?style=flat-square&logo=soundcloud&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FFD93D?style=flat-square&logo=databricks&logoColor=black" />
</p>
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" />
</p>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=OmegaKavya&show_icons=true&hide_border=true&bg_color=0a0d12&title_color=22e5ff&icon_color=22e5ff&text_color=93a1ad&ring_color=22e5ff&include_all_commits=true&rank_icon=github" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OmegaKavya&layout=compact&hide_border=true&bg_color=0a0d12&title_color=22e5ff&text_color=93a1ad&langs_count=8" height="165" alt="Top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=OmegaKavya&hide_border=true&background=0a0d12&stroke=22e5ff&ring=22e5ff&fire=22e5ff&currStreakLabel=22e5ff&sideLabels=93a1ad&currStreakNum=f3f6f8&sideNums=f3f6f8&dates=5f6b76" height="165" alt="Streak" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22e5ff,50:0891b2,100:0a0d12&height=120&section=footer" width="100%" alt="" />

</div>
