<!-- ════════════════════════════════════════════════════════════════════════
     Paulo Marcos Lucio · perfil GitHub — VIGÍLIA REV. B (Centro de Comando)
     Assets SVG próprios, auto-hospedados em ./assets — autocontidos (SMIL),
     zero refs externas, animados via <img> atrás do camo do GitHub.
     Regras de manutenção:
       · camo cacheia por URL de forma agressiva: NUNCA editar um asset
         reaproveitando o nome antigo — asset novo = nome de arquivo NOVO.
       · Zero shields.io nesta página. Um <img> = um link só.
       · Alt significativo em PT-BR em toda imagem.
       · Números SÓ de fatos reais, arredondados PARA BAIXO (343 → 340+).
       · SARIF existe SÓ no Guardião e na Esteira (Sentinela NÃO tem SARIF).
       · Nenhuma certificação é mencionada — não inventar OSCP/CEH/clientes.
       · Ética no footer em SVG E em <sub> de texto real, sempre.
     ════════════════════════════════════════════════════════════════════════ -->

<a href="https://paulo-marcos-lucio.github.io">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-command.svg" alt="Paulo Marcos Lucio — Segurança de Aplicações Web (AppSec): radar de vigilância com telemetria da suíte" width="100%"/>
</a>

<div align="center">

<a href="https://www.linkedin.com/in/paulo-marcos-a07379174/">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-linkedin-v2.svg" alt="LinkedIn — falar com Paulo Marcos Lucio" width="210"/>
</a>
<a href="mailto:pmlsp23@gmail.com">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-email-v2.svg" alt="E-mail — pmlsp23@gmail.com" width="210"/>
</a>
<a href="https://paulo-marcos-lucio.github.io">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-site.svg" alt="Site — serviços, pacotes e valores" width="210"/>
</a>
<a href="https://github.com/Paulo-Marcos-Lucio?tab=repositories">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-repos.svg" alt="Todos os repositórios no GitHub" width="210"/>
</a>

<br/><sub>São Paulo, BR — remote-first</sub>

</div>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

<div align="center"><a href="https://github.com/Paulo-Marcos-Lucio/sentinela"><img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/console-sentinela.svg" alt="Diagnóstico real do Sentinela contra paulo-marcos-lucio.github.io — reproduzível" width="88%"/></a></div>

<br/>

## `~/` Sobre

Atuo com **segurança de aplicações web (AppSec)**: **diagnóstico e correção de vulnerabilidades**, hardening e prevenção de falhas em sistemas expostos na internet — cabeçalhos de segurança, TLS/PKI, cookies, CORS, exposição de arquivos e segurança de DNS/e-mail — tudo mapeado ao **OWASP Top 10** e à **LGPD (art. 46)**.

Não venho "de fora" da engenharia. Meu background é **backend Java para o mercado financeiro regulado** — autenticação, mTLS ICP-Brasil, FAPI, integrações Pix e Open Finance — ou seja, venho de construir sistemas **onde errar em segurança não é uma opção**. Trago essa régua para o diagnóstico da sua aplicação: minhas recomendações de correção são realistas para o time de dev, porque eu **fui** o time de dev.

> **Precisa saber onde sua aplicação web está exposta — e como corrigir?**
> **[Fale comigo no LinkedIn](https://www.linkedin.com/in/paulo-marcos-a07379174/)** · ou veja os pacotes em **[paulo-marcos-lucio.github.io](https://paulo-marcos-lucio.github.io)**

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/ops-telemetry.svg" alt="Telemetria da operação: 5 ferramentas, 340+ testes automatizados, CI verde e licença MIT em todos os repositórios, mapeamento OWASP Top 10 + LGPD art. 46" width="100%"/>

<br/>

## `~/` Suíte AppSec

Um portfólio de **ferramentas de segurança de aplicações** — cada uma cobre uma frente do OWASP Top 10, do perímetro à autenticação, dos segredos vazados à cadeia de suprimentos. Todas com **testes, CI e documentação de nível de produto**: a ferramenta **é** a prova do critério técnico.

<a href="https://github.com/Paulo-Marcos-Lucio?tab=repositories">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/suite-map.svg" alt="Mapa de cobertura da suíte AppSec: Sentinela, Guardião, Chaveiro, Esteira e Laboratório OWASP — do perímetro à correção" width="100%"/>
</a>

| | Projeto | O que faz | Frente | Testes |
| :---: | --- | --- | :---: | :---: |
| `01` | **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** | Diagnóstico não-intrusivo de config web: cabeçalhos, TLS, cookies, CORS, DNS/e-mail (SPF/DMARC/MTA-STS), CSP profunda, descoberta de subdomínios via Certificate Transparency (`--descobrir`) e detecção de subdomain takeover; relatórios console/markdown/HTML/JSON com plano de ação. `Python` | Perímetro | `150+` |
| `02` | **[Guardião](https://github.com/Paulo-Marcos-Lucio/guardiao)** | Scanner de segredos vazados no código **e no histórico Git**: regex + entropia de Shannon, baseline, SARIF, hook pre-commit; detecta CPF/CNPJ (LGPD). `Python` | Segredos | `40+` |
| `03` | **[Chaveiro](https://github.com/Paulo-Marcos-Lucio/chaveiro)** | Auditor de tokens **JWT/JWS**: `alg:none`, confusão RS→HS, brute de segredo HMAC (inclui segredo vazio), `kid`/`jku` SSRF, validação de claims + referência de validação correta. `Python` | Autenticação | `40+` |
| `04` | **[Esteira](https://github.com/Paulo-Marcos-Lucio/esteira)** | Auditor de segurança de **CI/CD (GitHub Actions)**: script injection, actions não-fixadas por SHA, `pull_request_target`, permissões, `secrets: inherit`, imagens não-fixadas; saída SARIF. `Python` | Cadeia de suprimentos | `80+` |
| `05` | **[Laboratório OWASP](https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp)** | Cada vulnerabilidade em par **vulnerável → exploit → corrigido**, com teste JUnit provando os dois lados: SQLi, XSS, IDOR, Path Traversal, MD5→BCrypt. `Java 21` · `Spring Boot` | Correção | `16` |

<div align="center">

**[Ver todos os repositórios →](https://github.com/Paulo-Marcos-Lucio?tab=repositories)**

</div>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

## `~/` Serviços

<a href="https://paulo-marcos-lucio.github.io">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/services-pipeline.svg" alt="Como trabalho: trajetória do diagnóstico à adequação — diagnóstico, correção e hardening, reteste, LGPD art. 46" width="100%"/>
</a>

| | Serviço | O que entrego |
| :---: | --- | --- |
| `01` | **Diagnóstico de vulnerabilidades web** | Relatório com severidade, evidência e remediação priorizada. |
| `02` | **Correção & hardening** | CSP, HSTS, TLS moderno, cookies seguros, CORS restrito. |
| `03` | **Reteste & acompanhamento** | Comprovação da redução de risco + varredura recorrente por release. |
| `04` | **Adequação à LGPD (art. 46)** | Evidência datada e auditável das medidas técnicas de segurança. |

<div align="center">

**[Pacotes e valores no site →](https://paulo-marcos-lucio.github.io)**

</div>

<br/>

## `~/` Stack

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/stack-bom.svg" alt="Lista de materiais da stack: segurança de aplicações web, engenharia e automação, e background em fintech regulada — Spring, mTLS ICP-Brasil, FAPI, Pix, Open Finance, OAuth2/OIDC" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/footer-vigilia.svg" alt="Vigília: diagnóstico sob autorização e escopo definido — prompt aguardando o seu comando" width="100%"/>

<div align="center"><sub>Diagnóstico conduzido sempre sob autorização e escopo definido. Segurança é redução de risco — não promessa de perfeição.</sub></div>
<!-- profile-readme -->
