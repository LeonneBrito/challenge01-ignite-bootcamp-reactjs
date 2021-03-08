<img alt="Ignite" src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F2fbacb7a-e460-44a3-8fc5-e66f96dae148%2Fcover-reactjs.png?table=block&id=51e4099a-6e2f-4d4b-ae94-f9fe75bb769d&width=5120&userId=1b109781-8635-4162-80d6-714377721793&cache=v2" />

<h3 align="center">
Desafio 01: Conceitos do ReactJS
</h3>

<p align="center">	
   <a href="https://www.linkedin.com/in/leonne-sousa-brito/">
      <img alt="LeonneBrito" src="https://img.shields.io/badge/-LeonneBrito-5965e0?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <img alt="Languages" src="https://img.shields.io/github/languages/count/LeonneBrito/desafio01-ignite-trilha-reactjs?color=%235963C5" />
  <img alt="License" src="https://img.shields.io/github/license/LeonneBrito/desafio01-ignite-trilha-reactjs?color=%235965E0" />
  <img alt="Issues" src="https://img.shields.io/github/issues/LeonneBrito/desafio01-ignite-trilha-reactjs?color=%235965E0">
  <a href="mailto:contato@leonnebrito.com.br">
   <img alt="Email" src="https://img.shields.io/badge/-contato%40leonnebrito.com.br-%23525DCB" />
  </a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS
Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

## :wrench: Funcionalidades da aplicação

- Adicionar uma nova tarefa: Deve ser possível adicionar uma nova task no estado de tasks, com os campos id que deve ser gerado de forma aleatória, title que deve ser um texto e isComplete que deve iniciar como false.
- Remover uma tarefa: Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.
- Marcar e desmarcar uma tarefa como concluída:  Deve alterar o status de isComplete para uma task com um ID específico que é recebido por parâmetro. 

## :syringe: Específicação dos testes

Para esse desafio, temos os seguintes testes:

- **should be able to add a task**: Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface.

- **should not be able to add a task with an empty title**: Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

- **should be able to remove a task**: Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

- **should be able to check a task**: Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.

# :page_facing_up: Licença

Esse projeto está sob a licença [MIT](./LICENSE).

Desafio proposto com 💜 by Rocketseat 👋 [Entre nessa grande comunidade!](https://discordapp.com/invite/gCRAFhc)
