 #### No contexto de modelos de processo de desenvolvimento de software, qual é a principal vantagem do modelo interativo incremental em relação ao modelo em cascata, especialmente em cenários de negócios que atuam em um ambiente globalizado 

 - O modelo interativo incremental permite feedback constante do cliente e entregas frequentes de software funcional

-------------------
#### MVC (model-view-controller) é um padrão de arquitetura de software que permite desacoplar a solicitação de usuário das respostas retornadas pelo backend. Nessa arquitetura, o controller é responsável por
- executar uma solicitação de entrada.
-------------------

#### Em uma aplicação de votação online desenvolvida em três camadas do tipo MVC, o controller é responsável por

- transformar eventos gerados pela view em ações de negócio, alterando o model.

-------------------
#### Supondo que o programador usou a anotação @RequestMapping("/user/{id}") selecione a assinatura do método que deveria ser utilizada para extrair o valor de um parâmetro enviado na URL de acesso a uma funcionalidade disponibilizada pelo servidor de aplicações na Web.

- public String handleRequest(@PathVariable("id") String userId) { }

-------------------
#### Classes anotadas com @Controller interpretam uma requisição do usuário e retornam dados (model) que são apresentados para o usuário pela camada de visualização (view). Qual objetivo de se utilizar o ModelAndView na programação Web no Spring Boot?

- Permite retornar os dados e a página que será renderizada em uma requisição realizada pelo usuário.

-------------------
#### Considere um sistema de gerenciamento de estoque que precisa ser integrado com diferentes gateways de pagamento desenvolvido com tecnologia Java. Como o princípio da Inversão de Dependência, em conjunto com a Injeção de Dependência, pode ser aplicado para tornar este sistema mais flexível e manutenível?

- Definindo uma interface para os gateways de pagamento e injetando a implementação específica durante o tempo de execução

-------------------
#### A JPA (Java Persistence API) simplifica o desenvolvimento de aplicações Java que interagem com bancos de dados relacionais. Qual das alternativas a seguir descreve melhor o papel da JPA

- A JPA é útil apenas para aplicações pequenas e não é adequada para sistemas corporativos complexos.

-------------------
#### O estudo de caso menciona a entrega de software funcional a cada duas semanas. Essa prática está alinhada com qual conceito do desenvolvimento ágil?
- Sprints

-------------------
#### No modelo do processo de desenvolvimento de software, o projeto de arquitetura é o primeiro estágio no processo de projeto de software. O projeto da arquitetura é um elo crítico entre o projeto e a engenharia de requisitos porque...
- ajuda a explicar como o sistema pode ser particionado em componentes, reduzindo, assim, a complexidade para seu entendimento

-------------------
#### Analise o código abaixo, ao definir um endpoint REST com Spring MVC qual o comportamento esperado da classe UsuarioController ao receber uma request neste caso ?

```Java
  @RestController
  @RequestMapping("/usuarios")
  public class UsuarioController{

        @PostMapping
        public ResponseEntity<Usuario>criarUsuario(@RequestBody Usuario usuario){
//Logica criar usuario

        return ResponseEntity.created(URI.create("/usuarios/"+usuario.getId())).body(usuario);
  }
}
```
- recebe um objeto Json que é desserializado para um objeto java com objetivo de atender ao comportamento da logica definida de criação do usuário.

-------------------
#### À medida que aplicações Web se tornam cada vez mais integradas nas estratégias de negócio, de pequenas e grandes empresas a necessidade de construir sistemas confiáveis e fácil de adaptar cresce em importância. Qual deve ser o primeiro passo para que uma organização de desenvolvimento de software inicie a construção do sistema, considerando que o cliente especificou suas necessidades?

- Estabelecer o processo de desenvolvimento de software

-------------------
#### Uma organização decidiu utilizar o Waterfall como modelo de processo de desenvolvimento de software. Selecione entre as alternativas abaixo a que melhor define as características deste modelo.


- Em princípio, o resultado de cada fase consiste de um ou mais documentos aprovados (revisados pela equipe ou pelo cliente). As fases seguintes não devem começar antes que a fase anterior tenha terminado

-------------------
#### Uma organização de desenvolvimento de software esta iniciando um projeto para incluir novas funcionalidades em um sistema de matrículas para uma grande universidade pública. Este domínio é novo para a organização. Uma das tarefas é selecionar o modelo de ciclo de vida que será mais apropriado para as circunstâncias deste projeto. Entre as opções abaixo selecione a que permitiria a organização obter feedback enquanto entrega o sistema em estágios.

- Desenvolvimento incremental

-------------------
#### Uma organização de desenvolvimento de software implementa sistemas para dar apoio as questões comerciais da indústria de seguros. Uma nova aplicação foi solicitada para permitir que os segurados consultem o andamento do registro de sinistros online. O gerente do projeto tem enfatizado que os principais requisitos estão definidos mais alguns detalhes podem evoluir com o tempo na medida que aumenta a compreensão das funcionalidades que serão entregues. Selecione entre os modelos de processo de desenvolvimento de software relacionados abaixo, qual deve ser mais indicado para as características deste projeto?

- Interativo e incremental

-------------------
#### Uma característica do modelo Waterfall estabelece que as fases seguintes não devem começar antes que a fase anterior tenha terminado. Selecione entre as opções abaixo, a melhor reposta, que define o mecanismo que permite a equipe decidir se a fase anterior foi concluída ou não.

- Uma reunião de revisão da fase anterior envolvendo a equipe de desenvolvimento e em alguns casos o próprio cliente pode definir se a fase foi concluída.

-------------------
#### Um aluno da Fatec iniciou um estágio em uma empresa da Prefeitura. Nas primeiras semanas de trabalho percebeu que não havia um processo bem definido para as atividades de desenvolvimento de software, as demandas eram informadas em reunião pessoalmente pelo gestor e as atividades operacionais eram comunicadas em conversas informais com colegas da área. Qual deve ser a postura do estagiário nestas condições? Selecione a melhor resposta:

- Estabelecer um processo pessoal de desenvolvimento de software medindo os resultados de qualidade discutindo com os colegas as evidências obtidas.

-------------------
#### Uma organização de desenvolvimento de software está conduzindo um projeto de um sistema integrado de gestão de vendas e suprimentos para uma rede varejista. O analista responsável está implementando a consulta no catalogo de produtos. O sistema deverá solicitar ao usuário a descrição do produto que será usado para realizar a pesquisa nas bases de dados das lojas conveniadas.

#### Ao detectar a disponibilidade do produto solicitado, o sistema armazenará temporariamente os dados das lojas (nome, preço, data prevista para entrega do produto) e exibirá as informações ordenadas por preço. Após analisar as informações, o cliente poderá efetuar a compra.

#### A equipe do cliente deverá testar algumas operações do sistema antes de ele ser finalizado. Há tempo suficiente para que o analista atenda a essa solicitação e efetue eventuais modificações exigidas pelo contratante.

- Com relação a essa situação, julgue os itens a seguir quanto ao modelo de ciclo de vida utilizado.

  - I O entendimento do sistema como um todo e a execução sequencial das fases sem feedback produzem um sistema que pode ser validado pelo contratante no final.
  - II A elaboração do protótipo pode ser utilizada para resolver dúvidas de comunicação, o que aumenta os riscos de inclusão de novas funcionalidades não prioritárias.
  - III No modelo de execução sequencial do processo do processo de desenvolvimento de software uma única interação é definida e a verificação das fases intermediarias não são realizadas antes do projeto ser finalizado.
  - IV Um processo iterativo permite que versões progressivas mais completas do sistema sejam construídas e avaliadas.

##### Estão certos apenas os itens

- I e IV

-------------------
#### A primeira lei da engenharia de sistemas diz: "Independentemente de onde você está no ciclo de vida do sistema, o sistema vai se modificar e o desejo de modificá-lo vai persistir ao longo de todo o ciclo de vida." (PRESSMAN, 2006, 6ed.) Considerando as modificações que ocorrem durante o ciclo de vida do produto de software avalie as afirmações a seguir:
-
  - I. Frequentemente existe um aumento da carga de trabalho operacional, associado a inclusão de novas funcionalidades
  - II. A especialização da equipe de sustentação no tempo melhora a facilidade com a qual as modificações podem ser acomodadas reduzindo a quantidade de esforço.
  - III. O aumento do tráfego resulta na necessidade de se escalar a aplicação para atender as necessidades geradas pela demanda no uso do sistema.

##### É correto o que se afirma em

- I e III somente

-------------------
#### Um dos principais pontos que podem afetar o desempenho de um servidor web é a quantidade de requisições que ele recebe em um espaço de tempo. O balanceamento de cargas é bastante intuitivo no gerenciamento das demandas em um sistema de software. Para atender as necessidades de aumento da demanda uma cópia da aplicação é instalada em cada servidor e balanceadores de carga são ativados para adequar a demanda por servidor. 
                                          
                                           /---> Servidor 1
#### Cliente -----> Balanceador --->  Servidor 2 
                                           \---> Servidor 3

##### Sobre o aumento da escalabilidade do sistema, assinale a afirmativa correta.

- O acréscimo de servidores é uma das estratégias para se melhorar o desempenho em sistemas que tem um aumento de demanda.

-------------------
#### Alguns princípios da programação orientada a objetos ajudam a minimizar erros de programação e a facilitar a manutenibilidade do software. O SOLID são cinco princípios usados na POO que orientam a programação no desenvolvimento de software mais fáceis de manter e estender. Esses princípios podem ser aplicados a qualquer linguagem de POO.  O princípio S, que se refere ao Single Responsability Principle-SRP ou Princípio de Responsabilidade Única, indica que uma classe deve ter uma e, apenas uma, razão para mudar.  Considere a classe Java abaixo. 

```Java
public class UrnaEleitoral { 
     public void AdicionarCandidato(String nome, int numero, int partido) { } 
     public decimal CalcularTotalVotosCandidato() { }
      public void CadastrarPartidos() { } 
  public void CadastrarEleitores() { } 
     public void CadastrarMesarios() { } 
}
```

##### Com base no princípio SRP e na classe UrnaEleitoral é correto afirmar:

- A classe UrnaEleitoral apresenta uma quebra do SRP, uma vez que possui responsabilidades que deveriam ser de componentes distintos do software.

-------------------
#### Considere o principio do aberto/fechado no SOLID é correto afirmar que:

- O objetivo do principio é caso necessário adicionar uma nova função a uma classe e não alterar o que já existe. 
