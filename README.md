# 🌐 [IRL-ANRO] Instalação de Redes Locais · Avaliação de Necessidades de Rede de uma Organização

> **CTeSP em Redes e Sistemas Informáticos** · ISTEC Porto · Ano letivo 2023/2024

---

## 📋 Informações da UC

| Campo | Detalhe |
|-------|---------|
| **Unidades Curriculares** | Instalação de Redes Locais (IRL) · Avaliação de Necessidades de Rede de uma Organização (ANRO) |
| **Curso** | CTeSP — Redes e Sistemas Informáticos |
| **Período Letivo** | 2.º Semestre |
| **Ano Curricular** | 1.º |
| **Ano letivo** | 2023 / 2024 |
| **Docente** | Prof. Tiago Teixeira |
| **Aluno** | Gonçalo Lopes Fernandes · Nº 2022148 |
| **Nota Final** | 14 valores ✅  &&  14 valores ✅ 

---

## 📁 Estrutura do Repositório

```
.
├── exercicios/
│   ├── 2.7.24.png                                # Esquema de rede — planta do edifício (whiteboard)
│   ├── 2024 na 12_28.jpg                         # Fotografia do planeamento em sala de aula
│   ├── Cronograma.pdf                            # Cronograma do projeto (análise, instalação, config, testes)
│   ├── Esquema de rede.png                       # Diagrama de rede — topologia com pisos, APs e firewall
│   ├── Gráfico de Gantt.pdf                      # Gráfico de Gantt — fases do projeto (Fev–Out)
│   └── Mapa de Gantt.png                         # Mapa de Gantt visual — orçamento, aquisição, implantação
├── material/
│   ├── IRL AVALIAÇÃO.pdf                         # Ficha de avaliação IRL — 20 questões (redes, switching, firewall)
│   ├── Orçamento para rede - Folha1.pdf          # Orçamento detalhado — hardware, software, serviços (€10.375)
│   ├── Projeto de rede - 12.7.pdf                # Projeto de rede (versão 12/07) — farmácia completa
│   ├── Projeto de rede.pdf                       # Projeto de rede (versão inicial) — farmácia
│   ├── Relatório testes de redes.pdf             # Relatório escrito sobre testes de rede
│   └── Testes de rede.pdf                        # Apresentação: Testes de Rede (com Rafael Costa)
├── notas/
│   └── a.txt                                     # Placeholder — nota pendente
└── README.md
```

---

## 📝 Trabalhos Realizados

### Projeto de Grupo — Rede para uma Farmácia
**Alunos:** Gonçalo Fernandes [148], Rafael Costa [173] & Tiago Figueiredo [155] | **Data:** 12/07/2024

Projeto completo de planeamento, desenho e orçamentação de uma rede local para uma farmácia, incluindo:

**1. Definição de Objetivos**
Objetivos de negócio (atendimento eficaz, gestão de stock, conformidade GDPR, segurança de dados) e necessidades operacionais (capacidade de rede, QoS, Wi-Fi, redundância, escalabilidade).

**2. Análise de Requisitos**
Levantamento de utilizadores (farmacêuticos, assistentes, gerentes), postos de trabalho (POS, back-office, tablets) e aplicações críticas (SGF, POS, videovigilância, comunicação interna) com requisitos de largura de banda, latência e segurança.

**3. Projeto da Rede**
Topologia LAN com segmentação por VLANs (público, POS, administrativo), equipamentos (routers, switches gerenciáveis, APs Wi-Fi, firewall), QoS e configuração de segurança (VPN, WPA3, IDS/IPS).

**4. Redundância e Escalabilidade**
Cabeamento Cat6, switches modulares, servidores em failover, UPS, backup RAID, virtualização (VMware/Hyper-V) e serviços cloud (AWS, Azure, GCP).

**5. Segurança**
Firewall NGFW, autenticação MFA, VPN site-to-site e acesso remoto, criptografia TLS/HTTPS, conformidade LGPD e regulamentação farmacêutica.

**6. Orçamento**

| Categoria | Custo (€) |
|-----------|-----------|
| Hardware | 5.225 |
| Software | 1.750 |
| Serviços | 1.300 |
| Manutenção | 900 |
| Seguros e Proteções | 500 |
| Fundo de Contingência (10%) | 700 |
| **Total Geral** | **10.375** |

**Diagramas criados:**
- Esquema de rede multi-piso (piso 0, 1, 2) com firewall, roteador, switches, APs e dispositivos
- Diagrama de rede para farmácia (armazém de medicamentos, balcão, consultório, escritório)
- Planta do edifício desenhada em whiteboard com medidas e equipamentos
- Cronograma e gráfico de Gantt com fases do projeto

---

### Apresentação de Grupo — Testes de Rede
**Alunos:** Rafael Costa [173] & Gonçalo Fernandes [148]

Apresentação (11 slides) sobre metodologia e ferramentas de testes de rede:

| Tipo de Teste | Métricas / Conteúdo |
|---------------|---------------------|
| Desempenho | Largura de banda, latência, jitter, perda de pacotes |
| Segurança | Penetração, vulnerabilidade, conformidade |
| Funcionalidade | QoS, VoIP, cobertura Wi-Fi |
| Conectividade | Ping, traceroute, DNS lookup |

**Ferramentas abordadas:** Ping, Netstat, Wireshark, Speedtest-cli, Nagios, Wi-Fi Analyzer.

---

### Ficha de Avaliação — IRL
**Aluno:** Gonçalo Fernandes · Nº 148

Ficha com 20 questões de escolha múltipla sobre instalação de redes locais, abrangendo cabeamento estruturado (UTP, Cat6, RJ45), dispositivos de rede (hub vs. switch, router, AP), modelo OSI, protocolos (DHCP, DNS, NAT), VLANs, firewalls (hardware vs. software, DPI) e segurança.

---

## 🧠 Temas Abordados nas UC

| Tema | Conteúdo |
|------|----------|
| Cabeamento Estruturado | UTP Cat6, conectores RJ45, tomadas de rede, padrão T568B |
| Dispositivos de Rede | Switches (gerenciáveis vs. não gerenciáveis), routers, hubs, APs |
| Modelo OSI | Camadas, enquadramento de dispositivos (L2 switch, L3 router) |
| Topologias de Rede | LAN, VLAN, segmentação de tráfego, topologias físicas/lógicas |
| Protocolos | DHCP, DNS, NAT, ARP |
| Segurança | Firewalls (NGFW, DPI), VPN, WPA3, IDS/IPS, MFA |
| Testes de Rede | Ping, traceroute, Wireshark, Nagios, Speedtest-cli |
| Planeamento de Rede | Análise de requisitos, dimensionamento, orçamentação |
| Redundância | Failover, UPS, RAID, backup cloud, agregação de links |
| Virtualização e Cloud | VMware ESXi, Hyper-V, AWS, Azure, GCP, IaaS, SaaS |

---

## 📬 Contacto

**Gonçalo Fernandes** · [goncalo.fernandes.2022148@my.istec.pt](mailto:goncalo.fernandes.2022148@my.istec.pt)
