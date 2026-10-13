# SOC/SIEM Open-Source Lab

Projeto de monitoramento, correlacao e resposta a incidentes.

## Integrantes
* Erick Santos - Core SIEM/SOAR (Wazuh e Shuffle)
* Valderlan - Sensores e Ataques (Suricata, Zeek e Kali Linux)

## Topologia Hibrida
* **Docker Compose**: VM01 (Wazuh Server) e VM03 (Shuffle SOAR)
* **Vagrant / VirtualBox**: VM02 (Suricata + Zeek), VM04/VM05 (Endpoints) e VM06 (Kali Linux)

## Entregas da Semana 1
- [x] Arquitetura geral do laboratorio estruturada
- [x] Estrutura de IaC (Infraestrutura como Codigo) inicializada
- [x] Provisionamento base das VMs criado via Vagrantfile
- [ ] Subir stack do Wazuh via Docker Compose
