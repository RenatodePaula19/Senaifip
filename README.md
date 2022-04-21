# Senaifip
SENAI TESTE IMAGEM 
![imagem teste senai falta de documentaçao](https://user-images.githubusercontent.com/103609825/164120693-db1aa8c3-474c-48e3-abaa-5f3cf4d27da4.jpg)


Casso de uso: Gerar excel com tabela fipe dos veículos: usuário pesquisa veículo e sistemas . Após a pesquisa, o execel gera uma tabela contendo todos as marcas, modelo e preços . 

Consultar fipe :Logo depois de apertar o botão de cosulta o programa busca as informaçoes na  api  (preço, marca, modelo.)

Enviar tabela por e-mail: Após terminar a pesquisa o programa automaticamente envia um email com a tabela excel. 
 
O usuário deve acessar a opção de envio da planilha gerada por e-mail . O usuário insere o e-mail desejado e clica no botão selecionar para buscar o relátorio em excel
Ele então seleciona o relatório e clica na opção enviar . O sistema emite  um alerta dizendo que o e-mail com o relatório foi enviado com sucesso .

O usuário acessa o sistema e seleciona em uma caixa de seleção o tipo de veículo que ele está buscando (caminhão , carro ou moto ) , deve informar também o ano inicial da busca e o ano final da busca . Após o usuário clicar no botão gerar planilha e o sistema começa a busca baseado nos parametros informados (caso de uso : consulta FIPE). Após gerar o relatório o sistema deve emitir um alerta dizendo que a atividade foi concluída com sucesso . O arquivo excel devem ser exibidos os seguintes dados: 
Código fipe do veículo , nome do veículo , valor , ano e tipo de combustível . 

<h3> caso de uso : Consulta FIPE </h3>
#-----------------------

O sistema deve realizar uma busca através de uma API  web que traz dados oficiais da tabela FIPE  quais são os veículos de acordo com os parametros selecionados . Esses 
dados irão compor a planilha excel . API CONSULTADA : 
