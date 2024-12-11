# **DojoAppOrg - The Official Development Guide 🌟**

Welcome to **DojoAppOrg**, the home of DojoApp, a mobile-first solution built to deliver an exceptional user experience. This README serves as your guide to everything you need to know about our ecosystem. Whether you're new to the team or a seasoned contributor, you'll find all the essential details here.

---

## 📂 **Repository Overview**

### **1. DojoApp - Frontend Repository**
🌐 **GitHub:** [DojoApp Repository](https://github.com/CpartIL/dojoapp)  
The DojoApp frontend is a cross-platform mobile application built with **React Native**, **Expo**, and **Redux** for state management. It's designed to provide a seamless and efficient user experience.

### **2. dojoadmin - Backend Repository**
🌐 **GitHub:** [dojoadmin Repository](https://github.com/DojoAppOrg/dojoadmin)  
The backend is powered by **Strapi v4** (a headless CMS), running on **Node.js**, and deployed on **AWS**. It supports all content and data management needs for the DojoApp.

---

## 🚀 **Tools and Workflow**

### **Task Management with Taiga**  
Stay on top of your tasks with Taiga:  
🌐 **Taiga Project Timeline:** [Taiga Board](https://tree.taiga.io/project/avicpart-dojoapp/timeline)

### **Product & Development Boards with Miro**  
Get a visual overview of our workflow and product strategy:  
- 🌟 **Product Board:** [Miro Product Board](https://miro.com/app/board/uXjVLeqfu4Y=/)  
- 🔧 **Development Board:** [Miro Dev Board](https://miro.com/app/board/uXjVLdxjz2A=/)

---

## 🔑 **Getting Started**

### **Prerequisites**
Ensure you have the following installed on your machine:
- **Node.js** (v16 or later)
- **npm** or **yarn**
- **Git**
- [Expo CLI](https://docs.expo.dev/get-started/installation/) (for the frontend)
- [EAS CLI](https://docs.expo.dev/eas/cli/) (for deployment)
- **Postman** (optional, for API testing)

---

### **Development Setup**

#### **Frontend (DojoApp):**
1. Clone the repository:
   ```bash
   git clone https://github.com/DojoAppOrg/DojoApp.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npx expo start
   ```

#### **Backend (dojoadmin):**
1. Clone the repository:
   ```bash
   git clone https://github.com/DojoAppOrg/dojoadmin.git
   ```
2. Switch to the development branch:
   ```bash
   git checkout dev
   git pull origin dev
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the backend in development mode:
   ```bash
   npm run develop
   ```

---

## 🏗️ **Architecture Overview**

### **Frontend (React Native + Expo):**
The frontend utilizes:
- **React Native** for building cross-platform interfaces.
- **Expo** for streamlined development and deployment.
- **Redux** for predictable and scalable state management.

### **Backend (Strapi + Node.js):**
The backend is a Strapi-based **headless CMS**, designed for:
- Flexible content management.
- Scalable and secure data handling.
- REST API integration with the frontend.

---

## 🌐 **Access Requests**
For access to:
- **Taiga Board**
- **Miro Boards**
- **AWS Services**
- **Admin Panel Credentials**

👉 **Contact:** **Ibraheem Ganayim** (Team Lead)  
📧 Email: [Ganayim.Ibraheem@gmail.com](mailto:Ganayim.Ibraheem@gmail.com)

---

## 🛠️ **Development Workflow**

1. **Assign Yourself a Task on Taiga:**  
   Find a task, assign it to yourself, and mark it as "In Progress."

2. **Create a Feature Branch:**  
   Follow our naming conventions:
   ```bash
   git checkout -b feature/task-name
   ```

3. **Work on Your Feature:**  
   Write clean, well-commented code using reusable components and modular architecture.

4. **Commit Your Changes:**  
   Use clear, descriptive commit messages:
   ```bash
   git commit -m "Add feature: task description"
   ```

5. **Push Your Changes:**  
   ```bash
   git push origin feature/task-name
   ```

6. **Open a Pull Request (PR):**  
   Submit your PR to the `dev` branch. Add details about your changes and link to the corresponding Taiga task.

---

## 📜 **Important Links**

| **Platform**   | **Purpose**            | **Link**                                 |
|----------------|------------------------|-----------------------------------------|
| GitHub (Frontend) | Frontend Repository   | [DojoApp Repo](https://github.com/CpartIL/dojoapp) |
| GitHub (Backend)  | Backend Repository    | [dojoadmin Repo](https://github.com/DojoAppOrg/dojoadmin) |
| Taiga          | Task Management        | [Taiga Board](https://tree.taiga.io/project/avicpart-dojoapp/timeline) |
| Miro (Product) | Product Planning       | [Product Board](https://miro.com/app/board/uXjVLeqfu4Y=/) |
| Miro (Dev)     | Development Strategy   | [Dev Board](https://miro.com/app/board/uXjVLdxjz2A=/) |

---

## 🎉 **Contributing**

We’re excited to have you on board! Here's how you can contribute:
1. **Fork the Repository:** Clone your fork and create a new branch.
2. **Work on Your Task:** Follow our architecture and coding standards.
3. **Submit a PR:** Make sure to link your PR to a Taiga task for tracking.

---

## 📬 **Support**

For any queries or assistance, reach out to:  
**Ibraheem Ganayim** (Team Lead)  
📧 Email: [Ganayim.Ibraheem@gmail.com](mailto:Ganayim.Ibraheem@gmail.com)

---

Thank you for contributing to **DojoAppOrg**! Let's build something amazing together. 🚀
