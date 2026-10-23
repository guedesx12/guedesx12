<h1 align="center">Wagner Guedes Bartos</h1>
<h3 align="center">Segurança Industrial (OT/ICS) & Segurança de Aplicações</h3>

<p align="center">
  <a href="https://www.linkedin.com/company/industrial-cyber-defense">
    <img src="https://img.shields.io/badge/LinkedIn-Industrial%20Cyber%20Defense-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <img src="https://img.shields.io/badge/Foco-OT%2FICS%20Security-2ea44f?style=flat" alt="OT/ICS Security"/>
  <img src="https://img.shields.io/badge/Tamb%C3%A9m-AppSec%20%26%20Bug%20Bounty-blue?style=flat" alt="AppSec & Bug Bounty"/>
</p>

Trabalho com segurança defensiva aplicada a ambientes industriais — a convergência entre TI e OT, chão de fábrica, redes SCADA e infraestrutura crítica. Acompanho avisos de vulnerabilidade (CISA ICS-CERT) e traduzo cada um em ação prática para quem opera a planta: o que verificar, em que ordem, e o que não fazer fora de janela de manutenção. Em paralelo, atuo em segurança de aplicações — análise de APK Android e pentest web — incluindo bug bounty em programas responsáveis.

🏭 **[Industrial Cyber Defense](https://www.linkedin.com/company/industrial-cyber-defense)** — página onde publico, desde 2023, análises e defesas práticas para manter plantas industriais seguras e operacionais: avisos CISA traduzidos em checklist de planta, lições de incidentes reais (como o ataque a 22 operadoras de energia na Dinamarca em 2023), segmentação TI/OT, hardening de sistemas legados (IHM em Windows XP/7) e disciplina de patch management em janelas de parada.

---

### 🏭 Segurança OT/ICS

- **Triagem de avisos CISA/ICS-CERT** — leitura do aviso, mapeamento para o inventário de ativos, decisão de contenção (reduzir alcance de rede) antes mesmo da correção do fabricante chegar.
- **Modelo de ataque industrial em fases** — entrada (phishing, credencial, VPN esquecida, fornecedor) → permanência (reconhecimento silencioso) → travessia (nível 4 ao nível 2, quase sempre por caminho legítimo) → ação (manipulação de processo, ransomware, parada). Prioridade de defesa nas três primeiras fases, onde o controle é mais barato.
- **Hardening de sistemas legados** — isolamento de IHMs e estações em fim de vida, application whitelisting no lugar de antivírus por assinatura, desabilitação de USB por política, log de toda conexão de rede de entrada/saída.
- **Patch management disciplinado para OT** — patch como um controle entre vários (não o principal), compensado por segmentação, whitelisting, monitoramento de protocolo industrial e controle de acesso remoto; aplicação planejada na janela de parada, nunca fora dela.
- **Lições de incidentes reais** — leitura de relatórios públicos (ex.: SektorCERT, casos de exploração em massa de firewalls de borda) para entender onde o perímetro industrial realmente falha.

### 🔐 Segurança de Aplicações

- **Análise de APK Android** — engenharia reversa estática/dinâmica, identificação de armazenamento inseguro, lógica de autenticação falha e superfícies expostas (deep links, OAuth, componentes exportados).
- **Pentest web** — exercícios práticos em ambientes propositalmente vulneráveis (DVWA e similares) para validar técnica antes de levar a campo.
- **Bug bounty** — participação em programas de divulgação responsável (HackerOne), respeitando escopo e política de confidencialidade de cada programa.

---

### 📂 Projetos

| Projeto | Descrição |
|---|---|
| [desafio-brute-force-dvwa](https://github.com/guedesx12/desafio-brute-force-dvwa) | Exercício de brute force contra o DVWA (Damn Vulnerable Web Application), laboratório oficial para treino de técnicas de ataque e defesa web. |

> 🚧 Toolkit de análise de APK Android (triagem estática automatizada) em preparação para publicação.

---

### 🛠️ Ferramentas & Stack

<p>
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/-Android-3DDC84?style=flat&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/-Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white" alt="Wireshark"/>
  <img src="https://img.shields.io/badge/-Burp%20Suite-FF6633?style=flat" alt="Burp Suite"/>
  <img src="https://img.shields.io/badge/-SCADA%2FICS-2ea44f?style=flat" alt="SCADA/ICS"/>
</p>

---

<p align="center">
📫 <a href="https://www.linkedin.com/company/industrial-cyber-defense">LinkedIn — Industrial Cyber Defense</a>
</p>
