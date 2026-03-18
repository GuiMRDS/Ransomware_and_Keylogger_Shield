# 🛡️ Ransomware & Keylogger Shield

> ⚠️ **Aviso Legal:** Este projeto foi desenvolvido **exclusivamente para fins educacionais**, em ambiente controlado e isolado. Nenhum código aqui deve ser utilizado para atividades ilegais ou maliciosas. O objetivo é compreender como ataques funcionam para **melhorar a segurança de sistemas**.

Projeto de **Cibersegurança** que combina simulação ofensiva e defesa ativa contra dois dos ataques mais comuns no mundo digital: **Ransomware** e **Keylogger**. Desenvolvido como parte do **Bootcamp Riachuelo – Cibersegurança** da Digital Innovation One (DIO), com 40 horas de formação.

---

## 🎯 Objetivo

Entender na prática como ransomwares e keyloggers operam — desde a execução do ataque até a detecção e resposta — desenvolvendo uma visão completa do ciclo de ataque e defesa em segurança da informação.

---

## 🗂️ Estrutura do Projeto

```
Ransomware_and_Keylogger_Shield/
├── ransomware/
│   ├── encryptor.py          # Simula a criptografia de arquivos (ataque)
│   └── decryptor.py          # Restaura os arquivos criptografados (defesa)
├── keylogger/
│   ├── keylogger.py          # Simula a captura de teclas (ataque)
│   └── detector.py           # Detecta processos suspeitos de keylogging (defesa)
├── defense/
│   └── shield.py             # Script central de detecção e resposta
├── docs/
│   └── relatorio.pdf         # Relatório técnico com análise e conclusões
└── README.md
```

---

## ⚔️ Módulos

### 🔴 Módulo de Ransomware

Simula o comportamento de um ransomware real:

- Varredura de diretório-alvo em busca de arquivos
- Criptografia dos arquivos utilizando algoritmo simétrico
- Geração de chave de descriptografia
- Simulação de nota de resgate

**Contramedida incluída:** script de descriptografia que restaura os arquivos utilizando a chave gerada, demonstrando como backups e chaves seguras são essenciais para a recuperação.

---

### ⌨️ Módulo de Keylogger

Simula a captura silenciosa de teclas digitadas:

- Monitoramento de eventos de teclado em segundo plano
- Registro das teclas capturadas em arquivo de log
- Simulação de exfiltração dos dados

**Contramedida incluída:** detector de processos que identifica comportamentos característicos de keyloggers ativos no sistema.

---

### 🛡️ Script de Defesa — Shield

Script central de monitoramento e resposta que integra as defesas dos dois módulos:

- Verificação de integridade de arquivos
- Detecção de processos suspeitos
- Alertas em tempo real sobre comportamentos anômalos
- Recomendações de resposta a incidentes

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| Python | Desenvolvimento de todos os módulos |
| Linux | Ambiente de execução e testes |
| Kali Linux | Ambiente de análise de segurança |
| Git / GitHub | Versionamento de código |

---

## 🚀 Como Executar

### Pré-requisitos

- Python 3.x instalado
- Linux ou Kali Linux
- Ambiente **isolado** (máquina virtual recomendada)

```bash
# Instalar dependências
pip install -r requirements.txt
```

### Executando os módulos

```bash
# Simulação do Ransomware (em ambiente controlado)
python ransomware/encryptor.py

# Descriptografia (recuperação)
python ransomware/decryptor.py

# Simulação do Keylogger
python keylogger/keylogger.py

# Detector de Keylogger
python keylogger/detector.py

# Shield — Defesa integrada
python defense/shield.py
```

> 🔒 **Recomendação:** Execute sempre em uma máquina virtual isolada, nunca diretamente no sistema principal.

---

## 📚 O que foi Aprendido

- Como ransomwares criptografam arquivos e sequestram dados
- Como keyloggers capturam informações sem interação do usuário
- Técnicas de detecção de comportamento malicioso
- Boas práticas de defesa: backups, monitoramento de processos e resposta a incidentes
- Fundamentos de **hacking ético** e análise de vulnerabilidades

---

## 🎓 Contexto Acadêmico

> Projeto desenvolvido durante o **Bootcamp Riachuelo – Cibersegurança**, promovido pela **Digital Innovation One (DIO)** em parceria com **Lojas Riachuelo S.A.**
>
> **Carga horária:** 40 horas
> **Tópicos do bootcamp:** Segurança da Informação · Linux básico e intermediário · Kali Linux · Análise de vulnerabilidades · Hacking ético · Automação com Python

---

## 👨‍💻 Autor

**Guilherme Marinho**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-guilherme--marinho04-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/guilherme-marinho04/)
[![GitHub](https://img.shields.io/badge/GitHub-GuiMRDS-black?style=flat&logo=github)](https://github.com/GuiMRDS)
[![Email](https://img.shields.io/badge/Email-guimars22%40gmail.com-red?style=flat&logo=gmail)](mailto:guimars22@gmail.com)

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais. Uso malicioso é estritamente proibido e de responsabilidade exclusiva do usuário.
