# 🚀 ConstruaSeuERP  
## Do Zero à Produção — com LGPD, NF-e, Acessibilidade e Arquitetura Profissional

> Um sistema ERP completo, desenvolvido para a realidade brasileira:  
> **ético, acessível, legalmente conforme, tecnicamente robusto e pedagogicamente estruturado**.

O **ConstruaSeuERP** é um projeto educacional e profissional que demonstra, de forma **progressiva e aplicada**, como construir um ERP moderno — partindo do **zero absoluto** até um **ambiente real de produção** — cobrindo engenharia de software, legislação, arquitetura, segurança, acessibilidade e sistemas fiscais.

Este repositório é a **base prática oficial** do livro:

📘 **“ConstruaSeuERP — Engenharia de Software Aplicada ao ERP Brasileiro”**  
**Autor**: [Alex Correia da Silva](https://alexcsilva.com.br)  
**Pastos Bons – MA**

---

## 🎯 Propósito do Projeto

Este projeto existe para **formar desenvolvedores completos**, capazes de:

- ✅ Projetar sistemas corporativos reais  
- ✅ Compreender obrigações legais e fiscais (LGPD, NF-e, SPED)  
- ✅ Estruturar software escalável e sustentável  
- ✅ Escrever código limpo, seguro e testável  
- ✅ Transformar teoria em produto funcional, ético e inclusivo  

> **Aqui, você não aprende apenas a “programar telas”.**  
> **Você aprende a engenharia por trás de um ERP real.**

---

## 🧠 O que você aprenderá na prática

| Área | Habilidades Desenvolvidas |
|------|---------------------------|
| **Engenharia de Software** | Fundamentos sólidos, arquitetura limpa, separação de responsabilidades |
| **Arquitetura PHP Moderna** | MVC real, PSR-4, Composer, Services, Repositories, DTOs, Value Objects |
| **Conformidade Legal** | LGPD nativa, consentimento, anonimização, política de privacidade |
| **Sistemas Fiscais** | Estruturação de NF-e/NFC-e, integração com SEFAZ, XML, DANFE |
| **Acessibilidade** | WCAG 2.2 AA, navegação por teclado, leitores de tela, semântica HTML |
| **Infraestrutura** | Docker, HTTPS, logs, backup, deploy, observabilidade |
| **APIs e Integração** | RESTful seguras, padrões de resposta, autenticação |
| **Pedagogia Técnica** | Evolução progressiva, decisões justificadas, erros evitados |

---

## 🏛️ Pilares do ConstruaSeuERP

### 🛡️ 1. Conformidade Legal e Ética (by design)
- LGPD aplicada desde o banco de dados  
- Gestão de consentimento explícito  
- Anonimização automática após prazo legal  
- Política de privacidade integrada às views  
- Trilhas de auditoria (logs de acesso a dados sensíveis)

### 🧾 2. Fiscal e Empresarial (mundo real)
- Estruturação de dados fiscais (produtos, clientes, fornecedores)  
- Fundamentos da NF-e / NFC-e (modelo 55 e 65)  
- Preparação para comunicação com SEFAZ (homologação e produção)  
- Geração de XML assinado, DANFE e controle documental  
- Organização de cadastros fiscais (CFOP, NCM, CST, CSOSN)

### ♿ 3. Acessibilidade como Requisito, não como Extra
- WCAG 2.2 nível AA implementado desde o primeiro componente  
- Navegação total por teclado  
- Compatibilidade com leitores de tela (NVDA, JAWS)  
- Semântica HTML correta (`<label>`, `role`, `aria-*`)  
- Contraste adequado, foco visível e usabilidade real

### 🏗️ 4. Arquitetura Profissional
- PHP 8.3+ com tipagem rigorosa  
- MVC real (não “MVC de fachada”)  
- DDD aplicado quando pertinente  
- Camadas claras: Domain → Application → Infrastructure → Interfaces  
- Containers (Docker) para ambiente replicável  
- Organização limpa de responsabilidades (SRP, SOC)

### 🎓 5. Engenharia Pedagógica
Cada branch não é apenas código.  
**Cada branch é um capítulo vivo do livro**, com:
- Evolução arquitetural clara  
- Decisões técnicas justificadas  
- Erros comuns evitados  
- Padrões explicados em contexto  
- Preparação progressiva para produção

---

## 🌿 Estrutura do Repositório (por Módulos)

Cada **branch** representa um **módulo didático + evolução real do sistema**.

| Módulo | Branch | Conteúdo Central |
|--------|--------|------------------|
| **Fundamentos** | [`modulo-1-conceitos`](https://github.com/alexcsilva/construaseuerp/tree/modulo-1-conceitos) | ERP, engenharia de software, LGPD, NF-e, acessibilidade, visão sistêmica |
| **Arquitetura Base** | [`modulo-2-mvc-completo`](https://github.com/alexcsilva/construaseuerp/tree/modulo-2-mvc-completo) | MVC profissional, PHP 8.3+, Composer, Bootstrap 5.3, Docker |
| **Privacidade Aplicada** | [`modulo-3-lgpd-nativa`](https://github.com/alexcsilva/construaseuerp/tree/modulo-3-lgpd-nativa) | Consentimento, anonimização, políticas, base legal, auditoria |
| **Integração** | [`modulo-4-api-rest`](https://github.com/alexcsilva/construaseuerp/tree/modulo-4-api-rest) | API RESTful, autenticação, padrões de resposta, webhooks |
| **Produção** | [`main`](https://github.com/alexcsilva/construaseuerp/tree/main) | Sistema completo com todos os módulos integrados, pronto para expansão |

> ⚠️ A branch `main` representa a **obra final**: um ERP funcional, modular, documentado e **pronto para produção**.

---

## 🛠️ Como Utilizar o Projeto

### 🔹 1. Clonar o repositório
```bash
git clone https://github.com/alexcsilva/construaseuerp.git
cd construaseuerp
### 🔹 2. Escolher o módulo de estudo
```bash
1
git checkout modulo-1-conceitos
ou

```bash
1
git checkout modulo-2-mvc-completo
✅ Cada branch contém o estado exato do projeto naquele capítulo do livro.

###🔹 3. Instalar dependências
```bash
1
composer install
###🔹 4. Configurar ambiente
```bash
12
cp .env.example .env
# Edite .env com suas credenciais
###🔹 5. Iniciar com Docker
```bash
12
###🔹 6. Acessar
Abra seu navegador em:
👉 http://localhost

---

##🧩 Público-Alvo
Este projeto é indicado para:

-🎓 Estudantes de TI e cursos técnicos
-🧑‍💻 Autodidatas em busca de formação profissional
-👩‍🏫 Professores que desejam material didático realista
-💼 Desenvolvedores iniciantes e intermediários
-🏢 Profissionais que querem migrar para sistemas corporativos
-🏫 Equipes de ensino técnico e superior
-📜 Licença e Filosofia
Este projeto é educacional, técnico e social.
Foi idealizado para:

Democratizar o ensino de engenharia de software
Formar profissionais conscientes e éticos
Reduzir a distância entre teoria e prática
Respeitar leis, pessoas e acessibilidade
Licença: MIT License — use, modifique, distribua e ensine livremente.

---

✍️ Autor
Alex Correia da Silva

de Pastos Bons
Pesquisador independente em engenharia de software, sistemas fiscais e educação tecnológica
Autor do livro ConstruaSeuERP
Defensor da tecnologia como ferramenta de justiça social e desenvolvimento local
🌐 Site Pessoal
📧 alexsilva2018@gmail.com
📚 GitHub

🧠 Conclusão Técnica
O ConstruaSeuERP não é “mais um sisteminha em PHP”.

Ele é:

🔬 Um laboratório de engenharia de software aplicada
📚 Um modelo didático progressivo
🏭 Um protótipo de ERP brasileiro realista
❤️ Uma obra técnica com responsabilidade legal, social e pedagógica
Feito com propósito em Pastos Bons, Maranhão — para o Brasil inteiro.
