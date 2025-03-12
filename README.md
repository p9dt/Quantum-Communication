# 🔐 Quantum Communication

A collection of Quantum Key Distribution (QKD) protocols implemented using Python and PennyLane. This repository simulates secure communication between two parties (Alice and Bob) using quantum principles such as superposition, measurement, and entanglement.

> 💡 Built with ❤️ for researchers, students, and enthusiasts of quantum computing and cryptography.

---

## 🧪 Implemented Protocols

### ✅ BB84 Protocol  
📁 Path: `QKD/BB84_QKD.ipynb`

- Based on polarization states and random basis selection  
- Simulates key generation and eavesdropping detection  
- Includes XOR encryption of a secret message  
- 📽️ Animated visualization of key exchange (`bb84_animation.gif`)

---

### 🔗 E91 Protocol  
📁 Path: `QKD/E91_QKD.ipynb`

- Based on quantum entanglement and Bell inequalities  
- Simulates key generation from correlated entangled pairs  
- Detects eavesdropping via violation of Bell’s inequality  
- 📽️ Animated visualization of key exchange (`e91_animation.gif`)

---

## 💬 Quantum Chat App (BB84 Real-Time Simulation)
📁 Path: `QKD/Quantum_Chat_App.ipynb`

- Interactive chat-style simulation between Alice and Bob  
- Uses the BB84 protocol to establish a secure key  
- XOR-based encryption/decryption of user messages  
- Built with Streamlit for real-time visual feedback  
- Perfect for education, demos, and hands-on QKD understanding  
- 🎥 Includes optional circuit/key visualization

---

## 📦 Dependencies

Make sure you have the following Python packages installed:

```bash
pip install pennylane matplotlib numpy tqdm imageio IPython streamlit
Or install them directly in Google Colab:

python
Copy
Edit
!pip install pennylane imageio matplotlib tqdm streamlit
🚀 Run the Code
Option 1: Local Setup
bash
Copy
Edit
git clone https://github.com/your-username/Quantum-Communication.git
cd Quantum-Communication/QKD/BB84_QKD
jupyter notebook BB84_QKD.ipynb
Option 2: Google Colab
Upload the .ipynb files to Google Colab
Run all cells interactively — no local setup needed
📸 Visual Demos
BB84 Protocol

E91 Protocol

🎯 Goals
📚 Educational demos for understanding QKD protocols
🧠 Learn about quantum key distribution with hands-on code
🕵️ Simulate and detect eavesdropping attacks
💬 Build real-time QKD-based quantum chat
🧪 Integrate QKD principles with simple encryption schemes (XOR)
🛡️ Upcoming Additions
📦 B92 Protocol
⚛️ Device-independent QKD
🌐 Quantum teleportation-based communication
📊 Comparative analysis of QKD protocols
📃 License
This project is licensed under the MIT License.
Feel free to use, modify, and share!

👨‍💻 Author
Developed by Mayank Sharma & Bidipta Saha
B.Tech in Engineering Physics, IIT Dharwad

📫 Reach out on GitHub or LinkedIn to connect or collaborate.

⭐ Star This Repo!
If you like the project, give it a ⭐ on GitHub and share it with your quantum-curious friends and classmates!
