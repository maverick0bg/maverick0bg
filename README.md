- 👋 Hi, I’m Evgeniy Hristov
- 👀 I’m interested in software development lifecycle
- 🌱 I’m currently learning DevOps techniques to shorten lean time and to help my team doing things faster with less risk
- 💞️ I’m looking to collaborate on everithing related to SDLC

<!---
maverick0bg/maverick0bg is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
stateDiagram-v2
    [*] --> Still
    Still --> [*]

    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
