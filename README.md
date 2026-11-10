<p align="center">
  <img src="assets/header.svg" alt="Dhanusu E, Full Stack Developer" width="100%">
</p>

<p align="center">
  <a href="https://linkedin.com/in/dhanusu-e-9a04023a3"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:dhanusu13052004@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img alt="Status" src="https://img.shields.io/badge/Status-Open%20to%20Work-2EA44F?style=for-the-badge">
</p>

<img src="assets/divider.svg" width="100%" alt="">

## 👨‍💻 About

Final-year **B.Tech Information Technology** student (Pondicherry University, 2026) and **MERN stack developer**. I build responsive interfaces, secure REST APIs and database-driven apps, with internships in MERN development, Python and UI/UX design. I'm looking for an entry-level Software Developer role.

```ts
const dhanusu: Developer = {
  role: "Full Stack Developer (MERN)",
  stack: ["MongoDB", "Express.js", "React.js", "Node.js"],
  auth: "JWT",
  styling: ["Tailwind CSS", "CSS3"],
  alsoKnows: ["Python", "SQL", "Figma"],
  openToWork: true,
};
```

<img src="assets/divider.svg" width="100%" alt="">

## 🧰 Tech Stack

| Area | Technologies |
|:--|:--|
| **Frontend** | React.js · JavaScript (ES6+) · HTML5 · CSS3 · Tailwind CSS |
| **Backend** | Node.js · Express.js · REST APIs · CRUD · JWT Authentication |
| **Database** | MongoDB · Mongoose · SQL |
| **Languages** | JavaScript · Python |
| **Tools** | Git · GitHub · VS Code · Postman · Figma |

<p>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Express" src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white">
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white">
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
</p>

<img src="assets/divider.svg" width="100%" alt="">

## 🛒 Featured Project: Blueshell E-Commerce Platform

Full stack MERN e-commerce app with a responsive UI, REST APIs and JWT-secured authentication.

**Architecture**

```mermaid
flowchart LR
    A[React + Tailwind<br/>Client] -->|HTTPS · JSON| B[Express.js<br/>REST API]
    B --> C[Auth middleware<br/>JWT verify]
    C --> D[Controllers]
    D --> E[(MongoDB<br/>via Mongoose)]
```

**Authentication flow**

```mermaid
sequenceDiagram
    participant U as User
    participant C as React client
    participant S as Express API
    participant D as MongoDB
    U->>C: Login (email, password)
    C->>S: POST /auth/login
    S->>D: Find user, compare password hash
    D-->>S: User record
    S-->>C: Signed JWT
    C->>S: Request + Authorization: Bearer token
    S->>S: Verify token, check role
    S-->>C: Protected data
```

<details>
<summary><b>Technical details</b></summary>

- **Frontend:** component-based React.js UI styled with Tailwind CSS, responsive across screen sizes
- **Backend:** RESTful APIs in Node.js and Express.js with CRUD operations
- **Database:** MongoDB with Mongoose schemas and models
- **Security:** JWT-based authentication and authorization
- **Tested with:** Postman during API development

</details>

<img src="assets/divider.svg" width="100%" alt="">

## 🚀 Other Projects

| Project | What it does | Tech |
|:--|:--|:--|
| 🏥 **Hospital Appointment Booking** | Online appointment booking with form handling and validation of appointment details | HTML · CSS · JavaScript |
| 🧳 **Tourism Management System** | Manages tourism details, listings and bookings with structured data storage | Web app |
| 🫁 **Lung Disease Prediction** | Predicts lung disease from user input and medical data, and displays the result | Python |

<img src="assets/divider.svg" width="100%" alt="">

## 💼 Experience

| Role | Company | Highlights |
|:--|:--|:--|
| **MERN Full Stack Intern** | Valvanet Technologies | Built full stack features, responsive React components wired to REST APIs, and MongoDB schemas with CRUD |
| **Python Intern** | Tidal Neo · HTGE-Technology | Python development tasks, strengthening core programming and problem solving |
| **UI/UX Design Intern** | HighKon Medias | Layouts, wireframes and prototypes in Figma for web apps |

<img src="assets/divider.svg" width="100%" alt="">

## 🎓 Education

| Degree | Institution | Years | Score |
|:--|:--|:--|:--|
| B.Tech, Information Technology | Raak College of Engineering & Technology, Puducherry (Pondicherry University) | 2022 – 2026 | CGPA 8.0 |
| HSC | St. Joseph's Higher Secondary School | 2021 – 2022 | 70% |
| SSLC | St. Joseph's Higher Secondary School | 2019 – 2020 | 76% |

<img src="assets/divider.svg" width="100%" alt="">

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhanusu--e-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhanusu-e-9a04023a3)
[![Email](https://img.shields.io/badge/dhanusu13052004@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dhanusu13052004@gmail.com)
