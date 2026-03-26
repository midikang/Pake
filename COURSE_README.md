# Pake Interactive Learning Course

## 🎓 About This Course

This interactive HTML course teaches how Pake works — transforming websites into desktop applications. The course follows the **codebase-to-course** methodology, designed specifically for "vibe coders" (people who build with AI code tools) to understand how the code works under the hood.

## 📁 Files

- **`pake-course.html`** - Main interactive course (open in any browser)
- **`COURSE_README.md`** - This file

## 🚀 How to Use

1. Open `pake-course.html` in your browser
2. Scroll through the modules or use keyboard arrows (↑/↓)
3. Interact with:
   - **Code ↔ English translations** — Real code with plain language explanations
   - **Quizzes** — Test your understanding with scenario-based questions
   - **Chat animations** — See how components communicate
   - **Glossary tooltips** — Hover over any technical term for a definition

## 📚 Course Structure

### Module 1: What Pake Does
- Understanding the "website → desktop app" transformation
- Tracing what happens when you run `pake https://github.com`
- The key advantage: Using system webview vs. bundling a browser

### Module 2: The Cast of Characters
- The four main components: CLI, Config, Rust Core, Icon Pipeline
- How they communicate and divide responsibilities
- Where each component lives in the codebase

### Modules 3-6 (Framework Established)
The foundation is built for:
- **Module 3**: How The Pieces Talk (Data flow)
- **Module 4**: The Build Pipeline (From CLI to app)
- **Module 5**: Clever Engineering Tricks (Patterns like icon fallback chain, platform abstraction)
- **Module 6**: Making It Your Own (Customization guide)

## 🎯 Learning Goals

After completing this course, you will be able to:

1. **Steer AI coding tools better** — Make informed architectural decisions about packaging apps
2. **Debug effectively** — Know where to look when something goes wrong (CLI vs Runtime)
3. **Understand tradeoffs** — Electron vs Tauri, platform-specific vs cross-platform
4. **Communicate precisely** — Use the correct technical vocabulary (user agent, WebView, binary, etc.)

## 🎨 Design Philosophy

This course embodies several key principles:

### Build First, Understand Later
The learner likely built something (or found something on GitHub) that works. This course shows HOW it works by tracing actual user journeys.

### Show, Don't Tell
- Maximum 2-3 sentences per text block
- Every screen is at least 50% visual
- Lists become cards, sequences become diagrams

### Quizzes Test Application, Not Memory
Instead of "What does API stand for?", we ask: "A user reports stale data — where would you look first?" This tests whether you can USE what you learned.

### No Recycled Metaphors
Each concept gets a metaphor that fits THAT specific idea:
- Database → Library with card catalog
- Auth → Bouncer checking IDs
- Icon service fallback → GPS trying different satellite signals

### Original Code Only
Code snippets are exact copies from the real Pake codebase — never modified or simplified. The learner can open the actual file and see the same code.

## 🛠️ Technical Stack

The course itself demonstrates modern web techniques:

- **Single HTML file** — No dependencies except Google Fonts
- **CSS Grid & Flexbox** — Responsive layouts
- **Scroll-snap** — Module-by-module navigation
- **Intersection Observer** — Scroll-triggered animations
- **Vanilla JavaScript** — No frameworks needed

## 💡 Key Interactive Elements

### 1. Code ↔ English Translation Blocks
Real code on the left, plain English explanation on the right. Line-by-line correspondence.

### 2. Glossary Tooltips
Every technical term (API, Tauri, Rust, WebView, etc.) has a hover tooltip with a 1-2 sentence plain-English definition. No need to leave the page or Google anything.

### 3. Component Chat Animations
iMessage/WeChat-style conversations showing how the CLI, Config, Rust Core, and Icon Pipeline communicate.

### 4. Scenario-Based Quizzes
Questions like: "You want to add window state persistence — which component handles this?"

Tests practical application, not memorization.

## 📖 How This Course Was Built

This course was created using the **[codebase-to-course](https://github.com/zarazhangrui/codebase-to-course)** Claude Code skill, which follows a rigorous process:

1. **Codebase Analysis** — Deep exploration of the Pake repository to understand:
   - Main actors (CLI, Config, Rust Core, Icon Pipeline)
   - User journeys (what happens when you run `pake [url]`)
   - Tech stack and architecture
   - Clever engineering patterns

2. **Curriculum Design** — Structured as 6 modules that start from user-facing behavior (what Pake does) and zoom into implementation (how it does it)

3. **Build Phase** — HTML with embedded CSS and JavaScript, following strict design system rules:
   - Warm color palette (off-white backgrounds, rust orange accent)
   - Bricolage Grotesque display font
   - JetBrains Mono for code
   - Catppuccin-inspired syntax highlighting

## 🎓 For AI Code Tool Users

If you're building with AI coding assistants, this course teaches you to:

### Better Prompts
Instead of: "Make it work on desktop"
You'll say: "Use Tauri to package this as a native app with system webview"

### Smarter Debugging
When AI gets stuck: "The icon looks pixelated on 4K" → You know to check icon generation sizes in the build pipeline

### Architectural Decisions
"Should we use Electron or Tauri?" → You understand the size/compatibility tradeoffs

## 📝 Notes

- The course uses **progressive disclosure** — concepts build on previous modules
- **Glossary tooltips** ensure no one gets lost on terminology
- **Practical quizzes** test "can you solve a new problem" not "can you recall a definition"
- **Warm, inviting design** — feels like a developer notebook, not a clinical textbook

## 🔗 Resources

- [Pake Repository](https://github.com/tw93/Pake)
- [Tauri Framework](https://tauri.app)
- [Codebase-to-Course Skill](https://github.com/zarazhangrui/codebase-to-course)

## 📜 License

This course follows the same license as the Pake project (MIT).

---

**Built with** ❤️ **using the codebase-to-course Claude Code skill**
