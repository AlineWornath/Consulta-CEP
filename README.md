# Consulta CEP

Desenvolve uma solução para os problemas de desempenho na busca, localização, e validação de CEP.

## Resolução:
 *Problema 1: Erros e lentidão nas consultas de CEP*

Nossa aplicação utiliza a biblioteca java.net.HttpURLConnection, que ajuda a executar requisições HTTP. 
Utilizaremos a API externa ViaCEP, que é gratuita, fácil de usar e apresenta alto desempenho para consulta de CEP no Brasil. A API permite que façamos requisições HTTP e recebamos informações em formato JSON.
Criaremos um método que recebe um CEP como parâmetro e retorna uma classe do tipo Endereço. Trataremos os dados, convertendo JSON para String,  e faremos um mapeamento do que foi retornado com a classe Endereço. 

 *Problema 2: Falta de informações detalhadas sobre a região do comprador:*
As causas do problema precisam ser avaliadas. Caso se trate de 

 *Problema 3: CEP inexistente ou mal formatado:*
Incluir validações para garantir que o input do usuário atenda aos    requisitos básicos(por exemplo, apenas números digitados). Implementar no sistema a formatação padrão.
Checar em tempo real a existência do CEP na base de dados.
