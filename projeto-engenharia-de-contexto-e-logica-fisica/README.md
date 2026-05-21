🧰 Coleção de Mini-Sistemas em Python
Este projeto consiste em um script Python que agrupa quatro ferramentas utilitárias independentes. Cada função foi projetada para resolver um problema cotidiano específico, abrangendo desde cálculos comerciais até simulações financeiras e análises de dados básicos.

🚀 Funcionalidades
O script é dividido em quatro módulos principais, executados sequencialmente:

1. Processador de Vendas (processar_vendas)
Um sistema de caixa simples que processa a compra de múltiplos produtos.

O que faz: Solicita a quantidade de produtos diferentes, lê o nome, preço e quantidade de cada item, e calcula o valor total.
Regra de Desconto:
Compras acima de R$ 500,00 recebem 10% de desconto.
Compras acima de R$ 200,00 recebem 5% de desconto.
Validação: Impede o registro de itens com preços ou quantidades negativas/zeradas.
2. Analisador de Clima Semanal (analisar_clima)
Ferramenta meteorológica básica para monitoramento de temperaturas ao longo de uma semana (7 dias).

O que faz: Calcula e exibe a temperatura média da semana e conta quantos dias registraram temperaturas acima de 35°C.
Sistema de Alerta: Dispara um aviso de perigo caso registre temperaturas extremas (acima de 45°C ou abaixo de -5°C).
3. Sistema de Notas Escolares (sistema_notas_turma)
Utilitário para professores gerenciarem as notas de uma turma.

O que faz: Solicita a quantidade de alunos, lê os nomes e duas notas para cada um, calculando a média aritmética.
Critérios de Avaliação:
Aprovado: Média >= 7.0
Recuperação: Média >= 5.0 e < 7.0
Reprovado: Média < 5.0
4. Simulador de Poupança e Investimento (simulador_poupanca)
Calculadora financeira de juros compostos com suporte a aportes mensais.

O que faz: Projeta o crescimento de um investimento inicial com base em uma taxa de juros mensal definida pelo usuário ao longo de um determinado período (em meses). Permite a adição de novos depósitos mês a mês.
Gamificação (Meta): Emite uma mensagem de parabéns no exato mês em que o saldo ultrapassa a marca de R$ 10.000,00.
