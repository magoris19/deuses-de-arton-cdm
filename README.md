# Deuses de Arton — CDM

Módulo de compêndios para Tormenta20 no Foundry Virtual Tabletop. A versão `0.1.0` reúne 60 atores no compêndio **Ameaças**. Os compêndios **Itens** e **Diários** estão reservados para conteúdo futuro.

## Requisitos

- **Foundry VTT 14.369** e **Tormenta20 1.6.6**, versões de origem das fichas. A compatibilidade com outras combinações ainda precisa ser verificada.
- **CDM Icons** para carregar os retratos e tokens. [Repositório do CDM Icons](https://github.com/magoris19/cdm-icons)
- Algumas referências nas fichas abrem itens de compêndios externos. Esses links dependem de [Ameaças de Arton — CDM](https://github.com/magoris19/ameacas-de-arton-cdm) ou [Suplementos de Arton](https://github.com/mobguilherme/Suplementos-de-Arton).

## Instalação pelo manifesto

Na tela inicial do Foundry, abra **Módulos complementares → Instalar módulo** e cole a URL abaixo no campo **URL do manifesto**.

```text
https://raw.githubusercontent.com/magoris19/deuses-de-arton-cdm/main/module.json
```

Depois de instalar, entre em um mundo de Tormenta20 e ative **Deuses de Arton — CDM** em **Gerenciar módulos**. Abra o compêndio **Ameaças** para importar fichas para o mundo.

A instalação fica disponível quando a [release `v0.1.0`](https://github.com/magoris19/deuses-de-arton-cdm/releases/tag/v0.1.0) tiver o anexo `deuses-de-arton-cdm.zip`. O Foundry lê o manifesto e baixa o arquivo indicado em `download`.

## Empacotamento de uma versão

O ZIP deve ter `module.json` e `packs/` na raiz. A versão do manifesto deve corresponder à tag, e `download` deve apontar para o ZIP anexado a essa release. Mantenha a URL em `manifest` estável entre versões. [Documentação de pacotes do Foundry](https://foundryvtt.com/article/package-management/)

*Deuses de Arton* é uma publicação da Jambô Editora. Adaptação de compêndios por Magoris. [Página do suplemento](https://jamboeditora.com.br/produto/tormenta20-deuses-de-arton/)
