# uml-smart-access-control-system
⋆｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ────── ꒰ ✨ ꒱ ────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡⋆

# ˚₊‧꒰ა ☁️ Smart Access Control & IoT Automation (UML) ☁️ ໒꒱‧₊˚

> ✧･ﾟ: *✧･ﾟ:* Software engineering case study covering requirements elicitation, Use Case modeling, and Class Diagram architecture for a smart corporate building with facial recognition and voice-activated IoT devices. *:･ﾟ✧*:･ﾟ✧

‧₊˚ ⋅ ─────────────────────── ⋅ ˚₊‧

## ꒰ 🦢 ꒱ Project Overview & Requirements

The system automates corporate physical security and room climate/lighting control through biometric authentication and virtual assistants (Alexa / Google Home).

### Functional Requirements (`FR`)
* ₊˚⊹ **FR01 – Facial Recognition:** Automatic door unlocking via facial biometrics.
* ₊˚⊹ **FR02 – Voice Commands:** Control of lights and air conditioning via Alexa or Google Home.
* ₊˚⊹ **FR03 – Biometric Management:** Facial registration and role-based access levels (*Employee* vs. *Manager*).
* ₊˚⊹ **FR04 – Web Admin Panel:** Access management dashboard for HR and Management.
* ₊˚⊹ **FR05 – Energy Saving:** Automatic shut-off of lights and AC via presence sensors.
* ₊˚⊹ **FR06 – Mobile Control:** Remote device management through Android and iOS apps.

### Non-Functional Requirements (`NFR`)
* ₊˚✧ **NFR01 – Performance:** Voice command processing response time under `2 seconds`.
* ₊˚✧ **NFR02 – Hardware Quality:** Security cameras with minimum `1080p (Full HD)` resolution.
* ₊˚✧ **NFR03 – Aesthetics:** Physical sensors following a gray or white color standard.
* ₊˚✧ **NFR04 – Connectivity:** Local network integration between the server and IoT devices.
* ₊˚✧ **NFR05 – Budget:** Total hardware and software implementation capped at `$ 25,000.00`.
* ₊˚✧ **NFR06 – Data Integrity:** Consistent and reliable storage in the access logs database.

‧₊˚ ⋅ ─────────────────────── ⋅ ˚₊‧

## ꒰ 🎀 ꒱ UML Diagrams

### 1. Use Case Diagram
![Use Case Diagram](use-case-diagram.jpg)

### 2. Class Diagram
![Class Diagram](class-diagram.jpg)

‧₊˚ ⋅ ─────────────────────── ⋅ ˚₊‧

## ೃ⁀➷ Core Architecture & Concepts Practiced

* ₊˚⊹ **Object-Oriented Modeling:** Inheritance (`Employee` → `Manager`), composition, and association between `AccessControl`, `Door`, `FacialRecognition`, `VirtualAssistant`, `Lighting`, and `AirConditioning`.
* ₊˚⊹ **Requirements Engineering:** Classification of functional behaviors vs. quality/system constraints.
* ₊˚⊹ **UML Notation:** Actors, `<<include>>` / `<<extend>>` relationships, visibility modifiers (`+`, `-`), data types, and method signatures.

°•. ✿ .•° ────── ꒰ 🎀 ꒱ ────── °•. ✿ .•°

*made with 💗 by **Maria Eduarda Gonçalves***
