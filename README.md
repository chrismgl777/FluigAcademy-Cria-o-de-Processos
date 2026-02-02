# FluigAcademy-Cria-o-de-Processos
<h4> Criando esse repositório para indexar meu treinamento, afim de auxiliar iniciantes na área. </h4>


<h2> Primeiro passo, criando um projeto no Eclipse Luna. </h2>

<h2> Com o Eclipse aberto, esta é a imagem inicial: </h2>
<img width="1356" height="691" alt="image" src="https://github.com/user-attachments/assets/691faec3-a6e5-4a11-a5dc-fc355011c1f7" />

<h2> Criando o Projeto: </h2>
<img width="1375" height="412" alt="image" src="https://github.com/user-attachments/assets/a861df4f-5338-4610-b3bd-01a4d7941598" />
Caminho : File-New-Projeto Fluig.

<h2> Criando o nome do Projeto:  </h2>
Obs: Você não precisa criar um nome extremamente bem pensado, algo que arremate ao projeto ou algo auto descritivo já é o suficiente.
<img width="543" height="516" alt="image" src="https://github.com/user-attachments/assets/0f29da26-d211-4f4d-b231-e8ce258682e2" />

<h2> Criando o Formulário. </h2>
Obs: O formulário só pode ser criado se já houver o projeto, conforme criado anteriormente.
<img width="1374" height="376" alt="image" src="https://github.com/user-attachments/assets/9313404d-f916-4462-83d7-a5154f3f43ec" />
Caminho: Clique em cima do Projeto escolhido, vá em New, depois em Formulário.

<h2> Criando o nome do Formulário. </h2>
<img width="528" height="518" alt="image" src="https://github.com/user-attachments/assets/af1682ab-61b7-4f65-95a0-e89c28d69f64" />
Aqui é importante que crie um nome descritivo, bem pensado, pois será responsável pelo nome e indexação do formulário.

<h2> Formulário criado: </h2> 
<img width="1366" height="368" alt="image" src="https://github.com/user-attachments/assets/5cb1e19c-fc7d-4e94-bcd1-741d66aac852" />
Quando criamos o formulário, ele vem com a estrutura completa, Datasets, Events e também um Html padrão.

<h2> Fluig Style Guide </h2>
<img width="1366" height="368" alt="image" src="https://github.com/user-attachments/assets/dc456eb7-ecd1-47c8-908f-158dfc119674" />
Podemos chamar o Style Guide de biblioteca de componentes prontos, ele é de extrema relevância, através do site  https://style.fluig.com/
Podemos utilizar componentes já desenvolvidos para facilitar o trabalho e trazer rapidez no processo.

<h2> Criando o Formulário no HTML. </h2>
 <img width="950" height="242" alt="image" src="https://github.com/user-attachments/assets/5200ad5c-bf3a-4e62-8a45-06bb1858cdda" />

Dentro do formulário, vamos separar os cambos através de Divs, utilizando a classe padrão Form-group.
Primeiro, criamos um Label, que seria o titulo do campo.
Segundo, o campo por si só, chamado de Input, aonde o cliente/usuario vai inserir os dados.

<h2> Inicio do formulário criado: </h2>
<img width="1010" height="550" alt="image" src="https://github.com/user-attachments/assets/15f505d7-4ac3-40ac-a9a9-88ec38f68675" />

Aqui, eu criei alguns campos, tais como : Nome do Colaborador , CPF do colaborador, Regional e Cargo.

<h2> Visualizando o Formulário criado.  </h2>
Criamos os campos iniciais do nosso formulário, agora, precisamos visualizar.
Para visualizar o formulário, é necessário exportar para a base do Fluig, de prefêrencia na Base Teste...rs.
<img width="1333" height="425" alt="image" src="https://github.com/user-attachments/assets/dceb3535-8d6c-4a6e-95f3-dc74aa864de5" />
<img width="531" height="552" alt="image" src="https://github.com/user-attachments/assets/873bf690-623b-454e-8102-08bc5eb58f6b" />
Caminho: Clique em cima do Formulário que quer exportar utilizando o botão direito, vá na opção Export, depois  Exportar para Servidor Fluig.
<img width="526" height="237" alt="image" src="https://github.com/user-attachments/assets/a7768929-2bb0-4b44-b4be-cda34b0ffec0" />
Escolha para qual Servidor vai exportar.
Você vai ter duas oções, conforme imagem abaixo:
<img width="520" height="225" alt="image" src="https://github.com/user-attachments/assets/3beede8c-d792-4a77-8a31-aabbbce1de7e" />
Primeira: Criar um novo Formulário - Opção se é a primeira vez que você esta criando o formulário
Segunda:Editar um formulário do Servidor - Caso você esteja corrigindo, alterando ou manuseando um formulário Já existente.


<h2> Criar um Novo Formulário: </h2>
<img width="490" height="495" alt="image" src="https://github.com/user-attachments/assets/aaac7f46-048d-41dd-b689-5310696acc6c" />
Configurações necessárias:
<img width="490" height="495" alt="image" src="https://github.com/user-attachments/assets/89f0ea50-6bec-4496-b2ef-a59a6040cf54" />
O formulario você pode repetir o nome que criou  anteriormente.
O nome Dataset pode manter em branco, não estamos criando Dataset.
Pasta Destino é aonde vamos indexar ele na base do Fluig.


<h2> Não sabe como localizar ?? Vamos lá. </h2>

Localizando Pasta de Destino dentro do Fluig.
Dentro da Base Testes do Fluig, procure no menu lateral o campo "Documentos"
<img width="193" height="576" alt="image" src="https://github.com/user-attachments/assets/6660f0a7-000f-4efa-9381-f4308b3b2375" />

Dentro da Aba Documentos:
Aqui, você pode criar um documento para o Projeto ou identificar qual é o utilizado do processo:
<img width="1366" height="538" alt="image" src="https://github.com/user-attachments/assets/04e81376-0103-4f04-b3ac-89a419d949c7" />

<img width="904" height="703" alt="image" src="https://github.com/user-attachments/assets/6c07b734-9dd5-4a82-be68-e563603f915a" />
Com o código que identificamos na Aba documentos, conseguimos indexar nosso formulário no local correto.
Depois de vincular o documento, vá na opção "Finish" depois insira sua credencial da base teste e exporte.

<h2> Visualizando o Formulario. </h2>

Vá novamente na Aba Documentos. 
Depois clique no Documento criado para anexar o Formulário.
<img width="1256" height="256" alt="image" src="https://github.com/user-attachments/assets/02099191-f60f-49ba-b409-f75eab909714" />

Ao clicar no formulário, você vai se deparar com o titulo  "Esta Pasta esta vázia", isso se dá pois não publicou o formulário ainda.
Segue o passo a passo:
Vá em "Novo", depois "Registro de Formulário"
<img width="1288" height="292" alt="image" src="https://github.com/user-attachments/assets/0c6854da-31ee-426e-95db-7489aa55cd39" />
Confirme para publicar, depois poderá acessar normalmente:
<img width="1343" height="571" alt="image" src="https://github.com/user-attachments/assets/0a189d7d-4708-4c34-ab53-40171979565a" />
<img width="1267" height="212" alt="image" src="https://github.com/user-attachments/assets/a36359cb-9afb-471d-974a-4aa704384134" />

Formulário em branco após acessar pela primeira vez:
Não se preocupe, vá na opção Editar Formulário:
<img width="1315" height="260" alt="image" src="https://github.com/user-attachments/assets/b7294444-7514-4960-8727-d4668c54d34c" />
Edite as informações :
<img width="1317" height="357" alt="image" src="https://github.com/user-attachments/assets/af7554a3-d60e-43ec-ba73-4cdb34be1ea2" />
Depois publique e acesse de novo.

Vai ficar desta forma:
<img width="1323" height="300" alt="image" src="https://github.com/user-attachments/assets/f92222ac-5337-4710-bc13-dc4d26d38bdf" />


Ok, até aqui, aprendemos como criar um projeto, depois criar o formulário, montar os campos, criar o documento e postar o formulário.
Você viu que os campos estão simples, no proximo capitulo vamos melhorar esses campos.

Vejo vocês na parte 2. 

Um abraço!










