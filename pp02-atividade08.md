## Atividade 08: Praticando TDD

### Missão: Implementar um projeto usando TDD 

1. Criar um repositório no Github com o nome Exercicios-TDD e copiar a URL do repositório
2. Criar um projeto Java Project com o nome Aula2505
3. Ir para a pasta do projeto e clonar o repositório Exercicios-TDD
4. Desenvolver a atividade abaixo e submeter os códigos-fontes para o repositório remoto.

#### Sistema de Pagamentos 
###### Funcionalidade: Processador de Boletos
###### Domínio: Boleto, Pagamento, Fatura, Crédito

_*Objetivo*: Fazer a consistência dos boletos e faturas pendentes de um cliente. Para isso, a soma dos boletos precisam ser maior ou igual ao valor da fatura . Caso seja maior, deverá ser gerado um crédito para o cliente._

*Regras da funcionalidade:*
- [ ] Uma Fatura contém data, valor total e nome do cliente. 
- [ ] Um Boleto contem código do boleto, data, e valor pago. 
- [ ] Um Pagamento contém o valor pago, a data e o tipo do pagamento efetuado (neste caso BOLETO).
- [ ] Um Crédito conteḿ o valor de crédito, nome do cliente, data de emissão. 
- [ ] A funcionalidade ‘Processador de boletos’ deve receber uma lista de boletos e uma fatura.
- [ ] Para cada boleto deverá ser criado um Pagamento. 
- [ ] Caso a soma dos boletos seja menor que o valor da fatura, marcar a fatura como NÃO-PAGA.
- [ ] Caso a soma dos boletos seja maior ou igual ao valor da fatura, marcar a fatura como PAGA.
- [ ] Caso a soma dos boletos ultrapasse o valor da fatura, deverá ser gerado um crédito com o valor adicional. 

*Exemplo de uso da funcionalidade:*

ENTRADA | COMPORTAMENTO ESPERADO
------- | ---------------------------
Fatura de 1.500,00 com 3 boletos no valor de 500,00, 400,00 e 600,00 | Fatura marcada como PAGA, Três pagamentos do tipo BOLETO criados
Fatura de 1.500,00 com 3 boletos no valor de 1000,00, 500,00 e 250,00 | Fatura marcada como PAGA, Três pagamentos do tipo BOLETO criados, Um crédito de 250,00
Fatura de 2.000,00 com 2 boletos no valor de 500,00 e 400,00 | Fatura marcada como NAO-PAGA, Dois pagamentos do tipo BOLETO criados 
