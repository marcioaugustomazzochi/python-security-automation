# 🛡️ Automação de Segurança em Python

Este projeto automatiza processos de segurança usando **Python**:

- **Varredura de vulnerabilidades**
- **Coleta de dados de ameaças**
- **Análise de tráfego de rede**

---

## 📌 Funcionalidades

- **Varredura de Vulnerabilidades com Nmap**  
- **Coleta de Dados de Ameaças (CVE)**  
- **Análise de Tráfego de Rede**

---

## 🛠️ Tecnologias

- **Python 3.x**
- **Nmap**
- **Scapy**
- **Requests**

---

## ⚙️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/marcioaugustomazzochi/python-security-automation.git
cd python-security-automation
pip install -r requirements.txt
💻 Exemplos de Uso
🔍 Varredura de Vulnerabilidades com Nmap
python
import subprocess

def run_nmap(target):
    command = f"nmap -sV {target}"
    result = subprocess.run(command, shell=True, capture_output=True, text=True)
    print(result.stdout)

# Exemplo de uso
run_nmap("192.168.56.124")  # Alvo: Metasploitable
🌐 Coleta de Dados de Ameaças (CVE)
python
import requests

def get_cve_data():
    url = "https://cve.circl.lu/api/last"
    response = requests.get(url)
    data = response.json()
    for entry in data:
        print(f"CVE ID: {entry['id']}, Descrição: {entry['summary']}")

# Exemplo de uso
get_cve_data()
🗺️ Roadmap
Varredura de vulnerabilidades com Nmap

Coleta de dados de ameaças (CVE API)

Análise de tráfego com Scapy

Geração de relatórios automáticos

📄 Licença
Este projeto está licenciado sob a MIT License.
Consulte o arquivo LICENSE para mais detalhes.

⚠️ Aviso Ético
Todos os scripts devem ser utilizados exclusivamente em ambientes controlados e autorizados, para fins educacionais.
