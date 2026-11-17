<div align="center">

  <p>｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ──────────── ꒰ 🔐 ꒱ ──────────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡ﾟ</p>

  <h1>˚₊‧꒰ა ☁️ Smart Access Control & IoT Automation (UML) ☁️ ໒꒱‧₊˚</h1>

  <p>
    <i>✧･ﾟ: *✧･ﾟ:* Software engineering case study covering requirements elicitation, Use Case modeling, and Class Diagram architecture for a smart corporate building with facial recognition and voice-activated IoT devices *:･ﾟ✧*:･ﾟ✧</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/UML-Software%20Modeling-FFB7C5?style=for-the-badge&logoColor=white" alt="UML Modeling" />
    <img src="https://img.shields.io/badge/Diagrams-Use%20Case%20%7C%20Class-E6E6FA?style=for-the-badge&logoColor=555555" alt="Diagrams" />
    <img src="https://img.shields.io/badge/Domain-Smart%20IoT%20Security-FFD1DC?style=for-the-badge&logoColor=white" alt="Smart IoT Security" />
  </p>

</div>

<br/>

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪄 ꒱ Project Overview & Requirements

The system automates corporate physical security and room climate/lighting control through biometric authentication and virtual assistants (**Alexa** / **Google Home**).

#### Functional Requirements (`FR`)
* **₊˚💡 FR01 – Facial Recognition:** Automatic door unlocking via facial biometrics.
* **₊˚💡 FR02 – Voice Commands:** Control of lights and air conditioning via Alexa or Google Home.
* **₊˚💡 FR03 – Biometric Management:** Facial registration and role-based access levels (*Employee* vs. *Manager*).
* **₊˚💡 FR04 – Web Admin Panel:** Access management dashboard for HR and Management.
* **₊˚💡 FR05 – Energy Saving:** Automatic shut-off of lights and AC via presence sensors.
* **₊˚💡 FR06 – Mobile Control:** Remote device management through Android and iOS apps.

#### Non-Functional Requirements (`NFR`)
* **₊˚🛰️ NFR01 – Performance:** Voice command processing response time under `2 seconds`.
* **₊˚🛰️ NFR02 – Hardware Quality:** Security cameras with minimum `1080p (Full HD)` resolution.
* **₊˚🛰️ NFR03 – Aesthetics:** Physical sensors following a gray or white color standard.
* **₊˚🛰️ NFR04 – Connectivity:** Local network integration between the server and IoT devices.
* **₊˚🛰️ NFR05 – Budget:** Total hardware and software implementation capped at `$ 25,000.00`.
* **₊˚🛰️ NFR06 – Data Integrity:** Consistent and reliable storage in the access logs database.

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 💎 ꒱ UML Diagrams

#### 1. Use Case Diagram
![Use Case Diagram](use-case-diagram.jpg)

#### 2. Class Diagram
![Class Diagram](class-diagram.jpg)

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🗝️ ꒱ How It Was Built

* **₊˚☁️ Object-Oriented Modeling:** Structured inheritance (`Employee` → `Manager`), composition, and associations across `AccessControl`, `Door`, `FacialRecognition`, `VirtualAssistant`, `Lighting`, and `AirConditioning`.
* **₊˚🔐 Requirements Engineering:** Classified functional system behaviors separately from hardware, network, performance, and budget constraints.
* **₊˚☁️ UML Notation:** Applied actors, `<<include>>` / `<<extend>>` relationships, visibility modifiers (`+`, `-`), typed attributes, and method signatures.

<br/>

<div align="center">
  <p>°•. ☁️ .•° ────── ꒰ 💗 ꒱ ────── °•. ☁️ .•°</p>
  <p><i>made with 💗 by <b>Maria Eduarda Gonçalves</b></i></p>
</div>
