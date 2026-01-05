# mlops-iris-api

```text
mlops-iris-api/
├── deployments/           # Les services concernant le déploiements, que nous verrons plus tard.
├── models/
│   ├── model.joblib       # Le modèle entraîné  
├── src/
│   ├── api/
│   │   ├── Dockerfile     # Le Dockerfile pour construire notre image
│   │   ├── main.py        # Le code de notre API
│   │   └── requirements.txt
|── docker-compose.yml
├── Makefile
└── README.md
