# ProvaII_ES
Resolução da Prova de ES1<br><br>
Nome: Gabriel Fonseca Ferreira<br>
Matrícula: 21955310<br>
Contato: gf3612@gmail.com<br>
<br>
## Questão 1. Explique Ferramenta Case.

<p align="justify">Uma ferramenta CASE (do inglês Computer-Aided Software Engineering) é uma classificação que abrange toda ferramenta baseada em computadores que auxilia atividades de engenharia de software, desde análise de requisitos e modelagem até programação e testes. É uma ferramenta de apoio a modelagem de dados, utilizada para desenhar os modelos, gerar os scripts de criação das estruturas de dados e documentar essas estruturas.</p>

- <p align="justify">Uma característica dessa ferramenta é a de criação e ajustes dos diagramas, isso possibilita que criemos uma versão gráfica de um modelo de software e que ainda possibilita a migração para outras plataformas, desde que sejam feitos do mesmo padrão, como o XMI. Ele também valida um conjunto de modelos e a consistência entre eles.</p>

- <p align="justify">Temos também a característica de se ter a capacidade de interagir com o código-fonte do sistema em desenvolvimento. Há dois tipos: direta e reversa. A direta corresponde à possibilidade de geração de código-fonte a partir de diagramas produzidos com a ferramenta CASE em questão, já a reversa corresponde ao processo inverso, ou seja, a geração de diagramas a partir de código-fonte preexistente.</p>

- <p align="justify">Podemos citar também o rastreamento de requisitos que é uma praticidade importante em um processo de desenvolvimento. Rastrear um requisito significa poder localizar os artefatos de software gerados como consequência da existência daquele requisito. Essa funcionalidade é importante quando um requisito é alterado. Nesse caso, todos os artefatos correspondentes devem ser revisados.</p>
<br>

## Questão 2. Cite exemplos de três ferramentas e comente algumas de suas características.

<p align="justify">A maioria das ferramentas CASE atuais suporta a UML, sendo essa, em geral, sua principal característica. Entre as diversas ferramentas existentes hoje no mercado, podemos citar algumas:</p>

- <p align="justify">Enterprise Architect: é uma ferramenta muito fácil de utilizar. Embora não seja livre nem ofereça uma edição para a comunidade, é uma das ferramentas que mais oferecem recursos compatíveis com a UML em sua última versão. Apesar de não dispor de uma edição para a comunidade, a Sparx Systems, a empresa que produz a Enterprise Architect, disponibiliza uma versão trial, que pode ser utilizada por cerca de 60 dias, no site www.sparxsystems.com.au.</p>

- <p align="justify">Poseidon for UML: esta ferramenta também tem uma edição para a comunidade, apresentando bem menos restrições que a edição para a comunidade da Visual-Paradigm, mas a interface da Poseidon é sensivelmente inferior à VP-UML, além de apresentar um desempenho um pouco inferior, embora ambas as ferramentas tenham sido desenvolvidas em Java. Uma cópia da Poseidon for UML pode ser adquirida no site www.gentleware.com.</p>

- <p align="justify">ArgoUML: trata-se de uma ferramenta um tanto limitada, e sua interface não é das mais amigáveis e intuitivas. Porém, apresenta uma característica bastante interessante e atrativa: é totalmente livre. O projeto ArgoUML constitui-se em um projeto acadêmico, no qual os códigos-fonte dessa ferramenta podem ser baixados e utilizados até mesmo para o desenvolvimento de ferramentas comerciais, como foi o caso da Poseidon for UML. Os suários dessa ferramenta podem perceber muitas semelhanças entre as duas ferramentas, mas a Poseidon tem uma interface muito melhor e é, em geral, superior à ArgoUML. O projeto de código aberto ArgoUML exige apenas que quaisquer empresas que utilizarem seus códigos-fonte como base para uma nova ferramenta disponibilizem uma edição para a comunidade gratuitamente. Uma cópia da ArgoUML pode ser encontrada no site www.argouml.tigris.org</p>
<br>

## Questão 3. Explique a importância da UML.

<p align="justify">A modelagem é uma das principais atividades que levam à implementação de um bom software. Construímos modelos para comunicar a estrutura e o comportamento desejados do sistema, visualizar e controlar a arquitetura do mesmo e compreender melhor o sistema que estamos elaborando.
A modelagem de software utiliza vários modelos para projetar um determinado sistema. Um modelo é uma simplificação da realidade, criado para facilitar o entendimento de sistemas complexos. Estes modelos podem abranger planos detalhados, assim como planos mais gerais com uma visão panorâmica do sistema. 
Todos os sistemas podem ser descritos sob diferentes aspectos, com a utilização de modelos distintos, onde cada modelo será, portanto, uma abstração específica do sistema. Os modelos podem ser estruturais, dando ênfase à organização do sistema, ou podem ser comportamentais, dando ênfase à dinâmica do sistema.
Basicamente, UML (Unified Modeling Language) é uma linguagem de notação (um jeito de escrever, ilustrar, comunicar) para uso em projetos de sistemas.
Esta linguagem é expressa através de diagramas. Cada diagrama é composto por elementos (formas gráficas usadas para os desenhos) que possuem relação entre si.
Os diagramas da UML se dividem em dois grandes grupos como dito anteriormente: diagramas estruturais e diagramas comportamentais.</p>

- <p align="justify">Diagramas estruturais devem ser utilizados para especificar detalhes da estrutura do sistema (parte estática), por exemplo: classes, métodos, interfaces, namespaces, serviços, como componentes devem ser instalados, como deve ser a arquitetura do sistema etc.</p>

- <p align="justify">Diagramas comportamentais devem ser utilizados para especificar detalhes do comportamento do sistema (parte dinâmica), por exemplo: como as funcionalidades devem funcionar, como um processo de negócio deve ser tratado pelo sistema, como componentes estruturais trocam mensagens e como respondem às chamadas etc.</p>

<p align="justify">Dessa forma, nas próximas questões irão ser explicados de forma mais detalhada alguns dos diagramas citados.</p>

<br>

## Questão 4. Explique o Diagrama de Caso de Uso.

<p align="justify"></p>
<p align="justify">O caso de uso é utilizado para capturar os requisitos do sistema, ou seja, o que o software deve fazer a fim de atender as necessidades das partes interessadas pelo mesmo, partes estas que são conhecidas na área de projetos como stakeholders.
A UML apresenta o diagrama de casos de uso, que permite ao analista agrupar o comportamento esperado do sistema em rotinas de limites muito bem definidos, que farão a interação com os usuários. Contudo, além do diagrama, nos é oferecido a especificação dos requisitos na forma textual. Esse formato, na UML, é chamado de descrições informais, que nada mais são do que os cenários de cada caso de uso.
Os principais conceitos associados ao modelo de caso de uso são: atores e casos de uso.</p>

<p align="justify">Um ator representa um papel executado por um usuário ou por outro sistema que interaja com o sistema modelado. O ator não vai representar a pessoa e sim o papel que essa pessoa encena.
Um ator é representado visualmente por um ícone conhecido como stick man (homem palito), com o nome do ator abaixo ou acima do desenho. O mais comum é modelarmos abaixo. Outra representação para um ator é mostrá-lo como uma classe estereotipada, como por exemplo "Cliente". Por fim, podemos associar o ator a um ícone específico que indique o tipo do mesmo, como por exemplo a figura de um computador para representar um outro sistema que interaja com o sistema modelado. A vantagem dessa representação é separarmos a identificação visual de atores humanos dos atores não-humanos.</p>

<p align="justify">Um caso de uso é a especificação de um conjunto de ações executadas por um sistema, produzindo um resultado observável por um ou mais atores, e que são representadas por um cenário principal e cenários alternativos.
O principal objetivo de um caso de uso é mostrar o comportamento oferecido por um sistema (ou parte dele), sem fazer referência a sua estrutura interna.
Sua representação é feita por meio de uma elipse, com os títulos dos casos de uso no seu interior, ou abaixo dele.</p>

<p align="justify">São incluídos num diagrama de casos de uso os atores que interagem com o sistema, os casos de uso que representam os requisitos, e os relacionamentos existentes.
Os casos de uso representam conjuntos bem definidos de funcionalidades que não podem trabalhar sozinhas no contexto do sistema. Portanto, esses casos de uso precisam se relacionar com atores que enviarão e receberão mensagens deste, além de se relacionarem com os outros casos de uso do modelo.
Vejamos os relacionamentos existentes entre os elementos de um modelo de casos de uso:</p>

- <p align="justify">Para relacionamentos de casos de uso entre si temos: generalização, extensão e inclusão;</p>

- <p align="justify">Para relacionamentos de atores entre si temos um único tipo: generalização;</p>

- <p align="justify">Para relacionamentos entre atores e casos de uso temos apenas a associação.</p>

<p align="justify">No relacionamento de associação (que só existe entre atores e casos de uso) teremos um ator fazendo a chamada de uma instância do caso de uso.
</p>

<p align="justify">O relacionamento de generalização entre atores demonstra que há um compartilhamento de metas e propósitos. Isso permite, por exemplo, que possamos ter um determinado papel que herde todas as responsabilidades de um outro, acrescentando apenas as que lhe são inerentes.
</p>

<p align="justify">Já na generalização entre casos de uso, buscamos identificar o comportamento similar entre dois ou mais casos de uso, de forma a aproveitar as regras e soluções aplicadas para o primeiro caso. Isso também significa que um caso de uso filho herdará todos os relacionamentos existentes no caso de uso pai.</p>

<p align="justify">Entre casos de uso podemos ter relacionamentos de dependência, estereotipados como relacionamento de inclusão (include) ou extensão (extends).
</p>

<p align="justify">O relacionamento extends define um conjunto de comportamentos que incrementará a execução do caso de uso base. Contudo, o caso de uso base é definido independentemente do caso de uso de extensão. Assim, o caso de uso de extensão define um conjunto de comportamentos que incrementará a execução do caso de uso base de acordo com condições específicas. A extensão ocorre em um ou mais pontos de extensão específicos no caso de uso base.
De acordo com a documentação da UML, esse tipo de relacionamento é aconselhável a ser usado quando há algum comportamento adicional que deve ser acrescentado (possivelmente de forma condicional) ao comportamento de outro caso de uso. Não é raro eu ouvir o questionamento (quase afirmativo) de que o relacionamento de extensão é usado apenas para a modelagem de parte de um caso de uso que se considere como opcional. Não é verdade. É apenas uma das possibilidades. O relacionamento de extensão também pode ser utilizado para a modelagem de um subfluxo separado, que é executado somente sob determinadas condições. Isso significa que ele é condicional, não opcional.
Visualmente esse relacionamento é representado por uma seta com linha tracejada, cuja origem sai do caso de uso de extensão em direção ao caso de uso base. Junto à linha é colocado o estereótipo «extend». É possível ainda representar visualmente a condição para acionamento do relacionamento, as referências aos pontos de extensão. Essa representação é feita com uma nota ligada ao relacionamento extend.</p>

<p align="justify">O relacionamento include define que um caso de uso contém o comportamento definido em outro caso de uso.
O caso de uso incluído não é opcional, e é sempre requerido para que o caso de uso base execute corretamente. Esse tipo de relacionamento é utilizado quando há partes comuns de comportamento em dois ou mais casos de uso. Essa parte comum é então extraída para um caso de uso separado, para ser incluído por todos os casos de uso base que tenham essa parte em comum.
Visualmente esse relacionamento é representado por uma seta com linha tracejada, cuja origem sai do caso de uso base em direção ao caso de uso a ser incluído. Junto à linha é colocado o estereótipo «include».</p>
<br>

## Questão 5. Explique o Diagrama de Classe.

<p align="justify">A tarefa de encontrar classes entre um conjunto de requisitos requer questionamento e investigação. O caminho mais usual para essa tarefa é a de se encontrar as classes a partir dos cenários de casos de uso. Contudo, podemos partir também dos requisitos ainda brutos (não modelados em casos de uso), para obter uma primeira versão das classes que o sistema acolherá. Normalmente, essa segunda opção é realizada em sistemas de maior porte para se obter uma idéia macro de sua dimensão, antes que o trabalho duro tenha início; ou em sistemas de menor porte, para se ter a idéia precisa de seu tamanho.
Uma técnica simples para se encontrar uma classe é identificar os substantivos de uma lista de requisitos. Contudo, não se pode esquecer de analisar também as frases como um todo, pois algumas podem representar a conceituação de alguma classe candidata que não tenha sido explicitamente nominada nos requisitos.
As classes geralmente são divididas em 3 blocos: entidade, atributos e métodos.</p>

- <p align="justify">O primeiro bloco é destinado ao nome da Classe. Não basta apenas escrever o nome da classe num diagrama de classes; é preciso seguir a notação determinada pela UML, que consiste de: o nome da classe é escrito centralizado e em negrito; escrever as iniciais dos nomes das classes em maiúsculas, inclusive as primeiras letras de nomes compostos; Não se usa acentuação nem espaço no nome das classes. Apesar de ser permitido o uso do caractere underline (sublinhado), o mesmo não é usual, visto que a marcação de maiúscula na inicial de cada palavra composta já determina visualmente essa separação;</p>

- <p align="justify">O segundo e terceiro blocos são formados pelos atributos e métodos (ou operações) dessa classe. A UML oferece uma notação específica para os atributos e operações também: os atributos e operações devem ser escritos com formatação normal e alinhados à esquerda; os nomes de atributos e operações devem iniciar com letra minúscula, entretanto as iniciais das palavras compostas seguintes devem iniciar com letra maiúscula.</p>

<p align="justify">Um atributo pode ser expresso usando-se uma sintaxe simples: 
  
visibilidade nome : tipo

Uma operação pode ser expressa usando-se a seguinte sintaxe:

visibilidade nome (lista-de-parâmetros): tipo-de-retorno

A primeira característica que aparece em comum para os atributos e operações é a visibilidade. A visibilidade identifica por quem um atributo ou operação pode ser acessado. Divide-se em quatro tipos:</p>

- <p align="justify">público (public) ou +</p>

- <p align="justify">privado (private) ou -</p>

- <p align="justify">protegido (protected) ou #</p>

- <p align="justify">pacote (package) ou ~</p>

<p align="justify">(+) A visibilidade pública permite que o atributo ou operação seja acessado dentro da classe em que foi declarado, nas classes descendentes ou por qualquer elemento externo, incluindo-se as instâncias.

(-) A visibilidade privada é a mais restrita que existe. O atributo ou operação só poderá ser acessado dentro da classe em que foi declarado. Isso significa que ele será invisível para as classes filhas e para as instâncias.

(#) A visibilidade protegida determina que o atributo ou operação somente poderá ser visto dentro da classe em que foi declarado ou nas classes descendentes. As instâncias não acessam (enxergam) esse elemento.

(~) A visibilidade pacote determina que o atributo ou operação poderá ser visto dentro da classe em que foi declarado, nas classes descendentes ou por qualquer elemento externo, desde que estejam todos dentro do mesmo pacote da classe que declarou o elemento.

Exemplo:

~ nome : string

O nome de um atributo ou operação deve seguir as regras já descritas.

Para um atributo, tipo significa o tipo de dados desse atributo, j-a nos métodos são os tipos de retorno (ex: string, integer, float).

Juntando-se todas essas características podemos assim formar uma classe.

Após chegarmos a todas as classes definificas, partiremos para a relação de classes, e devemos identificar os relacionamentos existentes entre as mesmas. O relacionamento mais comum entre classes é o relacionamento de associação, representado por uma linha contínua ligando os dois lados. Nas extremidades dessa associação colocamos as cardinalidades, que representam essa associação entre elas definindo um número genérico para identificar como se dará essa associação, alguns exemplos são:

1..1 (1 para 1)<br>
0..1 (0 para 1)<br>
1..n (1 para muitos)<br>
0..n (0 para muitos)</p>
<br>

## Questão 6. Explique o Diagrama de Sequência.

<p align="justify">O Diagrama de Sequências é o principal dos quatro diagramas de interação. Os outros são: Diagrama de Comunicação, Diagrama de Visão Geral e Diagrama Temporal.

Um diagrama de interação tem por responsabilidade mostrar a interação entre os objetos de um sistema por meio de uma visão dinâmica. Essa interação entre objetos é representada por meio de mensagens. Ao se identificar as mensagens, estamos identificando os serviços oferecidos pelas classes. E, por sua vez, identificar os serviços significa que estamos descobrindo quais os métodos necessários a cada classe. Por isso, normalmente só chegamos a uma versão final do modelo de classes depois que passamos pelo diagrama de sequências, pois só com ele conseguimos enxergar claramente todos os métodos que serão necessários para atender aos casos de uso.
O Diagrama de Sequências enfatiza a troca de mensagens dentro de uma linha de tempo sequencial.

O Diagrama de Sequências não surge do nada e sim de uma modelagem feita a partir dos casos de uso, com o auxílio das classes já identificadas num modelo de classes. No caso de uso, estabelecemos a ordem das funcionalidades, sem nos preocuparmos com a implementação. Ao modelarmos o diagrama de sequências, representaremos por mensagens cada item descrito nos cenários principal e alternativos. Essas mensagens podem ser expressas do ator para o sistema, ou da interface para os objetos.
Ao se modelar um diagrama de sequências, em geral elaboramos ao menos um diagrama para cada caso de uso. Basicamente ele lida coma sequência de ações a partir de um caso de uso e ele exemplifica a troca de mensagens e dados no sistema com base nas restrições e condições na qual ele é inserido. 

Ao se modelar um diagrama de sequências, em geral elaboramos ao menos um diagrama para cada caso de uso. Primeiro desenhamos o mesmo ator do caso de uso no canto superior esquerdo. No topo desenhamos, em seguida, um objeto para representar a interface do sistema e um objeto para cada classe envolvida nesse caso de uso. A partir de cada objeto, incluindo o ator, desenharemos uma linha tracejada que é a linha de vida desse objeto. A linha de vida indica o tempo de vida desse objeto. Sendo colocada desde o início do diagrama é como se esse objeto fosse criado desde o início da rotina. Terminando no final do diagrama, indica que o objeto é destruído quando a rotina é encerrada. A maioria dos diagramas de sequências é desenhada dessa maneira. Contudo, se for necessário representar que um objeto é criado ou destruído durante a execução da rotina é possível fazê-lo.

Os objetos se diferenciam das classes por se apresentarem sublinhados. E podem ser desenhados com três notações diferentes:

nome do objeto : nome da classe

ou

: nome da classe

ou

nome do objeto

 A primeira notação traz primeiro um nome aleatório de objeto que será útil se precisarmos usar esse objeto como parâmetro de um método.

A segunda notação indica um objeto anônimo, ou seja, desconhecemos o nome do objeto por ele ser irrelevante, mas conhecemos a classe da qual ele é instanciado.

A terceira notação é a menos indicada, pois desconhecemos o nome da classe. Nesse caso o nome do objeto deve ser claro o suficiente para que o leitor identifique de qual classe ele foi instanciado.

A partir da estrutura inicial, já podemos desenhar as mensagens, que partem sempre de uma origem para o objeto destino que contém o serviço que se está querendo chamar. E assim se seguem com as condições e restrições de cada sistema até que todo o processo seja efetuado e encerrado.</p>
<br>

## Questão 7. Explique o Diagrama de Estado.

<p align="justify">Um estado representa a situação em que um elemento (muitas vezes um objeto), se encontra em determinado momento durante o período em que participa de um processo. Um estado pode demonstrar:</p>

- <p align="justify">A espera pela ocorrência de um evento;</p>

- <p align="justify">A reação a um estímulo;</p>

- <p align="justify">A execução de alguma atividade;</p>

- <p align="justify">A satisfação de alguma condição;</p>

<p align="justify">Um Estado Simples é um estado comum que não possui subestados.

Uma transição representa um evento que causa uma mudança no estado de um objeto, gerando um novo estado. Uma transição é representada por uma linha ligando dois estados, contendo uma seta em uma de suas extremidades, que aponta para o novo estado gerado. Uma transição pode conter ou não uma descrição.

O estado inicial determina o início da modelagem dos estados de um elemento. É representado por um círculo preenchido e pode conter ou não uma descrição, que pode identificar o evento que iniciou o processo.

O estado final tem como função indicar o final dos estados modelados. É representado por um círculo não preenchido.

As atividades internas são as atividades que o objeto pode executar quando estiver em um estado. Essas atividades podem ser detalhadas segundo as cláusulas:</p>

- <p align="justify">Entry: identifica uma atividade que é executada quando o objeto assume um estado;</p>

- <p align="justify">Exit: identifica uma atividade quando o objeto sai de um estado;
</p>

- <p align="justify">Do: identifica uma atividade realizada durante o tempo em que o objeto se encontra em um estado;</p>

<p align="justify">As duas primeiras cláusulas estão mais associadas às transições do que ao estado. As atividades internas são representadas em uma segunda divisão do estado.

As Transições Internas são aquelas que não produzem modificações no estado de um objeto.

As auto transições saem do estado atual do objeto e pode executar alguma ação dessa saída e retornam ao mesmo estado. Uma auto transição é representada por uma seta de transição que parte do objeto e retorna ao próprio objeto. 

Um Pseudo estado de escolha representa um ponto na transição de estados de um objeto em que deve ser tomada uma decisão, a partir da qual um determinado estado será ou não gerado.
Um pseudo estado de escolha representa uma decisão apoiada por condições de guarda, em que se decidirá qual o próximo estado do objeto a ser gerado.
Ele é representado pelo losango ou um círculo vazio de onde partem duas ou mais possíveis transições.

A barra de bifurcação determina o momento em que o processo passou a ser executado em paralelo e em quantos subprocessos se dividiu. A barra de união determina o momento em que dois ou mais subprocessos se uniram em um único processo.

Estado composto é o segundo tipo de estado e contém internamente dois ou mais estados, chamados subestados. Um estado composto pode apresentar somente uma região ou ser decomposto em duas ou mais regiões ortogonais, onde cada região terá estados e transições.

Um Pseudo estado histórico representa o registro do último subestado em que um objeto se encontrava, quando o processo tiver sido interrompido. O pseudo estado histórico, denotado por H, é utilizado para memorizar o último estado ativo quando se deixou um estado composto.
A flecha do H aponta para o estado default, ou seja, o subestado que é ativado na primeira vez em que o estado composto é alcançado. 

Os Estados Compostos Ortogonais é  quando um estado composto possui mais de uma região, onde uma região apresenta um conjunto de estados e os estados de cada região são assumidos paralelamente, o que força o processo a se dividir em dois ou mais subprocessos concorrentes. Os processos concorrentes são separados por uma linha tracejada.

O Estado de Sincronismo permite que duas ou mais regiões estejam sincronizados em um determinado momento do processo.

O Estado de Submáquina é equivalente a um Estado Composto ou Concorrente, no entanto, seus subestados não são descritos no diagrama, o que indica que estes terão de ser demonstrados em outro diagrama.
Representado por um retângulo com bordas arredondadas sem divisões internas e contendo em seu canto inferior esquerdo um símbolo que representa um diagrama de gráfico de estados, significando que o estado em questão possui subestados.

O Pseudo estado de Junção é utilizado para projetar caminhos transacionais complexos, podendo unir múltiplos fluxos em um único ou dividir um fluxo em diversos, podendo utilizar condições de guarda como auxílio.

Pseudo estado de Ponto de Entrada e Ponto de Saída são utilizados juntamente com estados de submáquina ou estados compostos e demonstram pontos de entrada e saída, que serão somente usados em casos excepcionais. O estado de entrada demonstra um caminho alternativo e é representado por um círculo vazio.
O estado de saída demonstra normalmente uma exceção que causa o cancelamento do fluxo normal do estado e é representado por um círculo com um X.

O Pseudo estado de Término força o término de uma máquina de estados devido, por exemplo, a ocorrência de uma exceção. É representado por um X.</p>
<br>

## Questão 8. Explique o Diagrama de Componentes.

<p align="justify">O Diagrama de Componentes, como o nome indica, identifica os componentes que fazem parte de um sistema, um subsistema ou mesmo os componentes ou classes internas de um componente individual. Um componente pode representar tanto um componente lógico (um componente de negócio ou de processo) ou componente físico, como arquivos contendo os códigos fontes, bibliotecas, plugins etc.
O Diagrama de Componentes pode ser utilizado como uma forma de documentar como estão estruturados os arquivos físicos de um sistema, permitindo assim uma melhor compreensão do mesmo, além de facilitar a reutilização de código. Esse diagrama também pode identificar os componentes utilizados no desenvolvimento de sistemas baseados em componentes.

Um componente pode sempre ser considerado uma unidade autônoma dentro de um sistema ou subsistema. Ele tem uma ou mais interfaces fornecidas e requeridas (potencialmente expostas via portas), e seus interiores são inacessíveis e invisíveis por outro meio que não seja fornecido por suas interfaces. Embora ele possa ser dependente de outros elementos em termos de interfaces que são requeridas, um componente é encapsulado e suas dependências são projetadas de tal forma que ele possa ser tratado tão independentemente quanto possível.
Na versão 1.4 da UML, componentes eram representados por um retângulo com dois retângulos menores sobressaindo-se à sua esquerda. A partir da versão 2 da UML, esse símbolo foi substituído por um retângulo contendo internamente o antigo símbolo.

Na versão 1.4 da UML um dos principais relacionamentos entre os componentes era realizado por meio de relacionamento de dependência. No entanto, a partir da versão 2 da UML, embora esse tipo de relacionamento continue sendo válido e utilizado, passou-se a utilizar com muito mais freqüência Interfaces Fornecidas e Interfaces Requeridas, descritas no Diagrama de Classes.

Uma Interface Fornecida descreve um serviço implementado por um componente específico. O conjunto de interfaces implementadas por um componente são suas Interfaces Fornecidas e representam o conjunto de serviços que o componente oferece aos seus clientes. Um componente, ao implementar uma interface, suporta o conjunto de características possuídas por este, além de obedecer às restrições possuídas pela interface. As Interfaces Fornecidas são representadas por um circulo fechado ligado ao componente por uma reta sólida.

Uma Interface Requerida descreve os serviços que outros componentes devem fornecer a um determinado componente, que não precisa ter conhecimento de quais componentes irão implementar tais serviços. As Interfaces Requeridas são representadas por um semicírculo ligado a um componente por uma linha sólida.

Um componente pode conter ou implementar uma ou mais classes internas, podendo também possuir componentes internos. A representação de um componente sem apresentar seus componentes ou classes internas é chamada de visão de caixa preta; já a representação de um componente com suas classes ou componentes internos é chamado de visão de caixa branca. A contenção de classes por um componente significa que este as implementa de alguma maneira.
Uma outra forma de representar classes internas de um componente é por meio do relacionamento de dependência, na qual o componente possui associações de dependência com suas classes internas.
É comum o uso de portas para comunicar os elementos internos de um componente com o ambiente externo, quando esses solicitam ou executam algum serviço.</p>
<br>

## Questão 9. Explique o Diagrama de Pacote.

<p align="justify">O Diagrama de Pacotes tem por objetivo representar os subsistemas ou sub-módulos englobados por um sistema de forma a determinar as partes que o compõem. Ele demonstra como os elementos estão organizados nos pacotes, e as dependências que existem entre os elementos e os próprios pacotes. Pode ser utilizado de maneira independente ou associado a outros diagramas. Esse diagrama pode ser utilizado também para auxiliar a demonstrar a arquitetura de uma linguagem, como ocorre com a própria UML.

Pacotes são utilizados para agrupar elementos e fornecer denominações para esses grupos. São muito úteis para a modelagem de subsistemas e para a modelagem de subdivisões da arquitetura de uma linguagem.

Pacotes normalmente possuem dependência entre si. Um relacionamento de dependência informa que o elemento dependente necessita de alguma forma do elemento do qual depende.
O relacionamento de dependência no Diagrama de Pacotes pode possuir dois estereótipos: <>, significando que os elementos do pacote que utiliza tal dependência serão unidos aos elementos do outro pacote, e <>, significando que o pacote que utiliza essa dependência está importando alguma característica ou elemento do outro pacote.

Também é muito comum na modelagem de sistemas um pacote se subdividir em diversos outros pacotes, por exemplo, na definição de arquiteturas de linguagens de modelagem.</p>
<br>
  
## Questão 10. Explique o Diagrama de Implantação.
  
<p align="justify">Diagrama de Implantação determina as necessidades de hardware do sistema, as características físicas como servidores, estações, topologias e protocolos de comunicação, ou seja, todo o aparato físico sobre o qual o sistema deverá ser executado. Os Diagramas de Componentes e de Implantação são bastante associados, podendo ser representados em separado ou em conjunto.
O Diagrama de Implantação é o diagrama com a visão mais física da UML. Este diagrama foca a questão da organização da arquitetura física sobe a qual o software irá ser implantado e executado em termos de hardware, ou seja, as máquinas (computadores pessoais, servidores etc.) que suportam o sistema, além de definir como estas máquinas serão conectadas e por meio de quais protocolos se comunicarão e transmitirão as informações. Os elementos básicos deste diagrama são os Nós, que representam os componentes, Associações entre Nós, que são as ligações entre os Nós do diagrama, e os Artefatos, representações de entidades físicas do mundo real. 

Nós são componentes fundamentais do Diagrama de Implantação. Um nó pode ilustrar um item de hardware, como um servidor em que um ou mais módulos do software são executados ou que armazene arquivos consultados pelos módulos do sistema, ou pode representar um ambiente de execução, ou seja, um ambiente que suporta o sistema de alguma forma.
Nós podem conter outros nós, sendo comum encontrar um nó que representa um item de hardware contendo outro nó que representa um ambiente de execução, embora nó que represente um item de hardware possa conter outros nós representando itens de hardware, e um nó que represente um ambiente de execução possa conter outros ambientes de execução.
Quando um nó representa um hardware, deve possuir o estereótipo <>; quando, porém, um nó representa um ambiente de execução, pode utilizar o estereótipo <>.

Os Nós possuem ligações físicas entre si de forma que possam se comunicar e trocar informações. Essas ligações são chamadas associações e são representadas por retas ligando um Nó a outro. Uma associação pode conter estereótipos utilizados para determinar, por exemplo, o tipo de protocolo e comunicação utilizado entre os nós.

Um artefato é uma entidade física, um elemento concreto que existe realmente no mundo real, assim como os nós que o suportam. Um artefato pode ser um arquivo fonte, um arquivo executável, um arquivo de ajuda, um documento de texto etc. Um artefato deve estar implementado em um Nó.</p>
