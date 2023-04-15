# Linhas & Agulhas

Trabalhei anteriormente em uma indústria vidreira e desenvolvi um estudo de Análise de Dados para as vendas no ano de 2021, especificamente.
Todos os arquivos disponibilizados já foram anonimizados, criei uma "empresa" da indústria têxtil que assim como a vidreira, venderia seus produtos por metragem.

###### Aqui, você terá acesso a:
- Print do Dashboard feito em Power BI
- Arquivo notebook em Python que criei para anonimizar os dados, comentei tudo para melhor entendimento.
- Arquivo .pbix para caso queira interagir ou realizar alguma alteração
- Base de dados já feita para caso queira navegar.

## Passo a passo
- OBJETIVO: Realizar um estudo sobre as vendas feitas no ano de 2021 afim de identificar padrões, insights, pontos fortes e fracos e traçar, a partir disso, possíveis estratégias para o ano seguinte.

- EXTRAÇÃO: O banco de dados da empresa é baseado na linguagem SQL.
A partir disso, foram feitas consultas com o nome do cliente, metragem comprada, valor comprado, cidade do cadastro, roteiro de entrega e o período (mês) em referência.
Informações básicas para visualizar potencial de venda... Os resultados das consultas foram salvos em arquivos no formato .csv
- TRANSFORMAÇÃO: Inseri o arquivo .csv dentro do Power Query para fazer as devidas correções e ajustes nos mínimos detalhes, desde correção de ortografia até formatação dos valores para evitar discrepância.
A partir do arquivo já corrigido, transformei-o em uma tabela dentro do Excel e adulterei os valores de metragem e faturamento.
- ANONIMIZAÇÃO: No Anaconda Prompt instalei a biblioteca Faker com o comando "pip install Faker", logo em seguida desenvolvi o código que segue dentro dessa pasta... Ele foi capaz de substituir todos os nomes de clientes, vendedores e cidades.
- LOAD: Sabendo do que precisava ser apresentado ao público e como apresentar, criei o Dashboard no Figma tomando cuidado com paleta de cores, distribuição dos elementos visuais, etc.

## Pontos a melhorar 
Afinal de contas, sempre há o que melhorar. 
- Usar inúmeras ferramentas diferentes para coleta e tratamento... Caso houvesse proficiência em uma única ferramenta, ela bastaria para que eu fosse mais eficaz.
- Na próxima oportunidade que eu tiver, ao invés de cidades fictícias, usarei cidades verdadeiras em um determinado perímetro.

###### Estamos no caminho! Estou em constante desenvolvimento.
