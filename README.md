<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:FFB6C1,50:FF8FB1,100:FFC0CB&height=220&section=header&text=Hi,%20I'm%20Yeongeun%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38"
    width="100%"
  />
</p>

<br>

## 🌷 About Me

- 💻 React와 TypeScript를 활용한 웹앱 개발을 경험했습니다.
- 🎨 사용하기 쉽고 직관적인 UI/UX에 관심이 있습니다.
- 🤖 Gemini API와 OCR을 활용한 AI 기능을 구현해봤습니다.
- 📷 카메라 촬영 및 이미지 업로드 기능을 웹 서비스에 적용해봤습니다.
- 🤝 팀 프로젝트를 통해 협업과 서비스 개발 과정을 배우고 있습니다.

<br>

## 💻 Tech Stack

```prisma
model Yeongeun {
  github    String   @default("rladuddms0815")
  focus     String   @default("Web & AI")
  interests String[] @default(["UI/UX", "AI Web Service"])
  languages String[] @default(["TypeScript", "JavaScript"])

  model TechStack {
    frontend   String[]
    ai         String[]
    features   String[]
    tools      String[]
    deployment String[]
  }

  techStack TechStack[] @default(
    [
      TechStack(
        frontend   = [
          "React",
          "TypeScript",
          "JavaScript",
          "Tailwind CSS"
        ],

        tools      = [
          "Git",
          "GitHub",
          "VS Code",
          "Figma"
        ],

        deployment = [
          "Bolt"
        ]
      )
    ]
  )
}
```

<br>

## 🟡 나의 Contributions

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/rladuddms0815/rladuddms0815/output/pacman-contribution-graph-dark.svg">
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/rladuddms0815/rladuddms0815/output/pacman-contribution-graph.svg">
    <img
      alt="팩맨 contribution graph"
      src="https://raw.githubusercontent.com/rladuddms0815/rladuddms0815/output/pacman-contribution-graph.svg">
  </picture>
</p>

<br>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:FFC0CB,50:FF8FB1,100:FFB6C1&height=120&section=footer"
    width="100%"
  />
</p>
