AI_DevOps_App/
├── app/                    # Code ứng dụng chính
│   ├── __init__.py
│   ├── main.py             # Điểm bắt đầu (API, UI, v.v.)
│   ├── inference.py        # Hàm chạy model AI
│   ├── model/              # Model, checkpoint, v.v.
│   ├── utils/              # Tiện ích chung
│   └── config/             # File config YAML/JSON
│
├── data/                   # Dữ liệu đầu vào/dòng thời gian
│   ├── raw/                # Dữ liệu gốc
│   ├── processed/          # Dữ liệu đã xử lý
│   └── samples/            # Dữ liệu mẫu demo
│
├── notebooks/              # Notebook để thử nghiệm nhanh
│   └── exploratory.ipynb
│
├── tests/                  # Unit test, integration test
│   ├── test_inference.py
│   └── test_api.py
│
├── docker/                 # File Docker & môi trường
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── scripts/                # Script CLI, train, deploy, cron
│   ├── train.py
│   ├── deploy.py
│   └── prepare_data.py
│
├── ci_cd/                  # File CI/CD (GitHub Actions, GitLab CI, Jenkinsfile...)
│   └── github_actions.yml
│
├── requirements.txt        # Python dependencies
├── environment.yml         # Conda environment (tùy chọn)
├── README.md               # Hướng dẫn project
├── .env                    # Biến môi trường (API key, db)
└── .gitignore              # File/directory cần bỏ qua khi commit
