# 🌐 Open Source Contributions Portfolio

<div align="center">

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Project](https://img.shields.io/badge/Contributed_To-Backlot-6366F1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shrikargs7-cloud/backlot)
[![Language](https://img.shields.io/badge/Language-Python_%2F_REST_APIs-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)

**Verified Open-Source Engineering Contributions to Enterprise SaaS Simulation Engines**

</div>

---

## 🎯 Featured Contribution: Backlot SaaS Emulator

**Backlot** is an enterprise local emulator for SaaS APIs (Slack, Gmail, Google Drive, GitHub, Jira, Notion, S3) that replicates realistic response shapes, pagination, authentication, and fine-grained per-document ACLs for AI agents and test harnesses.

### 📋 Contribution Summary & Scope

```mermaid
graph LR
    subgraph Enterprise SaaS Sandbox
        TestClient[AI Agent / Test Suite] --> Gateway[Backlot Gateway Engine]
        Gateway --> Auth[ACL & Permission Validator]
        
        Auth --> ServiceA[Slack API Emulator]
        Auth --> ServiceB[Jira Issue Emulator]
        Auth --> ServiceC[GitHub & Notion Mock]
    end

    subgraph Contributions
        Contribution[✨ Shrikar's Contributions] -.-> ServiceA
        Contribution -.-> ServiceB
        Contribution -.-> Docs[Validation & Test Suites]
    end
```

---

## 🔍 Key Engineering Highlights

1. **API Fidelity & Response Schema Conformance**:
   - Engineered mock response structures conforming to upstream API specifications.
   - Handled edge-case pagination tokens (cursor-based and offset-based) to ensure AI agents do not hallucinate schema errors.

2. **Access Control & ACL Simulation**:
   - Implemented role-based test cases validating unauthorized access rejections and permission scope boundaries.

3. **Documentation & Validation Reports**:
   - Comprehensive contribution documentation including test suites, step-by-step reproduction flows, and architectural rationale archived in `Contribution_3_Backlot.docx`.

---

## 📁 Repository Contents

- `Contribution_3_Backlot.docx`: Formal technical report detailing the PR implementation, design considerations, and verification logs.
- `README.md`: High-level overview and index for recruiters and open-source maintainers.

---

## 📄 License
MIT License © [Shrikar G S](https://github.com/shrikargs7-cloud)
