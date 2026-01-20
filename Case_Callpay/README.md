# Conciliação Financeira — CallPay Solutions

## Contexto
Este projeto simula um cenário real de conciliação financeira em uma empresa fictícia
chamada CallPay Solutions, responsável por faturamento e cobrança de clientes.

## Tecnologias utilizadas
- SQLite
- SQL
- Excel

## Desafio
Conciliar faturas emitidas com boletos pagos, identificando:
- Faturas pagas corretamente
- Faturas não pagas
- Divergências de valores

## Solução
- Importação dos dados para o SQLite
- Conciliação utilizando SQL com LEFT JOIN
- Aplicação de regras de negócio com CASE WHEN
- Exportação do resultado para Excel
- Criação de indicadores financeiros

## Indicadores gerados
- Total faturado
- Total recebido
- Quantidade de faturas pagas
- Quantidade de faturas não pagas
- Quantidade de divergências

## Resultado
Foi possível identificar inadimplência e divergências de pagamento, fornecendo uma visão
clara da saúde financeira da empresa.

## Aprendizado
Projeto desenvolvido simulando demandas reais de empresa, com foco em análise de dados,
tratamento de informações e entrega dentro de prazo.
