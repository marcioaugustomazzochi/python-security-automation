# 🔐 Automação de Segurança em Python

Projeto prático de automação de segurança da informação, desenvolvido em **Python**, com foco em **varredura de vulnerabilidades**, **coleta de inteligência de ameaças** e **análise de tráfego de rede**, aplicado exclusivamente em **ambientes controlados e autorizados**.

💡 Projeto criado para fins **educacionais**, **laboratório prático** e **portfólio profissional em Cibersegurança**.

---

## 🎯 Objetivos do Projeto

- Automatizar tarefas comuns de segurança ofensiva e defensiva  
- Integrar ferramentas amplamente utilizadas no mercado de Cibersegurança  
- Facilitar análises técnicas e coleta de evidências  
- Demonstrar habilidades práticas em Segurança da Informação e Python  

---

## ⚙️ Funcionalidades

### 🔎 Varredura de Vulnerabilidades
- Execução automatizada de scans com **Nmap**  
- Identificação de serviços e versões expostas  

### 🛡️ Coleta de Inteligência de Ameaças
- Consulta a APIs públicas de CVE  
- Exposição de vulnerabilidades recentes e riscos técnicos  

### 🌐 Análise de Tráfego de Rede
- Captura e inspeção de pacotes com **Scapy**  
- Base para identificação de comportamentos suspeitos  

---

## 🧰 Tecnologias Utilizadas

- Python 3.x  
- Nmap  
- Scapy  
- Requests  
- Kali Linux (ambiente de laboratório)  

---

## 📁 Estrutura do Projeto

```text
python-security-automation/
├── scans/
│   └── nmap_scan.py
├── threat_intel/
│   └── cve_collector.py
├── traffic_analysis/
│   └── scapy_sniffer.py
├── reports/
│   └── README.md
├── Impressões/
│   └── README.md
├── requirements.txt
├── LICENSE
└── README.md
📸 Evidências Práticas de Execução
Para comprovar a execução real dos scripts e a automação funcionando na prática, este projeto conta com evidências visuais obtidas em laboratório controlado.

👉 Ver prints do laboratório e evidências técnicas:
📸 Acessar evidências práticas de execução

🚀 Instalação
git clone https://github.com/marcioaugustomazzochi/python-security-automation.git
cd python-security-automation
pip install -r requirements.txt
▶️ Exemplos de Uso
🔎 Varredura de Vulnerabilidades com Nmap
python scans/nmap_scan.py 192.168.56.124
Exemplo de alvo: Metasploitable em laboratório virtualizado.

🛡️ Coleta de CVEs Recentes
python threat_intel/cve_collector.py
🌐 Análise de Tráfego de Rede
python traffic_analysis/scapy_sniffer.py
🗺️ Roadmap
 Varredura de vulnerabilidades com Nmap

 Coleta de dados de ameaças (CVE API)

 Análise de tráfego com Scapy

 Geração automática de relatórios (TXT / HTML / PDF)

 Integração com logs e SIEM (futuro)

⚠️ Aviso Ético e Legal
Este projeto deve ser utilizado exclusivamente em ambientes controlados, de teste ou com autorização explícita.

🚫 Qualquer uso fora desse contexto é ilegal e antiético.

📜 Licença
Este projeto está licenciado sob a MIT License.
Consulte o arquivo LICENSE para mais detalhes.

👤 Autor
Márcio Augusto Mazzocchi
🔐 Segurança da Informação | Cibersegurança | Automação com Python
💻 GitHub: https://github.com/marcioaugustomazzochi

