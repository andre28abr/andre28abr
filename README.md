## 👋 Olá

Sou **André Augusto Azarias de Souza**. Atuo na interseção entre **Compliance, GRC, privacidade e segurança da informação**, com formação em Direito e em Análise e Desenvolvimento de Sistemas.

→ [LinkedIn](https://linkedin.com/in/andreaugusto-azariasdesouza) · contato@azariasdesouza.com

---

### Quem sou

Gestor com **18 anos de atuação como Gerente Administrativo e Encarregado de Dados (DPO)** em organização do setor de saúde suplementar, ambiente regulado pela ANS e pela LGPD. Participei de decisões de diretoria, conduzi a relação com hospitais e operadoras, liderei a modernização dos sistemas administrativos e de segurança da informação e coordenei o programa de adequação à LGPD da organização, com dados sensíveis de saúde sob o Art. 11.

Formado em **Direito** e em **Análise e Desenvolvimento de Sistemas**, com pós-graduações em segurança digital, governança de dados, privacidade, direito digital e liderança ágil.

Trabalho com mapeamento de dados e ROPA (Art. 37), RIPD/DPIA (Art. 38), direitos do titular (Art. 18), gestão de operadores e terceiros (Art. 39), resposta a incidentes (Art. 48), interface com a ANPD, e com os frameworks NIST CSF, CIS Controls e ISO/IEC 27001/27701. Parto do princípio de que proteção de dados é também arquitetura: Security by Design, Zero Trust, defesa em camadas e menor privilégio.

Desde 2025 conduzo, como **product owner técnico**, projetos open-source de segurança e privacidade em Python, Go, Rust e Swift, com a codificação orquestrada por assistentes de IA generativa sob minha direção e revisão. Sou autor de cinco livros publicados, entre eles *Da Norma à Liderança*, sobre atualização profissional em GRC.

---

### Automação de processos com n8n

Projeto e opero **automações de processos de negócio e jurídicos em n8n**, self-hosted em Docker Compose, com foco em privacidade: processamento local, gravação em disco restrita a pastas definidas, sem envio de dados a serviços de terceiros. Entre o que já construí:

- **Triagem automática de publicações judiciais**: busca de hora em hora no DJEN (Comunica CNJ) por OAB, classificação por urgência, cálculo de prazo provisório em dias úteis, contexto do processo via DataJud e painel web de tratamento por advogado.
- **Onboarding de clientes**: formulário web que gera em segundos procuração, declaração de hipossuficiência e contrato de honorários em PDF (Gotenberg), com registro do cliente para os fluxos seguintes.
- **Portal e páginas servidas pelo próprio n8n** via webhooks, instaladores para Mac e Windows, variante para servidor com HTTPS automático e autenticação (Caddy) e rotina de backup.
- **Integrações com APIs públicas** (DJEN, DataJud, BrasilAPI) e desenho de fluxos com Code nodes, banco JSON local e controle de estado entre execuções.

---

### 📂 Projetos

**[SentinelBR](https://github.com/andre28abr/SentinelBR-platform)**: plataforma open-source de **SIEM + LGPD** para PMEs brasileiras. Agente Go com gRPC e mTLS, detecção em tempo real, resposta automatizada e compliance LGPD nativa, multi-tenant. 225 testes entre servidor, agente e frontend; CI em 16 jobs.

**[VigiaOS](https://github.com/andre28abr/VigiaOS)**: suíte de **segurança, privacidade e LGPD** para a estação de trabalho (Fedora Workstation, GTK4 + libadwaita), com 13 ferramentas defensivas, módulos de detecção e resposta e laboratório educacional com termo de uso. 1460 testes em Python e 28 em Rust.

**[Plataforma LGPD](https://github.com/andre28abr/lgpd-platform)**: plataforma web multi-tenant que **treina, avalia e certifica** os setores de uma empresa em LGPD e dá ao DPO as ferramentas de operação: ROPA, RIPD, direitos do titular e incidentes. 121 testes, 95% de cobertura.

**[Peapod](https://github.com/andre28abr/Peapod)**: sandboxes **isolados e descartáveis para agentes de IA**, dirigidos por MCP, CLI, dashboard web e app nativo de macOS: rede desligada por padrão, allowlist de domínios, trilha de auditoria. Go e Swift, distribuído por Homebrew.

**[Uptend](https://github.com/andre28abr/Uptend)**: app nativo de macOS para **configurar e manter o Mac** e **auditar servidores Linux**: coletor portátil, relatórios, correlação com CVEs, MITRE ATT&CK, lente LGPD e playbook de hardening com rollback. Swift 6, 428 testes.

**[banana](https://github.com/andre28abr/banana)**: editor **local-first** de notas Markdown, código e PDF, com vault cifrado (Argon2id + AES-256-GCM). Tauri 2, Rust e Svelte 5, 393 testes.

**SC Platform** *(privado, disponível para apresentação mediante solicitação)*: SaaS multi-tenant para gestão de licitações públicas, com PNCP em tempo real, simulador da Lei 14.133/2021, robô de lances em três modos, extração de PDF com IA local, CRM e Telegram. Cerca de 75 mil linhas e 547 testes.

Cada repositório tem um `AUTHOR.md` com o porquê do projeto e a minha atuação nele.

---

### 📫 Contato

→ [LinkedIn](https://linkedin.com/in/andreaugusto-azariasdesouza) · contato@azariasdesouza.com
