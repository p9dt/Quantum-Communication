# 🔐 Quantum Communication

A collection of Quantum Key Distribution (QKD) protocols implemented using Python and PennyLane. This repository simulates secure communication between two parties (Alice and Bob) using quantum principles such as superposition, measurement, and entanglement.

> 💡 Built with ❤️ for researchers, students, and enthusiasts of quantum computing and cryptography.

---

## 🧪 Implemented Protocols

### ✅ BB84 Protocol
📁 Path: `QKD/BB84_QKD.ipynb`

- Based on polarization states and random basis selection.
- Simulates key generation and eavesdropping detection.
- Includes XOR encryption of a secret message.
- 📽️ Animated visualization of key exchange (`bb84_animation.gif`)

### 🔗 E91 Protocol
📁 Path: `QKD/E91_QKD.ipynb`

- Based on quantum entanglement and Bell inequalities.
- Simulates key generation from correlated entangled pairs.
- Detects eavesdropping via violation of Bell’s inequality.
- 📽️ Animated visualization of key exchange (`e91_animation.gif`)

---

## 📦 Dependencies

Make sure you have the following Python packages installed:

```bash
pennylane
matplotlib
numpy
tqdm
imageio
IPython
You can install all required packages using:

bash
Copy
Edit
pip install -r requirements.txt
Or just install directly in Google Colab:

python
Copy
Edit
!pip install pennylane imageio matplotlib tqdm
🚀 Run the Code
Option 1: Local Setup
bash
Copy
Edit
git clone https://github.com/your-username/Quantum-Communication.git
cd Quantum-Communication/QKD/BB84_QKD
jupyter notebook BB84_QKD.ipynb
Option 2: Google Colab
Just upload the .ipynb file to Google Colab and run the cells.

📸 Visual Demos
BB84 Protocol

E91 Protocol

🎯 Goals
📚 Educational demos for understanding QKD protocols
🧠 Learn about quantum key distribution with hands-on code
🕵️ Simulate and detect eavesdropping attacks
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

