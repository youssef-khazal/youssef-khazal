### Hi, I'm Youssef 👋

M.Sc. graduate in Data Science & AI (Université Côte d'Azur), based in Paris, working on deep learning.
I like building deep-learning models **and checking that their results hold up**: clean evaluation, ablations and failure analysis.

- 🔐 **Most recent:** AI / Deep Learning intern at **PQShield** (Paris, 2026). Deep-learning side-channel analysis of post-quantum cryptography (masked ML-KEM / Kyber). Co-authored paper *under review* at IACR Communications in Cryptology.
- 🗂️ **LLMs and RAG:** a local assistant for French administrative procedures, built on official open data, with reliability measured on 163 test questions, and a QLoRA fine-tune of a smaller model for it.
- 🎧 **Audio, vision, video, RL:** CNNs, Vision Transformers, self-supervised video models (VideoMAE, V-JEPA), deep Q-learning.
- 🔎 **Open to** ML / AI engineer and research-engineer roles. Based in Paris, open to relocation and remote.

---

#### Featured projects

| Project | What it shows |
|---|---|
| [**Démarches FR: RAG assistant for French administrative procedures**](https://github.com/youssef-khazal/fr-admin-assistant) | Local assistant (Qwen3-8B, hybrid BM25 + bge-m3 search, reranker) over 3,000 official Service-Public.fr guides, answering in French, English and Arabic with citations. 163-question test set and 650+ hand-graded answers: right behaviour in 93% of cases, 100% on emergency and prompt-injection questions. Plus a QLoRA fine-tune of Qwen3-4B on 658 teacher answers, trained on an 8 GB GPU: +6 points of facts found over the base 4B, measured against the 8B ([model on Hugging Face](https://huggingface.co/youssef-khazal/qwen3-4b-demarches-lora)). Chat UI, Docker, tests and CI. |
| [**BirdCLEF+ 2025: bird sound classification**](https://github.com/youssef-khazal/birdclef-2025) | 206 species from audio spectrograms. Five models compared on held-out recordings; best: EfficientNet-B0, 0.96 ROC-AUC. Tests and CI. |
| [**Species classifier: deployed model**](https://github.com/youssef-khazal/birdclef-api) · [live demo](https://huggingface.co/spaces/youssef-khazal/species-sound-classifier) | The BirdCLEF model served in production style: ONNX export (2.3x faster on CPU), FastAPI + Docker API tested in CI, and an in-browser demo (ONNX Runtime Web). |
| [**Facial emotion recognition in videos**](https://github.com/youssef-khazal/dfer-video-ssl) | Four video transformers (VideoMAE, V-JEPA 2) fine-tuned on 16,000 movie clips under one protocol; best: 58.3% UAR / 70.2% accuracy on the test set. With Melissa Fahed. |
| [**Learning to race with deep Q-learning**](https://github.com/youssef-khazal/rl-racing-dqn) | Custom 2D racing game and a DQN agent that beats a rule-based car in 90% of 100 evaluation races. Reward-design study, demo GIF, tests and CI. |

---

#### Tools

- **Daily:** Python · PyTorch · NumPy / pandas · scikit-learn · Jupyter · Git
- **Also used:** torchvision · timm · Hugging Face Transformers · ONNX Runtime · FastAPI · Docker · Ollama · PEFT / LoRA · bitsandbytes · sentence-transformers · TensorFlow / Keras · Gymnasium · librosa · OpenCV · YOLOv8 · GPU cluster jobs (OAR) · SQL (basic) · R (basic) · Java

#### Find me

[LinkedIn](https://www.linkedin.com/in/youssef-khazal) · [Portfolio](https://youssef-khazal.netlify.app/)
