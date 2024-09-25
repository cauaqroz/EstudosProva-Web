## Formulario 02

####  Qual é o principal objetivo de um sistema de controle de versão? 

- Rastrear e gerenciar as alterações realizadas em um código-fonte ao longo do tempo.

---------
#### No contexto de controle de versão, o que significa "ramificação" (branch)?


- Uma linha de desenvolvimento alternativa que permite trabalhar em paralelo sem afetar a linha principal. 

----------
#### Qual a principal diferença entre "Trunk Based Development" e "Branch Based Development"? 


- Em "Trunk Based Development" todos trabalham na mesma ramificação, enquanto em "Branch Based Development" são criadas ramificações separadas. 

------------
#### Quando é recomendado utilizar o padrão "Trunk Based Development"? 

- Quando a equipe prioriza integração contínua e rápida resolução de problemas.
  
------------
#### O que significa realizar um "commit" em um sistema de controle de versão?


- Salvar as alterações realizadas localmente no repositório
  
------------
#### No contexto do GitHub, qual a finalidade do arquivo readme.md?

- Documentar o projeto, incluindo objetivos, instruções de instalação e outras informações relevantes

------------
#### O que pode acontecer quando dois desenvolvedores modificam a mesma linha de um mesmo arquivo? 

- Ocorre um conflito que precisa ser resolvido manualmente

------------
#### No cenário de um conflito de merge, como o desenvolvedor pode visualizar as diferenças entre as versões?


- Através da ferramenta de comparação ("Merge Tool") do sistema de controle de versão

------------
#### Qual a importância de escrever mensagens de commit claras e objetivas?


- Auxiliar na compreensão do histórico de desenvolvimento e na identificação de alterações específicas. 

------------
#### No contexto de monitoramento de projetos de software com GitHub, o que pode indicar um aumento na frequência de commits? 


- Aumento no esforço de desenvolvimento

## Formulario 01

#### Com relação a web services, assinale a afirmação correta.

- O problema com o REST está relacionado a sua flexibilidade, o padrão para definição das mensagens é estabelecido de acordo com as necessidades relacionadas a um projeto específico, consequentemente os problemas de interoperabilidade são mais comuns. 

------------
#### REST (Representational State Transfer), refere-se a um conjunto de restrições de design de arquitetura de software que geram sistemas eficientes, confiáveis ​​e escaláveis. Selecione entre as opções abaixo a característica que viola uma das restrições impostas pelo estilo arquitetural REST: 

- o armazenamento no servidor, entre requisições, de informações de contexto do cliente ou estado de sessão.

------------
#### Em um Web Service REST, o cliente envia uma mensagem "HTTP Request" e o servidor responde na forma de "HTTP Response". Usando esse serviço, um técnico, ao enviar uma mensagem, recebeu como resposta um código de status indicando que o recurso ou página desejada não foi encontrado. O código recebido foi:


- 404

------------
#### De acordo com Erl (2009) existem três estágios lógicos no processo de desenvolvimento de software orientado a serviços:

- Identificação do serviço candidato, Projeto de serviço, implementação e implantação de serviço.

------------
#### Thomas Erl (2009) define três tipos fundamentais de serviços que podem ser identificados.  Sobre a identificação de serviços é correto afirmar que:


- O escopo funcional de um serviço de tarefa pode ser comparada, a automação de um processo de negócio da empresa.

------------
#### Analise as afirmativas abaixo sobre Web Service projetados utilizando uma arquitetura REST.

1. Por definição, os serviços web são fracamente acoplados, já que foram concebidos com a interoperabilidade como requisito primário.
2. Uma das restrições, no processamento de uma requisição REST é a chamada “comunicação sem estado”, ou seja, toda requisição deve conter as informações necessárias para que o servidor consiga entendê-la e processá-la adequadamente.
3. Quando um cliente faz uma solicitação usando uma API REST, uma mensagem é encaminhada pelo solicitante a um endpoint. Essa informação (ou representação) é entregue via FTP (File Transfer Protocol - protocolo de transferência de arquivos) utilizando um formato suportado pela aplicação.

##### Assinale a alternativa que indica todas as afirmativas corretas.

- São corretas apenas as afirmativas 1 e 2.

------------
#### O conceito de microsserviços surgiu na comunidade de desenvolvimento de software como uma resposta direta a muitos dos desafios de tentar escalar técnica e organizacionalmente sistemas grandes e complexos implementados como um único módulo (monolítico). Existe pouca literatura sobre padronização de microservicos e poucos guias sobre como manter e construir ecossistemas de microservicos (FOWLER, 2017). Considerando o desenvolvimento orientado a serviços avalie as afirmações a seguir: 
I. Os microsserviços permitem decompor um aplicativo em componentes com responsabilidades bem definidas em contrapartida se aumenta a complexidade da implantação e da sustentação
II. Microsservicos são pequenos serviços autônomos que trabalham juntos. Pequeno significa o quão bem o serviço se alinha à estrutura da equipe
III. A implementação de um sistema seguindo uma arquitetura orientada a serviços, facilita escalar o sistema selecionando os serviços que necessitam de mais desempenho ou da troca de tecnologias antigas por outras mais recentes

##### É correto o que se afirma em:

- II e III, somente.

------------

#### Um novo sistema de software será desenvolvido na empresa e a especificação desse sistema indica que será utilizada uma arquitetura de microsserviços. Sobre microsserviço, é correto afirmar que:


- expõe as funcionalidades de negócio que encapsula por meio de um ou mais endpoints de rede

------------

#### Computação distribuída corresponde ao método de fazer vários computadores trabalharem juntos para resolver um problema comum. Isso faz com que uma rede de computadores pareça um único computador poderoso que fornece recursos em grande escala para lidar com desafios complexos. Em um sistema distribuído os componentes de hardware ou software, localizados em computadores interligados em rede, comunicam-se e coordenam suas ações (serviços) apenas enviando mensagens entre si. Com base na definição apresentada e nos conceitos básicos de sistemas distribuídos, assinale a opção correta.

- A adição de novos servidores em um sistema distribuído para atender a uma demanda temporária ou crescente está ligada à característica de escalabilidade do sistema.

------------
#### Microsserviços são pequenos serviços autônomos que trabalham juntos, trata-se de uma forma de projetar uma aplicação de modo a dividir o código completo em partes menores (serviços). Existe pouca literatura sobre padronização de microserviços no entanto, quase todos têm as mesmas características. Selecione entre as opções abaixo a que pode ser considerada um beneficio de uma arquitetura orientada a microserviços:

- A organização pode adotar uma tecnologia mais rapidamente e entender como os novos avanços podem melhorar a operação de negócio

