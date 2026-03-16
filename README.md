# TryHackMe Labs - Jornada em Cybersecurity 🛡️

Repositório destinado à documentação técnica de laboratórios práticos realizados na plataforma TryHackMe, focado em monitoramento, defesa cibernética e análise de logs.

## 🛠️ Ferramentas Utilizadas
* **Sysmon & Event Viewer:** Investigação de telemetria de endpoint e forense digital.
* **SIEM (Splunk):** Ingestão, tratamento e análise de eventos de segurança.
* **Wireshark:** Análise de pacotes e tráfego de rede para detecção de anomalias.

## 📁 Principais Laboratórios
### 🔹 Phishing & Malware Analysis
Análise de cadeia de ataque baseada em e-mails maliciosos e arquivos executáveis camuflados.
* **Key Findings:** Identificação de execução via `Process Create (ID 1)`, monitoramento de caminhos de diretório e conexões externas via `DNS Query (ID 22)`.

### 🔹 Monitoramento de RDP (Acessos Remotos)
* Detecção de ataques de força bruta utilizando filtros de `Logon Type 10` e Event IDs de sucesso/falha no Windows.
