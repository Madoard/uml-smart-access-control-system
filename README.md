<div align="center">

  <p>｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ──────────── ꒰ 🔐 ꒱ ──────────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡ﾟ</p>

  <h1>˚₊‧꒰ა ☁️ Controle de Acesso Inteligente & Automação IoT (UML) ☁️ ໒꒱‧₊˚</h1>

  <p>
    <i>✧･ﾟ: *✧･ﾟ:* Estudo de caso de engenharia de software cobrindo elicitação de requisitos, modelagem de Casos de Uso e arquitetura de Diagrama de Classes para um prédio corporativo inteligente com reconhecimento facial e dispositivos IoT ativados por voz *:･ﾟ✧*:･ﾟ✧</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/UML-Modelagem%20de%20Software-FFB7C5?style=for-the-badge&logoColor=white" alt="Modelagem UML" />
    <img src="https://img.shields.io/badge/Diagramas-Casos%20de%20Uso%20%7C%20Classes-E6E6FA?style=for-the-badge&logoColor=555555" alt="Diagramas" />
    <img src="https://img.shields.io/badge/Dom%C3%ADnio-Seguran%C3%A7a%20IoT%20Inteligente-FFD1DC?style=for-the-badge&logoColor=white" alt="Segurança IoT Inteligente" />
  </p>

</div>

<br/>

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪄 ꒱ Visão Geral do Projeto & Requisitos

O sistema automatiza a segurança física corporativa e o controle de iluminação/climatização de ambientes por meio de autenticação biométrica e assistentes virtuais (**Alexa** / **Google Home**).

#### Requisitos Funcionais (`RF`)
- **₊˚💡 RF01 – Reconhecimento Facial:** Destravamento automático de portas via biometria facial.
- **₊˚💡 RF02 – Comandos de Voz:** Controle de luzes e ar-condicionado via Alexa ou Google Home.
- **₊˚💡 RF03 – Gestão Biométrica:** Cadastro facial e níveis de acesso baseados em papel (*Funcionário* vs. *Gestor*).
- **₊˚💡 RF04 – Painel Web Admin:** Dashboard de gerenciamento de acessos para o RH e a Gestão.
- **₊˚💡 RF05 – Economia de Energia:** Desligamento automático de luzes e ar-condicionado via sensores de presença.
- **₊˚💡 RF06 – Controle Mobile:** Gerenciamento remoto de dispositivos por aplicativos Android e iOS.

#### Requisitos Não Funcionais (`RNF`)
- **₊˚🛰️ RNF01 – Desempenho:** Tempo de resposta no processamento de comandos de voz inferior a `2 segundos`.
- **₊˚🛰️ RNF02 – Qualidade de Hardware:** Câmeras de segurança com resolução mínima `1080p (Full HD)`.
- **₊˚🛰️ RNF03 – Estética:** Sensores físicos seguindo um padrão de cor cinza ou branco.
- **₊˚🛰️ RNF04 – Conectividade:** Integração em rede local entre o servidor e os dispositivos IoT.
- **₊˚🛰️ RNF05 – Orçamento:** Implementação total de hardware e software limitada a `$ 25,000.00`.
- **₊˚🛰️ RNF06 – Integridade de Dados:** Armazenamento consistente e confiável no banco de dados de logs de acesso.

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 💎 ꒱ Diagramas UML

#### 1. Diagrama de Casos de Uso
![Diagrama de Casos de Uso](use-case-diagram.jpg)

#### 2. Diagrama de Classes
![Diagrama de Classes](class-diagram.jpg)

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🗝️ ꒱ Como Foi Construído

- **₊˚☁️ Modelagem Orientada a Objetos:** Estruturação de herança (`Funcionário` → `Gestor`), composição e associações entre `AccessControl`, `Door`, `FacialRecognition`, `VirtualAssistant`, `Lighting` e `AirConditioning`.
- **₊˚🔐 Engenharia de Requisitos:** Classificação dos comportamentos funcionais do sistema separada das restrições de hardware, rede, desempenho e orçamento.
- **₊˚☁️ Notação UML:** Aplicação de atores, relacionamentos `<<include>>` / `<<extend>>`, modificadores de visibilidade (`+`, `-`), atributos tipados e assinaturas de métodos.

<br/>

<div align="center">
  <p>°•. ☁️ .•° ────── ꒰ 💗 ꒱ ────── °•. ☁️ .•°</p>
  <p><i>feito com 💗 por <b>Maria Eduarda Gonçalves</b></i></p>
</div>
