# Automação de Relatórios do Google Ads

Este projeto foi criado para automatizar a extração de dados do Google Ads e exportá-los para o Google Sheets. Foi meu primeiro contato com scripts e APIs, e estou muito feliz com o resultado!

## Configuração do Ambiente
1. Acesse o [Google Apps Script](https://script.google.com/).
2. Crie um novo projeto e cole o código.
3. Substitua `ID_PLANILHA` pelo ID da sua planilha.
4. Execute a função `main` para testar.

## O que o script faz?
1. **Coleta dados do Google Ads**: Extrai informações como cliques, impressões, custos e conversões das campanhas.
2. **Exporta para o Google Sheets**: Os dados são automaticamente salvos sempre na mesma planilha, organizados por campanha, dia e dispositivo.
3. **Executa automaticamente**: O script pode ser configurado para rodar no primeiro dia de cada mês, trazendo os dados do mês anterior.

## Como funciona?
- O script usa a **API do Google Ads** para buscar os dados.
- Ele calcula automaticamente o primeiro e o último dia do mês anterior.
- Os dados são salvos em uma planilha do Google Sheets, com cabeçalhos claros para facilitar a análise.

## Como usar?
1. Substitua `ID_PLANILHA` pelo ID da sua planilha no Google Sheets.
2. Execute o script no **Google Apps Script**.
3. Pronto! Os dados serão exportados automaticamente.

## Exemplo de saída no Google Sheets

| Data do Relatório | Campanha       | Status de campanha | Dia      | Dispositivo | Cliques | Impressões | CTR   | CPC méd. | Custo  | Conversões | Conv. de visualização | Taxa de conv. |
|-------------------|----------------|--------------------|----------|-------------|---------|------------|-------|----------|--------|------------|-----------------------|---------------|
| 2023-09-01        | Campanha 1     | Ativa              | Segunda  | Mobile      | 150     | 5000       | 3.0%  | 0.50     | 75.00  | 10         | 2                     | 6.67%         |
| 2023-09-01        | Campanha 2     | Pausada            | Terça    | Desktop     | 200     | 8000       | 2.5%  | 0.60     | 120.00 | 15         | 3                     | 7.50%         |

## O que aprendi com esse projeto?
- Como trabalhar com **APIs** e scripts.
- Como **automatizar tarefas repetitivas**.
- Como integrar ferramentas como Google Ads e Google Sheets.

## Próximos passos
- Adicionar mais fontes de dados.
- Criar dashboards automáticos no Power BI.

, por Aline Raulino. 💜
