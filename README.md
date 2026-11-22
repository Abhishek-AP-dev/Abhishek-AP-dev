# Hi, I'm Abhishek 👋

**C++ engine and systems programmer** · Third-year Computer Science (Real-Time Interactive Simulation) student at the Singapore Institute of Technology & DigiPen

I write performance-critical C++: engine architecture, multiplayer networking and real-time rendering. Currently looking for a **C++ software internship** under the Integrated Work Study Programme (IWSP).

---

## 🔧 What I'm building now

**[Crucible Engine](https://github.com/kwan-c/Crucible-Engine)**: our team's C++ entity component system (ECS) engine, used to build *Mekanomachia*, a multiplayer horde shooter. Team of 9.

- **Archetype-based component storage.** I switched it mid-project from sparse sets, so the game walks the whole enemy horde through contiguous arrays every frame. Component add/remove is slower as a result, so those changes are deferred to command buffers.
- **System scheduler.** Every engine and gameplay system declares its dependencies, and the scheduler runs them in a fixed order each frame.
- **Multiplayer on GameNetworkingSockets (GNS).** Playable over LAN in our current build. Internet play is in progress.

## 🧰 Tools

C++17 · OpenGL 4.5 · GLSL · Dear ImGui · GameNetworkingSockets · CMake · Visual Studio · Git

## 📫 Contact

**Email:** apabhish11@gmail.com · **LinkedIn:** [linkedin.com/in/abhishek-ap-cs](https://www.linkedin.com/in/abhishek-ap-cs)



<!--
**Abhishek-AP-dev/Abhishek-AP-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
