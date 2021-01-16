```typescript
const about = {
  name: "Gabriel Fair",
  location: "Charlotte/San Diego/D.C.",
  intro: "Living a muli-dimensional life",
};

const skills = {
  languages: [
    "TypeScript",
    "HTML/CSS/JavaScript",
    "Python",
  ],
  databases: ["MySQL", "MongoDB"],
  operatingSystems: {
    server: ["Ubuntu Server"],
    desktop: ["Windows", "Ubuntu", "macOS"],
  },
  tools: ["Docker", "Hyper-V", "VSCode"],
};

const hobbies = [
  "Biking",
  "Cars",
  "Gaming",
  "Homelab",
  "Photography",
  "Programming",
  "Baking",
];

export const gabeFair = {
  about: { ...about },
  skills: { ...skills },
  hobbies: { ...hobbies },
};
```
