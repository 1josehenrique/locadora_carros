# 🚗📋 Locadora de Carros 🚗📋

Este é um programa simples de locadora de carros, escrito em Python. Ele permite consultar os carros disponíveis, alugar um carro, devolver um carro e sair do programa.

### Como usar o programa
1️⃣ Execute o programa e será exibido um menu com as opções disponíveis.

2️⃣ Escolha a opção desejada digitando o número correspondente no teclado.

3️⃣ Se selecionar a opção 1, será exibida a lista de carros disponíveis para aluguel.

4️⃣ Se selecionar a opção 2, será exibida a lista de carros disponíveis e você poderá escolher um modelo para alugar. Informe o número do carro desejado e siga as instruções para concluir o aluguel.

5️⃣ Se selecionar a opção 3, será exibida a lista de carros alugados. Você poderá escolher um carro para devolver informando o número correspondente.

6️⃣ Se selecionar a opção 4, o programa será encerrado.

### Recursos adicionais
O programa faz uso da função clear_output do módulo IPython.display para limpar a saída do console e melhorar a legibilidade.

O programa mantém duas estruturas de dados principais: car_inventory (dicionário) para armazenar os carros disponíveis e seus preços, e rented_cars (dicionário) para armazenar os carros alugados.

Ao alugar um carro, ele é removido da lista de carros disponíveis e adicionado à lista de carros alugados.

Ao devolver um carro, ele é removido da lista de carros alugados e adicionado de volta à lista de carros disponíveis.

### Aviso
Este programa é apenas uma demonstração e não possui funcionalidades de persistência de dados. Isso significa que, ao reiniciar o programa, todos os carros disponíveis e alugados serão redefinidos aos valores iniciais.

Divirta-se alugando carros! 🚗💨




