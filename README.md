# Desktop App Empresarial Varejista para Recursos Humanos | Retail Business Desktop App for Human Resources

### Introdução | Introduction:

PT-BR: O projeto consiste em um software que sua aplicação é destinada a profissionais de recursos humanos presentes em uma empresa atuante no setor varejista. Nele é possivel criar, deletar, editar e visualizar dados dos setores, também como criar, deletar, editar e visualizar informações dos vendedores, tais como o nome, email, data de nascimento, salário e qual setor o mesmo está ligado. Todos os dados que o software irá apresentar são obtidos através de uma conexão com o bando de dados MySQL. O software tem como base Java e MySQL.

EN-US: The project consists of a software whose application is aimed at human resources professionals present in a company operating in the retail sector. It is possible to create, delete, edit and view sector data, as well as create, delete, edit and view seller information, such as name, email, date of birth, salary and which sector it is connected to. All the data that the software will present is obtained through connection with the MySQL database. The software is based on Java and MySQL.

<div>
<img src="https://github.com/GuilhermeOSCP/empresaDB-java/blob/master/aba.jpg">
</div>

### Instruções Para Inicialização do Software | Software Startup Instructions:
<div>
PT-BR: Para inicializar o software é necessário ter o MySQL instalado no seu computador. Após instalar o MySQL, verifique o arquivo "db.properties" presente na pasta principal do projeto e altere as configurações de acordo com as configurações presentes no seu MySQL, isto serve para estabelecer a comunicação do software com o banco de dados. <br> Depois de modificar o arquivo "db.properties"  de acordo com suas configurações de conexão com o MySQL, no seu software de administração de banco de dados (Eu utilizo o MySQL Workbench) copie todo o conteúdo do arquivo "database.sql" nas linhas de comando dentro da sua base de dados e execute. Isto serve para inicializar as tabelas e os dados previamentes contidos nas mesmas para o software conseguir consultar e mostrar. Após seguir os passos acima, é só acessar o projeto na sua IDE (Eu utilizo o Eclipse) e executar o software como uma aplicação java que o software irá funcionar normalmente. Não esqueça que para o software funcionar corretamente,  o serviço do MySQL deve estar em execução na sua máquina, se não, o software não conseguirá realizar as suas consultas.
</div>

EN-US: To start the software you must have MySQL installed on your computer. After installing MySQL, check the "db.properties" file present in the project's main folder and change the settings according to the settings present in your MySQL, this serves to establish the software's communication with the database. After modifying the "db.properties" file according to your MySQL connection settings, in your database administration software (I use MySQL Workbench) copy the entire contents of the "database.sql" file into the lines command into your database and run. This serves to initialize the tables and the data previously contained in them for the software to be able to query and display. After following the steps above, just access the project in your IDE (I use Eclipse) and run the software as a java application and the software will work normally. Do not forget that for the software to work correctly, the MySQL service must be running on your machine, otherwise, the software will not be able to perform your queries.


### Observação | Observation:

PT-BR: Você pode usar meu código como base de outro ou utiliza-lo como demonstração, mas gostaria que os devidos creditos fossem dados.

EN-US: You can use my code as a base for another or use it as a demonstration, but I would like the proper credits to be given.
