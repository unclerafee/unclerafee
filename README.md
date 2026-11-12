import pypandoc

readme = r'''<div align="center">

# 👋 Hey, I'm Uncle Rafee

### Curious Mind · AI Explorer · Tech Enthusiast

**Learn. Build. Explore. Share.**

I’m passionate about discovering how technology works, experimenting with new ideas, and sharing what I learn along the way.

[![GitHub followers](https://img.shields.io/github/followers/unclerafee?style=for-the-badge&logo=github&label=Followers)](https://github.com/YOUR_GITHUB_USERNAME)
[![Profile views](https://komarev.com/ghpvc/?username=unclerafee&style=for-the-badge&color=blueviolet)](https://github.com/YOUR_GITHUB_USERNAME)

</div>

---

## 🧑‍💻 A Little About Me

- 🤖 Exploring **Artificial Intelligence** and the latest AI tools
- 🧠 Learning about **AI agents, agentic workflows, and automation**
- 💻 Interested in **software development** and building useful projects
- 🔍 Always curious about emerging technologies and how things work
- 🎥 Sharing tech discoveries, experiments, and learning experiences through **Uncle Rafee**

I believe you don't have to know everything to start building. Stay curious, keep experimenting, and improve one step at a time.

## 🗺️ My Tech Journey

```mermaid
flowchart TD
    A["💡 Curiosity"] --> B["🔎 Explore New Technology"]
    B --> C["📚 Learn & Understand"]
    C --> D["🛠️ Build & Experiment"]
    D --> E["🧪 Test Ideas"]
    E --> F["🎥 Share What I Learn"]
    F --> A

    style A fill:#312e81,color:#fff,stroke:#818cf8
    style B fill:#1e3a8a,color:#fff,stroke:#60a5fa
    style C fill:#164e63,color:#fff,stroke:#22d3ee
    style D fill:#14532d,color:#fff,stroke:#4ade80
    style E fill:#713f12,color:#fff,stroke:#facc15
    style F fill:#581c87,color:#fff,stroke:#c084fc
```

## 🚀 What I'm Exploring

| Area | What interests me |
|---|---|
| 🤖 Artificial Intelligence | AI models, practical AI tools, and new developments |
| 🧩 Agentic AI | AI agents, workflows, and intelligent automation |
| 💻 Development | Programming, web technologies, and building projects |
| ⚙️ Automation | Connecting tools and simplifying repetitive tasks |
| 🎬 Tech Content | Making technology easier to understand and sharing discoveries |

## 🧰 Tools & Technologies

*My toolkit is always evolving as I learn and experiment.*

<p>
  <img src="https://skillicons.dev/icons?i=python,js,ts,html,css,react,nodejs,git,github,docker,linux,vscode" alt="Technologies and tools" />
</p>

## 📊 GitHub at a Glance

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&theme=tokyonight" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</p>

## 🎥 Beyond the Code

### Uncle Rafee

I share my journey through the world of technology — exploring AI tools, learning new concepts, experimenting with ideas, and discovering what’s possible.

**The goal isn't to know it all. It's to keep learning and share the journey.**

---

<div align="center">

### 🌱 Always learning. Always building.

**Thanks for stopping by!**

</div>
'''

output_path = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=output_path, extra_args=["--standalone"])
print(f"Created: {output_path}")
