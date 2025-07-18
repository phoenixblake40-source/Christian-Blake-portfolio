# Project Proteus: Autonomous Cyber Defense Dashboard

## A Multi-Layered, Adaptive Security Protocol System

### The Problem

In an era of constantly evolving threats, static cybersecurity defenses are no longer sufficient. Modern systems face an accelerating and dynamic threat landscape that demands an adaptive, intelligent security posture to maintain resilience.

### The Solution

To address this, I designed and developed **Project Proteus**, a multi-layered, adaptive security protocol system. The core of the system is an intelligent defense that uses machine learning to analyze network activity and a blockchain-based ledger to ensure the immutability of all changes. This allows the system to not only react in real-time to threats but also to learn and adapt its own security protocols dynamically.

### The Impact

The result is a self-evolving security system that demonstrates robust threat mitigation. The clear, verifiable output log—a feature I implemented for real-time visibility—provides a transparent audit trail, confirming that the system is fully operational and the integrity of all protocol changes is secure.

---

### **Technologies Used**

* **Python:** The core language for all system logic.
* **Streamlit:** For building the interactive, real-time dashboard.
* **Scikit-learn:** For the AI-driven threat detection model.
* **Numpy:** For numerical operations and data handling.
* **Hashlib:** To create the cryptographic hashes for the blockchain.

### **Getting Started**

#### **Prerequisites**

* Python 3.8+
* Git

#### **Installation**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/project_proteus.git](https://github.com/YourGitHubUsername/project_proteus.git)
    cd project_proteus
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```
3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

#### **Running the Application**

To launch the dashboard, run the following command from the root directory:

```bash
streamlit run src/app.py
