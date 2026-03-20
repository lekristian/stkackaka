## 📁 Project Structure

```
vehicle-tracker/

├── apps/
│   ├── mobile/            # Expo (React Native) app
│   └── backend/           # FastAPI API

├── services/
│   ├── worker/            # Background jobs
│   └── scraper/           # Data scraping

├── packages/
│   ├── types/             # Shared types
│   └── utils/             # Utilities

├── infra/
│   ├── docker/
│   │   └── docker-compose.yml
│   ├── k8s/
│   └── terraform/

├── .github/
│   └── workflows/

├── .env
├── Makefile
└── README.md
```
