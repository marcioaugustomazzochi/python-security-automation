# Automação de Segurança em Python

Este projeto automatiza processos de segurança usando **Python**:

- Varredura de vulnerabilidades
- Coleta de dados de ameaças
- Análise de tráfego de rede

---

# Funcionalidades

- Varredura de Vulnerabilidades com Nmap  
- Coleta de Dados de Ameaças (CVE)  
- Análise de Tráfego de Rede

---

# Tecnologias

- Python 3.x
- Nmap
- Scapy
- Requests

---

# Instalação

```bash
git clone https://github.com/marcioaugustomazzochi/python-security-automation.git
cd python-security-automation
pip install -r requirements.txt
Exemplos de Uso
Varredura de Vulnerabilidades com Nmap:

import subprocess

def run_nmap(target):
    command = f"nmap -sV {target}"
    result = subprocess.run(command, shell=True, capture_output=True, text=True)
    print(result.stdout)

run_nmap("192.168.56.124")
Coleta de Dados de Ameaças (CVE):

import requests

def get_cve_data():
    url = "https://cve.circl.lu/api/last"
    response = requests.get(url)
    data = response.json()
    for entry in data:
        print(f"CVE ID: {entry['id']}, Descrição: {entry['summary']}")

get_cve_data()
Licença e Aviso Ético
Licença:
MIT License

Aviso Ético:
Use apenas em ambientes controlados e autorizados.
Qualquer uso sem permissão é ilegal e antiético.
