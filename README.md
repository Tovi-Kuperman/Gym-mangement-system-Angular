# Gym Management System (Angular)

## Overview
Gym Management System is an advanced Angular-based platform for managing fitness center operations. Designed for scalability and efficiency, the application empowers administrators, trainers, and members with modern tools for scheduling, user management, and real-time monitoring.

---

## Key Features
- **Modern Angular Architecture:** Built with modular components, services, and routing, ready for enterprise needs.
- **Scalability:** Easily supports hundreds/thousands of members, trainers, and classes.
- **User Management:** Full CRUD for members, trainers, schedules, and more.
- **Class Scheduling:** Create, update, and manage group and personal training sessions.
- **Responsive Design:** Optimized for desktop and mobile devices.
- **Secure Data Handling:** Authentication and authorization flows to protect user and business data.
- **Easy Integration:** Configurable with external systems through standard REST APIs.
- **Configuration Files:** Flexible setup via angular.json, package.json, and TypeScript configs.

---

## Folder Structure

```
src/               # Application source code (modules, components, services)
public/            # Static assets
.vscode/           # Editor configuration
angular.json       # Main Angular CLI configuration
package.json       # Dependencies and scripts
tsconfig*.json     # TypeScript configuration files
```

---

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm (Node package manager)
- Angular CLI (recommended: npm install -g @angular/cli)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tovi-Kuperman/Gym-mangement-system-Angular.git
   cd Gym-mangement-system-Angular
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```

### Running the Application
```bash
ng serve
```
Open the browser at http://localhost:4200

---

## Documentation
Configuration details are available in the angular.json and TypeScript config files. For API usage and integration, see the service files inside src/app/services.

---

## License
No license specified.