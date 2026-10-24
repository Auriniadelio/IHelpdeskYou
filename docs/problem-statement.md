# Problem Statement

## Who is affected?
Corporate employees, and non-technical staff & person across organizations serve as the primary targets of social engineering attacks (Ambre et al., 2025; Patil et al., 2026)

## What exactly is going wrong?
Human error remains the primary vulnerability exploited by cybercriminals through psychological manipulation tactics such as artificial urgency, fake authority, and panic, across email, smishing, and vishing channels, contributing to **60% to 68% of all organizational data breaches globally** (Andersen, 2025; Khalil, 2025; Patil et al., 2026)[2]. Traditional cybersecurity awareness training relies on passive learning formats (e.g., static slides, annual compliance videos, and periodic quizzes) that fail to engage users, creating an **"awareness-action gap"** where employees cannot translate theoretical security rules into practical threat detection habits under live pressure (Ambre et al., 2025; Khalil, 2025; Patil et al., 2026)

## Why does it matter?
Social engineering is the leading mechanism behind cyber theft and data compromise, generating severe financial damage, with global data breach costs averaging **$4.88 million per incident**—alongside critical operational downtime, loss of sensitive records, and organizational reputational damage (Andersen, 2025; Khalil, 2025)

## Problem statement (3 to 5 sentences)
Corporate employees and non-technical personnel remain highly vulnerable to sophisticated social engineering attacks that exploit cognitive biases through psychological manipulation tactics such as artificial urgency, panic, and fake authority across email, smishing, and vishing channels (Andersen, 2025; Khalil, 2025; Patil et al., 2026)[4]. As a result, human error contributes to **60% to 68% of global data breaches**, incurring average breach costs exceeding $4.88 million alongside significant operational disruptions (Andersen, 2025; Khalil, 2025; Patil et al., 2026)[2]. Traditional cybersecurity training programs rely on passive slides and annual compliance videos, creating a critical **"awareness-action gap"** that fails to equip users with practical decision-making skills under live pressure (Ambre et al., 2025; Khalil, 2025; Patil et al., 2026)[6]. Without immersive, scenario-based learning—such as a narrative-driven helpdesk simulation governed by an **Event-Driven Finite State Machine (FSM)** organizations remain unable to foster the active threat detection habits necessary to prevent costly compromises (Ambre et al., 2025; Barri et al., 2026; Patil et al., 2026; Yason et al., 2025)

## Evidence

### **1. Human Error as the Primary Attack Vector and Financial Cost**
> *"The 2024 Verizon Data Breach Investigations Report said that people making mistakes contributed to 68% of all data breaches."*  
> — **Patil et al. (2026)**

> *"The cornerstone statistic from the Verizon 2025 Data Breach Investigations Report (DBIR) is that the human element was a factor in approximately 60% of breaches."*  
> — **Khalil (2025)**

> *"The global average cost of a data breach has hit an all time high of \$4.88 million in 2024, a clear indicator of the escalating damage."*  
> — **Khalil (2025)**

> *"Coalition's 2026 Cyber Claims Report found that 71% of funds transfer fraud (FTF) claims, in which an attacker redirects a legitimate payment to a fraudulent account, involved social engineering as the primary attack vector with average losses of \$127,00 per incident."*  
> — **Andersen (2025)**

---

### **2. Exploitation of Human Psychology and Multi-Vector Scams**
> *"Rather than taking advantage of system vulnerabilities, semantic attacks take advantage of the way humans interact with computers or interpret messages, exploiting differences between the system model and the user model."*  
> — **Sheng et al. (2007)**

> *"Attackers are amateur psychologists who exploit predictable cognitive biases to bypass our rational thought processes. They rely on a few key triggers: Fear and Urgency... Authority and Trust... Curiosity and Greed..."*  
> — **Khalil (2025)**

> *"Voice Phishing (Vishing): This vector has seen explosive growth. Detection of vishing attacks surged by 442% between the first and second halves of 2024."*  
> — **Khalil (2025)**

---

### **3. Ineffectiveness of Traditional Training (The "Awareness-Action Gap")**
> *"Contemporary methods of cybersecurity education, including classroom teaching, static tutorials, and education campaigns, usually consist of theoretical knowledge and do not provide an adequate opportunity for hands-on learning... leaving learners with insufficient opportunities to apply theoretical concepts into actual defensive measures against cyberattacks."*  
> — **Ambre et al. (2025)**

> *"Organizations invest heavily in security awareness training, yet breaches continue. This points to a profound 'awareness action gap'. Many employees know an action is risky but do it anyway for convenience or to save time."*  
> — **Khalil (2025)**

> *"The systematic literature review by Khando et al. on the subject of information security awareness among both the private and the public organizations gave a conclusion that passive formats do not tackle the affective aspect of security behaviour change."*  
> — **Patil et al. (2026)**

---

### **4. Technical & Pedagogical Justification for Game Simulations and FSM Logic**
> *"Research in learning science has established that interactive environments, in particular games, are one of the most effective training methods and are highly motivational for users, especially when they adhere to design principles for educational games."*  
> — **Sheng et al. (2007)**

> *"By familiarizing the users with a simulated attack experience similar to the real environment, the process efficiently increases the awareness levels and retention rates for the knowledge related to cybersecurity."*  
> — **Ambre et al. (2025)**

> *"Using a Design and Development (D&D) framework, the system was implemented... through an Event-Driven Finite State Machine (FSM) architecture that manages dialogue progression and environmental transitions... The results demonstrate the technical feasibility of implementing a failure-free interaction model while maintaining logical narrative progression and gameplay continuity."*  
> — **Barri et al. (2026)**

---

### User and Stakeholders

---

#### **Users and Stakeholders**
* **Primary Target Users:**
  * **Corporate Employees & Non-Technical Personnel:** Staff members across organizational departments (such as Finance, Human Resources, and General Operations) who are frequently targeted by human-centric social engineering attacks.
* **Key Stakeholders:**
  * **Organizational IT & Cybersecurity Teams:** Administrators seeking to lower organizational vulnerability, prevent data breaches, and foster an active security culture.
  * **Training Managers & Security Officers:** Instructional designers and compliance officers who require measurable tracking data on employee threat evaluation capabilities to meet regulatory standards.
  * **Executive Leadership:** Senior management wanting to in reducing financial losses associated with business email compromise and funds transfer fraud.

---

#### **In-Scope Project Elements**
* **Simulated Threat Vectors & Attack Typologies:**
  * **Email Phishing & Impersonation:** Evaluating deceptive email tickets containing lookalike domains, spoofed authentication headers (`SPF`/`DKIM`/`DMARC`), credential harvesting links, and malicious file attachments.
  * **Multi-Channel Scams (Smishing & Vishing):** Navigating incoming mobile SMS alerts and interactive audio vishing phone calls that simulate executive or IT helpdesk impersonation.
* **Core Gameplay Mechanics & Interface Modules:**
  * **Workstation Ticket Console & Virtual Smartphone:** Inspecting ticket artifacts, checking internal directory sticky notes, and interacting with smartphone pop-up alerts.
  * **Out-of-Band Secondary Verification:** Practicing secondary-channel verification via internal phone extensions prior to executing high-risk actions.
  * **Indicator-Level Feedback Subsystem:** Reviewing post-scenario debrief panels that highlight exact red flags, explain psychological manipulation principles, and guide corrective behavior without rigid failure states [94, 218, 273, 291–293].
* **Technical System Architecture:**
  * **Event-Driven Finite State Machine (FSM):** Implementing a state-driven logic engine in an interactive game engine (such as Unity or Ren'Py) to systematically govern gameplay state transitions across workstation, mobile, and feedback phases.

#### **Out-of-Scope Project Elements**
* **Offensive Exploit & Malware Development:** Active creation of weaponized malware binaries, reverse engineering of real-world payloads, buffer overflow exploits, or live network packet sniffing.
* **Physical Hardware & Virtual Reality (VR) Equipment:** Physical escape-room lockboxes, IoT wearable sensors, or dedicated VR headsets; the simulation is designed specifically for standard desktop and web browser environments to minimize hardware dependency.
To summarize : Anything to technical. The project is focused on basic awareness of cyber literacy rather than developing them as an offensive/defensive cyber professional

### References

* **Ambre, D. A., Marale, A. A., Narkhede, A. V., Jogdand, S., & Salunke, R. D. (2025).** CyberScape: A gamified simulation-based approach for practical cybersecurity awareness and education. *International Journal of Advanced Research in Science, Communication and Technology*, 5(5), 76–83.
* **Andersen, G. (2025, February 13).** *The psychology of social engineering*. Coalition Security Labs.
* **Barri, M. A. F., Sodikin, R. A., Majid, N. W. A., & Sari, A. P. (2026).** Beyond 'Game Over': Engineering a failure-free FSM architecture for emotion regulation in serious games. *Indonesian Journal of Informatics Education*, 10(1), 1–12.
* **Khalil, M. (2025, September 7).** *Social engineering statistics 2025: The human hack*. DeepStrike.
* **Patil, P. V., Sanika, K. S., Sree, N. N., & M, P. (2026).** Gamified phishing awareness training platform for corporate employees using Unity. *International Journal of Creative and Open Research in Engineering and Management*, 2(4), 1–10.
* **Sheng, S., Magnien, B., Kumaraguru, P., Acquisti, A., Cranor, L. F., Hong, J., & Nunge, E. (2007).** Anti-Phishing Phil: The design and evaluation of a game that teaches people not to fall for phish. In *Proceedings of the 3rd Symposium on Usable Privacy and Security (SOUPS)* (pp. 88–99). ACM.

