
# Projeto Minhas Tarefas

 Estou foi uma atividade feita na trybe simulando um desafio técnico. Onde tive que criar toda a aplicação do zero para testar meus conhecimentos. Aqui estão algumas das habilidades testadas: **Javascript**, **CSS**, **React**, **manipulação de componentes**, **ciclos de vida de componentes**, **node.js**, **React Hooks**, **Contex API** , **rotas**, e **integragrão entre o frontend e o backend**. 

---
<br>
Este projeto foi importante, pois eu pude ver como é a pressão ao tentarmos criar um projeto para ser avaliado, e caso não haja tempo, saber o que deve ser priorizado. Também aprendi a sempre fazer novos pull requests para cada nova etapa feita.

<br>

### Desafios

Houveram alguns desafios, como conseguir fazer a integração do front com o backend, sem ocorrer erros, e falta corrigir um bug no frontend com uma função de mapear a lista de tarefas.




---
---
<br>
<br>

## **SOBRE:**
---
 Neste projeto, devemos criar uma lista de tarefas com seus status. </br>

 A tarefa deverá ser enviada para o backend e ser salva em um banco de dados do tipo MySQL. </br>

 É possível também deletar e atualizar as tarefas ou seus status.

**OBS:** Algumas opções de configuração dá erro, pois a api devolve de forma incorreta, por exemplo, na configuração as opções : Dificuldade:difícil, Categoria:Esporte, Tipo:verdadeiro ou falso, a api não tem essas opções de configuração então dá erro.
Então isso pode ocorrer dependendo da combinação escolhida pelo usuário.
 




## Baixando o projeto
---

 Para rodar o projeto em sua máquina, é preciso ter o MySQL instalado. </br>

 Depois devemos ir na pasta app/backend e verificar se tem um arquivo **.env**, caso não tenha, ele deve ser criado. </br>

 **CONFIGURANDO O ARQUIVO .env**
</br>

MYSQL_HOST=localhost </br>
MYSQL_USER=seuUsuario</br>
MYSQL_PASSWORD=suaSenha</br>
PORTA=porta</br>
</br>

no arquivo .env, deve ter os campos MYSQL_HOST=(e aqui seu usuário do Mysql), MYSQL_PASSWORD=(sua senha de acesso ao mysql), PORTA=(a porta onde deseja rodar o projeto).
</br>

Depois de configurar o .env, voce pode popular a tabela estando na pasta app/backend e digitando no terminal **npx sequelize-cli db:seed:all** </br>

Despois depos pode rodar o comando *npm run dev* para rodar o backend, e apois isto, devemos ir na pasta app/frontend e rodar o comando **npm start**







