<p align="center">
<img src="assets/capa.png" alt="Comunicações Automatizadas" width="100%">
</p>

<h1 align="center">Comunicações Automatizadas</h1>
<p align="center"><i>Envio de e-mails personalizados com anexos a partir de uma base em Excel</i></p>

<p align="center">
<img src="https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square" alt="Power Automate">
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square" alt="Excel">
<img src="https://img.shields.io/badge/E--mail-0078D4?style=flat-square" alt="E-mail">
<img src="https://img.shields.io/badge/status-conclu%C3%ADdo-2DD4BF?style=flat-square" alt="status: concluído">
</p>

## Sumário

- [Sobre](#sobre)
- [Problema e solução](#problema-e-solução)
- [Funcionalidades](#funcionalidades)
- [Como funciona](#como-funciona)
- [Tecnologias](#tecnologias)
- [Benefícios](#benefícios)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Autor](#autor)

## Sobre

Fluxo automatizado no **Power Automate** para envio de **comunicações personalizadas**. O fluxo lê uma base de dados em **Excel**, gera e envia **e-mails personalizados com anexos**, padronizando e automatizando a comunicação em larga escala.

> [!NOTE]
> Projeto desenvolvido em ambiente corporativo. O código-fonte e os dados não são publicados por conterem informações internas; este repositório documenta o problema, a solução e o funcionamento.

## Problema e solução

| | |
| --- | --- |
| **Problema** | Enviar comunicações individuais, com anexos, para muitos destinatários era um trabalho manual, demorado e sujeito a erros. |
| **Solução** | Um fluxo que percorre a base em Excel e monta cada e-mail automaticamente, com os dados e o anexo de cada destinatário. |

## Funcionalidades

- Leitura automatizada da base em Excel
- Personalização da mensagem para cada destinatário
- Envio de e-mails com anexos
- Padronização das comunicações em larga escala

## Como funciona

```mermaid
flowchart LR
    A[Base em Excel] --> B[Power Automate]
    B --> C{Para cada linha}
    C --> D[Monta e-mail personalizado]
    D --> E[Anexa arquivo]
    E --> F[Envia e-mail]
    F --> C
```

Detalhes: [Como funciona](docs/como-funciona.md)

## Tecnologias

| Tecnologia | Uso no projeto |
| --- | --- |
| Power Automate | Orquestração do fluxo |
| Excel | Base de destinatários e dados |
| E-mail | Canal de envio das comunicações |

## Benefícios

- Menos trabalho manual no envio
- Comunicação padronizada
- Escala sem aumento de esforço

## Estrutura do repositório

```text
power-automate-comunicacoes/
├── assets/
│   └── capa.png
├── docs/
│   └── como-funciona.md
└── README.md
```

## Autor

**Rodrigo Lemes** · Analista de TI · Microsoft 365, AD/Entra ID, Automação, Power BI e IA aplicada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rodrigo%20Lemes-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigoalemes/)
[![GitHub](https://img.shields.io/badge/GitHub-rodrigoalemes-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rodrigoalemes)
