# Art Market Platform – Transaction & Compliance Module (NDA Project)

**Note:** This is a portfolio summary of a commercial project developed under NDA. Source code is not publicly available.

## 🎨 Project Overview

This project involved the development of a digital platform for managing and facilitating the trade of artworks between galleries and individual collectors. The system supports a range of operations from cataloging and pricing to secure transaction workflows and compliance verification.

## 👨‍💻 My Role

I joined the project during its mid-phase and was responsible for the **implementation of the banking & compliance module**, which served as an internal tool for financial institutions.

Key responsibilities included:

- Creating a **secure banking interface** for transaction officers
- Building views for transaction detail review, buyer/seller participant verification, and document uploads
- Implementing logic for **KYC (Know Your Customer) flow** integration
- Ensuring smooth handoff of verified cases to compliance teams
- Designing a user-friendly interface with a high level of data clarity
- Working within an existing React-based architecture and integrating seamlessly with backend APIs
- **Implementing components based on high-fidelity Figma designs**, ensuring UI consistency and accessibility

- The project followed an Agile workflow in Jira, and I maintained close coordination with the backend team to align data structures and API expectations. I collaborated with testers to cover edge cases in the KYC flow and handled UI logic for document handling and validation. Even though I joined mid-project, I quickly synchronized with the team and frequently took part in internal demo sessions to present progress and clarify interaction logic.

Thanks to my prior experience in the finance sector, I was able to contribute to the UX of the banking module — ensuring that flows for data verification, transaction overview, and document uploads met real-world expectations of banking professionals. I also had a direct influence on the design of some interface components, working iteratively with designers to improve clarity and usability based on domain knowledge. Final visuals were built based on Figma.

I worked on this project for approximately **4 months**, collaborating closely with backend developers and the product owner.

## 🛠️ Tech Stack

### Frontend
- **React 18**
- **TypeScript**
- **MobX** (state management)
- **Mantine UI** – component library for modern, accessible interfaces
- **Zod** – schema-based validation
- **React Router DOM** – routing
- **Day.js** – date handling
- **React DnD** – drag & drop where required

### Utility & Formatting
- **Prettier** + **ESLint** + **Husky**
- **Environment-based proxy configuration** (via `dotenv-cli`, `cross-var`, `local-cors-proxy`)
- **PostCSS** + Mantine theming

### PDF & Document Handling
- **React PDF**, **react-to-print**, **react-pdf-viewer**
- **QR code rendering** and **file uploading workflows**

### Testing
- **Jest**, **Testing Library**

## 🔐 Key Features Developed

- **Transaction Overview Dashboard** for banking teams
- **Participant Verification Panel** with access to submitted data and ID documents
- **KYC Document Workflow**, including file uploads and compliance routing
- **Banker Action Logging** for traceability and auditing
- **Conditional rendering and access control** based on transaction state

## 🚀 Outcome

- Successfully deployed module enabled internal banking teams to process transactions more efficiently and with full KYC traceability.
- Streamlined document handling and approval chains reduced delays and manual overhead.
- Positive feedback received for clarity of UI and overall usability.

---

_Want to know more about the banking module's technical structure or challenges? I'm happy to elaborate in a private conversation._
