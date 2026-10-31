# Raditya Hidayat

**Informatics graduate**, Telkom University · GPA 3.75/4.00

I build web applications, computer vision systems, and browser automation tools.
Currently focused on **test automation, full-stack development, and service monitoring**.

Bekasi, Indonesia · [radityahidayat39@gmail.com](mailto:radityahidayat39@gmail.com) · [LinkedIn](https://www.linkedin.com/in/radhid)

---

## Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![NUnit](https://img.shields.io/badge/NUnit-2E7D32?style=flat-square)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

---

## Experience

**Quality Assurance Intern** · PT United Tractors Tbk · Aug 2025

Extended the company's existing .NET test automation framework to cover **6 internal
web applications**. Wrote **64 page objects** and ~**8,900 lines of C#** following the
Page Object Model, spanning end-to-end risk-audit workflows from login and risk
dashboard through risk register, approval summary, and risk-based audit.

Tests ran cross-browser on a **Selenoid grid** backed by Docker, capturing video and
browser logs per test case. Environment configuration (browser, version, timeout,
endpoints) was parameterised through `.runsettings`, so the same suite ran against any
environment without code changes. Results were rendered through **ExtentReports** with
automatic pass/fail screenshots and download-artifact verification against the Selenoid
REST API.

---

## Featured Projects

### [QA Automation Sample](https://github.com/Radhdyt/qa-automation-sample)
`C#` `NUnit` `Selenium` `ExtentReports`

Complete UI test suite written from scratch: NUnit, Selenium WebDriver, and page objects over a
public demo storefront. Every environment value arrives through `.runsettings`, so the same build
runs locally or against a Selenoid grid without recompiling. Nine tests, an Extent report per run,
screenshots captured on failure, and a GitHub Actions job that publishes both.

### [Digital Certificate System](https://github.com/Radhdyt/sertifikat-digital-pelatihan)
`Next.js` `TypeScript` `Supabase` `Solidity` `IPFS`

Full-stack platform for issuing and verifying training certificates as Soulbound Tokens
on Polygon, with certificate metadata and images pinned to IPFS. Separate portals for
admins, assessors, and recipients, plus a public verification page that requires no
login, turning a forgeable PDF into a non-transferable on-chain credential.

**[Live demo](https://sertifikat-digital-pelatihan.vercel.app)**

### [Smart Waste Bin AI](https://github.com/Radhdyt/SmartWasteBin-AI)
`Python` `YOLOv8` `ESP32-CAM`

Real-time classification of organic and non-organic waste using a custom-trained YOLOv8
model. Detection pipeline includes anti-flicker smoothing, a `person` class filter to
ignore passers-by, HTTP-triggered servo control on the bin, and CSV event logging.
Runs in simulation mode against a webcam when no hardware is attached.

### [RC Session Manager](https://github.com/Radhdyt/RC-Session-Manager)
`JavaScript` `Chrome MV3` `Jest`

Chrome extension for running multiple accounts side by side without logging in and out.
Stores and re-injects browser cookies per profile, with a site-aware extractor for
pulling individual session tokens and a DOM storage injector for compatibility with
apps that keep state outside cookies. All data stays in IndexedDB locally. Logic is
unit-tested with Jest.

### [Semantic Segmentation](https://github.com/Radhdyt/Semantic-Segmentation-Penutup-Lahan-pada-Citra-Satelit)
`Python` `PyTorch` `U-Net`

U-Net implementation for land-cover classification on satellite imagery, built on the
LandCover.ai dataset. Uses sliding-window patch inference instead of resizing so
building and road edges stay sharp at full resolution, with resumable checkpointing and
alpha-blended overlay output for visual inspection.

---

<sub>Open to internship and junior roles in QA automation, backend, and full-stack development.</sub>
