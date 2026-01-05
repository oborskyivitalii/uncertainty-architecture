# Contributing to Uncertainty Architecture

Thank you for your interest in contributing! This repository defines a shared doctrine, operational patterns, and reference architectures for building AI-integrated systems responsibly. Contributions help us keep the doctrine evolving and accurate.

---

## 1. What This Repository Accepts

We focus on **doctrine, operational guidance, and controlled reference artifacts**. Contributions may include:

- Documentation: new explanations, clarifications, diagrams (`docs/`, `assets/`)  
- Specifications: normative language, term definitions, patterns (`spec/`, `patterns/`)  
- Reference Architectures: concrete examples (`reference-architecture/`)  
- Prompts and Golden Sets: controlled, versioned interface artifacts (`prompts/`, `golden-sets/`)  
- Scripts and tooling: small utilities to maintain the repository (`scripts/`)  
- Examples: illustrative end-to-end workflows (`examples/`)  

> ⚠️ We do **not accept**:
> - Large AI agents, universal SDKs, or frameworks  
> - Arbitrary model output dumps or prompt experiments outside controlled patterns  
> - Non-deterministic artifacts without documentation and versioning  

---

## 2. Zones of Ownership

To keep contributions clear and maintainable:

| Area                      | Owner       | Notes                                                        |
| ------------------------- | ----------- | ------------------------------------------------------------ |
| Operating Model           | Vitalii     | Team functions, roles, rituals, decision boundaries          |
| Reference Architectures   | Sam         | Implementation patterns, judgment nodes, persona design      |
| Prompts                   | Sam         | Prompt registry, persona scaffolding, input/output contracts |
| Doctrine, Specs, Glossary | Vitalii&Sam | Core definitions, shared language, control-theory framing    |
| Scripts & Templates       | Anyone      | Must follow repository conventions                           |

> Each pull request should clearly indicate which owner is responsible for reviewing.

---

## 3. Contribution Process

1. **Fork the repository**  
2. **Create a branch** named descriptively (e.g., `docs/metrics-update`)  
3. **Make your changes** using the repository structure  
4. **Add or update README.md** in the folder if necessary  
5. **Ensure compliance** with licensing and contribution guidelines  
6. **Submit a pull request** with a clear description and specify the owner for review  

---

## 4. Writing Guidelines

- Keep language **clear and precise**  
- Avoid speculative or magic-based statements about LLMs  
- Use **control-theory framing** when describing interfaces, patterns, and judgment boundaries  
- Include examples or diagrams wherever helpful  

---

## 5. Licensing

This repository uses a **dual-license model**:

- Documentation, doctrine, and specifications: **CC BY 4.0**  
- Code, scripts, and reference implementations: **Apache 2.0**

All contributions must comply with the applicable license for the files being modified.

---

## 6. Review and Merge

- Vitalii and Sam will **review PRs** in their respective areas of ownership  
- Minor fixes (typos, formatting, template updates) may be merged by maintainers  
- Larger contributions may require discussion and iterative improvements  

---

## 7. Code of Conduct

Please also read the [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) to ensure a welcoming and professional environment.