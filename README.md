# AngularPrimengApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.20.

---

## 🚀 Development Server

Run the development server:

```bash
ng serve
```

Navigate to [http://localhost:4200/](http://localhost:4200/). The application will automatically reload if you change any of the source files.

---

## 🛠️ Code Scaffolding

Generate a new component, directive, pipe, service, class, guard, interface, enum, or module:

```bash
ng generate component component-name
ng generate directive|pipe|service|class|guard|interface|enum|module
```

---

## 🏗️ Build

Build the project:

```bash
ng build
```

The build artifacts will be stored in the `dist/` directory.

---

## 🧪 Running Unit Tests

Run unit tests via [Karma](https://karma-runner.github.io):

```bash
ng test
```

---

## 🧭 Running End-to-End Tests

Run end-to-end tests (add a package for e2e testing first):

```bash
ng e2e
```

---

## ℹ️ Further Help

- Run `ng help` for Angular CLI help.
- See the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli).

---

## 📦 Common Commands

### Project Setup

```bash
ng new angular-primeng-app --routing
npm install primeng primeflex primeicons
```

### Generate Components, Services, Guards, Interfaces

```bash
ng g c components/login
ng g c components/register
ng g c components/home
ng g s services/auth
ng g g guards/auth
ng g i interfaces/auth
```

### Angular Features

- Angular Routing
- Router Outlet

---

## 🗄️ Mock API with JSON Server

Install and run [json-server](https://github.com/typicode/json-server):

```bash
npm install -g json-server
json-server --watch db.json
```