# Am_Ai
Am Ai the first ai that has willpower and full Autonomy power

### **Am Ai - AI with Human-like Decision Making**

This project implements an advanced **Autonomous AI Assistant** designed to simulate human-like autonomy in decision-making, task execution, and emotional understanding. The assistant is built with Python, incorporating natural language processing, speech synthesis, memory management, and a novel framework for independent task prioritization.

---

### **Key Features**

1. **Speech Recognition and Text-to-Speech**  
   - Converts speech to text using `speech_recognition` and provides responses with a natural tone using `pyttsx3`.

2. **Emotion Management**  
   - Simulates human-like emotions (e.g., happy, calm, curious).  
   - Dynamically adjusts emotions based on interaction context.  
   - Maintains a power system, emulating the assistant's energy levels.

3. **Memory System**  
   - Stores and recalls user interactions, preferences, and known faces.  
   - Persists memory across sessions using a file-based system.

4. **Decision-Making Framework**  
   - Evaluates options with a weighted memory model for improved decision accuracy.  
   - Learns from feedback to refine future decisions.  
   - Makes probabilistic or memory-informed decisions autonomously.

5. **Autonomous Task Execution**  
   - Continuously analyzes its environment and prioritizes tasks independently.  
   - Executes decisions without user intervention, mimicking self-driven behavior.

6. **Multithreaded Performance**  
   - Supports concurrent autonomous task execution while actively interacting with the user.

---

### **How It Works**

- **Interaction:** The assistant listens to user commands, evaluates contexts, and responds intelligently.  
- **Autonomy:** In the absence of user commands, it performs predefined tasks autonomously, based on priorities derived from its decision-making engine.  
- **Learning:** Feedback mechanisms improve the assistant’s long-term effectiveness and adaptability.  

---

### **Technologies Used**

- **Python Libraries:**  
  - `speech_recognition`: For real-time speech-to-text processing.  
  - `pyttsx3`: For converting text responses into speech.  
  - `threading`: For multitasking.  
  - `json`: To store and retrieve decision memory.

- **File Management:**  
  - Memory is persisted using JSON and text files to ensure the assistant "remembers" data across sessions.

---

### **Possible Applications**

- Personal AI assistants for productivity and scheduling.  
- Autonomous AI agents for simulations or gaming.  
- Educational tools for teaching AI decision-making and autonomy.

---

### **How to Use**

1. Install the required dependencies from `requirements.txt`.  
2. Run the program using Python.  
3. Interact with the assistant using voice commands or let it perform autonomous tasks.  

