# Awesome-Robotic-Process-Automation-RPA

# Top Robotic Process Automation (RPA) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Software Robots, Workflow Automation & Open-Source RPA Frameworks*  
**Last updated: October 2026**

This repository tracks notable **commercial RPA platforms** and **open-source projects** that automate repetitive, rule-based computer tasks — from simple data entry to complex business processes spanning multiple applications.

**Examples** include Microsoft Power Automate, UiPath, Automation Anywhere, Blue Prism, WorkFusion, Kofax RPA, Appian RPA, Nintex RPA, Robocorp, and Pega RPA (the category leaders).

**Open-source emphasis**: RPA is a domain where open-source tools provide genuine production alternatives. **Robot Framework** and **RPA Framework** lead as the most mature Python-based RPA stack, with **TagUI** offering a simple, flow-based language accessible to non-programmers. **taskt** provides a C#/.NET Windows automation client, **Ui.Vision** brings browser and desktop automation with computer vision, and **rpacore** delivers a modern framework with transaction persistence and observability. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[UiPath](https://www.uipath.com/)**  
  The market leader in RPA with the largest ecosystem, AI-powered document understanding, and enterprise-grade orchestration. **The reference implementation for enterprise RPA** — from attended bots to unattended automation at scale.

- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**  
  Microsoft's cloud-based automation platform integrated with Power Platform, Microsoft 365, and Dynamics 365. **The most accessible enterprise RPA** for Microsoft-centric organizations.

- **[Automation Anywhere](https://www.automationanywhere.com/)**  
  Enterprise RPA with cloud-native architecture, IQ Bot for document processing, and Bot Insight analytics.

- **[Blue Prism](https://www.blueprism.com/)**  
  Enterprise RPA platform (now SS&C Blue Prism) with strong governance, control room management, and regulated industry focus.

- **[WorkFusion](https://www.workfusion.com/)**  
  Intelligent automation platform with AI-powered document processing and pre-built digital workers for banking, insurance, and healthcare.

- **[Kofax RPA](https://www.kofax.com/)**  
  RPA with cognitive document automation, process intelligence, and mobile automation capabilities.

- **[Appian RPA](https://www.appian.com/)**  
  RPA integrated with Appian's low-code automation platform for process-centric automation.

- **[Nintex RPA](https://www.nintex.com/)**  
  RPA with workflow automation, document generation, and process intelligence in one platform.

- **[Pega RPA](https://www.pega.com/)**  
  RPA integrated with Pega's AI-powered decisioning and customer engagement platform.

## Open-Source GitHub Projects

- **[RPA Framework (Robocorp)](https://github.com/robocorp/rpaframework)**  
  **The most comprehensive open-source RPA library collection**, Apache-2.0 licensed . Built for **Robot Framework and Python** — provides libraries for **browser automation (Selenium/Playwright), Excel, Outlook, Word, SAP, PDF, email, HTTP, databases, and AI/OpenAI integration** . **The de facto open-source RPA toolkit** for Python developers — every major automation domain covered. **Best for developers building custom RPA workflows** with Python and Robot Framework.

- **[Robot Framework](https://robotframework.org/rpa/)**  
  **The leading open-source generic automation framework for RPA**, Apache-2.0 licensed . **Keyword-driven plain-text syntax** — accessible to non-programmers while remaining fully extensible via Python libraries. **Massive ecosystem of community libraries** including Browser (Playwright), RoboSAPiens (SAP GUI), Mainframe 3270 Library, and Pabot for parallel execution . **The foundation for most open-source RPA stacks** — RPA Framework builds directly on Robot Framework. **Best for teams wanting a structured, testable approach to automation**.

- **[TagUI](https://github.com/kelaberetiv/TagUI)**  
  **Free RPA tool by AI Singapore**, open-source and free forever . **Simple, human-readable flow language** — steps like `click` and `type` interact with web identifiers, image snapshots, screen coordinates, or **text via OCR** . **Works on Windows, macOS, and Linux** with **22+ languages** for flow writing . **Turbo mode runs automation 10X faster than human speed** . **Excel integration via standard formulas**, table extraction directly to CSV . **The most accessible open-source RPA for non-programmers** — flows are readable and writable in natural language.

- **[taskt](https://github.com/rcktrncn/taskt)**  
  **Free, open-source RPA client built on .NET Framework in C#**, Apache-2.0 licensed . **"What you see is what you get" bot designer** with dozens of automation commands — **no application code required** . Features **element recorder, screen recorder, and script engine** for replaying automation . Can **start/stop processes, launch VB and PowerShell scripts, work with Excel, and perform OCR** . **Optional server component** for managing digital workforce and publishing tasks remotely (alpha) . **Best for Windows-centric automation** without Python dependencies.

- **[Ui.Vision](https://chromewebstore.google.com/detail/uivision/gcbalfbdmfieckjlnblleoemohcganoc)**  
  **Open-source browser and desktop automation running locally, not in the cloud** . **AI Assistant describes what you want in plain English** — built-in AI builds, runs, and fixes macros . **JavaScript macros with `uiv.*` API** — real loops, error handling, breakpoints . **Browser Vision: click and type like a real user with visual targeting by image or OCR** . **Desktop automation for Windows, Mac, and Linux** via XModules . **MCP support for Claude Code, Cursor, Codex** . **100% local — no data sent anywhere** (except optional AI features which can run on local LLM) . **Best for browser-centric automation and users wanting AI-assisted macro creation**.

- **[rpacore](https://pypi.org/project/rpacore/)**  
  **Modern RPA framework with transaction persistence and observability**, Python-based . **Skill-based architecture** — `BusinessException` for retryable failures, `SystemException` for infrastructure issues . **SQLite transaction persistence** with checkpoint support for crash recovery . **JSON/NDJSON transaction export** for machine-readable records . **Webhook and email notifications** with screenshot attachments for exception reports . **OpenTelemetry instrumentation** for distributed tracing . **Best for developers wanting a lightweight, modern RPA framework** with strong observability and error handling.

- **[Automagica](https://archive.org/details/github.com-OakwoodAI-Automagica_-_2019-06-12_13-43-40)**  
  **Free open-source Python RPA library** built on PyAutoGUI, Selenium, PyWinAuto, pytesseract, OpenPyXL, python-docx, pywin32, PyPDF2, and more . **Potentially superior for learning, experimenting, and prototyping** RPA workflows . **Note**: Original project appears archived — valuable as reference but verify maintenance status before production use.

- **[Smithy](https://pypi.org/project/smithy-engine/)**  
  **Python desktop automation engine with visual editor (smithy-designer)**, MIT licensed . **Recording captures clicks and typed text** onto a drag-and-drop canvas . **Step debugger with breakpoints, XML-like selectors, typed variables** . **Flow format is versioned JSON** — the contract between designer, disk, and engine . **Subflows for reusable logic** with shared or isolated scope . **Transactional mode with REFramework loop** over SQLite or cloud queue . **Pack delivery contract** with SHA-256 manifests . **Best for developers wanting visual flow design with a clean JSON format**.

### Additional Strong Open-Source Options

- **RPA.ERPNext** — Robot Framework library for automating ERPNext using REST API .
- **robocorp-browser** — Light wrapper for Playwright with automatic lifecycle management, designed for robocorp-tasks .
- **Thoughtful** — Collection of open-source libraries and tools for RPA development with OpenTelemetry distributed tracing and structured logging .
- **rpaframework-aws / rpaframework-google / rpaframework-recognition** — Specialized libraries for AWS, Google Cloud, and recognition tasks .
- **Selenium / Playwright** — Browser automation foundations widely used in RPA stacks.
- **PyAutoGUI** — Cross-platform GUI automation for Python — the foundation for many RPA tools .

**Frameworks for building custom RPA solutions**: Choose based on team skills and automation target. **RPA Framework + Robot Framework** for the most comprehensive Python-based RPA stack covering browser, desktop, SAP, Excel, and document processing . **TagUI** for non-programmers wanting simple, readable automation flows with OCR and Excel integration . **taskt** for Windows-centric automation without Python dependencies . **Ui.Vision** for browser automation with AI-assisted macro creation and MCP support . **rpacore** for developers wanting a modern, lightweight framework with transaction persistence and observability . **Smithy** for visual flow design with clean JSON contracts . Note that true enterprise RPA with AI-powered document understanding, orchestration at scale, and vendor-supported SLAs remains primarily commercial territory; open-source stacks provide strong browser, desktop, and document automation foundations that require integration for complete RPA programs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- RPA bots execute actions with the privileges of the account they run under — **a bot can do anything a human can do**, including deleting files, sending emails, and accessing sensitive systems. Apply **least privilege** and run bots in isolated environments.
- **Credential management is critical** — never hardcode credentials in automation scripts. Use secrets managers (Robocorp Vault, environment variables, OS keychains) and rotate regularly.
- **Open-source RPA tools vary in maintenance status** — Automagica appears archived ; verify activity before committing to any project. Robot Framework, RPA Framework, TagUI, and taskt have active communities.
- **Ui.Vision processes everything locally by default** — image recognition and OCR run on your machine. Optional AI features are the only cloud component, and can run on local LLM for full privacy .
- The open-source ecosystem provides strong browser, desktop, and document automation foundations, but **AI-powered document understanding, enterprise orchestration, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for automation engineers, operations teams, and organizations seeking RPA sovereignty.**
Let's make robotic process automation more open, transparent, and accessible.
