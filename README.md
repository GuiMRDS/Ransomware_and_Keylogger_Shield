# 🛡️ Ransomware and Keylogger Shield (Educational Project)

Projeto educacional desenvolvido em **Python** para demonstrar, em um **ambiente totalmente controlado**, o funcionamento de dois tipos comuns de malware:

- **Ransomware**
- **Keylogger**

O objetivo deste repositório é **entender como essas ameaças funcionam na prática** e, principalmente, **aprender estratégias de defesa e prevenção** contra esse tipo de ataque.

⚠️ **Aviso Importante:**  
Este projeto foi desenvolvido **exclusivamente para fins educacionais e de estudo em cibersegurança**.  
Todos os testes devem ser realizados **apenas em ambiente controlado**, como máquinas virtuais ou laboratórios isolados.

---

# 📚 Sobre o Desafio

Este projeto foi desenvolvido como parte de um desafio prático de **cibersegurança utilizando Python**.

A proposta é **implementar e documentar exemplos simulados de malware**, permitindo compreender:

- Como malwares operam
- Como dados podem ser capturados ou sequestrados
- Como detectar e prevenir esses ataques

O projeto inclui:

✔ Simulação de **Ransomware**  
✔ Simulação de **Keylogger**  
✔ Documentação de **estratégias de defesa**

---

# 🎯 Objetivos de Aprendizagem

Ao desenvolver este projeto foi possível:

- Compreender o funcionamento básico de **Ransomware**
- Entender como funciona a captura de dados de um **Keylogger**
- Implementar scripts em **Python** simulando ataques em ambiente controlado
- Estudar **formas de prevenção e mitigação**
- Utilizar **GitHub como portfólio técnico**

---

# 🧪 Estrutura do Projeto

```
Ransomware_and_Keylogger_Shield
│
├── ransomware/
│   ├── encrypt.py
│   ├── decrypt.py
│
├── keylogger/
│   ├── keylogger.py
│
├── images/
│   ├── screenshots do projeto
│
└── README.md
```

---

# 🔐 Ransomware Simulado

O ransomware criado neste projeto simula o comportamento básico de um malware de sequestro de arquivos.

## Funcionamento

1. Cria ou seleciona arquivos de teste  
2. Utiliza criptografia para **criptografar os arquivos**  
3. Exibe uma mensagem simulando um **pedido de resgate**  
4. Possui um script separado para **descriptografar os arquivos**

## Biblioteca utilizada

- **Cryptography (Fernet)**

A biblioteca Fernet foi utilizada para realizar a **criptografia simétrica dos arquivos**.

---

# ⌨️ Keylogger Simulado

O Keylogger desenvolvido neste projeto captura **teclas digitadas no teclado** e registra em um arquivo `.txt`.

## Funcionamento

- Captura teclas pressionadas
- Registra em um arquivo `log.txt`
- Ignora algumas teclas especiais
- Trata teclas como:

- espaço  
- enter  
- tab  
- backspace  

## Biblioteca utilizada

- **pynput**

Essa biblioteca permite monitorar eventos de **teclado e mouse no sistema operacional**.

---

# 📧 Possível Extensão do Projeto

O projeto também pode ser expandido com:

- envio automático dos logs por e-mail usando:

- **smtplib**

Isso permite simular como alguns malwares **exfiltram dados capturados**.

---

# 🛡️ Estratégias de Defesa Contra Malware

Durante o estudo do projeto foram analisadas algumas medidas de proteção importantes:

## 🔹 Uso de Antivírus

Ferramentas de segurança podem detectar comportamento suspeito e bloquear execução de scripts maliciosos.

## 🔹 Firewall

Ajuda a bloquear comunicações suspeitas entre o malware e servidores externos.

## 🔹 Sandboxing

Executar arquivos desconhecidos em **ambientes isolados**, como:

- máquinas virtuais
- ambientes de teste

## 🔹 Conscientização do Usuário

Grande parte dos ataques ocorre devido a:

- downloads maliciosos
- anexos de e-mail
- engenharia social

Educação do usuário é uma das **defesas mais importantes**.

---

# 💻 Tecnologias Utilizadas

- Python
- Cryptography
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
python encrypt.py
```

⚠️ Execute apenas em **ambiente de testes**.

---

# 📷 Demonstrações

Capturas de tela do funcionamento podem ser encontradas na pasta:

```
/images
```

---

# 📖 Aprendizados

Este projeto permitiu entender na prática:

- Como malwares podem capturar dados
- Como funciona criptografia usada por ransomwares
- Como pequenas falhas de segurança podem ser exploradas
- A importância de práticas de **cibersegurança defensiva**

---

# ⚠️ Aviso Legal

Este repositório foi criado **exclusivamente para fins educacionais e de pesquisa em segurança da informação**.

O uso indevido dessas técnicas pode ser **ilegal**.  
O autor **não se responsabiliza por qualquer uso malicioso deste código**.

---

# 👨‍💻 Autor

**Guilherme Marinho**

Estudante de **Análise e Desenvolvimento de Sistemas** com interesse em:

- Cibersegurança
- Inteligência Artificial
- Desenvolvimento de Software

GitHub:  
https://github.com/GuiMRDS
