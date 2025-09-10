---
layout: post
title: "First Entry — Repo Setup"
---

I’ve set up the **RiskShield Security Playground** repo to showcase my AppSec work.  
- Copied RiskShield into a new repo  
- Configured Semgrep, SBOM, and IaC scans  
- ZAP Baseline pending a deployed URL  
- Drafted threat model with DFD, STRIDE, and abuse cases  

I’ve set up the RiskShield Security Playground as a standalone repo to showcase my AppSec capabilities. The process began by copying the original RiskShield repo into a new repository under my account, ensuring I had full control to experiment with security tooling. Once in place, I configured multiple GitHub Actions workflows to automate security scans.

So far, I’ve verified that the Semgrep, SBOM/Dependency Audit, and IaC workflows are working as expected. I had to log into Semgrep and configure the correct YAML file from their dashboard, but after that adjustment, the scans are running smoothly and reporting back to GitHub. The ZAP Baseline workflow has not executed yet, which I suspect is because there’s no live build or URL for the app to scan against. That will be addressed in the next phase when I configure a build step or deploy to a test environment.

In parallel, I drafted the initial threat model (docs/threat-model.md) for the app. This document outlines the system components, a data flow diagram (DFD), STRIDE threat categories, and detailed abuse case scenarios. I also included a planned security test matrix mapping tools (Semgrep, ZAP, pip-audit, etc.) to expected outcomes. This file will serve as the foundation for tracking security improvements, identifying mitigation strategies, and documenting before/after states as I address vulnerabilities.

<figure style="margin:1.2rem 0;">
  <img src="{{ site.baseurl }}/assets/images/posts_imgs/repo_README.png"
       alt="ZAP Baseline first run" style="max-width:100%;height:auto;">
  <figcaption style="color:#6a737d;font-size:.95rem;margin-top:.4rem;">
    RiskShield Security Playground README.md
  </figcaption>
</figure>

<figure style="margin:1.2rem 0;">
  <img src="{{ site.baseurl }}/assets/images/posts_imgs/threat-model.png"
       alt="ZAP Baseline first run" style="max-width:100%;height:auto;">
  <figcaption style="color:#6a737d;font-size:.95rem;margin-top:.4rem;">
    RiskShield Security Playground threat-model.md
  </figcaption>
</figure>

