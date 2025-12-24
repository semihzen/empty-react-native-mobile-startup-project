# Kiraci Mobile – React Native Starter

Clean, scalable and reusable **React Native starter project**.  
Designed to be cloned and used as a base for new mobile applications without rebuilding infrastructure every time.

---

## 🚀 Tech Stack

This starter comes with a modern and commonly used React Native stack:

- **React Native (CLI)**
- **TypeScript**
- **Zustand** – Global state management
- **Axios** – HTTP client
- **React Hook Form** – Form handling
- **Zod** – Schema validation
- **@hookform/resolvers** – RHF + Zod integration
- **ESLint & Prettier** – Code quality and formatting

> Libraries are installed and ready, but **not used by default**.  
> The project starts clean and grows based on real needs.

---

## 📁 Project Architecture

```txt
src/
├─ api/
│  ├─ client/        # HTTP / API clients (axios, fetch, etc.)
│  ├─ services/      # Endpoint-based service functions
│  └─ types/         # Backend / API contracts
│
├─ app/
│  ├─ layouts/       # Application layouts (MainLayout, AuthLayout, etc.)
│  ├─ routes/        # Navigation configuration
│  └─ screens/       # Application screens
│
├─ assets/           # Images, icons, fonts
├─ components/       # Reusable UI components
├─ hooks/            # Custom React hooks
├─ lib/              # Third-party wrappers & helpers
├─ store/            # Zustand stores
├─ theme/            # Colors, spacing, typography
├─ utils/            # Pure helper functions
│
└─ index.tsx         # Application entry (optional bootstrap layer)
