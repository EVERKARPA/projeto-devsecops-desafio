# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
> 🚀 Em DevOps (CI/CD) entendemos que a pipeline automatiza o ciclo de desenvolvimento:
Código é enviado (commit)
Testes são executados
Build é gerado
Deploy acontece automaticamente.
> O Gitleaks foi utilizado com o objetivo de procurar coisas que não deveriam estar no código, como senhas e chaves.
> O Semgrep examina o código sem executar - para encontrar bugs, vulnerabilidades e más práticas.
> O Grype é uma ferramenta usada para encontrar vulnerabilidades em dependências e imagens de containers.
> O GitHub Pages é um serviço do GitHub que permite publicar sites estáticos diretamente de um repositório.

## URL de Produção
> https://github.com/EVERKARPA/projeto-devsecops-desafio
