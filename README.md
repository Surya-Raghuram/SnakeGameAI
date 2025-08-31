# Snake AI Game

A reinforcement learning agent that learns to play Snake using **Deep Q-Learning** inside a single Jupyter Notebook.

---

## 🚀 Features
- Snake game built with `pygame`
- DQN agent with replay memory + target training
- Reward shaping:
  - +10 for eating food
  - -10 for dying
  - -0.1 step penalty
  - +1 closer to food, -1 farther
- Model uses:
   - Adam optimizer
   - Bellman function( Mean square loss)

---

## ⚙️ Setup
```bash
git clone https://github.com/Surya-Raghuram/SnakeGameAI.git
cd SnakeGameAI
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

Training

Run the notebook cells to train the agent.
Trained models are saved as model.pth.
(One pretrained model for 300 loops is included. ->Model)

<img width="630" height="470" alt="image" src="" />

    The training graph of the pretrained model attached
