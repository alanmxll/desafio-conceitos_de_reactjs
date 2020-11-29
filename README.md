## Sobre o desafio
Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no ReactJS!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend no último desafio utilizando o Node.js.


## Template da aplicação
Para te ajudar nesse desafio, criamos para você um modelo que você deve utilizar como um template do Github.

O template está disponível na seguinte url: <b>[Acessar Template](https://github.com/rocketseat-education/gostack-template-conceitos-reactjs)</b>

## Funcionalidades da aplicação
Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo src/App.js, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- <b>`Listar os repositórios da sua API:`</b> Deve ser capaz de criar uma lista com o campo <b>title</b> de todos os repositórios que estão cadastrados na sua API.

- <b>`Adicionar um repositório a sua API:`</b> Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto <b>Adicionar</b> e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- <b>`Remover um repositório da sua API:`</b> Para cada item da sua lista, deve possuir um botão com o texto <b>Remover</b> que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

## Específicação dos testes
Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Caso você tenha dúvidas quanto ao que são os testes, e como interpretá-los, dê uma olhada em nosso FAQ.

Para esse desafio temos os seguintes testes:

- <b>`should be able to add new repository:`</b> Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- <b>`should be able to remove repository:`</b> Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.