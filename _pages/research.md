---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## **Research Focus**

In the **Noisy Intermediate-Scale Quantum (NISQ)** era, quantum systems face unprecedented challenges arising from their inherent state complexity (e.g., quantum superposition and entanglement), noise unpredictability, and measurement uncertainties. My research systematically addresses these critical issues by developing **formal method theories, algorithms, and tools** to ensure that quantum systems operate **reliably**, **securely**, and **efficiently**.

By extending **formal methods** — a branch of computer science celebrated with multiple Turing Awards — to the quantum domain, I bridge the gap between quantum theory and real-world applications, providing a foundation for **trustworthy quantum systems**. Specifically, my contributions are organized into three interconnected areas: **quantum system correctness, robust and privacy-preserving quantum algorithms**, and **quantum-accelerated formal verification**, culminating in the development of **[VeriQ](https://www.veri-q.com)**, the world’s first comprehensive toolchain for trustworthy quantum computing.

---

## **Research Contributions**

### **1. Correctness of Quantum Systems**
Ensuring the correctness of quantum systems (protocols, algorithms, programs) is fundamental but complex due to the continuous nature of quantum states. My key contributions include:
- Introducing **Quantum Markov Chains** as a formal model for quantum system evolution.
- Developing **3-level decomposition techniques** (coherence, irreducibility, periodicity) for analyzing **reachability problems**.
- Proposing **quantum temporal logics** to specify dynamic correctness properties.
- Designing automated **model-checking algorithms** for system verification.

**Applications**: Validated quantum communication protocols and quantum algorithms.  

**Key Publications**:  *CAV 2024*,*SIAM Journal on Computing 2021*,*CONCUR 2021*,*TACAS 2022*,*ITCS 2020*,*QIC 2018*,*JCSS 2018*.  

*These results are featured prominently in the monograph* **Model Checking Quantum Systems: Principles and Algorithms** *(Cambridge University Press).*

---

### **2. Robust and Privacy-Preserving Quantum Algorithms**
Quantum machine learning algorithms are highly susceptible to noise and privacy risks. I developed a formal framework to define and verify:
- **Local robustness**, **global robustness**, and **differential privacy** for quantum algorithms.
- Designed quantum (machine learning) algorithm models that are both **noise-resistant** and **privacy-preserving**.

**Key Publications**: *CAV 2021, 2022*, *ACM CCS 2023*  

*These works were recognized as the "first step in the field" and were included in the German Federal Office for Information Security (BSI) quantum security report.*

---

### **3. Quantum-Accelerated Formal Verification**
To address the computational limitations of classical verification methods, I developed:
- **Polynomial-time quantum algorithms** for fidelity estimation using techniques like **block encoding** and **quantum amplitude estimation**.
- Algorithms to compute key quantum information metrics: **trace distance** and **entropy**.
- The **first quantum algorithm** for solving reachability problems in quantum systems, achieving **exponential speedup**.

**Key Publications**: *IEEE TIT 2023, 2024*, *QIC 2021*  

---

### **4. VeriQ Toolchain: Trustworthy Quantum Computing**
I co-led the development of **VeriQ**, the first comprehensive toolchain for trustworthy quantum computing. VeriQ offers:
- **Quantum Design Automation (QDA)** for quantum chip optimization.
- **Quantum Program Verification and Analysis** to ensure algorithm correctness.
- **Trustworthy Quantum Machine Learning** for robustness and privacy assessment.

**Achievements**:  
- **Key Publications**:  **FM 2024** and **DATE 2024**.
- Released **10 tools**, successfully deployed on **Zuchongzhi 2.0** superconducting quantum processor.  
- **3 national invention patents** secured.  

**More details**: [https://www.veri-q.com](https://www.veri-q.com)

---

## **Future Research Directions**
1. **Quantum Algorithms on NISQ Devices**  
   - Optimize and implement quantum machine learning algorithms for applications like:  
     - High-dimensional data classification  
     - Quantum state discrimination  
     - Entanglement detection  
   - Validate experimentally on real quantum hardware to demonstrate **quantum advantage**.

2. **Formal Verification Techniques**  
   - Tackle key problems such as **termination analysis** and **automatic invariant generation** to ensure program correctness and reliability.

3. **Quantum Circuit Optimization**  
   - Develop tools for transpilation, synthesis, and optimization of dynamic quantum circuits:  
     - **Circuit depth reduction**  
     - **Noise mitigation**  
     - **Hardware-specific optimization**

These efforts will further enhance the **VeriQ** toolchain, transforming it into a leading platform for **end-to-end trustworthy quantum computing** and bridging the gap between theoretical advancements and practical quantum systems.

---
