# storeapp_dlang
StoreApp escrito em D com acesso ao banco de dados MongoDB (Community)

Esse trabalho visa construir um aplicativo do tipo binário para gestão de lojas de comércio (ou pequenas fábricas artesanais),
que consiga rodar um computadores de 32 e 64 bits com alto desempenho, sendo que o banco de dados, por questão de suporte de hardware,
deverá estar em um computador de 64 bits.

![Tela principal](https://github.com/felipebastosweb/storeapp_dlang/blob/main/screenshots/home.png)

Foi observado que a maioria das linguagens de programação não dão mais suporte a computadores de 32 bits, o que não acontece com a linguagem D que ainda é compatível com esse tipo de hardware. Foi observado também que linguagens de programação como o Ruby, que apresenta bom desempenho no desenvolvimento do sistema pela equipe apresenta um péssimo rendimento em execução do sistema em computadores de 64 bits, tornando assim o custo computacional muito alto. Desta forma, a linguagem de programação D foi escolhida por se tratar de uma linguagem com recursos modernos, ser orientada a objetos, e apresentar ótimo rendimento em tempo de execução tanto em hardwares de 32 quanto de 64 bits (i386 e amd64). Isto se mostrou um fator muito importante no aproveitamento do poder computacional de dispositivos como netbooks e computadores mais antigos em lojas de pequeno porte. Ou nos foi permitido pensar, até mesmo, no aproveitamento de recursos computacionais em países pobres através de sucatas de informática. Desta forma, fica explícito também o carater social desse projeto ao qual visa abranger a inclusão tecnológica de todos os países, principalmente os mais pobres ou as populações mais carentes.

# Como instalar
Para instalar basta fazer o download do arquivo binário (storeapp.exe) na seção de releases localizada à direita dessa página --->>.
## Atualização
Para fazer a atualização do projeto basta baixar o arquivo binário storeapp.exe na seção de releases e substituir o arquivo já instalado.

# Rodar
Basta abrir o executável no shell ou console de sua preferência (Prompt de Comandos, Power Shell, etc) usando o comando: .\storeapp.exe. Em seguida, abrir a página http://localhost:8080 no navegador.

# O que já funciona
Aqui estão descritas algumas das telas que já estão funcionando (falta fazer o print das demais telas de CRUD destes recursos).

* [Gestão de Usuários](https://github.com/felipebastosweb/storeapp_dlang/blob/main/users.md)
* [Gestão de Marcas](https://github.com/felipebastosweb/storeapp_dlang/blob/main/brands.md)
* [Gestão de Fornecedores](https://github.com/felipebastosweb/storeapp_dlang/blob/main/suppliers.md)
* [Gestão de Produtos](https://github.com/felipebastosweb/storeapp_dlang/blob/main/products.md)
* [Gestão de Compras](https://github.com/felipebastosweb/storeapp_dlang/blob/main/purchases.md)
* [Gestão de Pedidos](https://github.com/felipebastosweb/storeapp_dlang/blob/main/orders.md)

# O que será produzido em breve
Estes são os próximos recursos a serem desenvolvidos no sistema:
  - Autenticação de Usuário e Permissão
  - Adição de Itens à Compra efetuada (W.I.P)
  - Adição de Pagamento a Compra (W.I.P)
    - forma de pagamento, data de pagamento
    - datas de parcelas do cartão
  - Cancelamento de Compra
  - Cadastro de Clientes (W.I.P)
  - Gráfico de Crescimento de Cadastro de Clientes na Tela Home
  - Cadastro de Pedidos (W.I.P)
  - Gráfico de Crescimento de Pedidos na Tela Home
  - Adição de Itens ao Pedido (W.I.P)
  - Cancelamento de Pedido
  - Adição de Pagamento ao Pedido (W.I.P)
  - Reembolso de Pedido Cancelado
  - Devolução de Produtos com Defeito
  - Troca de Produtos do Pedido
  - Cadastro de Contas à Pagar
  - Cadastro de Contas à Receber
  - Apagar recursos do banco de dados (W.I.P)
    - Usuários, Lojas, Marcas, Fornecedores, Compras, Produtos
    - Vendas, Clientes, Funcionários

