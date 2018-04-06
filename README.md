# Mockup Funcional da Aplicação Pet Shop

## Definição de Mockups

The most common use of mockups in software development is to create user interfaces that show the end user what the software will look like without having to build the software or the underlying functionality. Software UI mockups can range from very simple hand drawn screen layouts, through realistic bitmaps, to semi functional user interfaces developed in a software development tool.

## Objetivos

Desenvolver um mockup semi funcional da interface gráfica (lado cliente) da aplicação Pet Shop, com base nos requisitos apresentados na seção seguinte
Aplicar os conhecimentos em HTML5 e CSS3 abordados em sala

## Visão Geral

Um cliente solicita o desenvolvimento de uma aplicação web para sua pet shop. Essa loja fornece serviços (tosa, banho, vacina, etc), bem como produtos para sua clientela. Essa aplicação deve gerenciar tanto os produtos e serviços envolvidos, quanto os clientes que agendam idas à loja com seus animais de estimação.

## Requisitos

* O sistema deve ter 2 tipos de usuários: Cliente e Administrador
 + Administradores são responsáveis pelo cadastro/gerenciamento de administradores, clientes e de produtos/serviços providos. A aplicação já vem com um administrador, admin, com password admin.
 + Clientes são usuários que acessam o sistema para cadastro de animais, agendamento de horários, compra de produtos.

* O registro de administradores inclui, pelo menos: nome, id, foto, telefone, email.

* O registro de cada cliente inclui, pelo menos: nome, id, endereço, foto, telefone, email

* Cada animal de estimação é registrado sob um cliente responsável. Ele inclui nome, id, foto, raça, idade.

* Registros de produtos incluem, pelo menos: nome, id, foto, descrição, preço, quantidade (em estoque), quantidade vendida. Produtos podem ser, por exemplo: comida de cachorro/gato, casinhas, osso de brinquedo, coleiras, etc.

* Registro de serviços incluem, pelo menos: nome, id, foto, descrição, preço.

* Clientes podem agendar um horário via web para serviços
 + O calendário deve exibir janelas de horários (slots) livres para serem usadas. Clientes não podem cancelar um horário.
 + O calendário deve cobrir, pelo menos, 10 semanas com, pelo menos 10 slots por dia.
 + Horários ocupados mostram o nome e foto do serviço e o nome do animal do cliente que fez a reserva.
 + Cada slot livre deve mostrar um serviço ou vazio. Quem quiser fazer com mais de um serviço por slot, pode.
 + Recomendo fazer com apenas um serviço por slot.

* Venda de produtos: Produtos são selecionados, sua quantidade escolhida e são incluídos num carrinho. Os produtos são comprados, com o uso de um número de cartão de crédito. A quantidade do produto vendido é subtraída da quantidade em estoque e somada a quantidade vendida. Carrinhos são esvaziados apenas no pagamento ou pelos clientes.
* Venda de serviços: Serviços são selecionados e pagos, no momento da contratação, com um número de cartão.  Administradores podem ver e editar todos os produtos (podem modificar a quantidade em estoque, por exemplo) e serviços.
* Gerenciamento de produtos/serviços: Administradores podem criar novos produtos e serviços.
* Tela de ganhos: Mostra uma lista com todas as vendas de serviços e produtos e o total, por serviços e produtos.

## O que deve ser entregue

Arquivo texto (txt, pdf ou word) com o nome e número USP de todos os alunos do grupo, descrição do que cada arquivo submetido tem e qualquer explicação que você queira dar sobre o seu trabalho.

Arquivos html5 e css3 para cada tela do sistema. Você deve usar o estilo de Single-Page Application. Lembre-se que HTML5 tem várias widgets que podem ser usadas (buttons, textboxes, checkboxes, etc.) e elas ainda podem ser renderizadas com diferentes estilos CSS3. Não use nenhum framework JavaScript. Não precisa incluir qualquer JavaScript.

## Sugestões de Tela

Essas são apenas sugestões de telas, fiquem livres para usarem outras combinações.

* Pagina inicial com descrição de serviços/produtos oferecidos e área para login (qualquer tipo de usuário)
* Caso o usuário seja cliente:
 + Tela com as ações: agendar horário, comprar produto, editar seu registro, cadastrar/listar animais
 + Tela com o calendário do mês e lista de horários para selecionar um serviço.
 + Tela com detalhes de um animal cadastrado e detalhes como a situação atual (quantos serviços estão reservados para ele e o custo total).

* Caso o usuário seja administrador
 + Tela com as ações: cadastrar administradores/clientes/produtos/serviços/etc) em um menu
 + Tela para gerenciamento dos serviços, onde é possível associar serviços a slots de horário, liberar slots reservados, etc.
 + Tela para gerenciamento de estoque de produtos (adicionar, atualizar, apagar, consultar)
