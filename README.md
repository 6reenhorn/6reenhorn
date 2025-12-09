
#

```typescript
const aboutMe = {
  developer: {
    name: "6reenhorn",
    education: "CS Student @ USTP Cagayan de Oro",
    location: "Cagayan de Oro, PH",
    workingOn: ["Full-Stack Projects"],
    currentlyLearning: ["Advanced React Patterns", "TypeScript Deep Dive"]
  },
  
  techStack: {
    languages: ["JavaScript", "TypeScript", "Python", "HTML5", "CSS3"],
    technologies: {
      frontend: { frameworks: ["React"], styling: ["Tailwind CSS"] },
      backend: { javascript: ["Node.js"], python: ["Python"] },
      databases: ["PostgreSQL"]
    }
  },

  futureGoals: {
    machineLearning: ["TensorFlow", "PyTorch", "Scikit-learn"],
    exploring: ["Deep Learning", "Neural Networks", "AI Development"]
  }
} as const;

type AboutMe = typeof aboutMe;
```

---