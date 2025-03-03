# Análise Exploratória de Vendas de um Supermercado

Nesse projeto, o objetivo principal é analisar dados de uma empresa de supermercado utilizando Python e algumas das bibliotecas mais utilizadas em Análise Exploraótio de Dados.

## Dataset

O dataset utilizado está disponível no Kaggle no link:https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

## Variáveis

_Invoice ID_: Número de identificação da fatura do recibo de venda gerado por computador
_Branch_: Filial do supermercados (estão disponíveis 3 filiais identificadas por A, B e C).
_City_: Localização dos supermercados
_Custumer type_: Tipo de cliente, registado pelos Membros para clientes com cartão de sócio e Normal para sem cartão de sócio.
_Gender_: Tipo de gênero do cliente
_Product line_: Grupos de categorização geral de itens — Acessórios eletrônicos, Acessórios de moda, Alimentos e bebidas, Saúde e beleza, Casa e estilo de vida, Esportes e viagens
_Unit price_: Preço de cada produto em $
_Quantity_: Número de produtos adquiridos por
_Tax 5%_: taxa de imposto de 5% para compra do cliente
_Total_: preço total incluindo imposto
Date: Data da compra (Registro disponível de janeiro de 2019 a março de 2019)
Time: Horário da compra (10h às 21h
Payment: Pagamento usado pelo cliente para a compra (3 métodos disponíveis — Dinheiro, Cartão de crédito e Ewallet)
cogs: Custo dos produtos vendido
_gross margin percentage_: Porcentagem da margem bruta
_gross income_: Renda bruta
_Rating_: Classificação de estratificação do cliente em sua experiência geral de compra (em uma escala de 1 a 10)

## EDA

### _1 - Quais os produtos que são mais comprados por mulheres e homens?_
![image](https://github.com/user-attachments/assets/774c163d-681e-47df-a6b6-e15772bda0b5)

Produtos mais comprados por homens: Saúde e Beleza (530); Acessórios Eletronicos (483); Comidas e Bebidas (438); Esportes e Viagens (424); Casa e estilo de vida (413) e Acessórios de beleza (372).

Já as mulheres compram mais Acessórios de Beleza (530); Comidas e Bebias (514); Casa e Estilo de Vida (498); Esportes e Viagens (496); Acessórios Eletronicos (488) e Saúde e beleza (343).

Podemos notar que a grande maioria das vendas são realizadas por mulheres e que os produtos de saúde e beleza são muito mais consumidos pelos homens que pelas mulheres. Já para acessórios de beleza a diferença é grande na quantidade, representando uma volumetria muito maior para as mulheres.

É interessante analisar que o produto mais vendido para as mulheres é o menos vendido para os homens e o mesmo acontece no caso oposto.

### _2 - Quais os produtos mais vendidos?_
![image](https://github.com/user-attachments/assets/4ad1b2b9-5d9f-4c57-a5ee-32d57fe9a3fe)
Os produtos mais vendidos no supermercado são: Acessórios Eletrônicos (971), Bebidas e comidas (952), Esportes e Viagens (920), Casa e Estilo de Vida (911), Acessórios de beleza (902) e por último Saúde e Beleza (854).

### _3 - Qual o perfil de compra dos clientes do supermercado?_
![image](https://github.com/user-attachments/assets/0b0ca684-a4dd-4a9c-b7f7-30be1076b271)
O número de homens e mulheres é praticamente o mesmo, no total. Já se tratando da segmentação de clientes padrão ou membros, nota-se que as mulheres que participam dos membros são maioria enquanto os homens não participantes dos membros de descontos são minoria.

Uma análise posterior dos dados seria analisar quais as motivações que fazem as mulheres membros serem maioria, como por exemplo descontos em produtos específicos do sexo feminino, dias da semana de maiores compras, horários, etc.

### _4 - Qual o desempenho de vendas das 3 filiais?_
![image](https://github.com/user-attachments/assets/eab29ca8-a449-40d6-9efe-43f599a49c2c)
 Filial A (Yangon) é a filial que mais vendeu, seguido pela filial C (Mandalay) e em último a filial B (Naypyitaw)
 
### _5 - Existe um horário que ocorrem mais vendas? Se sim, quais são os períodos?_
![image](https://github.com/user-attachments/assets/f710ea7a-9d48-4845-9912-7654249270de)
As vendas acontecem principalmente nos horários de 10h, 13h, 15h e 19h. Todos esses horários tem a quantidade de vendas acima de 100 unidades.

### _6 - Clientes que são Membros tem receita maior que os clientes padrão?_
![image](https://github.com/user-attachments/assets/d629a10c-176f-4d00-a4f4-feaef869f3bf)
Clientes que são membros tem um ticket médio ligeiramente maior que os clientes padrão
