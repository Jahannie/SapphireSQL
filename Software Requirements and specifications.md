Software Requirements and specifications
1.1 Purpose 
This software requirements are intended to define the project that will be used as a n evaluation method in the programming languages course

1.2 Scope
Name: Sapphire SQL 
The product will:
Help database tester with an object oriented programming tactic 
Allow user to generate quicker queries.

1.3. Interface Requirements-Software Interface: 
The application will provide a simple graphical user interface, to provide the user an easy way to type code and be able to run it immediately after finishing. The design will be a simple big text area and a button to run and compile the code 

2. Functional Requirements
2.1 Inputs: 
The language to be designed will follow most commonly used object oriented programming rules, so that it will allow a user with no prior SQL knowledge or any other query language to be able to test a database. The user is expected to know the details of the database like tables, relations, entities, attributes etc. 
2.2 Processing Code: 
To process the code from the SQL query tester language there will be a lexical analyzer and syntax analyzer. For the lexical analyzer the tool used for producing a scanner will be JFlex because the language chosen for the development of the language is Java. The syntax analyzer tool used will be parsing simulator. The parsing strategy for the language will be bottom up parser LR (left-to-right, rightmost derivation) type. The query language used to process the code will be SQL because it is the most widely used query language in the world.
2.3 Outputs: 
The possible outputs will be all the possible queries possible regarding the table or tables specified. 

3. Non-Functional Requirements
3.1 Performance 
Java is a platform independent language, the code written in this language will also follow this.
3.2 Reliability 
Language reliability will focus on avoiding ambiguity in grammar by using a bottom up parser.
3.3 Maintainability
The language will be designed in a way that favors possible user implementations of new functions using the object oriented programming method.

