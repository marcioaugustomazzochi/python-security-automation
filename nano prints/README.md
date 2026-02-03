## 📸 Evidências Práticas — Automação de Segurança com Python

---

Esta pasta contém evidências visuais reais da execução automatizada dos scripts do projeto **Automação de Segurança com Python**.

Os prints demonstram a saída prática dos scripts Python, que utilizam o **Nmap** como engine de varredura, automatizando tarefas de reconhecimento, enumeração de serviços e coleta de evidências técnicas.

Todos os testes foram realizados em ambiente de laboratório controlado e autorizado, utilizando **Kali Linux** e a máquina vulnerável **Metasploitable**, exclusivamente para fins educacionais e de portfólio profissional.

---

## 🎯 Objetivo das evidências

Comprovar que o projeto:

- executa varreduras de segurança de forma automatizada;
- coleta informações relevantes sem intervenção manual;
- gera resultados reais, utilizáveis em análise técnica e relatórios.

---

## 🐍 Evidência 01 — Automação de Scan Básico com Python + Nmap

<img width="1920" height="936" alt="! Scan Básico Nmap ( 1_printsnmap_basic_scan_metasploitable png)" src="https://github.com/user-attachments/assets/0dc02233-8866-4f65-978e-a2c4b9f34a7a" />


Este print apresenta a execução automatizada de um scan básico, acionado por um script Python, responsável por iniciar o Nmap e coletar os resultados iniciais.

**Demonstra:**
- automação da descoberta de portas abertas;
- identificação inicial de serviços via script;
- substituição de comandos manuais por execução programada.

➡️ Primeiro estágio da automação de segurança.

---

## 🐍 Evidência 02 — Automação de Enumeração Avançada de Serviços

<img width="1920" height="936" alt="2 printsnmap_enum_metasploitable" src="https://github.com/user-attachments/assets/0e11c3a8-94d3-47a2-815b-1618bc2cd063" />


Este print mostra a enumeração avançada de serviços executada automaticamente via Python + Nmap.

**Demonstra:**
- coleta de versões de serviços;
- aumento da profundidade do scan;
- preparação de dados para análise de vulnerabilidades.

---

## 🐍 Evidência 03 — Automação de Enumeração SMB (Acesso Anônimo)

<img width="1920" height="936" alt="3 smb_enum_anonymous_rw" src="https://github.com/user-attachments/assets/5e243148-a4be-461f-9202-1c0454a6b009" />


Este print demonstra a enumeração automatizada do serviço SMB, identificando acesso anônimo com permissões de leitura e escrita.

**Identificado automaticamente:**
- serviço SMB vulnerável;
- autenticação anônima habilitada;
- risco real de exposição de dados.

---

## 🐍 Evidência 04 — Automação de Enumeração NFS

<img width="1920" height="936" alt="4 nfs_enum_no_exports_metasploitable" src="https://github.com/user-attachments/assets/f84d59eb-91d4-44f0-b6ff-f3dc38c48772" />


Enumeração automática do serviço NFS, indicando ausência de restrições adequadas nos exports.

**Demonstra:**
- detecção de serviços de compartilhamento;
- identificação de configurações inseguras;
- coleta automatizada de dados técnicos.

---

## 🐍 Evidência 05 — Automação de Enumeração FTP (vsftpd 2.3.4)

<img width="1920" height="936" alt="5 ftp_enum_anonymous_vsftpd_2 3 4" src="https://github.com/user-attachments/assets/d560a2ef-7b09-4fc2-8a74-1118aba53445" />


Enumeração automatizada do serviço FTP, identificando login anônimo e versão vulnerável do serviço.

**Permite:**
- correlação entre versão e risco;
- identificação rápida de superfícies exploráveis;
- ganho de eficiência em análises repetitivas.

---

## 🐍 Evidência 06 — Automação de Enumeração do Serviço HTTP

<img width="1920" height="936" alt="6 http_enum_metasploitable_nmap_results" src="https://github.com/user-attachments/assets/6caafbfe-b0f7-4cb5-b634-98573805674a" />


Resultados da enumeração automatizada do serviço HTTP, coletados via Nmap e organizados pelo script Python.

**Demonstra:**
- identificação de serviços web ativos;
- coleta de informações expostas;
- preparação para análises de segurança web.

---

## 🧠 O que estas evidências comprovam

Em conjunto, os prints demonstram que o projeto:

- automatiza tarefas reais de segurança com Python;
- integra ferramentas amplamente usadas no mercado (Nmap);
- reduz trabalho manual repetitivo;
- gera evidências práticas e reproduzíveis.

📌 **Não é um projeto teórico — é automação funcional validada em laboratório.**

---

## ⚠️ Aviso Ético e Legal

Todos os testes foram executados **exclusivamente em ambientes controlados e autorizados**, com finalidade:

- educacional;
- laboratório prático;
- projeto profissional.

🚫 O uso destes scripts fora desse contexto é ilegal e antiético.
