---
SPDX-FileContributor: SPDX AI Working Group and its Contributors
SPDX-FileType: DOCUMENTATION
SPDX-License-Identifier: CC0-1.0
---

# Publications

Publications on AI Bill of Materials (AI BOM), AI transparency, and related
SPDX and SBOM standards.

## Key publications

In addition to the SPDX AI and Dataset profiles,
the Working Group releases publications covering usage guidance and design rationale.

- **[Implementing AI bill of materials (AI BOM) with SPDX 3.0: A comprehensive guide to creating AI and dataset bill of materials](https://www.linuxfoundation.org/research/ai-bom)**

    Explores the concept of AI BOM and how to use AI and Dataset profiles in
    SPDX 3.0 to document AI systems and datasets.

    > Karen Bennet, Gopi Krishnan Rajbahadur, Arthit Suriyawongkul, and Kate Stewart, “Implementing AI Bill of Materials (AI BOM) with SPDX 3.0: A Comprehensive Guide to Creating AI and Dataset Bill of Materials”, The Linux Foundation, October 2024. <https://doi.org/10.70828/RNED4427>.

- **[Building an ppen AIBOM standard in the wild: An experience report on extending the SPDX SBOM (ISO/IEC 5962:2021) for AI supply chains](https://arxiv.org/abs/2510.07070)**

    Documenting the experiences, design decisions, and lessons learned
    from developing the AI and Dataset profiles in SPDX 3.0 in an open community setting.

    > Gopi Krishnan Rajbahadur, Keheliya Gallaba, Elyas Rashno, Arthit Suriyawongkul, Karen Bennet, Kate Stewart, and Ahmed E. Hassan, “Building an Open AIBOM Standard in the Wild”. Preprint, arXiv, October 2025. <https://doi.org/10.48550/arXiv.2510.07070>.

    *Accepted for the [Software Engineering in Practice (SEIP) track](https://conf.researchr.org/track/icse-2026/icse-2026-software-engineering-in-practice) of IEEE/ACM International Conference on Software Engineering 2026.*

## Presentations

Presentations and talks on SPDX AI and Dataset profiles and other works from
the SPDX AI Working Group:

- **[How to make SPDX industry standard for AI/ML](https://archive.fosdem.org/2024/schedule/event/fosdem-2024-3169-how-to-make-spdx-industry-standard-for-ai-ml/)**
    by Cheuk Ting Ho
    at FOSDEM 2024,
    4 February 2024.

    Although this talk predates the SPDX 3.0 final release, it provides
    insights into the motivations for the SPDX AI BOM and the roadmap for
    community adoption.

- **[Accountability taxonomy for AI software bill of materials](https://ossna2024.sched.com/event/1aBNk/accountability-taxonomy-for-ai-software-bill-of-materials-arthit-suriyawongkul-adapt-centre-trinity-college-dublin)**
    by Arthit Suriyawongkul
    at Open Source Summit North America 2024,
    16 April 2024.

    Provides an overview mapping of EU AI Act informational requirements
    (focused on the market-entry obligations) to SPDX 3.0 data model.

- **[From complexity to clarity: Addressing challenges in AI BOMs for compliance](https://ossaidevjapan24.sched.com/event/1jKEj/from-complexity-to-clarity-addressing-challenges-in-ai-boms-for-compliance-gopi-krishnan-rajbahadur-queens-university-kate-stewart-the-linux-foundation)**
    by Gopi Krishnan Rajbahadur and Kate Stewart
    at Open Source Summit Japan 2024,
    29 October 2024.

    Best practices and strategies to improve AI BOM accuracy and utility,
    equipping professionals with the insights to ensure their AI applications
    are compliant and prepared for future regulations.

- **[SPDX: Tackling system risk in modern supply chains](https://pytorchconference.sched.com/event/2AJ9O)**
    by Kate Stewart and Gary O'Neall
    at PyTorch Conference 2025,
    22 October 2025.

    Go through the key aspects in SPDX 3.0 that enable AI systems and the data
    used to train the systems to be made transparent, so proper system level
    risk analysis for licensing, security, and data biases in model training
    can be performed.

- **[Trust, track, and verify: Securing AI pipelines end-to-end](https://colocatedeventsna2025.sched.com/event/28D03/trust-track-and-verify-securing-ai-pipelines-end-to-end-adolfo-garcia-carabiner-systems-jun-victor-lu-independent)**
    by Adolfo Garcia & Jun (Victor) Lu
    at Open Source SecurityCon 2025,
    10 November 2025.

    Explores how to secure AI pipelines using bill of materials, such as SPDX,
    to capture complete lineage of code, data, and models; AI-specific controls
    from CoSAI’s supply chain framework; and Unified AI-Ops practices across
    MLOps, DataOps, SecOps, and AgentOps.

## Citations

When citing the SPDX AI Working Group or related standards, please reference:

- The official SPDX specification documents
- Working group publications and whitepapers
- Community repositories and resources

## Stay updated

For the latest publications and research:

- Watch the [SPDX GitHub organization](https://github.com/spdx)
- Follow [Linux Foundation Research](https://www.linuxfoundation.org/research)
- Join SPDX mailing lists and community channels

## Similar and related efforts

The SPDX AI Working Group is not the only technical group working on AI BOM.
There is a growing number of communities in this space, including:

- **[CycloneDX](https://cyclonedx.org/)**,
  an SBOM standard from OWASP Foundation, also has AI BOM "capabilities" called
  *[Machine Learning Bill of Materials (ML-BOM)](https://cyclonedx.org/capabilities/mlbom/)*.
- **[Croissant](https://mlcommons.org/working-groups/data/croissant/).**
  Standardize how ML datasets are described to make them easily discoverable
  and usable across tools and platforms. A project from MLCommons.
- **[SBOM for AI Use-Cases](https://github.com/aibom-squad/SBOM-for-AI-Use-Cases)**
  Use cases and recommendations to operationalize SBOMs for AI systems,
  developed by the CISA-facilitated SBOM for AI Tiger Team.
  The latest version of the document (0.3 draft, 23 June 2025) can be found on
  its GitHub repository.
- **OpenChain AI Study Group.**
  Part of the [OpenChain Project](https://openchainproject.org/),
  also under the Linux Foundation.
  The group published
  *[Artificial Intelligence System Bill of Materials: Compliance Management Guide for the Supply Chain](https://openchainproject.org/news/2025/10/20/welcoming-the-openchain-ai-system-bill-of-materials-compliance-guide)*
  in October 2025. Join its mailing list at
  <https://lists.openchainproject.org/g/ai>
- **[OWASP AI BOM Project](https://owaspaibom.org/).**
  A new initiative from the OWASP Foundation targeting first release
  in November 2025.
- **[TAIBOM](https://aibom.org/).** The Trustable AI Bill of Materials project
  addresses versioning and annotations for AI systems.
- **[OpenSSF AI/ML Security WG](https://github.com/ossf/ai-ml-security).**
  Part of the [Open Source Security Foundation](https://openssf.org/).
- **[TechOps](https://github.com/aloosley/techops/).** Not exactly BOM,
  but another AI system technical documentation approach for the EU AI Act
  compliance.
- **[Coalition for Secure AI (CoSAI)](https://www.coalitionforsecureai.org/).**
  A project from OASIS Open focused on AI security controls and mitigations.
- **[Responsible AI Licenses](https://www.licenses.ai/).**
  A project focused on standardizing licenses for AI models and datasets.

---

[Back to Home](./index.md){ .md-button }
