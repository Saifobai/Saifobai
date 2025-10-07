# Hi, I'm [Your Name] 👋  

![banner](https://your-banner-image-link)  

🌐 **Full-Stack Developer | AI Engineer | IoT Innovator**  
🎓 Founder of **EmotiVoice** — Emotion-Aware Assistive Tech  
💡 Passionate about accessible technology, machine learning, and building smarter web systems.  

---

### 🧠 What I Do  
```jsx
import { useState, useEffect } from "react";

function EmotiDev() {
  const [motto, setMotto] = useState("Bridging IoT, AI, and the Web 🌐🤖❤️");

  const stack = [
    "React.js", "Next.js", "Node.js", "MongoDB", 
    "Python", "Flask", "IoT", "LLMs", "Machine Learning"
  ];

  const dailyRoutine = [
    "☕ Wake up & boot sensors",
    "⚛️ Build responsive UIs in React & Next.js",
    "🧠 Train and prompt LLMs",
    "📡 Connect IoT devices to intelligent backends",
    "💬 Experiment with multimodal AI",
    "🚀 Deploy, test, repeat"
  ];

  const currentProjects = {
    "🎙️ EmotiVoice": "AI-powered assistive communication using IoT & emotion recognition",
    "🤖 LLM Playground": "Exploring reasoning & RAG pipelines with custom prompts",
    "🌐 MERN Lab": "Building scalable full-stack web solutions",
    "📡 Smart IoT Hub": "Integrating sensors and AI for adaptive environments"
  };

  useEffect(() => {
    console.log("Code, Create, Connect 🔁");
  }, []);

  return (
    <DeveloperLife>
      <Motto>{motto}</Motto>
      <Stack>{stack.join(" • ")}</Stack>
      <Daily>{dailyRoutine.map((task) => <Task key={task}>{task}</Task>)}</Daily>
      <Projects>{Object.entries(currentProjects).map(([name, desc]) => (
        <Project key={name} title={name} desc={desc} />
      ))}</Projects>
    </DeveloperLife>
  );
}

export default EmotiDev;

### 🌍 Find Me Online

- 💼 LinkedIn

- 🧠 Portfolio


