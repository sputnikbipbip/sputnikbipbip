<h1 align="center">Hello there 👋, I'm Daniel</h1>

<br></br>
<h3 align="left">Final project: </h3>

[DIRECT-SINCRO](https://github.com/RainPumpkin/direct-sincro)

**Direct-Sincro** is a traffic event access management system for owners and drivers. Together with two classmates, we tried to demonstrate the possibility of a new system to incorporate in the current systems of the **ANSR** (Autoridade Nacional de Segurança Rodoviária), by making speeding tickets available to citizen in a shorter period of time, while offering a set of new functionalities, such as the payment of fines and the delegation of vehicles to other subscribers. We used **PostgreSQL** as a database management system in conjunction with **SQL** to build and manage our **relational database**. The main module was built on the **JVM** using **Kotlin** as the main programming language. We also used **Spring Boot** in the business layer. **Node.js**, **Express**, **JavaScript**, **NPM**, **Handlebars**, **HTML & CSS**, **Node Fetch** for the **SIGET** and **SCOT** systems that are responsible for capturing, processing and issuing the infractions in the **ANSR** systems. **React**, **PWA**, **Bootstrap 5** for the user interface.   

<h3 align="left">Technologies used:</h3>

PostgreSQL V42.1.4, SQL, JVM, Kotlin V1.6.21, Spring Boot V2.7.0, Node.js V16.15.1, Express V4.18.1, JavaScript, NPM, Handlebars 4.2.0, HTML & CSS, Node Fetch V3.2.5, React V18.1.0, PWA, BootStrap 5, UML (MagicDraw), Git, OpenApi 3.0, Swagger

<br></br>
<h2 align="left">Other projects:</h2>

[Multithreaded server for exchanging messages between client - PC - Concurrent Programming 2022-2023](https://github.com/isel-leic-pc/s2122-2-leic42d-problem-sets-student-SPUTNIKBIPBIP)

<h3 align="left">Description</h3>

In the Concurrent Programming subject I made a server with a **TCP/IP** interface to exchange messages between clients in **Kotlin**. To manage multithreading I used the java.util.concurrent library and **Kotlin's Coroutines**.
The application allows you to create, leave or enter shared rooms. The management of messages between clients in the rooms is guaranteed using data structures incorporated in the java.util.concurrent Java library. 

<h3 align="left">Technologies used:</h3>

Kotlin, Kotlin Coroutines, Java NIO, Java Concurrent

<br></br>
[Chess Royale - PDM - Programming on Mobile Devices – 2021-2022](https://github.com/sputnikbipbip/ISEL_Projects/tree/main/PDM_Programa%C3%A7%C3%A3oDispositivosM%C3%B3veis/PDM-2122i-LI5X-G28-main)

<h3 align="left">Description</h3>

With another classmate, we created an **Android** application that presents daily chess puzzles. Puzzles are retrieved daily from the **Lichess API**. An **HTTP** request is made to the **API** and in the body of the response we get information about the puzzle in its initial state and the moves allowed. **Chess Royale** has a screen for the history of daily puzzles, which are stored in memory after being extracted from the **Lichess API**. The database that supports the puzzle history was built with the **Room** framework (an abstract **SQLite** implementation more suitable for mobile operating systems). We also used **Retrofit** to make the requests to the **Lichess API** and **WorkManager** to schedule a thread to collect the information of the daily puzzle form the **Lichess API** even if the user doesn’t start de application.


<h3 align="left">Technologies used:</h3>

Retrofit V2.9.0, Android Studio, Room V2.3.0, Kotlin V1.6.10, LiveData V2.4.0, WorkManager V2.7.1, Git, Gradle V7.0.3, Maven

<br></br>
[Jsonaif – AVE – Virtual Execution Environment – 2021-2022](https://github.com/sputnikbipbip/ISEL_Projects/tree/main/AVE_AmbientesVirtuaisExecu%C3%A7%C3%A3o/jsonaif-i42d_12-main)

<h3 align="left">Description</h3>

Together with another classmate we created a library for data processing in **JSON** format. This library allows the user to transform a **JSON** string into an instance of a compatible domain class in runtime. This application used the library **JavaPoet** (**Java API** to generate .java source files at runtime) and **Kotlin reflect** (allows to introspect the structure of the program at runtime). **Jsonaif** performance was measured with the **Java Microbenchmark Harness** framework. Lazy and eager techniques were explored and compared.


<h3 align="left">Technologies used:</h3>

Java Microbenchmark Harness, Kotlin V1.6.10, JavaPoet V1.13.0, Java V17.0.2, Kotlin Reflect, Gradle V6.8.3

<br></br>
[SO – Operating Systems – 2021-2022](https://github.com/sputnikbipbip/ISEL_Projects/tree/main/SO_SistemasOperativos/2021v-li42d-G09-main)

<h3 align="left">Description</h3>

In the Operating Systems subject, together with two classmates, we created the following programs in C:

We have developed a shell program for processing command lines with the ability to:

* Run programs with and without arguments.
* Run programs with and without arguments and redirect standard output.
* Run programs, redirecting the standard output of one program to the standard input of another.
* Chaining programs execution redirecting the standard output of the last run.


We made a program that allows you to edit the pixel values in a **BMP** type file, thus adjusting the tone of the image as a final result.

We create a thread synchronization framework, and explore mutual access control techniques based on the use of semaphores, count down latches, etc.

We generate a multi-threading program that allows searching by extension type, in all files (passed as an argument) a certain word.

In the final part, we created a server to answer **TCP/IP** connections, whose functionality consists of converting all the letters of the text typed in the command line into uppercase. It was necessary to develop a client application for the server, which was responsible for closing the connection with the server. All requests were serviced by a single thread using the functionality of the libuv library.

<h3 align="left">Technologies used:</h3>

Libuv, Kernel, Ubuntu, C, Virtual Box

<br></br>
[PI – Board Games Atlas – 2020-2021](https://github.com/sputnikbipbip/ISEL_Projects/tree/main/PI_ProgramacaoInternet/web-app-project-g_11-main)

<h3 align="left">Description</h3>

Together with another classmate, we created a web application that added functionality to the **Board Games Atlas API**. **Board Games Atlas** provides information about board games. The developed application allows creating a customer account, organizing games by different groups, associating **API** games with groups and browsing through game details.
The language used to develop the application was **JavaScript** together with the **Express.js** framework used to build the server responsible for serving the different requests. To document the different routes, and to test them we used an **OpenAPI 3.0** framework together with the supported language **YAML**. The database was supported by the **ElasticSearch** framework. The web application tests used **npm's** **supertest** and **node-fetch** libraries.

<h3 align="left">Technologies used:</h3>
JavaScript, NPM, Express, OpenAPI 3.0, YAML, ElasticSearch, Supertest, Node-fetch, Handlebars, CSS, HTML, Passport

<br></br>
[SI2 – Information Systems 2 – 2020-2021](https://github.com/MarcoFSBorges/SV2021-SI2-G05)

<h3 align="left">Description</h3>

<h3 align="left">Technologies used:</h3>
EntityFramework, .nuget, .NET, SQL, MySQL, C#, T-SQL

<br></br>
<p align="left">
</p>

<br></br>
[POO – Object Oriented Programming – 2020-2021](https://github.com/sputnikbipbip/ISEL_Projects/tree/main/POO_Programa%C3%A7%C3%A3oOrientadaObjetos)

<h3 align="left">Description</h3>

I made 2 games in Android. 

The design one is an application that lets you draw lines, circles or other figures in a view on Android.

covid_extermination is a game whose goal is to insert the viruses into the trash can, winning the game when there are no more viruses left. This one is the most complex.

<h3 align="left">Technologies used:</h3>
Java, Gradle, OOP, Android

<br></br>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>

<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.elastic.co" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> </p>
<br></br>

### Connect with me  
<div align="left">
<a href="https://www.linkedin.com/in/daniel-azevedo-8404a7112/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
</div>  
<br></br>



### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)


