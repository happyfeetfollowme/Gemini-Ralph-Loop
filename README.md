<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># Gemini-Ralph-Loop</span></span>
<span class="line"></span>
<span class="line"><span>[</span><span>![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)</span><span>](</span><span>https://opensource.org/licenses/MIT</span><span>)</span></span>
<span class="line"><span>[</span><span>![Gemini CLI Extension](https://img.shields.io/badge/Gemini%20CLI-Extension-4285F4.svg)</span><span>](</span><span>https://geminicli.com/extensions</span><span>)</span></span>
<span class="line"><span>[</span><span>![GitHub release](https://img.shields.io/github/v/release/kranthik123/Gemini-Ralph-Loop)</span><span>](</span><span>https://github.com/kranthik123/Gemini-Ralph-Loop/releases</span><span>)</span></span>
<span class="line"></span>
<span class="line"><span>**Self-referential iterative development loops for Gemini CLI**</span><span> - Based on the Ralph Wiggum technique by Geoffrey Huntley.</span></span>
<span class="line"></span>
<span class="line"><span><p align="center"></span></span>
<span class="line"><span>  <img src="https://img.shields.io/badge/Iterations-∞-blue" alt="Iterations"></span></span>
<span class="line"><span>  <img src="https://img.shields.io/badge/Persistence-100%25-green" alt="Persistence"></span></span>
<span class="line"><span>  <img src="https://img.shields.io/badge/Ralph%20Approved-Yes-orange" alt="Ralph Approved"></span></span>
<span class="line"><span></p></span></span>
<span class="line"></span>
<span class="line"><span>---</span></span>
<span class="line"></span>
<span class="line"><span>## 🎯 What is Ralph Loop?</span></span>
<span class="line"></span>
<span class="line"><span>Ralph Loop is a development methodology where:</span></span>
<span class="line"></span>
<span class="line"><span>1.</span><span> You give an AI agent a task </span><span>**once**</span></span>
<span class="line"><span>2.</span><span> The agent works on the task, creating/modifying files</span></span>
<span class="line"><span>3.</span><span> Your changes </span><span>**persist**</span><span> in the workspace</span></span>
<span class="line"><span>4.</span><span> The loop continues, with the AI seeing its previous work</span></span>
<span class="line"><span>5.</span><span> Loop continues until </span><span>**completion**</span><span> or </span><span>**max iterations**</span></span>
<span class="line"></span>
<span class="line"><span>### Key Insight</span></span>
<span class="line"></span>
<span class="line"><span>> The prompt never changes, but the </span><span>**context**</span><span> does. Each iteration, the AI sees the files it created/modified, learns from its mistakes, and improves.</span></span>
<span class="line"></span>
<span class="line"><span>### Real-World Results</span></span>
<span class="line"></span>
<span class="line"><span>-</span><span> ✅ </span><span>**6 repositories**</span><span> generated overnight at Y Combinator hackathon</span></span>
<span class="line"><span>-</span><span> ✅ </span><span>**$50k contract**</span><span> completed for $297 in API costs</span></span>
<span class="line"><span>-</span><span> ✅ </span><span>**Entire programming language**</span><span> created over 3 months</span></span>
<span class="line"></span>
<span class="line"><span>---</span></span>
<span class="line"></span>
<span class="line"><span>## ✨ Features</span></span>
<span class="line"></span>
<span class="line"><span>| Feature | Description |</span></span>
<span class="line"><span>|---------|-------------|</span></span>
<span class="line"><span>| 🔄 </span><span>**Self-referential loops**</span><span> | AI builds on its own work across iterations |</span></span>
<span class="line"><span>| 👁️ </span><span>**Real-time monitoring**</span><span> | Watch progress with </span><span>`/ralph:monitor`</span><span> |</span></span>
<span class="line"><span>| ⏸️ </span><span>**Pause/Resume**</span><span> | Take breaks without losing progress |</span></span>
<span class="line"><span>| 💾 </span><span>**Checkpoints**</span><span> | Save and restore loop state |</span></span>
<span class="line"><span>| ⏮️ </span><span>**Rollback**</span><span> | Undo iterations when things go wrong |</span></span>
<span class="line"><span>| 📊 </span><span>**Progress tracking**</span><span> | Iteration counts, timing, estimates |</span></span>
<span class="line"><span>| 🔍 </span><span>**Completion detection**</span><span> | String patterns and file signals |</span></span>
<span class="line"><span>| 🛡️ </span><span>**Safety limits**</span><span> | Max iterations prevent runaway loops |</span></span>
<span class="line"><span>| 📝 </span><span>**Full history**</span><span> | Track every iteration with logs |</span></span>
<span class="line"><span>| 🔧 </span><span>**Diagnostics**</span><span> | Analyze stuck loops |</span></span>
<span class="line"><span>| 📋 </span><span>**Reports**</span><span> | Generate summary documentation |</span></span>
<span class="line"></span>
<span class="line"><span>---</span></span>
<span class="line"></span>
<span class="line"><span>## 📦 Installation</span></span>
<span class="line"></span>
<span class="line"><span>### From GitHub (Recommended)</span></span>
<span class="line"></span>
<span class="line"><span>```bash</span></span>
<span class="line"><span># Install the extension</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> install</span><span> https://github.com/kranthik123/Gemini-Ralph-Loop</span></span>
<span class="line"></span>
<span class="line"><span># Enable auto-updates (recommended)</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> install</span><span> https://github.com/kranthik123/Gemini-Ralph-Loop</span><span> --auto-update</span></span></code></pre></div></div></pre>

### For Development

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># Clone the repository</span></span>
<span class="line"><span>git</span><span> clone</span><span> https://github.com/kranthik123/Gemini-Ralph-Loop.git</span></span>
<span class="line"><span>cd</span><span> Gemini-Ralph-Loop</span></span>
<span class="line"></span>
<span class="line"><span># Install dependencies</span></span>
<span class="line"><span>npm</span><span> install</span></span>
<span class="line"></span>
<span class="line"><span># Build the MCP server</span></span>
<span class="line"><span>npm</span><span> run</span><span> build</span></span>
<span class="line"></span>
<span class="line"><span># Link for development (changes reflect immediately)</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> link</span><span> .</span></span></code></pre></div></div></pre>

### Verify Installation

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># List installed extensions</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> list</span></span>
<span class="line"></span>
<span class="line"><span># Start Gemini CLI and check commands</span></span>
<span class="line"><span>gemini</span></span>
<span class="line"><span>/ralph:help</span></span></code></pre></div></div></pre>

---

## 🚀 Quick Start

### Basic Usage

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># Start Gemini CLI</span></span>
<span class="line"><span>gemini</span></span>
<span class="line"></span>
<span class="line"><span># Start a Ralph Loop</span></span>
<span class="line"><span>/ralph:start-loop</span><span> "Build a REST API for todos with CRUD operations and tests"</span><span> --max-iterations</span><span> 25</span></span>
<span class="line"></span>
<span class="line"><span># Monitor progress in real-time</span></span>
<span class="line"><span>/ralph:monitor</span></span>
<span class="line"></span>
<span class="line"><span># Check status anytime</span></span>
<span class="line"><span>/ralph:status</span></span></code></pre></div></div></pre>

### Complete Workflow Example

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># 1. Start a loop with clear requirements</span></span>
<span class="line"><span>/ralph:start-loop</span><span> "Create a Node.js CLI calculator.</span></span>
<span class="line"><span>Requirements:</span></span>
<span class="line"><span>- Support +, -, *, / operations</span></span>
<span class="line"><span>- Handle invalid input gracefully</span></span>
<span class="line"><span>- Include --help flag</span></span>
<span class="line"><span>- Write tests with Jest</span></span>
<span class="line"></span>
<span class="line"><span>When complete: <done>DONE</done>"</span><span> -m</span><span> 20</span><span> -c</span><span> "DONE"</span></span>
<span class="line"></span>
<span class="line"><span># 2. Monitor progress</span></span>
<span class="line"><span>/ralph:monitor</span></span>
<span class="line"></span>
<span class="line"><span># 3. Create checkpoint before risky changes</span></span>
<span class="line"><span>/ralph:checkpoint</span><span> "stable-v1"</span></span>
<span class="line"></span>
<span class="line"><span># 4. If something goes wrong, rollback</span></span>
<span class="line"><span>/ralph:rollback</span></span>
<span class="line"></span>
<span class="line"><span># 5. Or restore from checkpoint</span></span>
<span class="line"><span>/ralph:restore</span><span> "stable-v1"</span></span>
<span class="line"></span>
<span class="line"><span># 6. Check what happened</span></span>
<span class="line"><span>/ralph:history</span></span>
<span class="line"></span>
<span class="line"><span># 7. Generate final report</span></span>
<span class="line"><span>/ralph:report</span></span></code></pre></div></div></pre>

---

## 📖 Commands Reference

### Core Loop Control (7 commands)

| Command               | Description          | Example                               |
| --------------------- | -------------------- | ------------------------------------- |
| `/ralph:start-loop` | Start a new loop     | `/ralph:start-loop "task" -m 30`    |
| `/ralph:status`     | Check current status | `/ralph:status`                     |
| `/ralph:monitor`    | Real-time monitoring | `/ralph:monitor`                    |
| `/ralph:pause`      | Pause the loop       | `/ralph:pause`                      |
| `/ralph:resume`     | Resume paused loop   | `/ralph:resume`                     |
| `/ralph:complete`   | Mark as completed    | `/ralph:complete -s "Built API"`    |
| `/ralph:cancel`     | Cancel the loop      | `/ralph:cancel -r "Wrong approach"` |

### History & Debugging (4 commands)

| Command             | Description             | Example                  |
| ------------------- | ----------------------- | ------------------------ |
| `/ralph:history`  | View iteration history  | `/ralph:history -n 20` |
| `/ralph:logs`     | View detailed logs      | `/ralph:logs -i 5`     |
| `/ralph:retry`    | Retry current iteration | `/ralph:retry`         |
| `/ralph:diagnose` | Analyze stuck loops     | `/ralph:diagnose`      |

### State Management (4 commands)

| Command               | Description        | Example                    |
| --------------------- | ------------------ | -------------------------- |
| `/ralph:reset`      | Clear all state    | `/ralph:reset --confirm` |
| `/ralph:checkpoint` | Create save point  | `/ralph:checkpoint "v1"` |
| `/ralph:restore`    | Restore checkpoint | `/ralph:restore "v1"`    |
| `/ralph:rollback`   | Undo iterations    | `/ralph:rollback -s 2`   |

### Configuration & Utilities (4 commands)

| Command           | Description          | Example                       |
| ----------------- | -------------------- | ----------------------------- |
| `/ralph:config` | View/modify settings | `/ralph:config`             |
| `/ralph:adjust` | Modify mid-run       | `/ralph:adjust -m 50`       |
| `/ralph:report` | Generate report      | `/ralph:report -f markdown` |
| `/ralph:help`   | Show help            | `/ralph:help checkpoint`    |

---

## ⚙️ Configuration

### Extension Settings

Configure after installation:

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># Set default max iterations</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> settings</span><span> set</span><span> gemini-ralph-loop</span><span> "Default Max Iterations"</span></span>
<span class="line"></span>
<span class="line"><span># Set default completion promise</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> settings</span><span> set</span><span> gemini-ralph-loop</span><span> "Default Completion Promise"</span></span>
<span class="line"></span>
<span class="line"><span># Set iteration delay (helps with rate limiting)</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> settings</span><span> set</span><span> gemini-ralph-loop</span><span> "Iteration Delay Seconds"</span></span>
<span class="line"></span>
<span class="line"><span># Enable auto-commit (commits after each iteration)</span></span>
<span class="line"><span>gemini</span><span> extensions</span><span> settings</span><span> set</span><span> gemini-ralph-loop</span><span> "Auto Commit"</span></span></code></pre></div></div></pre>

### Available Settings

| Setting                    | Default  | Description                        |
| -------------------------- | -------- | ---------------------------------- |
| Default Max Iterations     | 100      | Maximum iterations before stopping |
| Default Completion Promise | COMPLETE | Text that signals completion       |
| Iteration Delay Seconds    | 2        | Delay between iterations           |
| Auto Commit                | false    | Git commit after each iteration    |
| Auto Checkpoint Interval   | 10       | Auto-checkpoint every N iterations |
| Max Log Size KB            | 100      | Maximum iteration log size         |

---

## 📝 Writing Good Prompts

### ✅ Good Example

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">text</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span>/ralph:start-loop "Build a Node.js REST API for user management.</span></span>
<span class="line"><span></span></span>
<span class="line"><span>## Requirements</span></span>
<span class="line"><span>- Express.js framework with TypeScript</span></span>
<span class="line"><span>- CRUD endpoints: GET/POST/PUT/DELETE /api/users</span></span>
<span class="line"><span>- Input validation with express-validator</span></span>
<span class="line"><span>- JWT authentication middleware</span></span>
<span class="line"><span>- MongoDB with Mongoose ODM</span></span>
<span class="line"><span>- Jest tests with >80% coverage</span></span>
<span class="line"><span>- Error handling middleware</span></span>
<span class="line"><span>- API documentation in README.md</span></span>
<span class="line"><span></span></span>
<span class="line"><span>## Project Structure</span></span>
<span class="line"><span>src/</span></span>
<span class="line"><span>├── index.ts</span></span>
<span class="line"><span>├── routes/users.ts</span></span>
<span class="line"><span>├── middleware/auth.ts</span></span>
<span class="line"><span>├── models/User.ts</span></span>
<span class="line"><span>└── tests/users.test.ts</span></span>
<span class="line"><span></span></span>
<span class="line"><span>## Verification Steps</span></span>
<span class="line"><span>1. npm run build - compiles without errors</span></span>
<span class="line"><span>2. npm test - all tests pass</span></span>
<span class="line"><span>3. npm start - server starts on port 3000</span></span>
<span class="line"><span>4. All endpoints return correct status codes</span></span>
<span class="line"><span></span></span>
<span class="line"><span>## Completion</span></span>
<span class="line"><span>When ALL of the above requirements are implemented and verified:</span></span>
<span class="line"><span><done>COMPLETE</done>" --max-iterations 30 --completion-promise "COMPLETE"</span></span></code></pre></div></div></pre>

### ❌ Bad Example

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">text</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span>/ralph:start-loop "Make a good user API"</span></span></code></pre></div></div></pre>

### Prompt Tips

1. **Be specific** - List exact requirements
2. **Include verification** - How to check if it works
3. **Define structure** - What files/folders to create
4. **Set completion criteria** - When is "done" really done
5. **Use phases** - Break complex tasks into steps

---

## 🔍 Monitoring

The `/ralph:monitor` command provides a real-time dashboard:

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">text</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span>╔══════════════════════════════════════════════════════════════╗</span></span>
<span class="line"><span>║  👁️ RALPH LOOP MONITOR                                       ║</span></span>
<span class="line"><span>╠══════════════════════════════════════════════════════════════╣</span></span>
<span class="line"><span>║  Status: 🔄 RUNNING                  Loop: ralph-2024-01-15  ║</span></span>
<span class="line"><span>╠══════════════════════════════════════════════════════════════╣</span></span>
<span class="line"><span>║  Progress: [████████████░░░░░░░░░░░░░░░░░░] 40%              ║</span></span>
<span class="line"><span>║  Iteration: 8 / 20         Remaining: 12                     ║</span></span>
<span class="line"><span>║  Elapsed: 5m 23s           Est. Left: 8m 12s                 ║</span></span>
<span class="line"><span>╠══════════════════════════════════════════════════════════════╣</span></span>
<span class="line"><span>║  Recent Activity:                                            ║</span></span>
<span class="line"><span>║  • [14:32] Iter 8: Created src/routes/users.ts               ║</span></span>
<span class="line"><span>║  • [14:30] Iter 7: Added validation middleware               ║</span></span>
<span class="line"><span>║  • [14:28] Iter 6: Fixed test failures                       ║</span></span>
<span class="line"><span>╠══════════════════════════════════════════════════════════════╣</span></span>
<span class="line"><span>║  Controls: Ctrl+C to exit | /ralph:pause | /ralph:cancel    ║</span></span>
<span class="line"><span>╚══════════════════════════════════════════════════════════════╝</span></span></code></pre></div></div></pre>

 **Exit** : Use `Ctrl+C` - the loop continues in background.

---

## 📊 Use Cases

### ✅ Ideal For

| Use Case                          | Why It Works                                |
| --------------------------------- | ------------------------------------------- |
| **Greenfield projects**     | Build from scratch, iterate until complete  |
| **Test-driven development** | Write test → implement → repeat           |
| **Code generation**         | Generate boilerplate, refine iteratively    |
| **Bug fixing**              | Iterate until all tests pass                |
| **Refactoring**             | Gradual improvements with test verification |
| **Documentation**           | Generate and refine docs                    |
| **API development**         | Build endpoints incrementally               |

### ❌ Not Ideal For

| Use Case                         | Why It Doesn't Work                         |
| -------------------------------- | ------------------------------------------- |
| **Subjective tasks**       | "Make it look good" has no clear completion |
| **One-shot operations**    | No benefit from iteration                   |
| **Production debugging**   | Needs human judgment                        |
| **Security-critical code** | Requires human review                       |
| **Unclear requirements**   | Loop can't clarify with you                 |

---

## 🔧 Troubleshooting

### Common Issues

| Issue                  | Solution                                                 |
| ---------------------- | -------------------------------------------------------- |
| Loop exits immediately | Check Gemini CLI auth, run `/ralph:diagnose`           |
| Loop never completes   | Verify completion promise matches, check `/ralph:logs` |
| Same output repeating  | Run `/ralph:diagnose`, improve prompt specificity      |
| Rate limiting          | Increase iteration delay in settings                     |
| State corrupted        | Run `/ralph:reset --confirm`                           |

### Debug Commands

<pre><div class="not-prose my-0 flex w-full flex-col overflow-clip border border-border text-text-primary rounded-lg not-prose relative" data-code-block="true"><div class="border-border flex items-center justify-between border-b px-4 py-2"><div class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code text-text-secondary"><path d="M10 12.5 8 15l2 2.5"></path><path d="m14 12.5 2 2.5-2 2.5"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7z"></path></svg><span class="text-text-secondary text-sm font-medium">Bash</span></div><button class="inline-flex items-center justify-center gap-2 whitespace-nowrap transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring ring-offset-2 focus-visible:ring-offset-surface-primary disabled:pointer-events-none disabled:opacity-50 [&_svg]:pointer-events-none [&_svg]:shrink-0 text-sm font-medium text-interactive-active hover:text-interactive-normal active:text-text-tertiary relative rounded-lg p-[6px]" type="button" data-state="closed" data-slot="tooltip-trigger"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-check text-interactive-positive absolute left-1.5 top-1.5 rotate-90 opacity-0 transition-all duration-300"><path d="M20 6 9 17l-5-5"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy opacity-100 transition-opacity duration-300"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div><div class="code-block_container__lbMX4"><pre class="shiki github-dark shiki-code-block" tabindex="0"><code class="whitespace-pre-wrap break-words"><span class="line"><span># Check what's happening</span></span>
<span class="line"><span>/ralph:status</span></span>
<span class="line"><span>/ralph:logs</span><span> --iteration</span><span> latest</span></span>
<span class="line"></span>
<span class="line"><span># Diagnose issues</span></span>
<span class="line"><span>/ralph:diagnose</span></span>
<span class="line"></span>
<span class="line"><span># View history</span></span>
<span class="line"><span>/ralph:history</span><span> --limit</span><span> 20</span></span>
<span class="line"></span>
<span class="line"><span># Reset if needed</span></span>
<span class="line"><span>/ralph:reset</span><span> --confirm</span></span></code></pre></div></div></pre>

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 🙏 Acknowledgments

* **Geoffrey Huntley** - Original Ralph technique ([ghuntley.com/ralph](https://ghuntley.com/ralph))
* **Anthropic** - Claude Code Ralph Wiggum plugin inspiration
* **Google** - Gemini CLI and extension system
* **The Simpsons** - Ralph Wiggum character

---

## 📚 Resources

* [Original Ralph Technique](https://ghuntley.com/ralph/)
* [Gemini CLI Documentation](https://geminicli.com/)
* [MCP Protocol](https://modelcontextprotocol.io/)

---

## 📜 License

MIT License - see [LICENSE](https://lmarena.ai/c/LICENSE) file.

---

<p align="center"> <i>"Me fail English? That's unpossible!"</i> - Ralph Wiggum </p><p align="center"> Made with ❤️ by <a href="https://github.com/kranthik123">kranthik123</a> </p> ```
