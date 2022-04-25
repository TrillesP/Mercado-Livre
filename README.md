--Aprendendo o básico de Selenium em Java

Baixei, organizei as pastas do projeto e instanciei o Chrome WebDriver
Aprendi a tirar screenshots dos testes e a salvar arquivos como reports.
Fiz testes com barra de busca e comecei a usar WebDriverWait pra conseguir rodar os testes.
Asserts usados pra identificar se os testes passaram.
Testei se identificava um smartphone específico numa página de busca.


Criei outra classe para uso comum de printscreens, organizei as pastas do projeto com datas e horários para os screenshots com nomes diferentes também.
Criei log files com data e hora. Aprendi a dar append nos arquivos e a formatar data até milisegundos.


--BDD, Cucumber

Usei Cucumber no método BDD com o pacote Selenium pra criar PageObject/PageFactory para eventualmente abrir um site, fazer uma pesquisa e identificar o preço e o nome de aulas no site https://iterasys.com.br/pt.

Otimizei o código que aprendi anteriormente para testes de buscas, aprendi sobre Scenario Outline com exemplos, parei de usar Thread.sleep, otimizando as formas de wait.until utilizadas em Java com certas condições esperadas.
Movimentação de mouse, clickar and esperar o load das páginas, treinei uso de xPath and utilizei ChroPath para achar mais facilmente classes boas de serem encontradas tanto com xPath como com cssSelector.

Mudei de JUnit para TestNG para aprender mais, criei uma nova classe Java para o projeto, com Hooks e Runner, criei um novo pacote para fazer o mapeamento útil do site, e finalizei o aprendizado de PageObject/PageFactory, criando reports.

Finalizando, otimizei o código, transformei todo o teste no método de PageObject/PageFactory, e vi o teste final passar (com diversas aulas diferentes) com a classe Runner.
