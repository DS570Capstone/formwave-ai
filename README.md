# formwave-ai
AI backend for FormWave: video ingestion, pose extraction, biomechanical analysis, and coaching inference.

formwave-ai
│
├── README.md
├── requirements.txt
├── .env.example
│
├── apps
│   ├── api
│   │   └── main.py
│   │
│   └── worker
│       └── run_worker.py
│
├── formwave
│   ├── pipeline
│   │   ├── ingestion
│   │   └── pose
│   │
│   ├── physics
│   │
│   ├── annotation
│   │
│   ├── dataset
│   │
│   ├── musclepose
│   │
│   └── common
│
├── resources
│   └── models
│
├── scripts
│   └── migrate.py
│
├── tests
│
└── docs