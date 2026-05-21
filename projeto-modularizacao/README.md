🛒 Sistema de Caixa Modularizado
📝 Descrição do Projeto
Este projeto consiste em um sistema de caixa modularizado desenvolvido a partir de fluxogramas e pseudocódigos. O objetivo principal é simular o funcionamento básico de um caixa de mercado ou loja, realizando operações como:

Soma de produtos;
Aplicação de descontos;
Cálculo de média dos produtos;
Validação de pagamento;
Cálculo de troco.
O sistema foi estruturado utilizando funções independentes, promovendo organização, reutilização de código e facilidade de manutenção.

⚙️ Funcionalidades do Sistema
🔹 Validação de Produtos
Responsável por realizar a leitura dos preços dos produtos e calcular o valor total da compra.

Fluxo:
Inicializa o total com valor 0;
Lê os preços dos produtos;
Soma os valores enquanto o preço for diferente de 0;
Retorna o valor total da compra.
🔹 Aplicação de Desconto
Aplica desconto automático caso o valor total ultrapasse um determinado limite.

Regra aplicada:
Se o total da compra for maior que 100, é aplicado 10% de desconto.
🔹 Média dos Produtos
Calcula a média de valor dos produtos inseridos.

Regra aplicada:
media = total / quantidade
