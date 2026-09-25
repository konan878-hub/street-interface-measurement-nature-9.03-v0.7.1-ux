## Scientific Baseline

Current workflow candidate:

```text
v0.7.1-UX1.3 FINAL UI CLEANUP CANDIDATE
```

Base verified release:

```text
v0.7.0 RELEASE VERIFIED
```

Scientific core:

```text
v0.6.3_GOLDEN_FREEZE
```

Deterministic validation:

```text
66 / 66 PASS
```

The v0.7.1 UX update changes the interface and operator workflow only.

It does not modify the frozen Nature 9.03 scientific computation, Qwen mapping logic, GWR values, or the frozen Street Interface Matrix engine.

## Street Interface Structure

The current scientific synthesis follows the Nature 9.03 No-Omega framework.

The interface exposes the three main dimensions:

- Imageability
- Identity
- Dependence

These dimensions are combined by the frozen Street Interface synthesis engine to produce the final Street Interface score.

Omega is not active in the current scientific core, and no external environmental A_i term is active.

## Local Development

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

On Windows PowerShell, if script execution blocks `npm`, use:

```powershell
npm.cmd install
npm.cmd run dev
```

## Environment Variables

The repository includes:

```text
.env.example
```

Do not commit a real `.env` file containing private API keys or credentials.

For AI Studio / Gemini-related functions, configure the required secrets through the appropriate environment or secrets panel.

## Repository Structure

Key directories include:

```text
src/
server/
public/
release/
scripts/
tool/
```

Key files include:

```text
package.json
server.ts
tsconfig.json
vite.config.ts
metadata.json
.env.example
```

The `release/` directory contains release status, verification, integrity, and reproducibility records for the current research workflow.

## Current Repository Status

This repository represents the research / technical interface of the Street Interface project.

Current status:

```text
WORKFLOW_CANDIDATE
```

Host lint / build validation:

```text
PENDING_USER_HOST_VALIDATION
```

Scientific change:

```text
false
```

Workflow change:

```text
true
```

## Relationship to the Public App

This repository is the transparent research-oriented version of the Street Interface application.

A separate public-facing application automates the full workflow from a single uploaded street photograph, including:

- Vision segmentation
- Qwen2-VL perceptual analysis
- VLM visual commentary
- Nature 9.03 Street Interface synthesis
- Final Street Interface score

This repository, by contrast, is designed to make the research process inspectable and auditable.

## Notes

The application is currently a research prototype and workflow candidate.

Before treating the repository as a final production release, complete the remaining host lint / build validation and any additional project-specific acceptance checks.