# 🛡️ Ransomware and Keylogger Shield

Projeto educacional desenvolvido em **Python** para simular o funcionamento de dois tipos comuns de malware em um **ambiente controlado**:

- 🔐 Ransomware (criptografia de arquivos)
- ⌨️ Keylogger (captura de teclas)

O objetivo deste projeto é **entender como essas ameaças funcionam na prática** e principalmente aprender **como detectá-las e se proteger delas**.

⚠️ **Aviso:**  
Este projeto foi criado **exclusivamente para fins educacionais e de estudo em cibersegurança**.  
Os scripts devem ser executados **apenas em ambientes de laboratório ou máquinas virtuais**.

---

# 🎯 Objetivos de Aprendizagem

Durante o desenvolvimento deste projeto foi possível:

- Compreender o funcionamento básico de **Ransomware**
- Entender como funciona a captura de dados de um **Keylogger**
- Praticar programação em **Python aplicada à segurança**
- Estudar **técnicas de defesa contra malware**
- Utilizar **GitHub como portfólio técnico**

---

# 🧪 Estrutura do Projeto

```
Ransomware_and_Keylogger_Shield
│
├── ransomware.py
├── decrypt.py
├── keylogger.py
├── log.txt
└── README.md
```

---

# 🔐 Ransomware Simulado

O script de ransomware desenvolvido neste projeto simula o comportamento de um malware que **criptografa arquivos e exige resgate para recuperação**.

## Funcionamento

1. Seleciona arquivos de teste
2. Utiliza criptografia para **criptografar os arquivos**
3. Simula uma mensagem de resgate
4. Possui um script separado para **descriptografar os arquivos**

## Biblioteca utilizada

- `cryptography`
- `Fernet`

Essas bibliotecas permitem realizar **criptografia simétrica**, técnica utilizada por diversos ransomwares reais.

---

# ⌨️ Keylogger Simulado

O keylogger criado neste projeto registra **teclas pressionadas no teclado** e salva as informações em um arquivo `.txt`.

## Funcionamento

O script:

- Monitora o teclado
- Registra teclas digitadas
- Salva os dados em `log.txt`
- Trata teclas especiais como:
  - espaço
  - enter
  - tab
  - backspace

## Biblioteca utilizada

- `pynput`

Essa biblioteca permite monitorar **eventos de teclado e mouse no sistema operacional**.

---

# 🛡️ Estratégias de Defesa Contra Malware

Durante o estudo deste projeto foram analisadas algumas medidas importantes de proteção:

### 🔹 Antivírus e EDR
Ferramentas de segurança podem detectar **comportamentos suspeitos** como captura de teclado ou criptografia em massa de arquivos.

### 🔹 Firewall
Bloqueia comunicações suspeitas entre malwares e servidores externos.

### 🔹 Sandbox / Máquina Virtual
Executar arquivos desconhecidos em ambientes isolados evita comprometer o sistema principal.

### 🔹 Conscientização do Usuário
Muitos ataques acontecem por:

- downloads maliciosos
- anexos de e-mail
- engenharia social

Treinamento de usuários é uma das **melhores defesas contra ataques**.

---

# 💻 Tecnologias Utilizadas

- Python
- cryptography
- pynput

---

# 🚀 Como Executar o Projeto

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/GuiMRDS/Ransomware_and_Keylogger_Shield.git
```

## 2️⃣ Instalar dependências

```bash
pip install cryptography
pip install pynput
```

## 3️⃣ Executar os scripts

Exemplo:

```bash
python keylogger.py
```

ou

```bash
python ransomware.py
```

⚠️ Execute apenas em **ambiente de testes**.

---

# 📖 Aprendizados

Este projeto permitiu compreender na prática:

- Como ransomwares utilizam **criptografia para sequestrar dados**
- Como keyloggers capturam **informações digitadas**
- Como esses comportamentos podem ser **detectados por ferramentas de segurança**
- A importância de boas práticas de **cibersegurança defensiva**

---

# ⚠️ Aviso Legal

Este repositório foi criado **exclusivamente para fins educacionais e de pesquisa em segurança da informação**.

O uso indevido dessas técnicas pode ser **ilegal**.  
O autor **não se responsabiliza por qualquer uso malicioso deste código**.

---

# 👨‍💻 Autor

**Guilherme Marinho**

🎓 Estudante de Análise e Desenvolvimento de Sistemas  
🔐 Interesse em Cibersegurança, Inteligência Artificial e Desenvolvimento de Software

GitHub:  
https://github.com/GuiMRDS
