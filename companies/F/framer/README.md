# Framer

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 0 | 1 |
| Fullstack | 9 | 9 | 11 | 14 | 4 | 14 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A designer wants generated microcopy to always fit specific UI character budgets across a whole app. How do you enforce hard length constraints reliably, and what post-processing backstop do you add when the model overshoots? | intermediate experience | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-designer-wants-generated-microcopy-to-always-fit-specific-ui-charact-27587) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a Flyweight-style shared-model layer for a real-time collaborative canvas so millions of nodes share style/geometry intrinsics across clients, and where does the extrinsic per-user cursor/selection state live to keep sync cheap? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-flyweight-style-shared-model-layer-for-a-rea-38437) |
| On the frontend you want interchangeable animation strategies (spring, tween, none) selectable at runtime and tree-shakeable. How do you structure them so unused strategies don't ship? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=on-the-frontend-you-want-interchangeable-animation-strategies-spring-t-16552) |
| Design the architecture for a design-collaboration canvas (Figma-scale) that must render a 100K-object document at 60fps in the browser and sync multiplayer edits — how do you split the rendering engine (WebGL/WASM) from the sync layer and keep memory bounded? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-design-collaboration-canvas-figma-scale--39444) |
| A designer wants generated microcopy to always fit specific UI character budgets across a whole app. How do you enforce hard length constraints reliably, and what post-processing backstop do you add when the model overshoots? | intermediate experience | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-designer-wants-generated-microcopy-to-always-fit-specific-ui-charact-27587) |
| How do CSS-in-JS libraries like styled-components affect bundle size and runtime performance versus utility CSS like Tailwind? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-css-in-js-libraries-like-styled-components-affect-bundle-size-a-10320) |
| How do you avoid a flash of the wrong theme (FOUC) on first paint when reading a saved dark-mode preference? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-avoid-a-flash-of-the-wrong-theme-fouc-on-first-paint-when-r-10273) |
| How would you animate a component's mount and unmount (like a modal or list item) in React? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-animate-a-component-s-mount-and-unmount-like-a-modal-or--10321) |
| How would you measure the width/height of a DOM element after render and react to it changing? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-measure-the-width-height-of-a-dom-element-after-render-a-10258) |
| Walk me through how React Fiber lets rendering be paused and resumed, at a high level. | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-react-fiber-lets-rendering-be-paused-and-resumed-a-10335) |
| What are the key differences between React Server Components and traditional SSR, and what runs on the server vs client? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-the-key-differences-between-react-server-components-and-tradi-10300) |
| What does useImperativeHandle do and when is exposing an imperative API from a component justified? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-useimperativehandle-do-and-when-is-exposing-an-imperative-ap-10257) |
| What is the concurrent rendering model in React 18, and what does it mean for interruptible renders? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-concurrent-rendering-model-in-react-18-and-what-does-it-me-10294) |
| Why can animating with React state be janky, and when should you drop to CSS transitions or a library like Framer Motion? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-can-animating-with-react-state-be-janky-and-when-should-you-drop-t-10322) |
| How would you architect defense against CSS injection that exfiltrates data via attribute selectors and font-face/unicode-range side channels when your app must render user-controlled CSS variables for theming at scale? | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-defense-against-css-injection-that-exfiltrates-38934) |
