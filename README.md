# Hi, I'm Shaahin Ashayeri 👋

### Software Engineer · Software Builder · Open Source

I'm a software engineer passionate about turning ideas into practical, reliable, and maintainable software.

I enjoy designing software architecture, building developer tools and reusable libraries, solving challenging engineering problems, and turning complex ideas into simple and usable solutions.

I don't limit myself to a specific programming language or technology. I choose the tools and technologies that best fit the problem and the solution.

---

## PineEngine — a Pine Script interpreter written in Delphi

A self contained interpreter for a practical subset of TradingView's Pine Script
(v3 through v6 style), written in plain Object Pascal with no third-party
dependencies. It compiles with Delphi (XE2 and newer) and with Free Pascal
3.2+ in Delphi mode, as a console program (`PineRun`) or as a DLL/shared
object (`PineLib`) callable from any language with a C FFI — see section 5.

The script is executed **bar by bar**, exactly like Pine does on a chart, so
`close[1]`, `var`, `ta.ema()` and friends behave the way you expect.

**The Pine Script code, the candle data and the settings are always three
separate inputs.** The code is plain text (a `.pine` file, never wrapped in
JSON); the candles travel as a plain JSON array; everything else —
`input()` overrides, synthetic-data settings, the pretty-print flag —
travels as a small JSON object. The library gives back exactly one JSON
response: the plotted series, logs and alerts, or an `"error"` object if
something went wrong. Nothing else is ever printed or returned.

---

## 🧠 What I Build

- 🛠️ Developer tools and reusable libraries
- 📊 Technical analysis and financial software
- ⚙️ Backend systems and APIs
- 🧩 Software components and frameworks
- 🗄️ Database-driven applications
- 🌐 Web applications and modern software systems
- 🔬 Experimental and research-oriented projects
- 💡 Software products from idea to implementation

---

## 🏗️ Engineering Philosophy

I believe good software should be:

**Simple · Reliable · Maintainable · Practical**

I care about clean architecture, readable code, thoughtful APIs, performance, and creating software that can evolve as requirements change.

For me, software engineering is not only about writing code.

It's about understanding the problem, designing the right solution, and building something that remains useful over time.

---

## 🌱 Open Source

I enjoy creating and sharing software that can be useful to other developers.

My repositories include libraries, developer tools, software components, experiments, and complete projects.

Some projects are built to solve specific engineering problems, while others are created to explore new ideas and possibilities.

---

## 📌 Currently

- Building developer tools and reusable software libraries
- Working on TA-Lib4D and PineScript4D
- Exploring new ideas in software engineering and financial technology
- Turning complex technical concepts into practical software

---

## 🤝 Let's Connect

I'm interested in software engineering, developer tools, open source, financial technology, and challenging technical problems.

If you find something useful here, feel free to explore the repositories, use the projects, and share your feedback.

**Building software that solves real problems.**
