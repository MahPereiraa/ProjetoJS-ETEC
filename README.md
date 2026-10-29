# Sistema Escolar — ProjetoJS ETEC

Projeto acadêmico desenvolvido ao final do módulo 2 da ETEC, com o objetivo de aplicar conhecimentos de desenvolvimento web e integração com banco de dados em um sistema de gestão escolar.

## Sobre o projeto
A aplicação reúne módulos para cadastro de alunos, professores, grade de aulas e registro de notas em boletins. O projeto explora a comunicação entre uma interface web em JavaScript e um backend em PHP, com armazenamento de informações em MySQL.

## Módulos
- **Alunos:** formulário com matrícula, nome, data de nascimento e turma.
- **Professores:** formulário com código, nome, disciplina e carga horária.
- **Grade de aulas:** cadastro de semestre, disciplina, turma e horário.
- **Boletins:** registro de duas notas, associação com aluno, disciplina e professor, além de consulta com cálculo da média.

## Tecnologias utilizadas
- HTML e CSS para estrutura e apresentação.
- JavaScript com XMLHttpRequest para requisições assíncronas.
- PHP para processamento das solicitações.
- PDO para conexão com o banco de dados.
- MySQL para armazenamento dos dados.

## Organização do código
- `form*.php`: páginas com formulários e interações em JavaScript.
- `contr*.php`: controladores que recebem as solicitações.
- `cls*.php`: classes com operações no banco de dados.
- `conexao.php`: configuração da conexão com o MySQL.
- `menu.php`: navegação entre os módulos.
- `adicionando.css`: estilos da interface.
- `bd.sescola.sql`: comandos de criação e manipulação do banco.

## Execução local
1. Extraia o arquivo `ProjFinaljsGabrielaeMariaEduarda.rar`.
2. Coloque a pasta `ProjFinaljs` em um servidor local com PHP e MySQL, como o XAMPP.
3. Prepare o banco `SistemaEscolar` e suas tabelas com base no arquivo SQL.
4. Configure os dados de conexão em `conexao.php`.
5. Com os serviços iniciados, acesse `http://localhost/ProjFinaljs/`.

**Atenção:** o arquivo SQL contém comandos repetidos de criação e comandos de exclusão, incluindo `DROP TABLE` e `DROP DATABASE`. Revise o conteúdo antes de executá-lo.

## Status do projeto
Protótipo acadêmico com funcionalidades parcialmente implementadas. As consultas de alunos, professores e grade precisam ser concluídas nos controladores. O módulo de boletins também requer ajustes na consulta e na interface de atualização.

## Aprendizados
Prática de formulários web, manipulação do DOM, requisições assíncronas, orientação a objetos em PHP e operações SQL.
