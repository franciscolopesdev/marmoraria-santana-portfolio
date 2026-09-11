<p align="center">
  <img src="assets/cover.svg" alt="Marmoraria Santana" width="100%"/>
</p>

<h1 align="center">Marmoraria Santana</h1>

<p align="center">
  Plataforma comercial para descoberta, inspiração, materiais e orçamento estruturado.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=nextdotjs&logoColor=ffffff" alt="Next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-1F2937?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Supabase-0F172A?style=for-the-badge&logo=supabase&logoColor=3ECF8E" alt="Supabase"/>
  <img src="https://img.shields.io/badge/Zod-18181B?style=for-the-badge&logo=zod&logoColor=3E67B1" alt="Zod"/>
  <img src="https://img.shields.io/badge/Playwright-111827?style=for-the-badge&logo=playwright&logoColor=2EAD33" alt="Playwright"/>
</p>

> **Status:** Prévia comercial desenvolvida para apresentação — código e dados de produção permanecem privados.

## Visão geral

Transformar uma presença digital tradicional em uma jornada comercial capaz de ajudar o visitante a descobrir materiais, explorar ambientes, se inspirar em projetos e chegar ao atendimento com contexto suficiente para iniciar um orçamento.

Este repositório é uma **vitrine técnica/documental**. O objetivo é demonstrar decisões de arquitetura, produto, UX e engenharia sem publicar código proprietário, credenciais, dados reais ou configurações internas.

<table>
<tr>
<td align="center"><strong>31</strong><br/><sub>páginas/rotas compiladas</sub></td>
<td align="center"><strong>18/18</strong><br/><sub>cenários aprovados</sub></td>
<td align="center"><strong>100</strong><br/><sub>acessibilidade na auditoria</sub></td>
<td align="center"><strong>Preview</strong><br/><sub>noindex + validação</sub></td>
</tr>
</table>

## Minha atuação

Atuação em **arquitetura, desenvolvimento full stack, integração, UX, validação, testes e refinamento da experiência**.

## Stack

Next.js • React • TypeScript • Tailwind CSS • React Hook Form • Zod • Supabase • Playwright

## Principais funcionalidades

- Exploração de materiais
- Projetos e ambientes em formato editorial
- Fluxo de orçamento em múltiplas etapas
- Persistência de intenção e contexto
- Upload de referências
- Integração contextual com WhatsApp
- Estrutura administrativa
- Autenticação e storage privado
- Modo preview com noindex
- Testes desktop e mobile

## Arquitetura

<p align="center">
  <img src="assets/architecture.svg" alt="Arquitetura de alto nível" width="100%"/>
</p>

> O diagrama é propositalmente de alto nível para não expor detalhes sensíveis da implementação.

## Decisões técnicas

### Validação server-side
Dados enviados passam por validação antes da persistência.

### Storage privado
Referências e anexos são tratados em estrutura privada com acesso controlado.

### Preview seguro
A prévia permanece noindex e separa conteúdo confirmado de elementos ainda pendentes de validação.

### Jornada por intenção
A navegação parte de três intenções: projeto, escolha de material e inspiração.

## Screenshots

<img src="assets/screenshots/home-full.png" alt="Marmoraria Santana — visão da página" width="100%"/>

## Privacidade e confidencialidade

Este repositório **não contém**:

- código-fonte de produção;
- arquivos `.env`;
- chaves, tokens ou credenciais;
- banco de dados real;
- dados pessoais;
- configurações internas;
- segredos comerciais.

As imagens utilizadas aqui servem somente para apresentar o trabalho realizado e não devem ser reutilizadas como material oficial das empresas sem autorização.

## Autor

**Francisco Lopes de Sousa Filho**  
Desenvolvedor Full Stack

[GitHub](https://github.com/franciscolopesdev) • contactdevlps@gmail.com
