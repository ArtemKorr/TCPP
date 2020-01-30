# The task of creating a program:

Develop a program that reads from the MySQL DB file ([aviadispetcher.sql]) information about the flights of Flight Airlines:
 
| Data | The name of the field in the database | The format of the field in the database |
| ------ | ------ | ------ |
| ID | id	| int(11) (Auto increment) |
| flight number | number	| varchar(6) |
| destination | city | varchar(25) |
| departure time | depature_time | time |
| the number of available seats in the salon | free_seats | int(4) |


**User - a company employee** can add entries to the flight file and edit the available information in the main application form.

**User – airline customer** can view in the main program form a list of all flights and search information:
- time of departure of the aircraft to the city X
- number of vacancies in city X with departure time not later than Y. 
The values of X, Y are entered by the user into the corresponding main form fields.
 
The user-client can retrieve the results of the information selection into a MS Word file that is formed based on a template [Template MS Word].

Flight is aware that more than 85 flights cannot be operated.

## Project limitations

- Project duration - from 27.01.2020 to 20.04.2020.
- The program must be written in C # in Visual Studio IDE. 
- Design should be based on company process models in IDEF notation and RUP models in UML notation.
- The implementation will be carried out by the Scrum method. The Product Backlog will be split into 2 sprints lasting 2 weeks.
- Upon completion of the project, the program must perform all the intended functions, have documentation

## Composition of program documentation

1. Specification of requirements (the template [Requirement Document])
2. Admin and user instructions.
3. Technical design software, which consists of:
  - structural and functional models of the process in IDEF notation:
     + context diagram
     + decomposition diagram
  - RUP models in UML notation:
     + use case model
     + model of analysis
     + design model
     + model of software implementation


## Limitations of the project team

The project involves 3 specialists: all participants have experience writing code, 1 of them - has experience in software design, 1 - has experience in creating documentation for the program and previously participated in projects as a specialist in software quality determination.

Workplaces are fully equipped.

[//]: # (Below are the links used in the text)


   [aviadispetcher.sql]: <https://github.com/OlgaTat/TSPP2018-19/tree/master/Input%20Files/>
   [Template MS Word]: <https://github.com/OlgaTat/TSPP2018-19/blob/master/Input%20Files/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%9F%D0%BE%D1%88%D1%83%D0%BA%D1%83_%D1%80%D0%B5%D0%B9%D1%81%D1%96%D0%B2.dot>
   [Requirement Document]: <https://business.esa.int/sites/default/files/RD%20Template.docx>
