.
├─ data/
│  ├─ raw/                 # original dataset (already added)
│  ├─ processed/           # train/dev/test splits, features
│  └─ artifacts/           # trained models, vectorizers, indices
├─ src/
│  ├─ data/                # loading & preprocessing
│  ├─ features/            # text/genre embeddings, normalization
│  ├─ models/              # content, collab, hybrid
│  ├─ eval/                # metrics & evaluation scripts
│  ├─ api/                 # FastAPI app
│  └─ utils/               # helpers, config, logging
├─ notebooks/              # EDA & experiments
├─ configs/
│  ├─ content.yaml
│  ├─ collab.yaml
│  └─ hybrid.yaml
├─ requirements.txt
├─ Dockerfile
├─ .env.example
└─ README.md  ← (you are here)
