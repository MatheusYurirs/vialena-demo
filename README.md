# Vialena — Demonstração v0.6

Protótipo **demonstrativo** da Vialena, produto em desenvolvimento pela M.Yuri Tech.

## Acesso

Após configurar o GitHub Pages: [Abrir demonstração](https://matheusyurirs.github.io/vialena-demo/).

## O que você pode experimentar

- Cadastrar **pacientes fictícios**.
- Agendar, reagendar e cancelar consultas de exemplo.
- Registrar atendimentos demonstrativos e rascunhos separados por paciente e registro.
- Registrar avaliações corporais por perimetria, dobras cutâneas, bioimpedância ou método combinado.
- Consultar histórico e evolução demonstrativos.

## Aviso importante

**Não use dados reais de pacientes.** Este protótipo não possui backend, autenticação, persistência, armazenamento seguro de prontuários, ou autorização entre profissionais. Os registros preenchidos existem somente na sessão de execução e podem se perder ao recarregar a página. O protótipo não é um dispositivo de bioimpedância nem ferramenta de diagnóstico clínico.

## Implantação

A hospedagem deste repositório é estática. Em **Settings → Pages**, selecione `Deploy from a branch`, branch `main` e pasta `/(root)`. A página inicial está em `index.html`. O arquivo `.nojekyll` desativa o processamento do Jekyll.

## Versionamento

Adotamos [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/) e tags [SemVer](https://semver.org/lang/pt-BR/). A referência inicial deste repositório é `v0.6.0-demo.1`.

## Desenvolvimento futuro

A versão full-stack v0.7 será planejada em repositório separado; não publicar códigos de backend, segredos ou dados clínicos nesta demonstração.
