# Arquitetura — Marmoraria Santana

## Objetivo

Documentar as decisões de alto nível que orientaram o projeto sem expor detalhes proprietários.

![Arquitetura](../assets/architecture.svg)

## Validação server-side
Dados enviados passam por validação antes da persistência.

## Storage privado
Referências e anexos são tratados em estrutura privada com acesso controlado.

## Preview seguro
A prévia permanece noindex e separa conteúdo confirmado de elementos ainda pendentes de validação.

## Jornada por intenção
A navegação parte de três intenções: projeto, escolha de material e inspiração.

## Limites desta documentação

A documentação pública omite deliberadamente código-fonte, credenciais, endpoints internos, esquemas completos de banco, dados de clientes e configurações de infraestrutura.
