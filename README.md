Payment_Service é um serviço de faturas de pagamento, onde o usuário entra com o seu numero de identificação, data e o valor de contrato

O contrato possui 1% de juro simples mensal + 2% de taxa de pagamento ja em cima dessse juros mensal
ex:

input:
numero:**8028**
Data:**25/03/2024**
Valor do contrato: **600.00**
Parcelas: **3**

output:

25/04/2024 
**206,04**

(200+1%*1=202
202+2%=**206.04**)

25/05/2024 
**208,08**

(200+1%*2=204
204+2%=**208.08**)

25/06/2024 
**210,12**

(200+1%*3=2026
202+2%=**210.12**)
