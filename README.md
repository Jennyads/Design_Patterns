<h3>Projetos desenvolvidos na formação da Plataforma Alura "Java com arquitetura e padrões de projeto"</h3>


<h4>Strategy</h4>

Todos os padrões de projeto definidos pela Gang of Four (GoF) possuem uma motivação: resolver um problema recorrente. 

Que tipo de problema o padrão Strategy visa resolver? A existência de diversos algoritmos para uma ação, resultando na possibilidade de vários ifs.Este padrão pode ser utilizado quando há diversos possíveis algoritmos para uma ação (como calcular imposto, por exemplo). Nele, nós separamos cada um dos possíveis algoritmos em classes separadas.

<h4>Chain of Responsibility</h4>

 Ter diversos if pode ser um problema, ter uma classe que "pode crescer para sempre" também é um problema.

Qual o problema real deste cenário, onde uma classe tem muitos if ou pode crescer para sempre?
Se precisar editar um pedaço de código, para implementar uma nova funcionalidade, as chances de quebrar funcionalidades existentes são grandes. Sempre que uma nova funcionalidade for implementada, o ideal é que possamos criar código novo e editar o mínimo possível de código já existente. Este é um dos principais pontos do princípio Aberto-Fechado (Open-Closed Principle) do SOLID. Ao editar código existente, podemos acabar quebrando funcionalidades já implementadas e funcionais.


<h4>Template Method</h4>

Aplica-se o Template Method com a criação de um método concreto na classe “mãe”, que chama métodos abstratos implementados nas classes “filhas”. 

Qual a principal vantagem da utilização desse padrão? Reaproveitar trechos de códigos comuns, evitando duplicações. O padrão Template Method favorece o reaproveitamento de códigos comuns entre classes, evitando assim duplicações de códigos.

<h4>State</h3>
O padrão State resolve um problema muito parecido com um problema resolvido por outro padrão.

Que outro padrão seria esse? O padrão State, assim como o padrão Strategy, resolve o problema de muitos ifs no código.
