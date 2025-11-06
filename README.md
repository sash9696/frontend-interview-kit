# Frontend Interview & Learning Kit 🚀

![GitHub stars](https://img.shields.io/github/stars/sash9696/frontend-interview-kit?style=social)
![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)
![Last Updated](https://img.shields.io/badge/updated-November%202025-green.svg)

**Your complete guide to mastering frontend interviews—curated resources, proven strategies, and hands-on projects.**

---

## Table of Contents

- [Quick Start](#quick-start)
- [Curriculum Overview](#curriculum-overview)
- [Fundamentals: HTML & CSS](#fundamentals-html--css)
- [JavaScript Core](#javascript-core)
- [React & Modern Frameworks](#react--modern-frameworks)
- [Data Structures & Algorithms](#data-structures--algorithms)
- [Frontend System Design](#frontend-system-design)
- [Testing & QA](#testing--qa)
- [Accessibility (a11y)](#accessibility-a11y)
- [Performance & Web Vitals](#performance--web-vitals)
- [Tooling, Build & Deploy](#tooling-build--deploy)
- [Machine Coding Rounds](#machine-coding-rounds)
- [Bonus: Frontend with AI](#bonus-frontend-with-ai)
- [Communication & Technical Leadership](#communication--technical-leadership)
- [Interview Kit](#interview-kit)
- [Projects & Build List](#projects--build-list)
- [Contribution & Community](#contribution--community)
- [Appendix](#appendix)
- [License](#license)

---

## Quick Start

**7-Minute Action Plan** — Copy this checklist:

```markdown
- [ ] Read Curriculum Overview (2 min)
- [ ] Bookmark top 3 resources for your weak area
- [ ] Pick ONE project from Build List
- [ ] Schedule 30-min daily study block for 8 weeks
- [ ] Join frontend communities (Reddit r/Frontend, Discord servers)
- [ ] Clone this repo and track progress with Issues
```

**First Week Goals:**
1. Complete 5 DSA pattern problems (two pointers, hashmap)
2. Build a small React component with tests
3. Read one system design case study

---

## Curriculum Overview

**12-Week Interview Prep Roadmap:**

| Week | Focus | Outcome |
|------|-------|---------|
| 1-2 | Fundamentals (HTML/CSS/JS) | Semantic markup, flexbox/grid, closures |
| 3-4 | React Deep Dive | Hooks, reconciliation, state management |
| 5-8 | DSA Patterns (Grind 169) | Master 8 core patterns, 40+ problems |
| 9-10 | System Design + Performance | Design 3 real systems, measure vitals |
| 11 | Testing + Accessibility | Write test suites, audit WCAG |
| 12 | Mock Interviews + Projects | Complete 2 portfolio projects |

**💡 Pro Tips:**
- Start with your weakest area—don't skip fundamentals if you're shaky on JavaScript closures or CSS positioning.
- Study in focused 90-minute blocks with 15-minute breaks (Pomodoro technique works well for technical learning).
- Practice coding without autocomplete once per week—interviews often use basic text editors or whiteboards.
- Join study groups or Discord communities—explaining concepts to others reinforces your understanding and reveals gaps.

---

## Fundamentals: HTML & CSS

### Resources

**[W3Schools HTML/CSS](https://www.w3schools.com/html/)**  
*Why:* Fastest reference for syntax and attributes.  
*How to Use:*
- **Study Plan:** 3 days, 1 hour/day. Focus on semantic HTML5 (`<article>`, `<section>`, `<nav>`), forms, and accessibility attributes.
- **Interview Talking Points:** "I use semantic HTML because it improves SEO, screen reader compatibility, and maintainability—`<button>` has built-in keyboard navigation that `<div>` doesn't."
- **Pitfalls:** Don't memorize every HTML entity; know the common ones (`&nbsp;`, `&lt;`, `&gt;`).
- **Exercise:** Build a form with validation (email, phone) without JavaScript.

**[web.dev (Google)](https://web.dev/learn/html/)**  
*Why:* Modern best practices, Core Web Vitals integration.  
*How to Use:*
- **Study Plan:** 5 days for HTML + CSS modules. Take notes on `<picture>`, `srcset`, CSS containment.
- **Interview Script:** "For responsive images, I use `<picture>` with WebP and JPEG fallbacks—it cut LCP by 40% in my last project."
- **Exercise:** Implement a responsive card grid using CSS Grid (no frameworks).

**[CSS-Tricks Flexbox/Grid Guide](https://css-tricks.com/)**  
*Why:* Visual diagrams for mental models.  
*How to Use:*
- Print the Flexbox and Grid cheatsheets. Recreate 5 common layouts (holy grail, sidebar, masonry-style).
- **Interview:** "Grid is for 2D layouts; Flexbox for 1D. I'd use Grid for a dashboard, Flexbox for a navbar."

### Practice Checklist

```markdown
- [ ] Memorize: Box model, specificity rules, BEM naming
- [ ] Experiment: CSS custom properties (variables), `@layer`, container queries
- [ ] Build: Landing page (mobile-first), CSS-only tooltip, dark mode toggle
- [ ] Accessibility: Use `:focus-visible`, ensure 4.5:1 contrast, test with screen reader
```

**💡 Pro Tips:**
- Use browser DevTools daily—inspect elements, modify CSS live, and understand the box model visually rather than memorizing rules.
- Create a personal "flexbox playground" CodePen where you test different flex properties—muscle memory beats theory for layout interviews.
- Learn CSS Grid by building real layouts (dashboard, magazine style, photo gallery) rather than reading documentation—practical experience sticks better.
- When debugging CSS, start with the browser's computed styles panel to see what's actually being applied (helps catch specificity issues fast).

**Tags:** `#fundamentals` `#html` `#css` `#accessibility`

---

## JavaScript Core

### Resources

**[JavaScript.info](https://javascript.info/)**  
*Why:* Best structured tutorial—from basics to advanced (event loop, microtasks).  
*How to Use:*
- **Study Plan:** 2 weeks. Read 2 chapters/day. Complete inline exercises.
- **Interview Gold:** Chapters 4 (objects), 6 (functions), 11 (Promises), 14 (event loop).
- **Pitfalls:** Don't skim the event loop—draw the diagram yourself (call stack, Web APIs, task queue, microtask queue).
- **Exercise:** Implement `Promise.all` from scratch; explain how it differs from `Promise.allSettled`.

**[Namaste JavaScript (YouTube Playlist)](https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)**  
*Why:* Visual explanations of closures, hoisting, `this`, prototypes.  
*How to Use:*
- **Study Plan:** Watch 2 videos/day (each 20-40 min). Pause and code along.
- **Interview Script:** "A closure is when an inner function retains access to its outer function's scope even after the outer function returns—this enables data privacy and factory patterns."
- **Exercise:** Write a `debounce` function and explain why closures are critical.

**[You Don't Know JS (GitHub Book Series)](https://github.com/getify/You-Dont-Know-JS)**  
*Why:* Deep dives into coercion, scope, `this`, prototypes, async.  
*How to Use:*
- **Study Plan:** Read one book per week (start with Scope & Closures, then this & Object Prototypes).
- **Interview:** "In JavaScript, `this` is determined by how a function is called, not where it's defined. Arrow functions lexically bind `this` from their enclosing scope."
- **Pitfall:** The books are dense—take notes, build examples.
- **Exercise:** Explain the difference between `call`, `apply`, and `bind` with code.

**[Learners Bucket](https://learnersbucket.com/)**  
*Why:* Hands-on JavaScript problems, polyfills, and frontend interview questions.  
*How to Use:*
- **Study Plan:** 1 week. Focus on JavaScript section—implement polyfills for `map`, `filter`, `reduce`, `bind`, `call`, `apply`.
- **Interview Gold:** "Polyfills" section—interviewers often ask "implement Array.prototype.map from scratch."
- **Practical Exercises:** Data structure implementations in JS (Linked List, Queue, Stack, Trie).
- **Interview Script:** "I implemented a polyfill for `Promise.all` that handles rejection properly and maintains order of resolved values."
- **Pitfall:** Don't just copy solutions—understand the underlying concepts (closures for bind, iteration patterns for array methods).
- **Exercise:** Implement `Function.prototype.bind` and explain how it uses closures to preserve context.

### Critical Concepts for Interviews

| Concept | What to Memorize | Interview Explanation Template |
|---------|-----------------|-------------------------------|
| **Closures** | Inner fn + outer scope | "Used for data encapsulation; enables module pattern and higher-order functions." |
| **Event Loop** | Call stack → Web APIs → Task Queue → Microtask Queue | "Microtasks (Promises) run before macrotasks (setTimeout). That's why Promise.then logs before setTimeout 0." |
| **Prototypes** | Every object has `[[Prototype]]`; classes are syntactic sugar | "Inheritance via prototype chain. `class` is cleaner but under the hood uses prototypes." |
| **Memory Leaks** | Detached DOM, global vars, event listeners | "Always remove listeners in cleanup; use WeakMap for cache." |
| **Async Patterns** | Callbacks → Promises → async/await | "Async/await is syntactic sugar for Promises; makes error handling easier with try/catch." |

**💡 Pro Tips:**
- Master the event loop by drawing it out on paper multiple times—visual memory helps in interviews when you need to explain execution order.
- Practice explaining JavaScript concepts out loud as if teaching a junior developer—if you can't explain it simply, you don't understand it well enough.
- Use Chrome DevTools' debugger extensively—set breakpoints, inspect closures, watch the call stack—hands-on debugging beats reading about concepts.
- Write small code snippets daily to test edge cases: what happens with `this` in arrow functions? How does `Promise.race` behave with rejected promises?

**Tags:** `#javascript` `#fundamentals` `#async` `#closures`

---

## React & Modern Frameworks

### Resources

**[React.dev (Official Docs)](https://react.dev/)**  
*Why:* New docs with interactive examples and mental models (e.g., "UI as a function of state").  
*How to Use:*
- **Study Plan:** 5 days. Read Learn React section. Focus on Thinking in React, Managing State, Escape Hatches.
- **Interview:** "React's reconciliation uses a virtual DOM diff. Keys help React identify which items changed—without keys, React may re-render unnecessarily."
- **Exercise:** Build a todo app with `useReducer` and explain when to use it vs. `useState`.

**[The Developer Way (YouTube)](https://www.youtube.com/c/DeveloperWay)**  
*Why:* Advanced patterns, performance optimization, anti-patterns.  
*How to Use:*
- **Study Plan:** Watch "React re-renders" and "useCallback/useMemo" videos.
- **Interview Script:** "useMemo caches computed values; useCallback caches function references. Overusing them adds complexity—profile first."
- **Pitfall:** Don't prematurely optimize; measure with React DevTools Profiler.

**[Jack Herrington (YouTube)](https://www.youtube.com/@jherr)**  
*Why:* Practical tutorials on TypeScript + React, state management, microfrontends.  
*How to Use:*
- **Study Plan:** Watch "State Management in React" and "Advanced TypeScript" playlists.
- **Interview:** "Context is great for global state (theme, auth) but causes re-renders. For complex state, I'd use Zustand or Jotai."
- **Exercise:** Compare Redux, Zustand, and Jotai—when would you pick each?

**[Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)**  
*Why:* Test user behavior, not implementation details.  
*How to Use:*
- **Study Plan:** 2 days. Read Guiding Principles, queries (`getByRole` > `getByTestId`), async utilities.
- **Interview:** "I use `getByRole` because it encourages accessible markup. If a button isn't queryable by role, it's not accessible."
- **Exercise:** Write tests for a form with validation; mock API calls with MSW.

### React Mental Models

**Rendering Pipeline:**
1. State change → React schedules re-render
2. React calls your component function → new JSX
3. Reconciliation: React diffs virtual DOM
4. Commit: React updates real DOM (batched)

**Interview Question:** "Why does my component re-render?"  
**Answer:** Parent re-render, state/props change, or Context change. Optimize with `React.memo`, split contexts, or lift state down.

**Hooks Rules:**
- Call at top level (not in loops/conditions)
- Only in function components or custom hooks

**State Management Decision Tree:**
- **Local state:** `useState`, `useReducer`
- **Shared state (few components):** Lift state up or Context
- **Global state (app-wide):** Zustand, Jotai, Redux Toolkit
- **Server state:** React Query, SWR

**💡 Pro Tips:**
- Use React DevTools Profiler before every optimization—measure first, optimize second. Most performance issues aren't where you think they are.
- Build a component library from scratch (don't use UI frameworks) to deeply understand composition, prop drilling, and when Context makes sense.
- Practice live-coding React components in CodeSandbox with a 20-minute timer—simulate interview pressure and improve speed.
- Read React's source code for core hooks (useState, useEffect)—understanding implementation details gives you confidence in interviews and helps debug weird issues.

**Tags:** `#react` `#hooks` `#performance` `#testing`

---

## Data Structures & Algorithms

### The "Grind 169" Strategy

**Why 169 Problems?**  
Research shows **pattern recognition** beats volume. The [Grind 169 list](https://www.techinterviewhandbook.org/grind75) covers 8 core patterns with optimal learning curve. Solving 169 deeply > 1000 randomly.

**8-Week DSA Plan (Grind 169 Approach):**

| Week | Pattern | Problems | Key Insight |
|------|---------|----------|-------------|
| 1 | Arrays + Hashing | Two Sum, Contains Duplicate, Valid Anagram | Hashmap trades space for O(1) lookup |
| 2 | Two Pointers | Valid Palindrome, Container With Most Water | Opposite-direction or same-direction pointers |
| 3 | Sliding Window | Best Time to Buy/Sell Stock, Longest Substring | Maintain window invariant |
| 4 | Binary Search | Search in Rotated Array, Find Min in Rotated | Eliminate half each iteration |
| 5 | Linked Lists | Reverse List, Merge Two Lists, Detect Cycle | Two-pointer (fast/slow) |
| 6 | Trees + BFS/DFS | Invert Tree, Max Depth, Level Order Traversal | Recursion vs. iteration tradeoffs |
| 7 | Graphs + Backtracking | Number of Islands, Clone Graph, Subsets | DFS with visited set |
| 8 | DP + Heaps | Climbing Stairs, Coin Change, Kth Largest | Memoization or tabulation |

### Resources

**[LeetCode](https://leetcode.com/) + [NeetCode Roadmap](https://neetcode.io/roadmap)**  
*Why:* NeetCode organizes problems by pattern with video explanations.  
*How to Use:*
- **Study Plan:** 2 problems/day (1 easy, 1 medium). Spend 30 min; if stuck, watch solution and retry next day.
- **Interview Script:** "I approach problems by identifying the pattern first—is it a graph, DP, or greedy problem? Then I think about time/space complexity before coding."
- **Pitfall:** Don't read solutions immediately. Struggle for 20 min; it builds intuition.

**[VisuAlgo](https://visualgo.net/en)**  
*Why:* Animated visualizations of sorting, trees, graphs.  
*How to Use:*
- Watch DFS/BFS animations. Understand why DFS uses a stack, BFS uses a queue.
- **Interview:** "BFS finds shortest path in unweighted graphs; DFS is better for detecting cycles or topological sort."

### Pattern Deep Dive (Examples)

#### Pattern 1: Two Pointers
**Canonical Problems:** Valid Palindrome, Container With Most Water  
**Approach:**
1. Initialize left = 0, right = n-1
2. While left < right:
   - Check condition
   - Move pointer(s) based on logic
3. Time: O(n), Space: O(1)

**Interview Script:**  
"Two pointers optimize brute force O(n²) to O(n) by using sorted data or opposite-direction traversal."

**Exercise:** Solve "3Sum" and explain how to avoid duplicates.

#### Pattern 2: Sliding Window
**Canonical Problems:** Longest Substring Without Repeating Chars, Max Sum Subarray  
**Approach:**
1. Expand window (move right pointer)
2. When condition violated, shrink window (move left)
3. Track max/min during expansion

**Interview Script:**  
"Sliding window maintains a window invariant—when violated, shrink until valid again. Reduces O(n²) to O(n)."

**Exercise:** Solve "Minimum Window Substring" and explain the template.

#### Pattern 3: BFS (Level-Order Traversal)
**Canonical Problems:** Binary Tree Level Order, Word Ladder  
**Approach:**
```python
from collections import deque

def bfs(root):
    queue = deque([root])
    while queue:
        level_size = len(queue)
        for _ in range(level_size):
            node = queue.popleft()
            # Process node
            if node.left: queue.append(node.left)
            if node.right: queue.append(node.right)
```

**Interview Script:**  
"BFS uses a queue; processes nodes level by level. Space: O(w) where w = max width of tree."

#### Pattern 4: Dynamic Programming
**Canonical Problems:** Climbing Stairs, Coin Change  
**Approach:**
1. Define subproblem: `dp[i]` = answer for input `i`
2. Find recurrence relation: `dp[i] = f(dp[i-1], dp[i-2], ...)`
3. Base cases
4. Return `dp[n]`

**Interview Script:**  
"DP optimizes recursion with memoization. I start with recursive solution, identify overlapping subproblems, then cache results."

**Exercise:** Solve "House Robber" top-down (memoization) and bottom-up (tabulation).

### Frontend-Specific DSA

- **Autocomplete/Typeahead:** Trie data structure
- **Debounce/Throttle:** Closure + timers
- **Virtual Scrolling:** Calculate visible indices with math
- **Undo/Redo:** Stack data structure

**💡 Pro Tips:**
- Don't just solve problems—after each one, write down the pattern (two pointers, sliding window, etc.) and keep a pattern journal for quick review.
- When stuck, spend exactly 20 minutes thinking before looking at hints—this struggle builds pattern recognition better than immediately reading solutions.
- Practice explaining your approach BEFORE coding in interviews—5 minutes of planning saves 15 minutes of debugging and shows structured thinking.
- Revisit problems after 3 days, then 1 week, then 1 month (spaced repetition)—this retention technique is proven more effective than solving 1000 problems once.

**Tags:** `#dsa` `#algorithms` `#leetcode` `#patterns`

---

## Frontend System Design

### Resources

**[GreatFrontEnd System Design](https://www.greatfrontend.com/system-design)**  
*Why:* Frontend-specific frameworks (not backend-focused).  
*How to Use:*
- **Study Plan:** Read 1 case study/day. Focus on RADIO framework (Requirements, Architecture, Data Model, Interface, Optimizations).
- **Interview:** Start with clarifying questions—scale, devices, offline support, real-time needs.

**[Frontend at Scale](https://frontendatscale.com/)**  
*Why:* Newsletter and articles on frontend architecture, scaling, and design patterns by Maxi Ferreira (Staff Engineer at Google Chrome).  
*How to Use:*
- **Study Plan:** Read newsletter archive (2 weeks). Focus on articles like "Visualizing Frontend Architecture," "Domain Modeling for Building UIs," "Separation of Concerns," and "May I Interest You In a Modular Monolith?"
- **Key Insights:** Architectural decision records (ADRs), modular monoliths, complexity management, coupling vs. cohesion, preparatory refactoring.
- **Interview Script:** "I follow frontend architecture best practices like separation of concerns and document decisions using ADRs to track tradeoffs over time."
- **Pitfall:** Don't just read—apply concepts to your current projects to internalize patterns.
- **Exercise:** Draw an architecture diagram for a project you've worked on using the C4 model (Context, Container, Component, Code).

**[Frontend System Design YouTube (Chirag Goel)](https://www.youtube.com/c/chirag-goel)**  
*Why:* Walkthrough of Uber, Netflix, Twitter UI designs.  
*How to Use:*
- Watch 3 videos; pause and diagram yourself.
- **Pitfall:** Don't jump to tech stack—define requirements first.

### Case Study 1: **High-Throughput Analytics Dashboard**

**Requirements:**
- Display 100k+ data points (time-series charts)
- Real-time updates (WebSocket)
- Filters, drill-downs, exports

**Architecture:**
```
┌─────────────┐
│   Browser   │
│  ┌───────┐  │     WebSocket      ┌──────────────┐
│  │ React │◄─┼────────────────────┤  Backend WS  │
│  └───┬───┘  │                    └──────────────┘
│      │      │
│  ┌───▼───┐  │
│  │ Web   │  │ (aggregation,
│  │Worker │  │  data transform)
│  └───────┘  │
└─────────────┘
```

**Tech Decisions:**
- **Canvas vs. SVG:** Canvas for >10k points (faster), SVG for <10k (interactive)
- **State Management:** Zustand (lightweight, no boilerplate)
- **Data Fetching:** React Query (caching, refetch on window focus)
- **Virtualization:** `react-window` for large lists

**Scaling:**
1. **Data Aggregation:** Backend sends pre-aggregated data (hourly → daily rollups)
2. **Web Workers:** Move chart calculations off main thread
3. **Debounced Filters:** Don't re-fetch on every keystroke (300ms debounce)
4. **Pagination:** Load 1000 rows at a time

**Interview Script:**  
"For a dashboard with 100k points, I'd use Canvas because SVG's DOM overhead slows rendering. I'd move data aggregation to a Web Worker to keep the UI responsive. For real-time updates, I'd use WebSocket with automatic reconnection and exponential backoff."

**Tradeoffs:**
- **Canvas:** Fast but less accessible (need fallback table)
- **WebSocket:** Real-time but complex (handle reconnections, missed messages)

### Case Study 2: **Image-Heavy E-Commerce Site**

**Requirements:**
- 1000+ product images per page
- Fast load time (target: LCP < 2.5s)
- Mobile-first

**Architecture:**
```
CDN (Cloudflare) → Next.js (ISR) → Image Optimization API
                                    ↓
                           - WebP, AVIF formats
                           - Responsive sizes (srcset)
                           - Lazy loading (below fold)
```

**Optimizations:**
1. **Formats:** WebP (30% smaller), AVIF (50% smaller) with JPEG fallback
2. **`<picture>` Element:** Serve optimal size per viewport
3. **Lazy Loading:** `loading="lazy"` for images below fold
4. **Blur-up Placeholder:** Load tiny LQIP (low-quality image placeholder), fade in full image
5. **CDN:** Edge caching, geographic distribution

**Performance Checklist:**
```markdown
- [ ] Measure baseline with Lighthouse (LCP, CLS)
- [ ] Enable Next.js Image Optimization or Cloudinary
- [ ] Implement `<picture>` with 3 sizes (mobile, tablet, desktop)
- [ ] Compress images (TinyPNG, Squoosh)
- [ ] Measure after: target LCP < 2.5s, CLS < 0.1
```

**Interview Script:**  
"To optimize images, I'd use Next.js Image component for automatic WebP conversion and responsive sizes. I'd lazy-load below-the-fold images and serve from a CDN. This reduced LCP from 4.2s to 1.8s in a recent project."

### Case Study 3: **Real-Time Collaboration (Google Docs-like)**

**Requirements:**
- Multiple users edit simultaneously
- Low latency (<100ms)
- Conflict resolution

**Architecture:**
```
Client (Editor) ←→ WebSocket ←→ Server (OT/CRDT) ←→ Database
       ↓
   Local State
   (Optimistic UI)
```

**Tech Stack:**
- **OT (Operational Transformation):** Google Docs approach—transform operations based on order
- **CRDT (Conflict-Free Replicated Data Type):** Yjs, Automerge—mathematically guaranteed convergence
- **Optimistic UI:** Apply change locally before server confirmation
- **WebSocket:** Persistent connection for low latency

**Tradeoffs:**
- **OT:** More complex, central server required
- **CRDT:** Decentralized, heavier payload

**Interview Script:**  
"For real-time collaboration, I'd use CRDTs (Yjs) because they guarantee eventual consistency without a central server. I'd implement optimistic UI—apply edits locally first, then sync to server. If conflict, CRDT resolves automatically."

**💡 Pro Tips:**
- Always start system design by clarifying requirements—ask about scale, users, devices, real-time needs before jumping into architecture.
- Draw diagrams on paper or whiteboard first before discussing implementation—visual communication is crucial in system design interviews.
- Study 2-3 real-world case studies in depth rather than skimming 20—deep knowledge of how Twitter handles feeds beats surface knowledge of many systems.
- Practice the "scale-up" approach: design for 1000 users first, then explain how you'd scale to 1M, then 100M—shows progressive thinking.

**Tags:** `#system-design` `#architecture` `#scaling` `#performance`

---

## Testing & QA

### Why Testing Matters in Interviews

"Untested code is broken code"—senior engineers proactively write tests. Interviewers look for test-aware design (dependency injection, pure functions).

### Testing Pyramid

```
      ╱╲
     ╱E2E╲         (10%) - Critical user flows
    ╱──────╲
   ╱ Integ. ╲      (30%) - Component interactions
  ╱──────────╲
 ╱   Unit     ╲    (60%) - Functions, hooks, utils
╱──────────────╲
```

### Resources

**[Jest Documentation](https://jestjs.io/)**  
*Why:* Industry standard for unit tests.  
*How to Use:*
- **Study Plan:** 2 days. Focus on mocks, spies, async tests.
- **Exercise:** Write tests for a `formatCurrency` function (edge cases: negatives, decimals, locales).

**[Testing Library (React)](https://testing-library.com/)**  
*Why:* Tests resemble how users interact with your app.  
*How to Use:*
- **Study Plan:** Read "Guiding Principles" and "Queries" docs.
- **Interview:** "I use `getByRole('button', { name: /submit/i })` instead of `getByTestId` because it enforces accessible markup."
- **Pitfall:** Don't test implementation details (internal state, function calls)—test outcomes.

**Example Test:**
```javascript
import { render, screen, fireEvent } from '@testing-library/react';
import LoginForm from './LoginForm';

test('shows error for invalid email', async () => {
  render(<LoginForm />);
  
  const emailInput = screen.getByLabelText(/email/i);
  const submitBtn = screen.getByRole('button', { name: /submit/i });
  
  fireEvent.change(emailInput, { target: { value: 'invalid' } });
  fireEvent.click(submitBtn);
  
  expect(await screen.findByText(/invalid email/i)).toBeInTheDocument();
});
```

**[Playwright](https://playwright.dev/) / [Cypress](https://www.cypress.io/)**  
*Why:* E2E tests for critical flows (login, checkout).  
*How to Use:*
- **Study Plan:** Pick one (Playwright is newer, faster). Write 3 E2E tests.
- **Interview:** "E2E tests are slow and flaky—I run them in CI before deploy, not on every commit. They catch integration bugs unit tests miss."

**Example E2E (Playwright):**
```javascript
test('user can complete checkout', async ({ page }) => {
  await page.goto('/products');
  await page.click('text=Add to Cart');
  await page.click('text=Checkout');
  await page.fill('[name=email]', 'test@example.com');
  await page.click('text=Submit Order');
  await expect(page.locator('text=Order Confirmed')).toBeVisible();
});
```

### Test Strategy Interview Rubric

| Scenario | Test Type | Why |
|----------|-----------|-----|
| Pure function (date formatter) | Unit | Fast, deterministic |
| React component with user interaction | Integration | Test behavior, not implementation |
| Critical flow (payment) | E2E | Ensures end-to-end correctness |
| API calls | Mock with MSW | Don't hit real APIs in tests |

**💡 Pro Tips:**
- Write tests BEFORE fixing bugs—create a failing test that reproduces the bug, then fix it. This prevents regressions and shows disciplined debugging.
- Aim for test names that read like documentation: "should show error message when email is invalid" beats "test1" every time.
- Don't test implementation details (internal state, private functions)—test user-facing behavior so refactors don't break tests unnecessarily.
- Learn Testing Library's philosophy deeply—it forces you to write accessible components because you query by role/label, not test IDs.

**Tags:** `#testing` `#jest` `#testing-library` `#e2e`

---

## Accessibility (a11y)

### Why a11y is Non-Negotiable

- **Legal:** ADA compliance (lawsuits cost millions)
- **Product:** 15% of users have disabilities—a11y expands market reach
- **SEO:** Semantic HTML improves search rankings
- **Interview:** Demonstrates inclusive design thinking and attention to detail

### The 5-Minute Accessibility Audit

```markdown
- [ ] Semantic HTML: `<button>` not `<div onClick>`, `<nav>`, `<main>`, `<article>`
- [ ] Keyboard Nav: Tab through page—can you access everything?
- [ ] ARIA: Only when semantic HTML insufficient (e.g., `aria-label` for icon buttons)
- [ ] Color Contrast: 4.5:1 for text, 3:1 for large text (use WebAIM Contrast Checker)
- [ ] Screen Reader: Test with VoiceOver (Mac) or NVDA (Windows)
```

### Resources

**[WebAIM](https://webaim.org/)**  
*Why:* Checklists, contrast checker, articles.  
*How to Use:*
- Read "WCAG 2 Checklist" (30 min). Focus on Level A and AA.
- **Exercise:** Audit a website; fix 5 issues (missing alt text, low contrast, missing labels).

**[MDN Accessibility Docs](https://developer.mozilla.org/en-US/docs/Web/Accessibility)**  
*Why:* Technical reference for ARIA roles, states, properties.  
*How to Use:*
- Bookmark ARIA roles reference. Learn when to use `role="button"` vs. `<button>`.

### Common Fixes

| Issue | Fix | Code |
|-------|-----|------|
| Icon button no label | Add `aria-label` | `<button aria-label="Close"><X /></button>` |
| Form input no label | Use `<label>` + `for` | `<label for="email">Email</label><input id="email">` |
| Low contrast text | Increase color difference | `color: #333` on `background: #fff` (12.6:1) |
| Div click handler | Use `<button>` | `<button onClick={...}>Click</button>` |
| Images missing alt | Add descriptive alt | `<img src="..." alt="User profile photo">` |

### Interview Script

**Question:** "How do you ensure accessibility?"  
**Answer:** "I start with semantic HTML—buttons, not divs—which gives keyboard nav for free. I test with a screen reader and automated tools like axe DevTools. I ensure color contrast meets WCAG AA (4.5:1). For dynamic content, I use ARIA live regions to announce updates."

**💡 Pro Tips:**
- Install axe DevTools browser extension and run it on every project—catch 80% of a11y issues in 30 seconds without manual testing.
- Practice keyboard navigation daily by unplugging your mouse for one hour—you'll quickly discover which patterns are frustrating for keyboard-only users.
- Learn VoiceOver (Mac) or NVDA (Windows) basics—spend 15 minutes navigating popular sites to understand screen reader UX before building features.
- Remember: if it's not keyboard accessible, it's not accessible—always test Tab, Enter, Escape, and Arrow keys for interactive components.

**Tags:** `#accessibility` `#a11y` `#wcag` `#inclusive-design`

---

## Performance & Web Vitals

### Core Web Vitals (Google Ranking Factors)

| Metric | Meaning | Target | How to Improve |
|--------|---------|--------|----------------|
| **LCP** (Largest Contentful Paint) | Time for main content to load | < 2.5s | Optimize images, reduce server time, preload resources |
| **FID** (First Input Delay) | Time to first interaction | < 100ms | Minimize JS, code-split, use Web Workers |
| **CLS** (Cumulative Layout Shift) | Visual stability | < 0.1 | Reserve space for images, avoid injected content |

### Optimization Checklist

```markdown
Phase 1: Measure
- [ ] Run Lighthouse (Chrome DevTools)
- [ ] Record baseline: LCP, FID, CLS, bundle size

Phase 2: Optimize
- [ ] Code-splitting: Dynamic imports (`React.lazy`, `import()`)
- [ ] Image optimization: WebP, `srcset`, lazy loading
- [ ] Minify JS/CSS: Vite, Webpack, Terser
- [ ] Tree-shaking: Remove unused code
- [ ] Caching: Service Worker, HTTP cache headers (Cache-Control)

Phase 3: Re-measure
- [ ] Run Lighthouse again—aim for 90+ score
- [ ] Test on slow network (Chrome DevTools throttling)
```

### Code-Splitting Example

```javascript
// Before: Bundle size 500 KB
import Dashboard from './Dashboard';

// After: Lazy load, initial bundle 150 KB
const Dashboard = React.lazy(() => import('./Dashboard'));

<Suspense fallback={<Spinner />}>
  <Dashboard />
</Suspense>
```

**Result:** Initial load 3x faster.

### Resources

**[web.dev Performance](https://web.dev/performance/)**  
*Why:* Guides on every optimization technique.  
*How to Use:*
- Read "Optimize LCP" and "Reduce JavaScript" articles.
- **Exercise:** Optimize a slow page; measure before/after with Lighthouse.

**[Webpack Bundle Analyzer](https://www.npmjs.com/package/webpack-bundle-analyzer)**  
*Why:* Visualize what's in your bundle.  
*How to Use:*
- Run analyzer, find large dependencies, replace or lazy-load them.

### Interview Script

**Question:** "How would you improve a slow app?"  
**Answer:** "First, I'd measure with Lighthouse to identify bottlenecks. If LCP is slow, I'd optimize images (WebP, lazy loading). If FID is high, I'd code-split heavy components and defer non-critical JS. I'd also check for memory leaks with DevTools Performance tab."

**💡 Pro Tips:**
- Run Lighthouse on 3G throttled connection—your fast WiFi masks real user experience. Most users don't have your network speed.
- Optimize images first—they're usually the biggest win for least effort. A single unoptimized hero image can tank your LCP score.
- Use Chrome DevTools Performance tab's flamegraph to find expensive re-renders—spending 30 minutes here often reveals surprising bottlenecks.
- Set performance budgets in CI—fail builds if bundle size grows >10KB or Lighthouse score drops below 90. Prevention beats optimization.

**Tags:** `#performance` `#web-vitals` `#optimization` `#lighthouse`

---

## Tooling, Build & Deploy

### Essential Resources

**[Vite Documentation](https://vitejs.dev/)**  
*Why:* Next-generation build tool—lightning-fast HMR, native ES modules, and optimized production builds.  
*How to Use:*
- **Study Plan:** 2 days. Read Getting Started, Features, and Plugin API sections.
- **Interview Script:** "I use Vite for its instant HMR and native ES modules support—dev server starts in milliseconds vs. seconds with Webpack. Build times are 10-100x faster."
- **Exercise:** Migrate a Create React App project to Vite and compare dev server startup and build times.

**[Next.js Documentation](https://nextjs.org/docs)**  
*Why:* React framework with SSR, ISR, file-based routing, and API routes built-in.  
*How to Use:*
- **Study Plan:** 1 week. Focus on App Router, Server Components, and rendering strategies (SSR, SSG, ISR, CSR).
- **Interview Gold:** Explain when to use each rendering strategy and their tradeoffs.
- **Exercise:** Build a blog with SSG for posts, ISR for content updates (revalidate every 60s), and CSR for comments.

**[TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/)**  
*Why:* Type safety catches bugs at compile time and improves developer experience with autocomplete.  
*How to Use:*
- **Study Plan:** 1 week. Focus on Basic Types, Interfaces, Generics, and Utility Types (`Partial`, `Pick`, `Omit`, `Record`).
- **Interview Script:** "TypeScript reduces runtime errors by 15-38% according to Microsoft research. I use it for better IDE support, refactoring confidence, and self-documenting code."
- **Exercise:** Add TypeScript to an existing JavaScript project incrementally—start with `allowJs` and gradually add types.

**[ESLint Documentation](https://eslint.org/docs/latest/)**  
*Why:* Catch code quality issues, bugs, and enforce consistent style across teams.  
*How to Use:*
- **Study Plan:** 1 day. Learn about rules, plugins (eslint-plugin-react, eslint-plugin-jsx-a11y), and shareable configs.
- **Interview:** "I configure ESLint with accessibility plugins to catch a11y issues during development, not after deployment."
- **Exercise:** Set up ESLint with Prettier, TypeScript, and Airbnb or Standard style guide.

**[Prettier Documentation](https://prettier.io/docs/en/)**  
*Why:* Opinionated code formatter—stops style debates and saves time in code reviews.  
*How to Use:*
- **Study Plan:** 1 hour. Learn configuration options and editor integration.
- **Interview:** "Prettier automates formatting so code reviews focus on logic, not style. I run it on pre-commit hooks with Husky."
- **Exercise:** Set up Prettier with ESLint (eslint-config-prettier) and configure it to format on save.

**[GitHub Actions Documentation](https://docs.github.com/en/actions)**  
*Why:* Automate CI/CD pipelines—tests, builds, deployments, and quality checks.  
*How to Use:*
- **Study Plan:** 2 days. Focus on workflow syntax, marketplace actions, caching, and secrets management.
- **Interview Script:** "I set up GitHub Actions to run tests, Lighthouse CI, and bundle size checks on every PR. Failed checks block merges—caught a 500KB bundle increase before it hit production."
- **Exercise:** Create a workflow that runs tests, builds, checks bundle size, and deploys to Vercel on merge to main.

**[Storybook Documentation](https://storybook.js.org/docs)**  
*Why:* Develop and document UI components in isolation—improves component reusability and team collaboration.  
*How to Use:*
- **Study Plan:** 3 days. Learn about stories, args, decorators, and addons (a11y, interactions, viewport).
- **Interview Gold:** "Storybook improves designer-developer collaboration—design specs and coded components live together. Reduces 'it looks different in production' issues."
- **Exercise:** Set up Storybook for a component library with a11y addon, interaction testing, and visual regression testing.

**[Webpack Documentation](https://webpack.js.org/concepts/)**  
*Why:* Still widely used—understanding module bundlers helps with debugging and optimization.  
*How to Use:*
- **Study Plan:** 3 days. Focus on loaders, plugins, code splitting, and tree shaking.
- **Interview:** "I optimized bundle size by analyzing with webpack-bundle-analyzer, implementing code splitting with dynamic imports, and enabling tree shaking."
- **Exercise:** Configure Webpack from scratch for a React app with dev server, production optimization, and CSS modules.

**[Vitest Documentation](https://vitest.dev/)**  
*Why:* Vite-native testing framework—instant test execution with HMR.  
*How to Use:*
- **Study Plan:** 1 day. Learn API compatibility with Jest and UI mode for debugging.
- **Interview:** "Vitest leverages Vite's speed—tests run 10x faster than Jest in large projects."
- **Exercise:** Migrate a Jest test suite to Vitest and compare execution times.

**[Turbopack Documentation](https://turbo.build/pack)**  
*Why:* Next-generation bundler built in Rust—successor to Webpack, incrementally adopted by Next.js.  
*How to Use:*
- **Study Plan:** 1 day. Read architecture and migration guide.
- **Interview:** "Turbopack offers 700x faster updates than Webpack in large apps—key for developer experience at scale."

### The Modern Frontend Stack

| Tool | Purpose | Why It Matters |
|------|---------|----------------|
| **Vite / Next.js** | Build tool / Framework | Fast HMR, SSR, ISR |
| **TypeScript** | Type safety | Catch bugs at compile time, better DX |
| **ESLint / Prettier** | Linting / Formatting | Enforce code quality, consistency |
| **Husky + lint-staged** | Git hooks | Run lints before commit |
| **GitHub Actions / CircleCI** | CI/CD | Automated tests, deploy |
| **Storybook** | Component library | Develop in isolation, documentation |

### CI Pipeline Example (GitHub Actions)

```yaml
name: CI
on: [push, pull_request]
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
      - run: npm ci
      - run: npm run lint
      - run: npm test
      - run: npm run build
```

### Demonstrating Ownership in Interviews

**Show Initiative and Impact:**
- "I set up CI to run tests on every PR. Reduced prod bugs by 40%."
- "I added bundle size checks—PRs fail if bundle grows >10%."
- "I wrote a postmortem after an outage—root cause was missing error boundary."

**💡 Pro Tips:**
- Learn TypeScript incrementally—start with basic types, then interfaces, then generics. Don't try to master advanced types on day one.
- Set up ESLint + Prettier on every project from day 1—consistency matters more than perfect rules, and automating style debates saves team energy.
- Understand your build tool (Vite, Webpack)—know where to find bundle analysis, how code-splitting works, and how to configure optimizations for interviews.
- Create starter templates with CI/CD preconfigured—shows you value automation and can hit the ground running on new projects.

**Tags:** `#tooling` `#ci-cd` `#typescript` `#devops`

---

## Machine Coding Rounds

Machine coding rounds test your ability to **build working features under time pressure** (60-120 minutes). Unlike DSA, these focus on **UI components, interactions, and real-world functionality**.

### What to Expect

**Common Challenges:**
- Build a component (autocomplete, infinite scroll, image carousel, star rating)
- Implement a feature (debounced search, drag-and-drop, undo/redo)
- Create a mini-app (todo list, calculator, tic-tac-toe, weather dashboard)

**Evaluation Criteria:**
- ✅ **Working code** - Does it work? Are edge cases handled?
- ✅ **Code quality** - Clean, readable, maintainable code
- ✅ **Problem-solving** - How you approach breaking down the problem
- ✅ **Best practices** - Component structure, state management, error handling
- ✅ **Performance** - Efficient rendering, proper optimizations

### Resources

**[GreatFrontEnd](https://www.greatfrontend.com/questions)**  
*Why:* Real machine coding questions asked at top companies (Google, Meta, Amazon).  
*How to Use:*
- **Study Plan:** 2 weeks. Solve 2-3 questions per day. Time yourself (60-90 min each).
- **Focus Areas:** UI components (autocomplete, tabs, accordion), data fetching, form handling.
- **Interview Script:** "I broke down the autocomplete into state management, debouncing, keyboard navigation, and accessibility."
- **Exercise:** Build an autocomplete with keyboard navigation (Up/Down arrows, Enter, Esc) and explain your approach.

**[BigFrontEnd.dev](https://bigfrontend.dev/)**  
*Why:* JavaScript coding challenges and React component questions.  
*How to Use:*
- **Study Plan:** 1 week. Focus on "JavaScript Coding" and "React Coding" sections.
- **Interview Gold:** Implement utility functions (throttle, debounce, flatten, deepClone).
- **Exercise:** Implement `Promise.all`, `Promise.race`, and explain edge cases.

**[Frontend Eval](https://frontendeval.com/)**  
*Why:* Timed challenges mimicking real interview conditions.  
*How to Use:*
- **Study Plan:** 3-4 days. Complete challenges in timed mode (60 min).
- **Focus:** Component behavior, state management, API integration.
- **Exercise:** Build a "Stop Watch" with start, stop, lap, and reset functionality.

**[DevTools Tech - Frontend Challenges](https://www.devtools.tech/?ref=frontend-interview-kit)**  
*Why:* Practice frontend machine coding with real interview-style problems—covers HTML/CSS, JavaScript, and React.  
*How to Use:*
- **Study Plan:** 1 week. Complete challenges in HTML/CSS and JavaScript sections.
- **Focus Areas:** Vanilla JavaScript implementations, DOM manipulation, event handling, no-framework challenges.
- **Interview Gold:** Problems like modal, tooltip, tabs, accordion teach fundamental patterns used across frameworks.
- **Exercise:** Build a multi-step form with validation and local storage persistence without using React.

**[Learners Bucket - Frontend Machine Coding](https://learnersbucket.com/examples/interview/)**  
*Why:* Collection of commonly asked frontend interview coding problems with solutions explained.  
*How to Use:*
- **Study Plan:** 5 days. Solve problems in "Frontend Machine Coding" section—focus on understanding patterns, not memorizing code.
- **Interview Gold:** Star rating, progress bar, pagination, accordion, modal, infinite scroll—these patterns appear in 70% of machine coding rounds.
- **Key Patterns:** Event delegation, debouncing/throttling, lazy loading, keyboard accessibility.
- **Exercise:** Implement a progress bar that fills based on scroll position and add keyboard shortcuts for accessibility.

**[JavaScript30](https://javascript30.com/)**  
*Why:* 30 vanilla JavaScript projects in 30 days—builds muscle memory for DOM manipulation and browser APIs.  
*How to Use:*
- **Study Plan:** 2 weeks (2 projects/day). Code along with Wes Bos, then rebuild from scratch without watching.
- **Focus:** Projects like Drum Kit, Clock, Video Player teach event handling, timers, and media APIs.
- **Interview:** "I've built 30 vanilla JavaScript projects which taught me to solve problems without reaching for libraries first."
- **Exercise:** Build the "Type Ahead" project (autocomplete) without watching the solution video.

**[Frontend Mentor](https://www.frontendmentor.io/)**  
*Why:* Real-world UI challenges with professional designs—practice building pixel-perfect components.  
*How to Use:*
- **Study Plan:** 1-2 weeks. Start with "Newbie" challenges, progress to "Junior" and "Intermediate."
- **Focus:** Responsive design, CSS Grid/Flexbox, accessibility, semantic HTML.
- **Interview:** "Frontend Mentor taught me to work from designs like in real jobs—I learned to estimate time and handle edge cases."
- **Exercise:** Complete the "Interactive Rating Component" challenge in 2 hours—includes state management and form handling.

**[Coding Challenges (Cassidy Williams)](https://github.com/cassidoo/interviews)**  
*Why:* Weekly interview questions (algorithms + frontend challenges) from a senior engineer.  
*How to Use:*
- **Study Plan:** Ongoing. Subscribe to newsletter, solve one challenge per week.
- **Focus:** Mix of DSA, JavaScript problems, and UI components.
- **Exercise:** Check the repository's issues for past challenges and solutions from the community.

### Common Machine Coding Problems

#### 1. **Autocomplete / Typeahead**
**Requirements:**
- Fetch suggestions from API as user types
- Debounce input (300ms)
- Keyboard navigation (Up/Down/Enter/Esc)
- Handle loading and error states
- Accessible (ARIA attributes)

**Key Concepts:** Debouncing, async/await, keyboard events, useRef, accessibility

**Gotchas:**
- Race conditions (cancel old requests)
- Memory leaks (cleanup on unmount)
- Empty states and error handling

---

#### 2. **Infinite Scroll**
**Requirements:**
- Load 20 items initially
- Fetch next page when user scrolls to bottom
- Show loading indicator
- Handle end of data

**Key Concepts:** Intersection Observer, pagination, useState, useEffect

**Gotchas:**
- Avoid multiple simultaneous fetches
- Cleanup observer on unmount
- Handle errors gracefully

---

#### 3. **Star Rating Component**
**Requirements:**
- Click to rate (1-5 stars)
- Hover preview
- Half-star support (optional)
- Keyboard accessible

**Key Concepts:** Event handling, controlled components, CSS (star icons)

**Gotchas:**
- Separate hover state from selected state
- Reset hover on mouse leave
- Keyboard navigation (Tab, Enter, Arrow keys)

---

#### 4. **Image Carousel**
**Requirements:**
- Show one image at a time
- Previous/Next buttons
- Auto-play (optional)
- Dot indicators

**Key Concepts:** useState, useEffect, setInterval, CSS transitions

**Gotchas:**
- Clear interval on unmount
- Handle edge cases (first/last image)
- Pause auto-play on hover

---

#### 5. **Tic-Tac-Toe**
**Requirements:**
- 3x3 grid, X and O players
- Detect winner
- Reset game
- Show game history (optional)

**Key Concepts:** State management, game logic, winner detection algorithm

**Gotchas:**
- Immutable state updates
- Efficient winner check (O(1) instead of checking all combinations)
- Handle draw (board full, no winner)

---

### Machine Coding Template

Use this structure for any component:

```javascript
import React, { useState, useEffect, useRef } from 'react';

function ComponentName({ prop1, prop2 }) {
  // 1. State
  const [data, setData] = useState([]);
  const [loading, setLoading] = useState(false);
  const [error, setError] = useState(null);
  
  // 2. Refs (for DOM access or mutable values)
  const inputRef = useRef(null);
  
  // 3. Effects (data fetching, subscriptions)
  useEffect(() => {
    // Fetch data or set up subscriptions
    
    // Cleanup
    return () => {
      // Remove listeners, cancel requests
    };
  }, [/* dependencies */]);
  
  // 4. Event handlers
  const handleClick = () => {
    // Logic
  };
  
  // 5. Render
  if (loading) return <div>Loading...</div>;
  if (error) return <div>Error: {error.message}</div>;
  
  return (
    <div>
      {/* Component UI */}
    </div>
  );
}

export default ComponentName;
```

### Interview Strategy

**Before coding (5-10 minutes):**
1. **Clarify requirements** - Ask about edge cases, browser support, accessibility needs
2. **Design component structure** - Sketch on paper or whiteboard
3. **Identify state** - What needs to be tracked?
4. **Plan approach** - Break into smaller tasks

**While coding (50-80 minutes):**
1. **Start with basic structure** - Get something rendering first
2. **Add functionality incrementally** - One feature at a time
3. **Handle edge cases** - Empty states, errors, loading
4. **Test as you go** - Run code frequently
5. **Communicate** - Explain your thought process

**After coding (10-20 minutes):**
1. **Test edge cases** - Empty input, rapid clicks, network errors
2. **Code cleanup** - Remove console.logs, add comments
3. **Discuss improvements** - Accessibility, performance, scaling

### Practice Schedule (2 Weeks)

**Week 1: Foundations**
- Day 1-2: Autocomplete (2 versions: basic, then with keyboard nav)
- Day 3: Star Rating + Tooltip
- Day 4: Infinite Scroll
- Day 5: Image Carousel
- Day 6-7: Todo List (add, delete, edit, filter, persist to localStorage)

**Week 2: Advanced**
- Day 8: Tic-Tac-Toe
- Day 9: Debounced Search with Filters
- Day 10: Drag and Drop (Kanban board)
- Day 11: Pagination with Filters
- Day 12: Modal with Focus Trap
- Day 13-14: Mock interview (timed, 90 min)

### Common Mistakes to Avoid

❌ **Don't:**
- Jump into coding without clarifying requirements
- Over-engineer (don't add Redux for a simple component)
- Ignore edge cases (null, undefined, empty arrays)
- Forget cleanup (event listeners, intervals, API calls)
- Skip accessibility (keyboard nav, ARIA)

✅ **Do:**
- Ask clarifying questions
- Start simple, iterate
- Handle loading and error states
- Test edge cases
- Explain your reasoning out loud
- Use semantic HTML
- Write clean, readable code

**💡 Pro Tips:**
- Practice with a timer—60-90 minutes max per problem to simulate real pressure.
- Use browser DevTools actively—check React DevTools for unnecessary re-renders, console for errors.
- Build a personal "component library" of 5-10 commonly asked components you can reference quickly.
- Record yourself coding and watch playback—you'll catch nervous habits, unclear explanations, and areas where you hesitate.
- Don't memorize solutions—memorize patterns (debouncing, keyboard handling, infinite scroll logic) that apply across problems.

**Tags:** `#machine-coding` `#live-coding` `#components` `#react`

---

## Bonus: Frontend with AI

AI is revolutionizing frontend development—from AI-assisted coding to building AI-powered UIs. Understanding AI tools and how to integrate AI into frontend applications is becoming essential for modern developers.

### Why AI Matters for Frontend Developers

- **Productivity:** AI tools like GitHub Copilot can increase coding speed by 30-50%
- **Code Quality:** AI catches bugs, suggests improvements, and generates tests
- **New Opportunities:** Building AI-powered UIs (chatbots, recommendations, image generation) is a growing skill
- **Interview Relevance:** Companies ask "How would you integrate AI into [feature]?" and "Have you used AI coding tools?"

### AI-Powered Development Tools

**[GitHub Copilot](https://github.com/features/copilot)**  
*Why:* AI pair programmer—suggests code, completes functions, generates tests.  
*How to Use:*
- **Study Plan:** 1 week trial. Use it for daily coding, observe patterns it suggests.
- **Best For:** Boilerplate code, test generation, documentation, common patterns.
- **Interview Script:** "I use GitHub Copilot to speed up boilerplate but always review suggestions—AI can introduce bugs or security issues. I use it for ~30% productivity boost."
- **Pitfall:** Don't blindly accept suggestions—AI hallucinates, especially with new libraries or edge cases.
- **Exercise:** Use Copilot to generate a React component with TypeScript types and tests, then refactor it yourself.

**[Cursor](https://cursor.sh/)**  
*Why:* AI-first code editor—built-in chat, codebase-aware AI, multi-file edits.  
*How to Use:*
- **Study Plan:** 3 days. Use Cmd+K for inline edits, Cmd+L for chat.
- **Best For:** Refactoring, explaining code, generating components from descriptions.
- **Interview:** "Cursor's AI understands my entire codebase—I ask it to refactor a component to use better patterns or explain legacy code."
- **Exercise:** Ask Cursor to refactor a class component to hooks, review the changes, and ask follow-up questions.

**[v0 by Vercel](https://v0.dev/)**  
*Why:* Generate UI components from text prompts—outputs React/Tailwind/Shadcn code.  
*How to Use:*
- **Study Plan:** 2 days. Generate 5-10 components, study the patterns it uses.
- **Best For:** Prototyping, learning new patterns, design-to-code workflows.
- **Interview:** "I use v0 for rapid prototyping—generate a component, customize it, learn new patterns from AI-generated code."
- **Exercise:** Prompt: "Create a pricing table with 3 tiers, monthly/yearly toggle, and feature comparison." Study the generated code.

**[ChatGPT / Claude](https://chat.openai.com/)** (Free tiers available)  
*Why:* General-purpose AI for debugging, learning, code review, and technical writing.  
*How to Use:*
- **Study Plan:** Daily use. Ask it to explain code, debug errors, generate examples.
- **Best For:** Learning concepts, debugging, generating test data, documentation.
- **Interview Script:** "When I encounter complex errors, I paste the code and error into ChatGPT to get potential solutions, then verify them myself."
- **Exercise:** Paste a bug you're stuck on, analyze ChatGPT's suggestions, and understand why the fix works.

**[Phind](https://www.phind.com/)**  
*Why:* AI search engine for developers—answers coding questions with sources.  
*How to Use:*
- **Study Plan:** Use it instead of Google for technical searches for 1 week.
- **Best For:** Finding solutions, comparing approaches, understanding error messages.
- **Interview:** "Phind gives me developer-focused answers with code examples and cites sources—faster than StackOverflow searching."

### Building AI-Powered Frontend Features

**[Vercel AI SDK](https://sdk.vercel.ai/)**  
*Why:* Framework-agnostic toolkit for building AI-powered streaming UIs with React, Vue, Svelte.  
*How to Use:*
- **Study Plan:** 3 days. Build a chatbot with streaming responses using `useChat` hook.
- **Key Features:** Streaming text generation, function calling, tool use, generative UI.
- **Interview Gold:** "I built a chatbot with the Vercel AI SDK that streams responses in real-time and maintains conversation context."
- **Exercise:** Build a chat interface that streams OpenAI responses and handles loading/error states.

**[LangChain.js](https://js.langchain.com/)**  
*Why:* JavaScript framework for building LLM-powered applications—chains, agents, memory.  
*How to Use:*
- **Study Plan:** 1 week. Focus on chains, prompt templates, and memory.
- **Best For:** RAG (Retrieval Augmented Generation), chatbots with context, AI agents.
- **Interview:** "I used LangChain to build a RAG system that answers questions from documentation using embeddings and vector search."
- **Exercise:** Build a Q&A system that searches your project's docs using embeddings.

**[OpenAI API](https://platform.openai.com/docs)** (Free credits for new users)  
*Why:* Direct access to GPT models—text generation, embeddings, image generation (DALL-E).  
*How to Use:*
- **Study Plan:** 2 days. Try completions, chat, embeddings, and image generation endpoints.
- **Best For:** Custom AI features, fine-tuning, function calling.
- **Interview Script:** "I integrated OpenAI's API to add AI-powered search suggestions that understand user intent, not just keywords."
- **Exercise:** Build an AI-powered autocomplete that suggests completions based on context.

**[Anthropic Claude API](https://docs.anthropic.com/)** (Free tier available)  
*Why:* Alternative to OpenAI with larger context window (100K+ tokens)—great for long documents.  
*How to Use:*
- **Study Plan:** 1 day. Compare with OpenAI for your use case.
- **Best For:** Processing long documents, code analysis, detailed explanations.

**[Hugging Face Transformers.js](https://huggingface.co/docs/transformers.js)**  
*Why:* Run machine learning models directly in the browser with WebAssembly—no backend needed!  
*How to Use:*
- **Study Plan:** 3 days. Try sentiment analysis, text classification, image classification.
- **Best For:** Privacy-focused AI (runs locally), offline AI features, edge computing.
- **Interview Gold:** "I used Transformers.js to run sentiment analysis in the browser—no API calls, user data stays private."
- **Exercise:** Build a sentiment analyzer that runs entirely client-side.

### AI for Learning & Productivity

**[Perplexity AI](https://www.perplexity.ai/)** (Free)  
*Why:* AI-powered research tool with cited sources—better than ChatGPT for factual information.  
*How to Use:*
- **Study Plan:** Use for technical research instead of Google.
- **Best For:** Understanding new technologies, comparing libraries, finding best practices.
- **Exercise:** Ask "What's the best state management library for React in 2024 and why?" Compare answers with your research.

**[Codeium](https://codeium.com/)** (Free forever)  
*Why:* Free alternative to GitHub Copilot—code completion, chat, multi-language support.  
*How to Use:*
- **Study Plan:** Install extension in VS Code, use for 1 week.
- **Interview:** "I use Codeium for free AI-assisted coding—generates tests, suggests refactors, explains complex code."

**[Tabnine](https://www.tabnine.com/)** (Free tier)  
*Why:* AI code completion trained on open-source code—works offline, privacy-focused.  
*How to Use:*
- **Study Plan:** 3 days. Compare with Copilot/Codeium to find what works best for you.
- **Best For:** Teams concerned about code privacy, offline development.

**[CodeWhisperer (Amazon)](https://aws.amazon.com/codewhisperer/)** (Free)  
*Why:* AI coding assistant from AWS—optimized for AWS services but works for general code.  
*How to Use:*
- **Study Plan:** Free forever. Great if you work with AWS.
- **Best For:** AWS integrations, general code completion.

### Prompt Engineering for Developers

**[Learn Prompting](https://learnprompting.org/)** (Free course)  
*Why:* Comprehensive guide to prompt engineering—essential skill for working with AI.  
*How to Use:*
- **Study Plan:** 3 days. Focus on "Applied Prompting" section for developers.
- **Key Concepts:** Few-shot learning, chain-of-thought prompting, system prompts.
- **Exercise:** Write prompts for code generation, debugging, and test creation.

**[OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)** (Free)  
*Why:* Official guide from OpenAI—best practices for getting good results.  
*How to Use:*
- **Study Plan:** 1 day. Learn tactics like splitting complex tasks, giving the model time to think.
- **Interview:** "I use few-shot prompting—providing examples helps the model understand the pattern I want."

### AI in Frontend Interviews

**Common Questions:**
1. "Have you used AI tools in your workflow?"
2. "How would you integrate AI into [feature]?"
3. "What are the risks of AI-generated code?"
4. "How do you ensure AI-generated code is secure?"
5. "Build a chatbot UI with streaming responses"

**Interview Strategy:**

**✅ Good Answers:**
- "I use AI tools for productivity but always review generated code for bugs, security issues, and performance"
- "For AI integration, I'd use streaming responses for better UX, handle rate limits, and cache responses"
- "I'm cautious about AI-generated code—verify dependencies exist, check for security vulnerabilities, test edge cases"

**❌ Bad Answers:**
- "I don't use AI tools" (falling behind)
- "AI writes all my code" (red flag—no critical thinking)
- "Just copy-paste AI code without review" (security risk)

### Building AI Projects (Portfolio Ideas)

1. **AI-Powered Chatbot**
   - Streaming responses with Vercel AI SDK
   - Conversation memory and context
   - Function calling (search, calculations)
   - **Talking Point:** "Built with React, OpenAI API, streaming for real-time UX"

2. **AI Code Review Tool**
   - Analyze code for improvements
   - Suggest refactors and best practices
   - Security vulnerability detection
   - **Talking Point:** "Uses LLM to analyze code and generate actionable feedback"

3. **Smart Search with RAG**
   - Semantic search using embeddings
   - RAG (Retrieval Augmented Generation)
   - Cite sources and show relevant docs
   - **Talking Point:** "Implemented vector search with Pinecone, generates answers from documentation"

4. **AI Image Generator UI**
   - DALL-E or Stable Diffusion integration
   - Prompt suggestions and history
   - Image editing and variations
   - **Talking Point:** "Integrated DALL-E API with React, handles async generation with optimistic UI"

5. **AI-Powered Form Filler**
   - Extract data from text/images
   - Auto-fill forms intelligently
   - Validate and format data
   - **Talking Point:** "Uses GPT-4 Vision to extract form data from documents"

### Best Practices for AI in Frontend

**Do:**
- ✅ Review all AI-generated code
- ✅ Test edge cases AI might miss
- ✅ Handle API errors and rate limits
- ✅ Implement streaming for better UX
- ✅ Cache responses to reduce costs
- ✅ Add loading states and error handling
- ✅ Consider privacy (don't send sensitive data to AI APIs)

**Don't:**
- ❌ Blindly copy-paste AI code
- ❌ Ignore security implications
- ❌ Send user data to AI without consent
- ❌ Rely on AI for critical security code
- ❌ Skip testing AI-generated code
- ❌ Forget to handle token limits

**💡 Pro Tips:**
- Learn prompt engineering—better prompts = better code from AI tools. Invest 2-3 days learning this skill.
- Use AI for boilerplate, not architecture—let AI generate repetitive code, but you design the system.
- Build AI-powered features for your portfolio—chatbots and AI search are impressive in interviews.
- Stay skeptical—AI hallucinates, especially with new libraries. Always verify against official docs.
- Understand costs—OpenAI API isn't free at scale. Learn about tokens, pricing, and optimization.

**Tags:** `#ai` `#chatgpt` `#github-copilot` `#machine-learning` `#future-of-development`

---

## Communication & Technical Leadership

### How to Present Tradeoffs

**Framework:** Always show both sides, then recommend with context.

**Example:**  
*Question:* "Redux vs. Zustand?"  
*Answer:*  
"**Redux** is great for large teams—strict patterns prevent chaos, middleware (Redux Thunk, Saga) handles complex async, and DevTools time-travel debugging is powerful. But it's verbose.  
**Zustand** is minimal—less boilerplate, smaller bundle. Great for small-to-medium apps.  
**I'd choose Redux** if the team is 10+ engineers or if we need middleware for analytics. **I'd choose Zustand** for a startup MVP where speed matters."

### Code Review Template

```markdown
## Summary
Brief description of changes.

## Testing
- [ ] Unit tests added/updated
- [ ] Tested locally
- [ ] E2E tests (if applicable)

## Accessibility
- [ ] Keyboard navigation works
- [ ] Screen reader tested (if UI change)

## Performance
- [ ] No unnecessary re-renders
- [ ] Bundle size impact: +X KB

## Screenshots
(if UI change)
```

### Design Doc One-Pager

```markdown
# [Feature Name]

## Problem
What user pain point are we solving?

## Proposal
High-level solution (2-3 sentences).

## Design
- Architecture diagram
- API contracts
- Data models

## Alternatives Considered
What did we reject and why?

## Risks & Mitigations
What could go wrong?

## Success Metrics
How do we measure success? (e.g., "Reduce load time by 30%")
```

**💡 Pro Tips:**
- Practice the "disagree and commit" approach—state your technical opinion clearly, but if overruled, commit fully. This shows maturity in interviews.
- When reviewing code, always say one positive thing before suggesting improvements—builds trust and shows you're thinking about team dynamics.
- Document decisions with ADRs (Architecture Decision Records)—in interviews, mention "I documented the tradeoffs between Redux and Zustand in an ADR" shows systematic thinking.
- Learn to say "I don't know, but here's how I'd find out"—honesty plus problem-solving approach beats faking knowledge every time in technical discussions.

**Tags:** `#communication` `#leadership` `#collaboration`

---

## Interview Kit

### The 30-Second Elevator Pitch

"I'm a frontend engineer with X years experience. I specialize in [React, performance, a11y]. Recently, I [built a dashboard that handles 100k data points / reduced LCP by 50% / led a team of 5]. I'm excited about [company's mission/product]."

### The 2-Minute Project Walkthrough

**Template:**
1. **Context:** "We needed to rebuild our checkout flow—conversion was dropping."
2. **My Role:** "I led the frontend redesign. I worked with design and backend."
3. **Technical Decisions:** "I used React + TypeScript, optimized images (WebP), lazy-loaded payment module."
4. **Outcome:** "Conversion increased 15%. Load time dropped from 4s to 1.8s."
5. **Learning:** "I learned to prioritize metrics—not every optimization matters."

### Common System Design Prompts + Model Answers

**Prompt 1:** "Design a news feed (Twitter/Facebook)."

**Model Answer:**
1. **Requirements:**
   - Infinite scroll, real-time updates, 1M users
2. **Architecture:**
   - Frontend: React + React Query (caching)
   - Backend: REST API or GraphQL, paginated responses
   - Real-time: WebSocket or Server-Sent Events
3. **Data Flow:**
   - Fetch initial 20 posts
   - User scrolls → fetch next page (offset/cursor pagination)
   - New post event via WebSocket → prepend to feed
4. **Optimizations:**
   - Virtual scrolling (`react-window`) for 1000+ posts
   - Lazy-load images
   - Optimistic UI (show post immediately, sync in background)
5. **Tradeoffs:**
   - Cursor pagination > offset (consistent with new inserts)
   - GraphQL > REST (overfetching problem)

**Prompt 2:** "Design an autocomplete widget."

**Model Answer:**
1. **Requirements:**
   - Search-as-you-type, 10k queries/day
2. **Data Structure:**
   - Trie (prefix tree) for O(k) lookup (k = query length)
3. **Frontend:**
   - Debounce input (300ms) → API call
   - Cache results (React Query, 5 min TTL)
   - Keyboard navigation (arrow keys, Enter)
4. **Accessibility:**
   - `role="combobox"`, `aria-expanded`, `aria-autocomplete`
5. **Edge Cases:**
   - Slow network → show loading spinner
   - API error → show fallback UI
   - Race condition → cancel old requests (AbortController)

### Mock Interview Self-Grading Rubric

| Category | Poor | Good | Excellent |
|----------|------|------|-----------|
| **Problem Solving** | Stuck, no progress | Solved with hints | Optimal solution, explains tradeoffs |
| **Code Quality** | Buggy, unreadable | Works, some issues | Clean, edge cases handled |
| **Communication** | Silent or rambling | Explains approach | Thinks aloud, collaborates |
| **Testing** | No mention | Describes tests | Writes test cases |
| **Tradeoffs** | One-sided | Mentions tradeoffs | Compares 2-3 approaches, recommends |

**💡 Pro Tips:**
- Record yourself doing mock interviews—watching playback reveals filler words, unclear explanations, and nervous habits you don't notice in real-time.
- Practice the STAR method for behavioral questions (Situation, Task, Action, Result)—structure helps you stay concise and hit key points under pressure.
- Prepare 3 "go-to" projects you can discuss at different depths (30 seconds, 2 minutes, 5 minutes)—interviewers will cut you off or ask for more based on interest.
- When asked about failures, choose real examples but focus on learnings—"I deployed without testing, site crashed, now I always run integration tests before deploy" shows growth.

**Tags:** `#interview` `#system-design` `#behavioral`

---

## Projects & Build List

### Why These Projects?

Each project demonstrates **multiple skills** (React, DSA, testing, a11y, performance) and has **extensibility** for senior-level talking points.

---

### Project 1: **Real-Time Kanban Board**

**MVP (1 day):**
- Drag-and-drop cards between columns (react-beautiful-dnd)
- Add/edit/delete cards
- Local state (no backend)

**Extensions:**
- Real-time sync (Firebase or Socket.io)
- Undo/redo (stack data structure)
- Keyboard shortcuts (a11y)
- Optimistic UI updates

**Skills Demonstrated:** React hooks, state management, drag-and-drop, data structures (stack).

**Interview Talking Points:**  
"I used optimistic UI—cards move instantly, then sync to server. If sync fails, I roll back with undo stack. For a11y, I added keyboard shortcuts to move cards without mouse."

---

### Project 2: **Infinite Scroll Image Gallery**

**MVP (1 day):**
- Fetch images from API (Unsplash)
- Infinite scroll (Intersection Observer)
- Lazy-load images

**Extensions:**
- Virtual scrolling (react-window)
- Skeleton loaders (better UX)
- Search with debouncing
- Lighthouse score >90

**Skills Demonstrated:** Performance optimization, Web APIs, async JS, UX.

**Interview Talking Points:**  
"I used Intersection Observer to detect when user scrolls to bottom, then fetch next page. I debounced search to avoid excessive API calls. Lazy-loaded images cut LCP from 3.5s to 1.2s."

---

### Project 3: **Markdown Editor with Preview**

**MVP (1 day):**
- Split-pane: editor on left, preview on right
- Convert markdown to HTML (marked.js or remark)
- Syntax highlighting (Prism)

**Extensions:**
- Autosave to localStorage
- Export to PDF
- Dark mode toggle
- Vim keybindings

**Skills Demonstrated:** State management, text processing, localStorage API.

**Interview Talking Points:**  
"I debounced the markdown parsing (300ms) to avoid re-rendering on every keystroke. Used localStorage for autosave—even if user closes tab, their work is saved."

---

### Project 4: **Expense Tracker with Charts**

**MVP (1 day):**
- Add/edit/delete expenses (form validation)
- Pie chart by category (Chart.js or Recharts)
- Filter by date range

**Extensions:**
- Export to CSV
- Budget alerts (if spending exceeds limit)
- Recurring expenses (DP: scheduling algorithm)
- PWA (offline mode)

**Skills Demonstrated:** Forms, validation, data visualization, algorithms.

**Interview Talking Points:**  
"I used controlled components for forms with validation (email regex, min/max). For charts, I aggregated data by category—O(n) time using a hashmap. Made it a PWA with service worker for offline access."

---

### Project 5: **Accessible Dropdown Menu**

**MVP (4 hours):**
- Multi-level dropdown (nested menus)
- Keyboard navigation (Tab, Arrow keys, Esc)
- ARIA attributes

**Extensions:**
- Typeahead search within menu
- Mobile-friendly (touch gestures)
- Unit tests (Testing Library)

**Skills Demonstrated:** Accessibility, event handling, testing.

**Interview Talking Points:**  
"I used `role="menu"` and `aria-haspopup` for screen readers. Arrow keys navigate items, Esc closes menu, Tab exits. Tested with NVDA screen reader and wrote integration tests with Testing Library."

---

### Project 6: **Type-Ahead Search (Autocomplete)**

**MVP (1 day):**
- Trie data structure for fast prefix matching
- Debounced input
- Highlight matching text

**Extensions:**
- Recent searches (localStorage)
- API integration (fetch suggestions from backend)
- Fuzzy matching (Levenshtein distance)

**Skills Demonstrated:** Data structures (Trie), algorithms, async JS.

**Interview Talking Points:**  
"I built a Trie to store 10k words—search is O(k) where k = query length, much faster than array.filter's O(n). Debounced input to avoid excessive re-renders. For fuzzy search, I used Levenshtein distance to handle typos."

---

**💡 Pro Tips:**
- Deploy every project (Vercel, Netlify are free)—live links in your resume get 10x more attention than GitHub repos that require local setup.
- Write a brief README for each project explaining technical decisions—"Why React Query over Redux?" shows you think about tradeoffs, not just features.
- Add analytics to your projects (Google Analytics or Plausible)—being able to say "my project got 500 monthly users" demonstrates real-world impact beyond code.
- Pick projects that solve YOUR pain points—genuine interest shows in interviews, and you'll have deeper insights than building yet another todo app.

**Tags:** `#projects` `#portfolio` `#hands-on`

---

## Contribution & Community

We welcome contributions! Here's how:

### How to Contribute

1. **Add a Resource:**
   - Open an issue with title "Resource: [Name]"
   - Include: URL, one-line summary, why it matters, how to use it
   - Wait for maintainer review

2. **Fix an Error:**
   - Fork repo → create branch → make fix → open PR
   - Use PR template (see `.github/PULL_REQUEST_TEMPLATE.md`)

3. **Share Your Experience:**
   - Comment on issues with study tips, interview stories
   - Suggest improvements to study plans

### Review Rubric

We accept contributions that:
- ✅ Add value (no spam links)
- ✅ Include practical guidance (not just a link dump)
- ✅ Are well-formatted (use markdown)
- ✅ Cite sources

We reject:
- ❌ Affiliate links
- ❌ Duplicate resources (check existing first)
- ❌ Low-quality content (typos, vague descriptions)

### Code of Conduct

- Be respectful and inclusive
- No harassment, discrimination, or spam
- Assume good intentions

**Tags:** `#community` `#contributing` `#open-source`

---

## Appendix

### 30/60/90-Day Study Plans

**30-Day Plan (Interview in 1 month):**
- Days 1-10: Grind 20 DSA problems (focus: arrays, hashmaps, two pointers)
- Days 11-20: React deep dive + build 2 projects
- Days 21-25: System design (study 5 case studies)
- Days 26-30: Mock interviews (Pramp, Interviewing.io)

**60-Day Plan (More thorough prep):**
- Weeks 1-2: JS fundamentals (javascript.info)
- Weeks 3-4: React + Testing Library
- Weeks 5-6: Grind 169 (40 problems)
- Weeks 7-8: System design + Performance + Mock interviews

**90-Day Plan (Senior+ level):**
- Follow 12-week roadmap (Curriculum Overview)
- Add: 2 open-source contributions, 3 blog posts, mentor 1 junior engineer

---

### Cheatsheets

**Big-O Complexity:**
- O(1): Array access, hashmap lookup
- O(log n): Binary search, balanced tree operations
- O(n): Linear scan, array.map
- O(n log n): Merge sort, quick sort
- O(n²): Nested loops, bubble sort

**React Hooks:**
- `useState`: Local state
- `useEffect`: Side effects (cleanup on unmount)
- `useReducer`: Complex state (similar to Redux)
- `useRef`: Persist value without re-render, access DOM
- `useMemo`: Cache computed value
- `useCallback`: Cache function reference
- `useContext`: Access Context value

**HTTP Status Codes:**
- 200: OK
- 201: Created
- 400: Bad Request
- 401: Unauthorized
- 403: Forbidden
- 404: Not Found
- 500: Internal Server Error

---

### One-Page Printable Study Card

```
┌────────────────────────────────────────────────────────┐
│          FRONTEND INTERVIEW STUDY CARD                 │
├────────────────────────────────────────────────────────┤
│ JAVASCRIPT                                             │
│ ☑ Closures, event loop, prototypes, async/await       │
│ ☑ Implement: debounce, throttle, Promise.all          │
│                                                        │
│ REACT                                                  │
│ ☑ Hooks rules, reconciliation, keys                   │
│ ☑ When to use: useState, useReducer, Context          │
│                                                        │
│ DSA PATTERNS                                           │
│ ☑ Two pointers, sliding window, BFS/DFS, DP           │
│ ☑ Solve 2 problems/day from Grind 169                 │
│                                                        │
│ SYSTEM DESIGN                                          │
│ ☑ Ask clarifying questions (scale, devices)           │
│ ☑ Discuss tradeoffs (Canvas vs SVG, REST vs GraphQL)  │
│                                                        │
│ PERFORMANCE                                            │
│ ☑ LCP < 2.5s, FID < 100ms, CLS < 0.1                  │
│ ☑ Code-split, lazy-load, optimize images (WebP)       │
│                                                        │
│ ACCESSIBILITY                                          │
│ ☑ Semantic HTML, keyboard nav, 4.5:1 contrast         │
│ ☑ Test with screen reader                             │
└────────────────────────────────────────────────────────┘
```


## If This Helped You

**Please ⭐ this repo** — it helps others discover it!

**Share it:**
- Tweet: "Best free frontend interview guide: [link]"
- LinkedIn: "If you're prepping for frontend interviews, this repo is gold."
- Reddit: Post in r/Frontend, r/webdev

**Contribute:**
- Add resources, fix typos, share your interview stories

---

**Built with ❤️ by the dev. Good luck with your interviews!**

---

### Tags for GitHub

`frontend` `interview-preparation` `react` `javascript` `algorithms` `system-design` `web-development` `career`

