<h1>Design Patterns - Singleton</h1>

<h2>Uma Breve História</h2>

<p style="text-align: justify;">&emsp;Não sei se isso já aconteceu com você, mas já teve a sensação de aprender algo na faculdade só por aprender? Lembro-me como se fosse hoje das aulas de programação, com meu querido professor Giuliano, mostrando para nós, seus alunos, uma tal de classe que se autoinstanciava, chamada de singleton, e como ela era interessante para ter uma única instância, como um banco de dados, e blá, blá, blá. Recentemente, estava trabalhando em uma aplicação em Python e tinha que guardar algumas informações em memória. Eu queria algo como uma variável global, mas que fosse controlada por uma classe. Nesse momento, lembrei-me das minhas aulas de programação em Java, onde eu criava uma classe singleton para garantir que houvesse apenas uma conexão com o banco de dados por execução da aplicação.</p>

<h2>Mas o que é singleton afinal?</h2>
<p style="text-align: justify;">&emsp;Quando uma nova classe é instanciada, o compilador vai até a memória RAM e reserva uma quantidade de espaço para alocar o novo objeto que está sendo instanciado. Você não vê isso, mas tudo isso acontece nos bastidores do seu programa. O padrão singleton é o oposto disso: todos os novos objetos instanciados sempre terão a mesma instância, pois compartilham o mesmo espaço de memória alocada.</p>
