
# Online Exam Platform

A modern online examination platform built with Angular 21, designed to provide a structured and interactive experience for students taking online exams.

The application includes authentication, diploma browsing, exam management, timed examinations, and results visualization.

## Features

### Authentication & User Management
- User registration and login.
- Multi-step authentication flow.
- Forgot and reset password functionality.
- Route protection using Angular Guards.
- Profile management and email verification.

### Diploma Management
- Browse available diplomas.
- View diploma details.
- Paginated diploma listing.
- Show More functionality.

### Examination System
- Browse exams associated with diplomas.
- Start and complete timed examinations.
- Countdown timer.
- Navigate between questions.
- Select and track answers.
- Submit exam answers.

### Results
- Display examination results.
- Visualize correct and incorrect answers.
- Results summary with progress indicators.

### UI & User Experience
- Responsive dashboard layout.
- Reusable standalone components.
- Dynamic breadcrumbs.
- Toast notifications.
- Interactive dialogs and forms.

## Tech Stack

| Technology | Purpose |
|---|---|
| Angular 21 | Frontend framework |
| TypeScript | Application logic |
| Angular Signals | Reactive state management |
| RxJS | Asynchronous data handling |
| Angular Router | Navigation and route protection |
| PrimeNG | UI components |
| Tailwind CSS 4 | Styling |
| Font Awesome | Icons |
| ngx-sonner | Toast notifications |
| Vitest | Unit testing |
| Angular SSR | Server-side rendering support |

## Architecture

The application follows a feature-based architecture with reusable components and dedicated services.

- **Core:** Shared application services and configuration.
- **Features:** Authentication, diplomas, exams, and account settings.
- **Shared:** Reusable UI components and utilities.
- **Services:** API communication and business logic.
- **Interfaces:** TypeScript models and API response types.
- **Guards:** Authentication and authorization route protection.

## Getting Started

### Prerequisites

- Node.js
- npm
- Angular CLI 21

### Installation

Clone the repository:

```bash
git clone https://github.com/Dev-Mahmoud28/online-exam.git
```

Navigate to the project directory:

```bash
cd online-exam
```

Install dependencies:

```bash
npm install
```

### Development Server

Run the application locally:

```bash
npm start
```

Open your browser at:

```text
http://localhost:4200
```

### Production Build

Generate an optimized production build:

```bash
npm run build
```

### Unit Tests

Run unit tests:

```bash
npm test
```

## Deployment

The application can be deployed to Vercel after configuring the appropriate Angular build output and routing settings.

## Author

**Mahmoud Mohamed**

Frontend Developer | Angular

- GitHub: [Dev-Mahmoud28](https://github.com/Dev-Mahmoud28)

---

Built with Angular ❤️