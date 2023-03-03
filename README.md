01-A programação orientada a objetos é um paradigma de programação que se baseia na ideia de criar objetos
que possuem atributos e métodos, permitindo a organização e reutilização de código de forma mais eficiente e modular.

02-Encapsulamento, herança, polimorfismo e abstração.

03-Uma classe é um elemento do código Java que utilizamos para representar objetos do mundo real.

04-Uma vez que a classe a partir da qual deseja-se criar o objeto exista, a criação do objeto dá-se através
da aplicação do operador new: new NomeDaClasse();

05-Cria uma instancia de um tipo de objeto definido pelo usuário ou de um dos tipos nativos (built-in)
que possuem uma função construtora.

06-Java e C são ambas linguagens de programação que suportam programação estruturada, são compiladas em
código de máquina e usam sintaxe semelhante para declaração de variáveis e estruturas de controle de fluxo.

07-Paradigma de programação, gerenciamento de memória, portabilidade, bibliotecas, e velocidade de execução.

08-A classe InputReader é uma classe em Java que fornece métodos para ler dados de entrada a partir do console
 ou de um arquivo. Sua função é permitir que o programa obtenha entradas do usuário ou de arquivos para uso em
 processamento posterior.

09-O método readDouble na classe InputReader é usado para ler um valor do tipo double (número de ponto flutuante)
a partir da entrada do usuário ou de um arquivo. Ele retorna o valor lido como um double.

10-A interface PaymentType é uma interface em Java que define métodos para diferentes tipos de pagamento (por exemplo, 
cartão de crédito, PayPal, etc.). Ela é utilizada no programa para fornecer uma estrutura comum para processar diferentes
tipos de pagamento, permitindo que o código do programa seja mais modular e extensível.

11-A classe PaymentTypeSelector em Java é responsável por permitir que o usuário selecione um tipo de pagamento a ser  
utilizado por meio da entrada de dados fornecida pelo console ou por um arquivo. A classe usa a interface PaymentType 
para criar uma lista de opções de pagamento e permite que o usuário selecione uma opção, com base na qual é retornado
 o objeto correspondente à opção selecionada.

12-A classe PaymentTypeSelector utiliza as classes PixPayment, CreditPayment e BoletoPayment por meio da interface
PaymentType. As três classes implementam a interface PaymentType e são retornadas como opções de pagamento na lista
de opções gerada pela classe PaymentTypeSelector.

13-Polimorfismo é um conceito da programação orientada a objetos que permite que um objeto de uma classe seja tratado
 como se fosse de outra classe, desde que a outra classe seja uma superclasse ou interface implementada pela classe 
 atual. No programa, o polimorfismo é utilizado quando as classes PixPayment, CreditPayment e BoletoPayment implementam 
 a interface PaymentType, permitindo que sejam tratadas como objetos do tipo PaymentType. Isso permite que o código do 
 programa seja mais modular e extensível, facilitando a adição de novos tipos de pagamento no futuro.

14-O método getName na interface PaymentType e nas classes que a implementam tem a finalidade de retornar o nome do 
tipo de pagamento. Esse método é utilizado no programa para exibir as opções de pagamento disponíveis para o usuário 
selecionar, apresentando o nome do tipo de pagamento na lista de opções.

15-A classe Scanner é usada em Java para ler valores de entrada fornecidos pelo usuário e é utilizada no programa para 
obter os valores necessários para processar pagamentos, como nome, número do cartão de crédito e valor da transação.

16-Uma exceção em Java é um evento que ocorre durante a execução de um programa que interrompe o fluxo normal de execução.
No método selectPaymentType da classe PaymentTypeSelector, a exceção é tratada por meio de um bloco try-catch que captura
e trata a exceção gerada caso o usuário selecione um tipo de pagamento inválido ou inexistente. O bloco catch exibe uma
mensagem de erro ao usuário e solicita que ele selecione um tipo de pagamento válido a partir das opções disponíveis.

17- Para adicionar um novo tipo de pagamento ao programa, seria necessário criar uma nova classe que implemente a interface 
PaymentType e fornecer uma implementação para os métodos exigidos pela interface. Em seguida, essa nova classe seria 
adicionada às opções de pagamento disponíveis na classe PaymentTypeSelector.

18-Interfaces são importantes no desenvolvimento de sistemas orientados a objetos porque permitem que diferentes classes 
implementem um conjunto comum de métodos, o que promove a reutilização de código e a modularização do sistema. Além disso,
as interfaces fornecem uma abstração que permite que as classes que as implementam sejam intercambiáveis, permitindo que
o sistema seja mais flexível e extensível.

19-Uma classe abstrata é uma classe que pode conter métodos abstratos e concretos, bem como variáveis de instância, 
enquanto uma interface é uma coleção de métodos abstratos e constantes. Uma classe pode estender apenas uma classe
abstrata, mas pode implementar várias interfaces.

20-Encapsulamento é o conceito de esconder os detalhes de implementação de uma classe dos usuários externos e 
fornecer uma interface consistente para interagir com a classe. No programa, o encapsulamento é aplicado por meio
da declaração de variáveis de instância como privadas, o que restringe o acesso a elas a métodos públicos específicos,
garantindo assim o controle sobre as modificações feitas nos atributos da classe.

21-Para melhorar a legibilidade do programa, seria possível adicionar comentários explicativos em trechos de código
complexos, utilizar nomes de variáveis e métodos mais descritivos e dividir o código em métodos menores com funcionalidades
bem definidas. Isso tornaria mais fácil entender o que o programa faz e como ele funciona.

22-A classe Main é o ponto de entrada do programa e é responsável por iniciar a execução do mesmo. Nela é criada uma 
instância da classe PaymentProcessor, que é responsável por processar o pagamento selecionado pelo usuário.

23-Um construtor padrão é um construtor que não possui parâmetros e é automaticamente gerado pelo compilador, caso 
nenhum construtor seja definido na classe. Ele é utilizado quando não há necessidade de inicializar variáveis de instância
da classe durante a criação de objetos ou quando as variáveis de instância têm valores padrão.
 
24-Para proteger o programa contra erros de entrada do usuário, é possível utilizar técnicas como validação de entrada, 
tratamento de exceções e fornecer mensagens de erro claras e precisas para orientar o usuário sobre como fornecer entrada 
válida. Por exemplo, é possível verificar se o tipo de entrada fornecido corresponde ao tipo esperado e se a entrada está 
dentro de um intervalo válido, entre outras validações. Se um erro de entrada ocorrer, o programa pode ser projetado para 
tratar a exceção adequadamente e informar ao usuário sobre o erro ocorrido.

25-A utilização de nomes descritivos ajuda a tornar o código mais legível e compreensível, tornando mais fácil para outros
desenvolvedores entenderem a função e o objetivo de cada classe, método ou variável. Isso também torna o código mais fácil
de manter e modificar, pois torna mais fácil identificar o que cada parte do código faz. Além disso, nomes descritivos 
ajudam a evitar ambiguidades e reduzir a chance de erros causados por má interpretação do código.

26-Herança é um conceito da orientação a objetos que permite que uma classe (chamada de classe derivada ou subclasse) 
herde atributos e métodos de outra classe (chamada de classe base ou superclasse). No programa, por exemplo, seria possível
criar uma classe "PaymentWithDiscount" que herda da classe "Payment" e acrescenta a funcionalidade de aplicar um desconto ao
valor do pagamento. Isso permitiria reutilizar o código da classe "Payment" sem precisar escrever todo o código novamente na 
nova classe.

27-A sobrecarga de métodos permite definir vários métodos com o mesmo nome em uma classe, porém com assinaturas diferentes, 
ou seja, com parâmetros diferentes. No programa, seria possível utilizar a sobrecarga de métodos para criar diferentes 
versões do método "selectPaymentType", com parâmetros diferentes, como por exemplo, uma versão que recebe um valor mínimo 
para pagamento com cartão de crédito e outra que recebe uma lista de opções de pagamento. Isso permite que o código seja 
mais flexível e possa ser reutilizado em diferentes contextos.
