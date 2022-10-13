## Contexto

A classe Pessoa representará o hóspede, já as classes Suíte e Reserva, farão um relacionamento entre ambos.

Este programa calculará os valores dos métodos da classe Reserva, que trará a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% caso a reserva seja para um período maior que 10 dias.

## Validações:

1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva retorna a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria retorna o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, é concedido um desconto de 10% no valor da diária.
