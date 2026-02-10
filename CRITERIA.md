# Aluci Labeling Criteria

This document defines the standards required for a project to receive **Aluci**'s label. Our criteria focus on transparency, technical justification, and human-centric design.

## 1. Open Source & Licensing

To ensure accessibility and collaboration, the project must meet these legal standards:

- **Approved License**: The project must use an OSI-approved license. Aluci's recommended baseline is the **Apache-2.0 License**.
- **License Visibility**: A `LICENSE` file must be clearly present in the root directory.

## 2. Technical Excellence & Justification

We value intentional engineering over "vibe coding" (unstructured, trial-and-error development):

**Justified Tech Stack**: Any programming language or framework is authorized, provided the choice is justified. For instance, using web technologies for a desktop app is acceptable if cross-platform compatibility (web, mobile, desktop) is a core requirement of the project.

- **Architecture Integrity**: The project must demonstrate a clear structure and logical organization rather than a collection of unmanaged snippets.
- **Dependency Management**: Projects should use robust tools for environment and package management *(e.g., Poetry for Python, Cargo for Rust, Make or CMake for C/C++, Gradle for JVM)*.
- **Automated Setup**: We favor projects that provide scripts to automate environment creation *(e.g., `setup.sh` for virtual environments (Venv or Miniconda), installation of necessary tools)*.

## 3. Documentation & Setup Standards

A project must be easy to audit and install for other developers:

- **README tandard**: Every project must include a `README.md` with an Overview, Setup instructions, and Usage examples.
- **Status Transparency**: Projects in early development must include a prominent warning stating they are not yet ready for production use.
- **Clear Requirements**: All hardware and software requirements must be explicitly listed.

## 4. AI Usage Transparency

Transparency regarding generative AI is a non-negotiable pillar of the Aluci hub:

- **Mandatory Disclosure**: Any use of AI tools *(e.g., ChatGPT, GitHub Copilot)* during development must be documented.
- **AI Usage File**: Projects must include an `AI_USAGE.md` file based on the Aluci template to detail where and how AI was utilized.
- **Human Validation**: Contributors must confirm that all AI-generated code has been reviewed, tested, and validated by a human to ensure security and reliability.

## 5. Ethical & Human-Centric Design

- **Data Privacy**: The project must prioritize user privacy and avoid unnecessary data collection.
- **Resource Efficiency**: We encourage techniques that optimize performance to reduce resource consumption (e.g., CPU, RAM, GPU, energy hardware). For example, use: 
  - Small Language Models (SLMs) instead of general-purpose LLMs when appropriate
  - Efficient algorithms *(e.g., Binary search, quick sort)*
  - Adequate data structure *(e.g., Tree)*

## 6. Review & Approval Process

Projects seeking Aluci's label will undergo a review process by the Aluci labeling committee to ensure compliance with these criteria. Approval will be granted based on adherence to the outlined standards. Once approved, the project will receive the Aluci label and be featured in the Aluci hub.
