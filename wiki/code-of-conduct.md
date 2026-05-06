# Code of Conduct

# Code of Conduct

<details>
<summary>Relevant source files</summary>

The following files were used as context for generating this wiki page:

- [.github/CODE_OF_CONDUCT.md](.github/CODE_OF_CONDUCT.md)

</details>



This page outlines the social and professional standards for the `react-native-onfido` project. The project adopts the **Contributor Covenant v1.4** to ensure a welcoming, harassment-free environment for all contributors, regardless of background or experience level [.github/CODE_OF_CONDUCT.md:1-10]().

## Project Pledge and Scope

The maintainers of `react-native-onfido` pledge to foster an inclusive community. This commitment applies to all project spaces, including GitHub issues, pull requests, and the project wiki [.github/CODE_OF_CONDUCT.md:3-10](). It also extends to public spaces where individuals represent the project, such as official social media interactions or technical events [.github/CODE_OF_CONDUCT.md:46-53]().

### Behavioral Standards

The following table categorizes expected vs. unacceptable behaviors within the project ecosystem:

| Positive Behaviors [.github/CODE_OF_CONDUCT.md:14-21]() | Unacceptable Behaviors [.github/CODE_OF_CONDUCT.md:23-32]() |
| :--- | :--- |
| Using welcoming and inclusive language | Sexualized language, imagery, or unwelcome advances |
| Respecting differing viewpoints and experiences | Trolling, insulting comments, or personal/political attacks |
| Gracefully accepting constructive criticism | Public or private harassment |
| Focusing on the community's best interests | Doxing (publishing private info without permission) |
| Showing empathy towards other members | Any conduct inappropriate for a professional setting |

**Sources:** [.github/CODE_OF_CONDUCT.md:14-32]()

## Maintainer Responsibilities and Enforcement

Project maintainers are the primary enforcers of these standards. They possess the authority to moderate contributions and community interactions to maintain project health [.github/CODE_OF_CONDUCT.md:34-38]().

### Enforcement Powers
Maintainers have the right and responsibility to [.github/CODE_OF_CONDUCT.md:40-44]():
1.  **Remove/Edit Content:** Modify or delete comments, commits, code, wiki edits, or issues not aligned with the Code of Conduct.
2.  **Reject Contributions:** Block pull requests that violate community standards.
3.  **Account Suspension:** Ban contributors temporarily or permanently for harmful or offensive behavior.

### Reporting Process
Instances of unacceptable behavior should be reported to the project team via email:
*   **Contact:** `jamesjara@agmail.com` [.github/CODE_OF_CONDUCT.md:58]()
*   **Confidentiality:** The project team is strictly obligated to maintain the confidentiality of the reporter [.github/CODE_OF_CONDUCT.md:61]().
*   **Investigation:** All complaints will be reviewed and investigated, resulting in a response deemed appropriate to the circumstances [.github/CODE_OF_CONDUCT.md:59-60]().

**Sources:** [.github/CODE_OF_CONDUCT.md:34-66]()

## Governance Data Flow

The following diagram illustrates the relationship between community participants, the reporting pipeline, and the enforcement actions taken by maintainers.

### Community Governance Logic
```mermaid
graph TD
    subgraph "Natural Language Space"
        [Contributor_Behavior] --> [Positive_Interaction]
        [Contributor_Behavior] --> [Unacceptable_Conduct]
    end

    subgraph "Enforcement Pipeline"
        [Unacceptable_Conduct] -- "Report to" --> [Email_jamesjara@agmail.com]
        [Email_jamesjara@agmail.com] -- "Confidential Review" --> [Maintainer_Action]
    end

    subgraph "Code Entity Space"
        [Maintainer_Action] -- "Delete/Edit" --> [GitHub_Issues]
        [Maintainer_Action] -- "Reject" --> [Pull_Requests]
        [Maintainer_Action] -- "Revert" --> [Commits]
        [Maintainer_Action] -- "Moderate" --> [Wiki_Pages]
    end
```
**Sources:** [.github/CODE_OF_CONDUCT.md:40-44](), [.github/CODE_OF_CONDUCT.md:57-61]()

## Attribution and Maintenance

This code is adapted from the Contributor Covenant, version 1.4 [.github/CODE_OF_CONDUCT.md:68-71](). Maintainers who fail to enforce the Code of Conduct in good faith may face repercussions from the project's leadership [.github/CODE_OF_CONDUCT.md:64-66]().

### Organizational Structure
```mermaid
graph LR
    subgraph "Project Entities"
        [Contributor_Covenant_v1.4] -- "Adopted By" --> [react-native-onfido]
    end

    subgraph "Roles"
        [Maintainers] -- "Responsible for" --> [Standards_Clarification]
        [Maintainers] -- "Execute" --> [Corrective_Action]
        [Contributors] -- "Adhere to" --> [Expected_Behaviors]
    end

    [Corrective_Action] -- "Targets" --> [Non-Compliant_Content]
```
**Sources:** [.github/CODE_OF_CONDUCT.md:1-10](), [.github/CODE_OF_CONDUCT.md:34-45]()

---