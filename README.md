```tsx
interface Profile {
  pronouns: string;
  startedIn: number;
  presentPosition: string;
  liveIn: string;
  makeWith: {
    code: string[];
    tools: string[];
    styling: string[];
    etc: string[];
  };
  hobbies?: string[];
};

// @TODO: Add new fields to the joyoung object to reflect newly acquired skills and experiences
export const joYoung: Profile = {
  pronouns: "he",
  startedIn: 2022,
  presentPosition: "Web Front-end Developer",
  liveIn: "Seoul",
  makeWith: {
    code: ["JavaScript", "TypeScript", "HTML", "CSS"],
    tools: ["React", "Next.js", "React Query", "REST API"],
    styling: ["Ant Design", "React Hook Form", "Tailwind CSS"],
    etc: ["JavaScript Libraries", "Responsive Web"],
  },
  hobbies: ["✈️ Travel", "🚶 Walking", "🏊 Swimming", "🎳 Bowling"],
}
```
