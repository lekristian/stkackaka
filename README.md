## 📁 Project Structure

```
stkacka/

├── apps/                  # Main applications
│   ├── mobile/            # 📱 Expo (React Native) app
│   └── backend/           # ⚙️ FastAPI API

├── services/              # Background & data processing
│   ├── worker/            # 🔄 Temporal worker (jobs, scheduling)
│   └── scraper/           # 🕷️ External data scraping

├── packages/              # Shared code
│   ├── types/             # 🧾 TypeScript types
│   └── utils/             # 🛠️ Utilities

├── infra/                 # Infrastructure & deployment
│   ├── docker/            # 🐳 Local development
│   │   └── docker-compose.yml
│   ├── k8s/               # ☸️ Kubernetes (future)
│   └── terraform/         # 🌍 IaC (future)

├── .github/workflows/     # 🤖 CI/CD pipelines

├── .env                   # 🔐 Environment variables
├── Makefile               # ⚡ Dev commands
└── README.md
```
