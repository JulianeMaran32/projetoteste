# projetoteste

Trata-se de um repositório onde testo meus conhecimentos adquiridos durante a faculdade e cursos extracurriculares.

* Contato: julianemaran@gmail.com

Estrutua MVC para PHP


Hierarquia de Diretórios

NomeDoApp
- Controllers	 classes controladoras, que são responsáveis por fazer o intermédio entre o Models e a Views
- DataBase		 conecta ao Banco de Dados MySQL ou SQLite
- lib				   classes diretamente ligadas ao sistema (ex.: classes de filtros de dados, validações genéricas, helpers, interfaces e abstrações não ligadas à camadas de negócio do sistema
- Models			 classes de dados diretamente  abstraídas e ligadas às regras de negócio do sistema.
- Views			   arquivos HTML do sistema
- index.php 	 início da execução do programa

/*
*	@package
*	@author:  juliane
*	@version: 1.0 2020-12-16
*
*	Diretório:
*	Arquivo:
*/

Diretório Controllers:
- IndexController.php
- Exemplo1Controller.php
- Exemplo2Controller.php

Diretório lib:
- Application.php
- View.php
- PersistModelAbstract.php
- DataFilter.php
- DataValidator.php
- PersistModelAbstract.php			-> centraliza a conexão com o banco de dados

Diretório Model
- Exemplo1Model.php
- Exemplo2Model.php

Diretório Views
- listarExemplo1.phtml
- listarExemplo2.phtml
- manterExemplo1.phtml
- manterExemplo2.phtml

