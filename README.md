# ⚛️ Quantum Computing Lab

**by Yasandu Kethmika**

🧠 Learning quantum computing in public - from qubits to real quantum hardware, explained for anyone, built for engineers.

---

## 🗺️ New here? Pick your path

- 🧑‍🎓 **New to quantum?** Start with [`01-fundamentals`](./01-fundamentals) - no prior physics or math background assumed.
- 👩‍💻 **Know how to code, new to quantum?** Same folder - each notebook explains the intuition first, then the circuit, then the code.
- 🔍 **Evaluating my work?** This repo is a work in progress - check the progress table below for what's done.

---

## 💡 Why I'm doing this

I'm a Computer Science undergraduate building toward AI/ML engineering. Quantum computing is my secondary specialization - not a replacement for that path, but a genuine differentiator on top of it. This repo is my public learning log: real notebooks, real results, including the parts that didn't work.

---

## 📊 Progress

| Section | Status | What's covered |
|---|---|---|
| ⚙️ Environment setup | ✅ Done | Qiskit, Qiskit Runtime, IBM Quantum account, local simulator |
| 🧩 Fundamentals | 🚧 In progress | Superposition, measurement, Bell states, entanglement |
| 🧮 Core algorithms | ⬜ Not started | Deutsch-Jozsa, Grover's, Shor's |
| 🔄 NISQ algorithms | ⬜ Not started | VQE, QAOA |
| 🖥️ Hardware experiments | ⬜ Not started | Real QPU runs, noise benchmarking |
| 🚀 Flagship project | ⬜ Not started | Original applied project - TBD |

---

## 📒 What's in here so far

- 📓 [`01-fundamentals/hello_qubit.ipynb`](./01-fundamentals/hello_qubit.ipynb) - my first circuit: a single qubit in superposition, measured 1000 times to show the 50/50 probability distribution

---

## 🛠️ Tech stack

`Qiskit` · `Qiskit Runtime` · `Qiskit Aer` (local simulator) · `IBM Quantum Platform` (real hardware) · `Jupyter`

---

## ▶️ How to run this yourself

```bash
python -m venv .venv
.venv\Scripts\Activate.ps1   # Windows
pip install qiskit qiskit-ibm-runtime qiskit-aer notebook matplotlib pylatexenc
jupyter notebook
```

🔑 You'll also need a free [IBM Quantum Platform](https://quantum.cloud.ibm.com) account if you want to run anything on real hardware - the simulator notebooks work with no account needed.

---

## 📜 License

This project uses a dual license:
- 💻 **Code** (notebook code cells, scripts): [MIT License](./LICENSE) - free to use, modify, and reuse, with attribution.
- ✍️ **Written content** (explanations, notes, documentation): [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) - free to reuse and adapt, with attribution.

---

## 👤 Author

** K A D Yasandu Kethmika**

🎓 B.Sc. Computer Science & Engineering (UG), University of Moratuwa


🔗 GitHub: [@Kethmika2004](https://github.com/Kethmika2004)
