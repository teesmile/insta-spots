# Insta-Spots

A collaborative photo-sharing web project inspired by Instagram. Built by a team of 11, starting with HTML and CSS and gradually evolving to a full React app.

## Live Site
[View Insta-Spots](https://insta-spots.vercel.app/)

---

## Project Goals
- Phase 1: Static site using HTML & CSS

---

## Collaborative Workflow & Quality Assurance

To ensure a smooth development process, maintain code quality, and foster effective collaboration within our team of 11, we've implemented the following key practices:

### ✅ 1. Designated Code Ownership

To streamline code reviews and ensure accountability, we've established a clear code ownership policy.

*   **How it Works**: We've added a `.github/CODEOWNERS` file to our project.
    ```
    * @kachi-jasperD
    ```
*   **Impact**: This configuration automatically assigns `@kachi-jasperD` as the designated reviewer for all pull requests. This crucial step ensures that every piece of code undergoes a thorough review by a dedicated owner before being merged, promoting consistency and maintaining high standards.

### ✅ 2. Robust Main Branch Protection

The `main` branch is the heart of our project, representing the most stable version of our codebase. To safeguard its integrity and enforce a rigorous review process, we've configured comprehensive branch protection rules.

*   **Our Goal**: To prevent direct commits to `main` and ensure all changes are introduced via carefully reviewed and approved pull requests.
*   **Key Protections Enabled**:
    *   **Require pull request before merging**: All changes must be proposed through a pull request.
    *   **Require at least 1 approving review**: A pull request needs at least one approval to proceed.
    *   **Require review from Code Owners**: The designated Code Owner must approve the changes.
    *   **Require status checks to pass before merging**: All automated checks (e.g., linters, tests) must succeed.
    *   **Require branches to be up to date before merging**: Feature branches must be synchronized with `main` before merging to prevent conflicts.
    *   **Do not allow bypassing the above settings**: These rules are strictly enforced for everyone.

*   **The Outcome**: This robust setup significantly reduces the risk of introducing bugs, merge conflicts, or accidental overwrites to our primary branch. It fosters a disciplined workflow where all contributions are systematically reviewed, tested, and integrated, leading to higher code quality and a more stable and reliable project for the whole team.

---

## 📁 Project Structure – `insta-spots`

insta-spots/
├── index.html
├── css/
│ └── style.css
├── js/
│ └── main.js # (to be added later)
├── images/
├── README.md

---

