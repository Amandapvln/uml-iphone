# iPhone
Este projeto implementa a funcionalidade de um iPhone com três componentes principais: Reprodutor Musical, 
Aparelho Telefônico e Navegador na Internet. Cada componente é representado por uma interface que define seus comportamentos, 
e a classe iPhone implementa as três interfaces.

<h2>Funcionalidades</h2>
<ul>
<li>Reprodutor Musical: tocar, pausar, selecionar música</li>
<li>Aparelho Telefônico: ligar, atender, iniciar correio de voz</li>
<li>Navegador na Internet: exibir página, adicionar nova aba, atualizar página</li>
</ul>

<h2>Implementação</h2>
As interfaces MusicPlayer, Phone e WebBrowser definem os comportamentos dos componentes do iPhone. A classe abstrata Device implementa as interfaces, 
e a classe iPhone herda de Device.
<br>
As implementações das interfaces são injetadas na classe iPhone através do construtor, permitindo que as implementações possam ser trocadas sem alterar a classe iPhone.
<br>
O código está escrito em Java e utiliza interfaces funcionais para reduzir a quantidade de código necessário para criar implementações das interfaces.

<h2>Execução</h2>
O projeto pode ser executado através do arquivo Main.java, 
que cria uma instância da classe iPhone e chama alguns dos métodos das interfaces para demonstrar as funcionalidades do iPhone.

<h2>Melhorias Futuras</h2>
Algumas melhorias que poderiam ser feitas no projeto incluem:
<ul>
<li>Adicionar validação de entrada de dados nos métodos das interfaces</li>
<li>Implementar testes unitários para garantir o correto funcionamento das interfaces e suas implementações</li>
<li>Utilizar uma biblioteca de injeção de dependência para tornar a injeção de dependência mais fácil de usar e configurar</li>
</ul>
<br>
Este é um projeto apenas a nível de estudo e o que foi oferecido como proposta para o desafio do curso Java Developer da plataforma de ensino da DIO.
