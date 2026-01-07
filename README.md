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

- Cadastro de usuários e funcionários
- Gestão de condomínios e apartamentos
- Controle de documentos e eventos
- Sistema de permissões e acessos
- Notificações e mensagens internas

---



---

## 🗂 Estrutura do Banco

- **TAB_Usuarios**: Armazena dados dos usuários.
- **TAB_Condominio**: Informações dos condomínios.
- **TAB_Apartamentos**: Detalhes dos apartamentos.
- **TAB_Eventos**: Registro de eventos.
- **TAB_Documentos**: Controle de documentos.
- **TAB_PermissoesAcessos**: Gerenciamento de permissões.
- **TAB_MensagensNotificacoes**: Sistema de mensagens internas.

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/aquaImob.git
   ```
2. Configure o banco de dados PostgreSQL.
3. Execute as migrações.
4. Inicie a aplicação:
   ```bash
   docker-compose up -d
   ```

---

## 📄 Licença
Este projeto é licenciado sob a [MIT License](LICENSE).
