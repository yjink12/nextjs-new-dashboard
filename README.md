# Next.js new Dashboard

<div align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
</div>

<div align="left">
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
    <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=Vercel&logoColor=white"/>
</div>

---

## 프로젝트 목적
- Next.js 개념 다시 돌아보기
- [Next.js 공식 문서](https://nextjs.org/learn?utm_source=next-site&utm_medium=homepage-cta&utm_campaign=home) (App Router Course - Starter)


## 프로젝트 설치 및 실행

**버전**

- Next.js: 15.3.1
- Next-Auth: 5.0.0-beta.27
- TailwindCSS : 3.4.17
- Typescript: 5.7.3

**실행**

```
npm run dev
npm run start
```

**URL**

[Next.js new Dashboard](https://nextjs-new-dashboard.vercel.app/)

---

## 개념
- [Next.js 렌더링 방식](https://swamp-bass-b68.notion.site/Next-1e9204588dd68078a7abd5386f48c712?pvs=4)
- [Next.js 이미지/폰트 최적화](https://swamp-bass-b68.notion.site/Next-1e9204588dd680728386f1d8d68953fa?pvs=4)
- [Next.js API - useSearchParams, usePathname, useRouter](https://swamp-bass-b68.notion.site/Next-API-useSearchParams-usePathname-useRouter-1eb204588dd680f88d41d55083e808f4?pvs=4)
- [Next.js Server Action](https://swamp-bass-b68.notion.site/Server-Action-1eb204588dd6803eb880e1a9149e0694?pvs=4)
- [Next.js 오류 처리](https://swamp-bass-b68.notion.site/1eb204588dd68057bd87c7ac2fd742d5?pvs=4)
- [Next.js 접근성](https://swamp-bass-b68.notion.site/1eb204588dd6804aabf9f1b2e3772615?pvs=4)
- [Next.js Next-Auth](https://swamp-bass-b68.notion.site/Next-auth-1eb204588dd6801487e2c9fafb5ef54f?pvs=4)
- [Next.js Metadata](https://swamp-bass-b68.notion.site/Metadata-1eb204588dd6802ead5fd53487cf8a24?pvs=4)



## 이슈사항

- [[Issue] ESLint no-unused-vars](https://swamp-bass-b68.notion.site/Issue-ESLint-no-unused-vars-1ec204588dd6803a8bb8c52afdac6530?pvs=4)

---

## 폴더구조
- [Next.js 폴더구조](https://swamp-bass-b68.notion.site/Next-1e9204588dd680148cc0c06686659006?pvs=4)
- `app/` directory 사용

```
nextjs-dashboard
├─ app
│  ├─ dashboard
│  │  ├─ (overview)
│  │  │  ├─ loading.tsx
│  │  │  └─ page.tsx
│  │  ├─ customers
│  │  │  └─ page.tsx
│  │  ├─ invoices
│  │  │  ├─ create
│  │  │  │  └─ page.tsx
│  │  │  ├─ error.tsx
│  │  │  ├─ page.tsx
│  │  │  └─ [id]
│  │  │     └─ edit
│  │  │        ├─ not-found.tsx
│  │  │        └─ page.tsx
│  │  └─ layout.tsx
│  ├─ favicon.ico
│  ├─ layout.tsx
│  ├─ lib
│  │  ├─ actions.ts
│  │  ├─ data.ts
│  │  ├─ definitions.ts
│  │  ├─ placeholder-data.ts
│  │  └─ utils.ts
│  ├─ login
│  │  └─ page.tsx
│  ├─ opengraph-image.png
│  ├─ page.tsx
│  ├─ query
│  │  └─ route.ts
│  ├─ seed
│  │  └─ route.ts
│  └─ ui
│     ├─ acme-logo.tsx
│     ├─ button.tsx
│     ├─ customers
│     │  └─ table.tsx
│     ├─ dashboard
│     │  ├─ cards.tsx
│     │  ├─ latest-invoices.tsx
│     │  ├─ nav-links.tsx
│     │  ├─ revenue-chart.tsx
│     │  └─ sidenav.tsx
│     ├─ fonts.ts
│     ├─ global.css
│     ├─ home.module.css
│     ├─ invoices
│     │  ├─ breadcrumbs.tsx
│     │  ├─ buttons.tsx
│     │  ├─ create-form.tsx
│     │  ├─ edit-form.tsx
│     │  ├─ pagination.tsx
│     │  ├─ status.tsx
│     │  └─ table.tsx
│     ├─ login-form.tsx
│     ├─ search.tsx
│     └─ skeletons.tsx
├─ public
│  ├─ customers
│  │  ├─ amy-burns.png
│  │  ├─ balazs-orban.png
│  │  ├─ delba-de-oliveira.png
│  │  ├─ evil-rabbit.png
│  │  ├─ lee-robinson.png
│  │  └─ michael-novotny.png
│  ├─ hero-desktop.png
│  └─ hero-mobile.png
├─ auth.config.ts
├─ auth.ts
├─ middleware.ts
├─ next.config.ts
├─ package-lock.json
├─ package.json
├─ postcss.config.js
├─ README.md
├─ tailwind.config.ts
└─ tsconfig.json
```
