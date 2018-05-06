# API
Desafio Citra
Durante o processo encontrei algumas dificuldades porém estou feliz de ter tentado, aprendi bastante nessa semana, porem não posso dizer
que cumpri com o desafio, afinal não criei a aplicação Angular, instalei o angular começei a desenvolver o corpo colocando um navbar para cada função e
um campo texto para receber o json.
Json foi outra coisa que tive que procurar e entender a estrutura para saber como realizar o mapeamento das classes, utilizei como ferramenta 
esse site:https://jsonformatter.curiousconcept.com/#about o mesmo ajuda a enxergar o json de forma mais clara pois quando coloquei a url ou o corpo
do json enviado no postman, nao conseguia enviar a requisição para a api. Desta forma coloquei no postman a seguinte estrutura:


{
   "listaControleLancamento":[  
      {  
         "lancamentoContaCorrenteCliente":{  
            "numeroRemessaBanco":64320236054,
            "nomeSituacaoRemessa":"Pago",
            "dadosDomicilioBancario":{  
               "codigoBanco":123,
               "numeroAgencia":1,
               "numeroContaCorrente":"00000000065470"

            },
            "nomeTipoOperacao":"regular"
         },
         "dataEfetivaLancamento":"03/06/2016",
         "dataLancamentoContaCorrenteCliente":"03/06/2016",
         "numeroEvento":42236790,
         "descricaoGrupoPagamento":"LA-56",
         "codigoIdentificadorUnico":"1",
         "nomeBanco":"BANCO ABCD S.A.             ",
         "quantidadeLancamentoRemessa":22,
         "numeroRaizCNPJ":"12996721",
         "numeroSufixoCNPJ":"1597",
         "valorLancamentoRemessa":11499.1,
         "dateLancamentoContaCorrenteCliente":1464922800000,
         "dateEfetivaLancamento":1464922800000
      }
]}

e o mesmo json porem com o primeiro item da lista separo




Caso tenha problemas com a porta da api é possivel mudar a porta que a mesma está utilizando no caso a 8080
colocando no applicationproprietes o codigo"server.port=(numero de porta livre)"


espero que goste do meu trabalho
ainda continuarei usando essa api para aprender mais com hibernate mais sobre Rest quando se possui um banco para comunicar.
Grato Ronald Guedes
