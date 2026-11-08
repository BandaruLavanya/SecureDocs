# 🔐 SecureDocs - Role Based Document Access

> A Secure File Sharing System where users can access documents ONLY based on their Role.
> Built to solve real company data leakage problem.

## 🎯 Problem Statement
In many companies, all employees can see all files. Salary files, Strategy files leak avuthunnayi.
There is no control on WHO can see WHAT.

**Solution:** SecureDocs - Role Based Access Control (RBAC)

## ✨ Key Features
- Role-Based Login - Admin / Manager / Employee
- Admin - Can access 100% documents (4/4)
- Manager - Can access 75% documents (3/4)
- Employee - Can access 50% documents (2/4)
- Access Denied UI for restricted files
- View & Download buttons
- Fully Responsive Design

## 👥 Role Access Matrix
| Document | Admin | Manager | Employee |
| :--- | :---: | :---: | :---: |
| Company Strategy.pdf | ✅ | ❌ | ❌ |
| Salary Report.xlsx | ✅ | ✅ | ❌ |
| Project Plan.docx | ✅ | ✅ | ✅ |
| Leave Policy.pdf | ✅ | ✅ | ✅ |

## 🛠️ Tech Stack
- Frontend: HTML5, CSS3, JavaScript
- Logic: Role Based Access Control (RBAC)
- Hosting: GitHub Pages
- Version Control: GitHub

## 🚀 How To Run (Live Demo)
1. Open `index.html`
2. Click on Admin - You will see all 4 documents
3. Click on Manager - You will see 3 documents
4. Click on Employee - You will see only 2 documents
5. Try to access restricted file - You will get Access Denied

## 🔮 Future Scope
- Real Backend with Node.js + MongoDB
- JWT Authentication
- File Upload with Encryption
- Audit Log - Who viewed which file
- Admin Dashboard

## 👩‍💻 Developed By
**Bandaru Lavanya**
Role Based Document Access - Secure File Sharing Project
