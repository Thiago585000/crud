# crud


Documentação do Projeto CRUD com Flask e SQLite
Este projeto é uma aplicação web simples que implementa operações CRUD (Create, Read, Update, Delete) utilizando o framework Flask para o backend e SQLite como banco de dados. A aplicação permite gerenciar usuários, onde você pode adicionar, visualizar, editar e deletar registros de usuários.
Configuração e Execução do Projeto
Pré-requisitos
Antes de começar, certifique-se de que você tem os seguintes itens instalados em sua máquina:
•	Python 3.x: A aplicação foi desenvolvida em Python. Você pode baixar a versão mais recente do Python 
•	Pip: Gerenciador de pacotes do Python, geralmente já vem instalado com o Python.
Instalação
1.	Clone o repositório (se estiver usando um repositório Git) ou baixe o código-
2.	Instale as dependências:
O projeto utiliza o Flask como principal dependência. Para instalar, execute:
pip install Flask
3.	Execute a aplicação:
Após instalar as dependências, execute o seguinte comando para iniciar o servidor Flask:
python app.py
O servidor Flask será iniciado e estará disponível em http://127.0.0.1:5000/
4.	Acesse a aplicação:
Abra o navegador e acesse http://127.0.0.1:5000/. Você verá a página inicial da aplicação, onde poderá listar, adicionar, editar e deletar usuários.
Funcionalidades Implementadas
1. Listar Usuários (Read)
•	Descrição: Exibe uma lista de todos os usuários cadastrados no banco de dados.

 
2. Adicionar Usuário (Create)
Descrição: Permite adicionar um novo usuário ao banco de dados. O usuário deve fornecer um nome e um e-mail.
 
3. Editar Usuário (Update)
Descrição: Permite editar as informações de um usuário existente. O usuário pode alterar o nome e o e-mail.
 
4. Deletar Usuário (Delete)
Descrição: Remove um usuário do banco de dados. Após a exclusão, o usuário é redirecionado para a página inicial.
 
Tecnologias Utilizadas
•	Flask: Framework web leve para Python, utilizado para criar as rotas e gerenciar as requisições HTTP.
•	SQLite: Banco de dados embutido, utilizado para armazenar os dados dos usuários.
•	HTML/CSS: Para a criação das páginas web e estilização básica.
•	Jinja2: Motor de templates utilizado pelo Flask para renderizar as páginas HTML.
