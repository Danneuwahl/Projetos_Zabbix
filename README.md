# PROJETO ZABBIX 7.0 LTS HA
Apresentação de solução para monitoramento Zabbix- Suporte N3

![Logo do Projeto](https://astraya-associacao.org/imagens/zabbix1.png?_t=1767805587)

Sistema para monitoramento NOC N3.

---
## 🛠️ Tecnologias Utilizadas

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

![Modelo Relacional](https://astraya-associacao.org/imagens/zabbix2.png?_t=1767805587)

Este diagrama representa a estrutura desenvolvida para solução em monitoramento.

---
## 📊 Topologia
![Modelo](https://astraya-associacao.org/imagens/zabbix3.png?_t=1767805587)

## 🚀 Funcionalidades

- Zabbix supports TimescaleDB, o Zabbix oferece suporte ao TimescaleDB, uma solução de banco de dados baseada em PostgreSQL de 
particionamento automático de dados em blocos baseados em tempo para oferecer suporte a um desempenho mais rápido em escala.
- Hypertables são tabelas PostgreSQL que particionam automaticamente seus dados por tempo. Você interage com hipertabelas da 
mesma forma que as tabelas regulares do PostgreSQL, mas com recursos extras que facilitam muito o gerenciamento de seus dados de 
séries temporais.
- Tunning timescaleDB prepara o ambiente de acordo com size do hardware.
- HAProxy The Reliable, High Performance TCP/HTTP Load Balancer
- ETCD É um armazenamento de chave/valor open source, distribuído e consistente para configurações compartilhadas, descoberta de 
serviços e coordenação do agendador de sistemas distribuídos ou clusters de máquinas. Ele ajuda a viabilizar atualizações automáticas 
mais seguras, coordena a programação de trabalhos em hosts e ajuda a configurar redes de sobreposição para containers
- Zabbix HA O Zabbix oferece uma solução nativa de alta disponibilidade (HA) que é fácil de configurar e não requer expertise prévia 
em HA. No modo de alta disponibilidade do Zabbix, múltiplos servidores Zabbix são executados como nós em um cluster. 


---
