# André Augusto Azarias de Souza

**Compliance · GRC · Privacidade · Segurança da Informação · Automação de processos**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andreaugusto--azariasdesouza-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/andreaugusto-azariasdesouza)
[![E-mail](https://img.shields.io/badge/E--mail-contato%40azariasdesouza.com-D14836?logo=gmail&logoColor=white)](mailto:contato@azariasdesouza.com)
![Localização](https://img.shields.io/badge/Campinas-SP%2C%20Brasil-6B7280)

![DPO](https://img.shields.io/badge/DPO-Encarregado%20de%20Dados-1F6FEB)
![LGPD](https://img.shields.io/badge/LGPD-Lei%2013.709%2F2018-10B981)
![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%20%C2%B7%2027701-0F766E)
![NIST CSF](https://img.shields.io/badge/NIST-CSF-374151)
![CIS Controls](https://img.shields.io/badge/CIS-Controls-374151)
![Security by Design](https://img.shields.io/badge/Security-by%20Design-7C3AED)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

---

## Quem sou

Gestor com **18 anos de atuação como Gerente Administrativo e Encarregado de Dados (DPO)** em organização do setor de saúde suplementar, ambiente regulado pela ANS e pela LGPD. Participei de decisões de diretoria, conduzi a relação com hospitais e operadoras, liderei a modernização dos sistemas administrativos e de segurança da informação e coordenei o programa de adequação à LGPD da organização, com dados sensíveis de saúde sob o Art. 11.

Formado em **Direito** e em **Análise e Desenvolvimento de Sistemas**, com pós-graduações em segurança digital, governança de dados, privacidade, direito digital e liderança ágil.

Trabalho com mapeamento de dados e ROPA (Art. 37), RIPD/DPIA (Art. 38), direitos do titular (Art. 18), gestão de operadores e terceiros (Art. 39), resposta a incidentes (Art. 48), interface com a ANPD, e com os frameworks NIST CSF, CIS Controls e ISO/IEC 27001/27701. Parto do princípio de que proteção de dados é também arquitetura: Security by Design, Zero Trust, defesa em camadas e menor privilégio.

Desde 2025 conduzo, como **product owner técnico**, projetos open-source de segurança e privacidade em Python, Go, Rust e Swift, com a codificação orquestrada por assistentes de IA generativa sob minha direção e revisão. Sou autor de cinco livros publicados, entre eles *Da Norma à Liderança*, sobre atualização profissional em GRC.

---

## Automação de processos com n8n

Projeto e opero **automações de processos de negócio e jurídicos em n8n**, self-hosted em Docker Compose, com foco em privacidade: processamento local, gravação em disco restrita a pastas definidas, sem envio de dados a serviços de terceiros. Entre o que já construí:

- **Triagem automática de publicações judiciais**: busca de hora em hora no DJEN (Comunica CNJ) por OAB, classificação por urgência, cálculo de prazo provisório em dias úteis, contexto do processo via DataJud e painel web de tratamento por advogado.
- **Onboarding de clientes**: formulário web que gera em segundos procuração, declaração de hipossuficiência e contrato de honorários em PDF (Gotenberg), com registro do cliente para os fluxos seguintes.
- **Portal e páginas servidas pelo próprio n8n** via webhooks, instaladores para Mac e Windows, variante para servidor com HTTPS automático e autenticação (Caddy) e rotina de backup.
- **Integrações com APIs públicas** (DJEN, DataJud, BrasilAPI) e desenho de fluxos com Code nodes, banco JSON local e controle de estado entre execuções.

---

## Projetos

**[SentinelBR](https://github.com/andre28abr/SentinelBR-platform)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) ![React](https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB)<br>
Plataforma open-source de **SIEM + LGPD** para PMEs brasileiras: agente Go com gRPC e mTLS, detecção em tempo real, resposta automatizada e compliance LGPD nativa, multi-tenant. 225 testes entre servidor, agente e frontend; CI em 16 jobs.

**[VigiaOS](https://github.com/andre28abr/VigiaOS)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) ![GTK4](https://img.shields.io/badge/-GTK4-4A86CF?logo=gtk&logoColor=white)<br>
Suíte de **segurança, privacidade e LGPD** para a estação de trabalho (Fedora Workstation, GTK4 + libadwaita), com 13 ferramentas defensivas, módulos de detecção e resposta e laboratório educacional com termo de uso. 1460 testes em Python e 28 em Rust.

**[Plataforma LGPD](https://github.com/andre28abr/lgpd-platform)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)<br>
Plataforma web multi-tenant que **treina, avalia e certifica** os setores de uma empresa em LGPD e dá ao DPO as ferramentas de operação: ROPA, RIPD, direitos do titular e incidentes. 121 testes, 95% de cobertura.

**[Peapod](https://github.com/andre28abr/Peapod)** ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) ![Swift](https://img.shields.io/badge/-Swift-F05138?logo=swift&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)<br>
Sandboxes **isolados e descartáveis para agentes de IA**, dirigidos por MCP, CLI, dashboard web e app nativo de macOS: rede desligada por padrão, allowlist de domínios, trilha de auditoria. Distribuído por Homebrew.

**[Uptend](https://github.com/andre28abr/Uptend)** ![Swift 6](https://img.shields.io/badge/-Swift%206-F05138?logo=swift&logoColor=white) ![macOS](https://img.shields.io/badge/-macOS-000000?logo=apple&logoColor=white)<br>
App nativo de macOS para **configurar e manter o Mac** e **auditar servidores Linux**: coletor portátil, relatórios, correlação com CVEs, MITRE ATT&CK, lente LGPD e playbook de hardening com rollback. 428 testes, zero warnings.

**[banana](https://github.com/andre28abr/banana-releases)** ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) ![Tauri 2](https://img.shields.io/badge/-Tauri%202-24C8D8?logo=tauri&logoColor=white) ![Svelte 5](https://img.shields.io/badge/-Svelte%205-FF3E00?logo=svelte&logoColor=white)<br>
Editor **local-first** de notas Markdown, código e PDF, com vault cifrado (Argon2id + AES-256-GCM). 393 testes.

**SC Platform** *(privado, disponível para apresentação mediante solicitação)* ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)<br>
SaaS multi-tenant para gestão de licitações públicas: PNCP em tempo real, simulador da Lei 14.133/2021, robô de lances em três modos, extração de PDF com IA local, CRM e Telegram. Cerca de 75 mil linhas e 547 testes.

**AUGRAZ** *(privado, produto da empresa do autor)* ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white)<br>
Plataforma de compliance **LGPD + ISO 27001** para assessoria de proteção de dados: 11 módulos por empresa-cliente (ROPA, canal do titular, incidentes, ANPD, fornecedores, treinamentos), biblioteca dos 93 controles do Anexo A da ISO/IEC 27001:2022 com Gap Analysis, relatórios e geradores de política de privacidade, aviso de cookies e termos de uso. Testes em SQLite e PostgreSQL, CI com lint e auditoria de dependências.

**Site AUGRAZ** *(privado, protótipo ainda não publicado)* ![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white) ![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white)<br>
Site institucional com formulário de contato em PDO e prepared statements, credenciais fora do repositório e `.htaccess` com HTTPS forçado, bloqueio de arquivos sensíveis e cabeçalhos de segurança (HSTS, nosniff, X-Frame-Options, Referrer-Policy, Permissions-Policy).

Cada repositório tem um `AUTHOR.md` com o porquê do projeto e a minha atuação nele.

---

## Livros

Autor de cinco livros publicados na Amazon, no Clube de Autores e na UiClap. O técnico é *Da Norma à Liderança*, sobre atualização profissional em GRC.

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andreaugusto--azariasdesouza-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/andreaugusto-azariasdesouza)
[![E-mail](https://img.shields.io/badge/E--mail-contato%40azariasdesouza.com-D14836?logo=gmail&logoColor=white)](mailto:contato@azariasdesouza.com)
