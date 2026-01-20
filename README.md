# 🏢 Conference Room Booking System

## 📑 Table of Contents

- [📌 Purpose of This Repository](#-purpose-of-this-repository)
- [🚀 What the Project Does](#-what-the-project-does)
- [💡 Why This Project Is Useful](#-why-this-project-is-useful)
- [🗂 Repository Contents](#-repository-contents)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [🤝 Contributing](#-contributing)
  - [Contribution Guidelines](#contribution-guidelines)
  - [Contribution Workflow](#contribution-workflow)
- [🐞 Known Issues](#-known-issues)
- [👥 Maintainers](#-maintainers)
- [🧑‍💻 Developer Onboarding (In Progress)](#-developer-onboarding-in-progress)
- [🧩 System Context](#-system-context)
- [📚 Project Documentation](#-project-documentation)
- [🛣 Upcoming Documentation](#-upcoming-documentation)
- [📄 License](#-license)
- [✍️ Author](#️-author)

---

## 📌 Purpose of This Repository
This repository contains the documentation, planning artefacts, and evolving implementation of the **Conference Room Booking System**.

The project is intended to demonstrate structured software development practices, including system analysis, documentation, collaboration workflows, and iterative development. Over time, this repository will evolve from conceptual artefacts into a fully implemented system.

---

## 🚀 What the Project Does
The **Conference Room Booking System** is designed to manage the reservation and scheduling of conference rooms within an organization. It provides a centralized way to view availability, make bookings, and prevent scheduling conflicts.

Core objectives include:
- Managing conference room availability
- Allowing users to request and confirm bookings
- Preventing double bookings and time conflicts
- Supporting administrative oversight of rooms and reservations

---

## 💡 Why This Project Is Useful
Shared meeting spaces are often difficult to manage without a dedicated system. This project addresses common challenges such as:

- Scheduling conflicts caused by manual booking
- Lack of visibility into room availability
- Inefficient coordination between teams
- Administrative overhead in managing shared resources

By centralizing bookings and enforcing rules, the system improves efficiency, transparency, and productivity within organizations.

---

## 🗂 Repository Contents
The repository is organised as follows:

.
├── README.md
│   Project overview, purpose, usage, and contribution guidelines
│
├── artifacts/
│   Core project artefacts and system documentation
│
│   ├── V&E_Reasoning.md
│   │   Validation and evaluation reasoning for system decisions
│   │
│   ├── sprint-1-epics.md
│   │   High-level epics defined for Sprint 1
│   │
│   └── sprint-1-artifacts/
│       └── user-stories.md
│           Detailed user stories derived from sprint epics
│
├── ceremonies/
│   Scrum ceremony documentation organised by sprint
│
│   └── sprint-1-ceremonies/
│       ├── sprint-1-planning.md
│       │   Sprint planning notes and objectives
│       │
│       ├── sprint-1-dailies.md
│       │   Daily stand-up records
│       │
│       ├── sprint-1-review.md
│       │   Sprint review outcomes
│       │
│       ├── sprint-1-retrospective.md
│       │   Retrospective reflections and improvement actions
│       │
│       ├── sprint-1-checkpoint.md
│       │   Progress checkpoint documentation
│       │
│       ├── sprint-1-summary.md
│       │   Sprint summary and conclusions
│       │
│       ├── priority-matrix.md
│       │   Task prioritisation matrix
│       │
│       └── personal-reflection.md
│           Individual reflection on sprint execution
│
├── .gitignore
│   Git ignore rules
│
├── .git/
│   Git version control metadata
│
└── LICENSE
    Project licensing information


---

## ⚙️ Installation

Follow the steps below to set up the project locally.

**Prerequisites**

Before installing, ensure you have the following installed:
- Git
- Visual Studio or Visual Studio Code

How to create a copy of a remote repo to your desktop, so to push the work into a newly created repo on Github without affecting the origional one.

**Instructions**
On you local PC.

1. Create or navigate to a folder which you want the repository to be copied/cloned into. (Rename the folder if you want)

3. Open VS Code.

4. On the VS Code terminal, type:

- cd c://your-pc-user/folder-name[Assignment-4.2] (this navigates to the repo folder locally, or just click 'Open Folder' in the VS Code 'File' dropdown menu, after the file-explorer window opens, navigate, select and open the folder which you want to work on, then VS Code will open the directory for you to work on)

-  type: git init (this will initialize/configure the folder for you then will be able to modify .gitFiles locally on your PC)

-  type: git clone https://github.com/tjgaba/Assignment-4.2.git

-  type: git remote remove origin (this removes any link with the origional remote repo in GitHub. This helps if you are going to make changes on your local repo so that when you push, you push to tge forked repo you created. You can view and confirm this by typing 'git remote -v' on the local VS Code terminal. There should be nothing following the command) Note: You now can work on you project and make changes as you want locally.

-  type: git add . (To track all changes made on local repo on PC)

-  type: git commit -m "Put your detailed and clear message of the change here"

-  type: Create a new repository through GitHub with the same name created on your local PC repo/folder.

-  type: git push --set-upstream origin main (On VS Code terminal. This will push all changes and files from your local PC repo/folder to the remote repo)

Note: You the should be having all the files both locally and remotely so that any changes you do locally you could push to the romote repo. But remember to fork/create a branch of the Main repo/folder, make changes on it, then only after testing the code you could Pull Request the branch to the main branch.

Additional dependencies will be documented as the project evolves.

Future installation guidance may include:
- Dependency installation
- Database configuration
- Running the system using Visual Studio

---

## 🚀 Usage
The system is intended to be used by organizations or teams that share conference or meeting rooms.

Typical usage scenarios include:
- Viewing available conference rooms
- Booking rooms for meetings
- Managing and reviewing reservations
- Administering room details and access rules

Detailed usage instructions will be added as system features are implemented.

---

## 🤝 Contributing
Contributions to this project are welcome and encouraged.

All changes must be made using **Pull Requests**. Direct commits to the main branch are not permitted.

### Contribution Guidelines
Contributors may:
- Create feature, bug-fix, or documentation branches
- Propose improvements or new features
- Fix issues related to incorrect or unexpected system behaviour
- Improve or clarify documentation and artefacts

Contributors must **not**:
- Modify licensing information
- Remove or alter core project documentation without justification
- Push directly to protected branches

### Contribution Workflow
1. Fork the repository
2. Create a new branch for your change
3. Make and test your changes
4. Submit a Pull Request
5. Clearly describe the intent and scope of the change

- Contributors who wish to improve the project should follow the workflow to ensure changes are clear, reviewable, and aligned with project goals.

- All contributors are required to complete the Pull Request template when submitting a Pull Request. Incomplete Pull Requests may be rejected or returned for revision.

- The branch names are to be given according to the type of changes implemented(feature/bugfix/docs). If however, there is more then one change to implement, then create a branch for every each fix in order to successfully Pull Request to avoid conflict.

Here are a few examples of the branch names you can use;

- `feature/<short-description>` – for new features or enhancements  
- `bugfix/<short-description>` – for fixes to incorrect or unexpected behaviour  
- `docs/<short-description>` – for documentation or artefact updates  

---

## 🐞 Known Issues
Some edge cases in the room availability and booking logic are not yet fully handled.

These include scenarios overlapping time boundaries, and future support for complex recurring bookings. 

### Description
The current room availability logic does not fully account for certain edge cases related to booking time boundaries. While core conflict detection is in place, some scenarios may result in incorrect booking rejections or approvals.

### Identified Edge Cases
- Back-to-back bookings (e.g., 10:00–11:00 followed by 11:00–12:00)
- Bookings that start or end exactly at existing booking boundaries in unrealistic.

### Expected Behaviour
- Adjacent bookings should not be allowed less given a time frame of 10-15 minutes for care-taking.
- Availability logic should be extensible for recurring bookings

### Current Behaviour
- Some adjacent or boundary-aligned bookings may be incorrectly flagged as conflicts

### Context
This issue was identified during Sprint 1 validation while reviewing the booking availability logic.

### Acceptance Criteria
- Edge cases around booking time boundaries are handled correctly
- Existing behaviour for standard overlaps remains unchanged
- There is a 10-15 time frame for care takers.

Contributors are encouraged to review open issues—especially those labelled `good first issue` or `help wanted`—and submit fixes via Pull Requests.

---

## 👥 Maintainers
This project is maintained by:

- **Andile**    – Developer  
Email:          masokaandile17@gmail.com
- **Sillo**     – Developer  
Email:          sillojunior8@gmail.com
- **TJ**        - Developer
Email:          tjgaba@outlook.com

They are responsible for reviewing pull requests, managing releases, and guiding the project direction.

---

## 🧑‍💻 Developer Onboarding (In Progress)

This section is intended for developers and contributors who are joining the project.

At this stage, the Conference Room Booking System is in its early development and documentation phase. The purpose of this onboarding section is to help new contributors understand the structure, intent, and direction of the project before active implementation begins.

### What New Contributors Should Understand
This section will provide guidance on:

- The long-term vision and goals of the Conference Room Booking System
- How project documentation, artefacts, and sprint materials are organised
- How to navigate the repository structure effectively
- Where to find key project artefacts such as sprint plans, user stories, and system documentation
- The technologies planned for development using the Visual Studio IDE

Onboarding documentation will expand as the project progresses.

---

## 🧩 System Context
The Conference Room Booking System is a conceptual system intended to manage:

- Room availability
- Booking requests
- Conflict prevention
- Administrative oversight

At the current stage, the system is documented through:
- Sprint artefacts
- System documentation
- Planning and design records

---

## 📚 Project Documentation
Project documentation is distributed across structured artefact and ceremony directories, reflecting an iterative Scrum-based development process.

Documentation includes:

- **Sprint artefacts** located in the `artifacts/` directory, such as:
  - Sprint epics
  - User stories
  - Validation and evaluation reasoning

- **Scrum ceremony records** located in the `ceremonies/` directory, including:
  - Sprint planning documents
  - Daily stand-up records
  - Sprint reviews and retrospectives
  - Sprint summaries and checkpoints
  - Priority matrices and personal reflections

These documents collectively capture the planning, reasoning, execution, and evaluation of the Conference Room Booking System as it evolves.

---

## 🛣 Upcoming Documentation
The following documentation will be added as the project evolves:

- API documentation (Swagger / OpenAPI)
- Runtime instructions (Docker)
- Developer setup and contribution workflows

---

## 📄 License
This project is licensed under the MIT License.

---

## ✍️ Author
**TJ Gaba**  
📧 TJ Gaba
