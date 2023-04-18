# tabelafipe

•	Introdução
 	A Tabela Fipe expressa preços médios de veículos no mercado nacional, servindo apenas como um parâmetro para negociações ou avaliações. Os preços efetivamente praticados variam em função da região, conservação, cor, acessórios ou qualquer outro fator que possa influenciar as condições de oferta e procura por um veículo específico.
 O ano do veículo refere-se ao ano do modelo e não são considerados veículos para uso profissional ou especial.
 Os valores são expressos em R$ (reais) do mês/ano de referência.

Referencia: Fundação Instituto de Pesquisas Econômicas – Fipe, 2023, 
disponível em: <https://veiculos.fipe.org.br/> Acesso em 17 de abril de 2023

•	Arquitetura

O framework utilizado para a implementação do front-end é o Angular, que possui uma arquitetura orientada a componentes. 
Para o armazenamento, consulta e alteração de dados da aplicação, será usada a API da Tabela FIPE, que disponibiliza um conjunto de serviços REST. Onde o cliente envia uma requisição a uma URL (endpoint) para acessar os serviços da API, e tem como retorno um objeto na forma de um JSON.
