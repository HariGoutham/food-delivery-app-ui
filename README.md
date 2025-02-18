# Angular Application Guide (food-delivery-app-ui)

Food delivery app front end in angular 

## What You Need

Before starting, make sure you have the following installed:

- **Node.js 16.x or higher** (to run JavaScript and npm commands)
- **Angular CLI 15.x or higher** (to scaffold and manage Angular projects)
- **Git** (optional, to download the code)
- **Docker** (optional, to run the app in a container)

## How to Set Up

### 1. Download the Code
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure the Application(If needed)
environment.ts or environment.prod.ts file in the src/environments
Example:
typescript
export const environment = {
  production: false,
  apiUrl: 'http://localhost:8080/api',
};

### 4. Run the Application
```bash
ng serve
```
The application will be available at:
http://localhost:4200

### 5. Run with Docker
```bash
docker build -t your-angular-app .
```

```bash
docker run -p 4200:80 your-angular-app
```

The app will be accessible at:
http://localhost:4200

### 6. Run Tests
ng test
