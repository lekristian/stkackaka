stkacka/
│
├── apps/
│   ├── mobile/              # Expo (React Native)
│   └── backend/             # FastAPI (API layer)
│
├── services/
│   ├── worker/              # Temporal worker
│   └── scraper/             # scraping logic (optional split)
│
├── packages/                # shared veci (optional early)
│   ├── types/               # TS types (mobile)
│   └── utils/               # shared utils
│
├── infra/
│   ├── docker/
│   │   └── docker-compose.yml
│   ├── k8s/                 # neskôr
│   └── terraform/           # neskôr
│
├── .github/
│   └── workflows/           # CI/CD
│
├── .env
├── Makefile
└── README.md
