# 🏆 CAARE 2026: Hackathon Technical Requirements Checklist

Har Quarter ka Hackathon aik naye level ki requirements mangta hai. Agar aap ye requirements puri kar lete hain, to aap ko **Full Marks** aur **Bonus Points** milne se koi nahi rok sakta.

---

### 📘 Quarter 1: The Intelligent Textbook
* **Core Requirement:** Ek functional Docusaurus website jo GitHub Pages par live ho.
* **RAG System:** Aik chatbot jo sirf aapki book ke content se jawab de (Qdrant ya local vector store use karein).
* **Spec-Driven:** Aapke project mein `.spec-kit` folder aur `spec.md` file ka hona lazmi hai.
* **Bonus (50-150 pts):** Urdu translation button, Better-Auth login survey, aur Claude Subagents ka istemal.



---

### 🧠 Quarter 2: The Agentic Challenge
* **Core Requirement:** Ek aisa AI Agent jo "Self-Correction" kar sake (LangGraph use karein).
* **Tool Calling:** Agent ke paas kam az kam 2 tools hon (e.g., Internet Search aur Database write).
* **Type Safety:** Poora code **Pydantic V2** aur Python Type Hints ke saath hona chahiye.
* **Bonus (50 pts):** Agar aapka agent complex multi-step tasks (jaise poori research report likhna) khud kar sake.

---

### 🦾 Quarter 3: The Physical AI Challenge
* **Core Requirement:** NVIDIA Isaac Sim ya Gazebo mein ek simulated robot ka task (e.g., Obstacle Avoidance).
* **ROS 2 Integration:** Robot ko control karne ke liye ROS 2 nodes aur topics ka istemal.
* **Computer Vision:** Camera ke zariye objects ko detect karna (YOLO integration).
* **Bonus (50 pts):** Simulation mein robot ko Urdu voice commands se control karna.



---

### 🕺 Quarter 4: The Humanoid Brain
* **Core Requirement:** Ek Humanoid robot (simulation) ka balance maintain karna aur "Walking" demonstrate karna.
* **VLA Model:** Vision-Language-Action model ka istemal (e.g., "Pick the red ball" kehne par robot action le).
* **Sim-to-Real:** Proof dena ke aapka code real hardware (Jetson) par chalne ke qabil hai.
* **Bonus (50 pts):** Robot ko "Imitation Learning" ke zariye koi naya insani kaam sikhana.

---

### 🌐 Quarter 5: The Fleet Master
* **Core Requirement:** Kam az kam 3-5 robots ko ek sath cloud se manage karna.
* **Infrastructure:** Kubernetes (K8s) ya Docker Swarm ka istemal deployment ke liye.
* **Monitoring:** Ek live dashboard (Grafana) jahan saare robots ki health dikh rahi ho.
* **Bonus (50 pts):** "Self-Healing" system (agar ek robot fail ho to cloud dusre ko task assign kar de).



---

### 🚀 Quarter 6: The Grand Capstone
* **Core Requirement:** Ek End-to-End Production ready product jo kisi real problem ko solve kare.
* **Optimization:** AI models ko **TensorRT** ke zariye optimize karna (Latency < 50ms).
* **Documentation:** Mukammal technical manual aur user guide.
* **Bonus (100 pts):** Aik mukammal Startup Pitch aur business model (BOM, Pricing, Scaling plan).

---

### 🛡️ Common Requirements (Mandatory for All)
1.  **Governess Check:** Har project `npx spec-kit-plus govern check` pass karna chahiye.
2.  **Open Source:** Code GitHub par public hona chahiye (Professional README ke saath).
3.  **Demo Video:** Aik 2-3 minute ki video jo poore project ka flow dikhaye.

---

**Tip for Students:** Har Quarter ka project aapka "Job Portfolio" hai. Isse sirf pass hone ke liye nahi, balkay duniya ko dikhane ke liye banayein!
