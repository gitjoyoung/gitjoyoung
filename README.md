```tsx
export interface Profile {
 pronouns: string;
 startedIn: number;
 presentPosition: string;
 liveIn: string;
 skills: {
   primary: {
     languages: string[];
     frameworks: string[];
     libraries: string[];
     styling: string[];
   };
   secondary: {
     languages: string[];
     frameworks: string[];
     databases: string[];
     servers: string[];
   };
 };
 hobbies?: string[];
};

// @TODO: "Little by little, one travels far" - J.R.R. Tolkien
// Personal growth and skill development journey
export const joYoung: Profile = {
 pronouns: "he/him",
 startedIn: 2022,
 presentPosition: "Web Front-end Developer",
 liveIn: "Seoul",
 skills: {
   primary: {
     languages: ["JavaScript", "TypeScript", "HTML", "CSS"],
     frameworks: ["React v18", "Next.js v14"],
     libraries: ["React Query", "React Hook Form", "Zustand" , "D3", "Rechart"],
     styling: ["Styled Components", "Tailwind CSS", "Ant Design", "Shadcn"]
   },
   secondary: {
     languages: ["Java", "Python", "Dart"],
     frameworks: ["Django", "Flutter", "JSP"],
     databases: ["MySQL"],
     servers: ["Apache Tomcat", "Nginx"]
   }
 },
 hobbies: ["✈️ Travel", "🚶 Walking", "🏊 Swimming", "🎳 Bowling"],
}
```
