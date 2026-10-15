# Recuperador de Orçamentos | Automação com n8n

## Sobre o projeto

Sistema de automação comercial desenvolvido para ajudar empresas a recuperar oportunidades de vendas, acompanhar orçamentos pendentes e reduzir o trabalho manual dos vendedores.

A solução utiliza **n8n, Google Sheets e WhatsApp**, permitindo organizar contatos e automatizar lembretes comerciais.

## Problema que a automação resolve

Muitas empresas perdem oportunidades porque os vendedores não conseguem acompanhar todos os orçamentos enviados.

Com esta automação, os orçamentos pendentes são monitorados diariamente, reduzindo o risco de esquecimentos e facilitando o acompanhamento dos clientes.

## Funcionalidades

- Consulta automática dos orçamentos cadastrados no Google Sheets.
- Identificação de orçamentos pendentes.
- Envio de mensagens de acompanhamento aos clientes autorizados.
- Lembretes diários aos vendedores pelo WhatsApp.
- Atendimento a múltiplos vendedores, com instâncias de WhatsApp separadas.
- Controle de tentativas de contato.
- Atualização automática das informações na planilha.
- Verificação de datas para evitar lembretes duplicados no mesmo dia.

## Tecnologias utilizadas

- **n8n:** criação e execução dos fluxos de automação.
- **Google Sheets:** armazenamento e gerenciamento dos orçamentos.
- **Evolution API:** integração com WhatsApp.
- **Docker:** execução local dos serviços.
- **JavaScript:** expressões e condições utilizadas nos fluxos.

## Benefícios para empresas

- Economia de tempo nas tarefas repetitivas.
- Maior organização comercial.
- Acompanhamento sistemático de oportunidades.
- Menor risco de esquecer clientes interessados.
- Possibilidade de aumentar a conversão de orçamentos em vendas.

## Status do projeto

**Protótipo funcional, testado em ambiente local.**

Foram realizados testes de envio de mensagens pelo WhatsApp, lembretes para diferentes vendedores, execução agendada e atualização dos registros no Google Sheets.

## Arquivo do workflow

O arquivo `recuperador-de-orcamentos-portfolio.json` contém uma versão demonstrativa do fluxo n8n, preparada para apresentação do projeto, sem as credenciais reais de acesso.

Para utilizar a automação em outro ambiente, é necessário configurar as próprias credenciais e integrações.

## Próximas melhorias

- Implantação em servidor VPS.
- Painel de indicadores comerciais.
- Relatórios de acompanhamento de orçamentos.
- Adaptação para diferentes segmentos empresariais.

---

**Projeto desenvolvido para demonstrar conhecimentos em automação de processos comerciais, integração de sistemas e desenvolvimento de soluções com n8n.**
