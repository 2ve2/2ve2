## Hi there 👋

<h1 align="center">Abdulrahman Matouk</h1>

<p align="center">
  Software Engineer · Mobile Developer · Full-Stack Developer
</p>

<p align="center">
  TypeScript · React Native · Expo · Bun · Hono · PostgreSQL
</p>

---

### `~/abdulrahman.ts`

```ts
type SkillLevel = "advanced" | "intermediate" | "learning";

type Language =
  | "TypeScript"
  | "JavaScript"
  | "Python"
  | "Java";

type Frontend =
  | "React"
  | "Next.js"
  | "Tailwind CSS"
  | "shadcn/ui";

type Mobile =
  | "React Native"
  | "Expo"
  | "Expo Router"
  | "TanStack Query"
  | "Zustand"
  | "Tamagui";

type Backend =
  | "Bun"
  | "Hono"
  | "REST APIs"
  | "Zod"
  | "Better Auth";

type Database =
  | "PostgreSQL"
  | "Drizzle ORM"
  | "Redis"
  | "Neon";

type Infrastructure =
  | "Docker"
  | "Cloudflare Workers"
  | "Vercel"
  | "Linux"
  | "Nginx";

type AI =
  | "AI Agents"
  | "RAG"
  | "LLM Integrations"
  | "Tool Calling"
  | "Automation";

interface Socials {
  github: string;
  linkedin: string;
  email: string;
}

interface Education {
  university: string;
  major: string;
}

interface SkillSet {
  languages: Record<SkillLevel, Language[]>;
  frontend: Frontend[];
  mobile: Mobile[];
  backend: Backend[];
  database: Database[];
  infrastructure: Infrastructure[];
  ai: AI[];
}

interface Environment {
  os: string;
  editor: string;
  runtimes: string[];
  packageManagers: string[];
}

abstract class Developer {
  abstract readonly name: string;
  abstract readonly role: string;
  abstract readonly location: string;

  abstract get stack(): SkillSet;
  abstract get currentFocus(): readonly string[];

  introduce(): string {
    return `${this.name} — ${this.role}`;
  }
}

class Abdulrahman extends Developer {
  readonly name = "Abdulrahman Matouk";

  readonly role =
    "Software Engineer · Mobile Developer · Full-Stack Developer";

  readonly location = "Riyadh, Saudi Arabia";

  readonly education: Education = {
    university: "Arab Open University",
    major: "Computer Science",
  };

  readonly socials: Socials = {
    github: "https://github.com/2ve2",
    linkedin: "https://www.linkedin.com/in/abdulrahman-matouk-00965b350",
    email: "bdalrhmnmtwq53@gmail.com",
  };

  get stack(): SkillSet {
    return {
      languages: {
        advanced: [
          "TypeScript",
          "Python",
        ],

        intermediate: [
          "JavaScript",
          "Java",
        ],

        learning: [],
      },

      frontend: [
        "React",
        "Next.js",
        "Tailwind CSS",
        "shadcn/ui",
      ],

      mobile: [
        "React Native",
        "Expo",
        "Expo Router",
        "TanStack Query",
        "Zustand",
        "Tamagui",
      ],

      backend: [
        "Bun",
        "Hono",
        "REST APIs",
        "Zod",
        "Better Auth",
      ],

      database: [
        "PostgreSQL",
        "Drizzle ORM",
        "Redis",
        "Neon",
      ],

      infrastructure: [
        "Docker",
        "Cloudflare Workers",
        "Vercel",
        "Linux",
        "Nginx",
      ],

      ai: [
        "AI Agents",
        "RAG",
        "LLM Integrations",
        "Tool Calling",
        "Automation",
      ],
    };
  }

  readonly environment: Environment = {
    os: "Fedora Linux",
    editor: "VS Code",
    runtimes: [
      "Bun",
      "Node.js",
    ],
    packageManagers: [
      "Bun",
      "npm",
    ],
  };

  readonly interests = [
    "Mobile Engineering",
    "Backend Architecture",
    "AI Agents",
    "Developer Tools",
    "Automation",
  ] as const;

  get currentFocus(): readonly string[] {
    return [
      "Building production-ready mobile applications",
      "Designing clean and scalable TypeScript backends",
      "Improving software architecture and performance",
      "Exploring AI agents and automation workflows",
    ];
  }

  get availableFor(): readonly string[] {
    return [
      "Mobile Development",
      "Full-Stack Development",
      "Software Engineering Internships",
      "Open Source Collaboration",
    ];
  }

  get philosophy(): string {
    return "Build. Break. Learn. Improve. Repeat.";
  }

  get profile() {
    return {
      developer: this.introduce(),
      location: this.location,
      education: this.education,
      stack: this.stack,
      environment: this.environment,
      interests: this.interests,
      focus: this.currentFocus,
      availableFor: this.availableFor,
      philosophy: this.philosophy,
    };
  }
}

const me = new Abdulrahman();

export default me;
```

---

### Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,python,java,react,nextjs,tailwind,nodejs,bun,postgres,docker,cloudflare,vercel,linux,git,github,vscode" />
</p>

---

### Currently Focused On

```ts
const currentFocus = [
  "React Native applications",
  "TypeScript backend development",
  "Clean architecture",
  "API design",
  "AI agents",
  "Automation",
] as const;
```

---

### Contact

```ts
const contact = {
  github: "https://github.com/2ve2",
  linkedin: "https://www.linkedin.com/in/abdulrahman-matouk-00965b350",
  email: "bdalrhmnmtwq53@gmail.com",
};
```

---

<p align="center">
  Building software with TypeScript, mobile-first thinking and clean architecture.
</p>
