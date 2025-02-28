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

## O que aprendi com esse projeto?
- Como trabalhar com **APIs** e scripts.
- Como **automatizar tarefas repetitivas**.
- Como integrar ferramentas como Google Ads e Google Sheets.

## Próximos passos
- Adicionar mais fontes de dados.
- Criar dashboards automáticos no Power BI.

, por Aline Raulino. 💜
