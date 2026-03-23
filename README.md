🥖 Sistema de Gerenciamento - Padaria Peter Pão
Este é um projeto em Python desenvolvido para modernizar o atendimento da Padaria Peter Pão, permitindo que clientes visualizem o cardápio, façam pedidos personalizados e escolham a forma de entrega e pagamento de forma automatizada.

O programa utiliza estruturas de dados para organizar o carrinho de compras, categorias de produtos e processamento de finalização de pedidos.

🚀 Funcionalidades
O sistema está dividido em módulos principais:

Acesso e Cadastro: Sistema de login seguro e registro de dados do cliente (E-mail, CPF, Endereço).

Cardápio Interativo: Navegação por categorias (Salgados, Doces, Bebidas e Promoções) com exibição de preços.

Carrinho Dinâmico (CRUD): Adição de itens ao pedido com cálculo automático de subtotal em tempo real.

Logística Flexível: Opção para o cliente escolher entre Retirada no Estabelecimento ou Entrega (Delivery).

Multi-Pagamento: Suporte para diversas modalidades: Dinheiro, PIX, Cartão de Crédito ou Débito.

Confirmação de Recebimento: Sistema de status que confirma quando o pedido foi enviado com sucesso para a cozinha da padaria.

🛠️ Tecnologias e Estruturas Utilizadas
O projeto foi construído utilizando conceitos fundamentais de Python, focando em lógica de programação pura:

Listas ([]): Utilizadas para armazenar os itens do carrinho de compras durante a sessão.

Dicionários ({}): Gestão da tabela de preços e nomes de produtos para busca rápida.

Laços de Repetição (while): Mantêm o menu interativo ativo até que o cliente decida sair.

Condicionais (if/elif/else): Responsáveis por toda a inteligência de navegação e validação de pagamentos.

Formatação de Dados: Uso de f-strings para exibição de valores monetários corrigidos (R$).

📋 Como Executar
Certifique-se de ter o Python 3.x instalado.

Salve o código em um arquivo chamado padaria_peter_pao.py.

Abra o terminal ou prompt de comando.

Execute o comando:

Bash
python padaria_peter_pao.py
📖 Exemplo de Uso
Ao iniciar o programa, o usuário seguirá este fluxo:

Identificação: O sistema saúda o cliente pelo nome.

Seleção: O cliente navega no menu "3", escolhe uma "Coxinha" e um "Suco".

Revisão: No menu "4", o cliente vê a lista de itens e o total de R$ 9,00.

Finalização: Escolhe "Entrega", define "PIX" como pagamento e recebe a confirmação: “O estabelecimento recebeu seu pedido!”.

Desenvolvido como projeto de aprendizagem em lógica de programação com Python.
