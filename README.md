# SupermarketPython
# Descrição

Este é um sistema de supermercado desenvolvido em Python, projetado para gerenciar o cadastro de clientes, produtos e carrinhos de compras, além de realizar o processo de compra. O sistema simula o funcionamento de um supermercado simples, onde os clientes podem adicionar produtos ao carrinho, verificar o estoque e concluir a compra. Ele é composto por classes para representar produtos, clientes, carrinhos e o supermercado, além de um terminal de interação para o usuário.

# Funcionalidades

1. **Cadastro de Produtos**:
   - O sistema permite cadastrar novos produtos no supermercado, especificando o nome, preço e a quantidade disponível em estoque.

2. **Cadastro de Clientes**:
   - Os clientes podem ser registrados com seus dados pessoais, como nome e CPF, para que possam interagir com o sistema de compras.

3. **Visualização de Produtos**:
   - O administrador pode visualizar todos os produtos disponíveis no supermercado, incluindo detalhes como nome, preço e quantidade em estoque.

4. **Adição de Produtos ao Carrinho**:
   - Os clientes podem adicionar produtos ao carrinho, especificando a quantidade desejada. O sistema verifica se há estoque suficiente para a quantidade solicitada e, se disponível, adiciona o produto ao carrinho.

5. **Finalização de Compras**:
   - Quando o cliente decide concluir a compra, o sistema calcula o total da compra (baseado nos produtos e quantidades no carrinho) e exibe o valor final. Após o pagamento, o carrinho é esvaziado.

6. **Controle de Estoque**:
   - Quando um produto é adicionado ao carrinho, a quantidade em estoque é automaticamente atualizada. O sistema impede que o cliente adicione mais unidades do que as disponíveis.

7. **Interface Simples de Texto**:
   - A interação com o sistema é feita por meio de um terminal de comandos, onde o usuário escolhe entre as várias opções, como cadastrar produtos, visualizar o estoque e gerenciar o carrinho de compras.

# Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o sistema.
- **Conceitos de Programação Orientada a Objetos**: Utilização de classes para representar entidades como produtos, clientes e carrinhos de compras.

# Como Usar

1. Clone o repositório para sua máquina local.
2. Execute o código Python em seu terminal.
3. Siga as instruções no terminal para interagir com o sistema.
   - Cadastrar produtos.
   - Registrar clientes.
   - Adicionar produtos ao carrinho.
   - Finalizar compras.

# Estrutura do Código

O código é dividido em várias classes que representam os componentes do sistema:

- **Produto**: Representa um produto no estoque, com atributos como nome, preço e quantidade disponível.
- **Cliente**: Representa um cliente, com métodos para adicionar produtos ao carrinho.
- **Carrinho**: Representa o carrinho de compras do cliente, calculando o total da compra e gerenciando os produtos.
- **Supermercado**: Controla o estoque de produtos, gerencia clientes e processa a finalização das compras.
- **Terminal**: Responsável pela interface com o usuário, fornecendo um menu interativo de opções.

# Possíveis Melhorias Futuras

- **Persistência de Dados**: Atualmente, os dados são perdidos ao fechar o programa. Implementar uma solução de banco de dados ou salvar os dados em arquivos seria uma melhoria importante.
- **Interface Gráfica**: Para uma experiência mais intuitiva, seria interessante criar uma interface gráfica com o uso de bibliotecas como Tkinter ou PyQt.
- **Validações e Erros**: Melhorar a validação de entradas, como verificar formatos de CPF e preços válidos.
- **Relatórios de Vendas**: Adicionar funcionalidades para gerar relatórios detalhados de vendas realizadas, produtos mais vendidos e estoques baixos.

# Autor
Erick Vinícius
