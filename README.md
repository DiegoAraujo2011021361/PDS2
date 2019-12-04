# PDS2
Trabalho prático

Sistema de gestao de RH -  folha de pagamento

Funções:

- Realizar consulta de informações sobre pagamento de todos os funcionários de uma empresa no mês corrente.
- Realizar consulta sobre pagamento de cada funcionário individualmente no mês corrente.
- Calcular salário de funcionários que recebem comissão.
- Calcular salário de funcionários que não são comissionados.
- Exibir informações na tela.

Teste:

- Executar o programa.
 
- Escolher entre as opções de consultar dados de todos funcionários ou consultar individualmente cada funcionário. 
  Para tal deve se digitar 1 ou 2 no menu de seleção.

- Digitando um 1, o programa busca no arquivo clients.dat a pelos dados de todos funcionários de uma empresa. Posteriormente  exibe essas informações na tela. Essa etapa pressupõe que numa situação real o arquivo seria disponibilizado por outro dispositivo, como uma máquina de ponto. 

- Digitando um 2, o programa  entra na opção de consulta individual. A matricula do funcionário é requerida. 
  Deve se digitar um numero de 1 a 10, pois o quadro de funcionários é de 10 pessoas . 
  Em seguida é feito uma busca no arquivo clients.dat por um determinado funcionário mediante uma chave. 
  Uma vez encontrado, o um objeto (SalarioBase empregado) é criado.

- O objeto é instanciado pelo construtor explicitamente com os dados obtidos pela leitura do registo do funcionário do arquivo clients.dat.

- Finamente, as funções membro da Classe SalarioBase e ComissãoEmpregado são chamadas para fornecer os dados e operações requisitadas.

- O salario total é calculado pela função ganhos(), que retorna a soma do salario base com a comissão, quando aplicada.


Observações:

-Foram utilizados os seguintes conceitos no desenvolvimento do TP:  

	* Encapsulamento;
	* Herança;
	* Separação entre a interface e implementação de uma classe;
	* Validação de entradas;
	* Leitura e manipulação de arquivos.
