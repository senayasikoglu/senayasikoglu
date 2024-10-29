                                              Hello, I'm Şenay 👋
                                             Full Stack Developer





```javascript
const senayAsikoglu = { 
  personalInfo: { 
    name: "Senay", 
    role: "Full Stack Developer", 
    linkedIn: "https://www.linkedin.com/in/senayasikoglu/", 
  },

  skills: { 
    frontend: ["JavaScript", "HTML", "CSS", "Tailwind", "Bootstrap"], 
    backend: ["NodeJS", "Express"], 
    databases: ["MongoDB"], 
    frameworks: ["React"], 
    tools: ["Git", "GitHub", "VS Code", "npm"], 
  },

  currentlyLearning: "TypeScript",

  introduceYourself: () => { 
    console.log(`
      Hello! I'm ${senayAsikoglu.personalInfo.name}, a ${senayAsikoglu.personalInfo.role}.
      If you want to know a bit more about me, visit my LinkedIn profile: ${senayAsikoglu.personalInfo.linkedIn}
    `); 
  },
};

senayAsikoglu.introduceYourself();

console.log(`
  I have experience in a variety of technologies, including:

  Frontend: ${senayAsikoglu.skills.frontend.join(', ')}
  Backend: ${senayAsikoglu.skills.backend.join(', ')}
  Databases: ${senayAsikoglu.skills.databases.join(', ')}
  Frameworks: ${senayAsikoglu.skills.frameworks.join(', ')}
  Tools: ${senayAsikoglu.skills.tools.join(', ')}
`);

console.log(`
  I have a passion for gaining new insights. Right now, I am learning ${senayAsikoglu.currentlyLearning}.
`); 


