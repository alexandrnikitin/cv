## Alexandr Nikitin

![Blog](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/blog.png) https://alexandrnikitin.github.io/blog/  
![GitHub](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/github.png) https://github.com/alexandrnikitin  
![Stackoverflow](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/stackoverflow.png) https://stackoverflow.com/users/974487/alexandr-nikitin  
![Gmail](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/gmail.png) [nikitin.alexandr.a@gmail.com](mailto:nikitin.alexandr.a@gmail.com)  
![Skype](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/skype.png) [nikitin.alexandr.a](skype:nikitin.alexandr.a)  
![Twitter](https://raw.githubusercontent.com/alexandrnikitin/cv/master/images/twitter.png) https://twitter.com/nikitin_a_a  

### About Me

I'm a Software Engineer at Adform (Ad Tech industry) focused on server-side, back-end and database development. I have extensive experience in creating scalable, distributed, fail-safe and high-load services. I'm passionate about high-performance systems and enjoy working on nontrivial tasks. I worked for enterprise, outsource, startup companies and as a freelancer in various industries: from banking to adtech, from entertainment to financial.  


### Skills

Languages: **C#**, **Scala**, Java, Python, SQL.  
Databases: KV (**Aerospike**) SQL (**MSSQL**, Sybase, PostgreSQL), Column (**Vertica**)  
Platforms: **.NET**, **JVM**, **Kafka**  
Infrastructure: **Linux**, **Ansible**, Docker, Mesos, AWS, Azure.  
Stack: **Netty**, **Akka/ Akka Streams**, Spark, Storm.  


### Professional Experience

#### Jul 2014 - Present, Senior Software/ Data Engineer at "Adform", Lithuania, Vilnius

>"Adform is the independent and open full stack ad-tech platform that encompasses creativity, data and trading, servicing media agencies, trading desks, brands and publishers globally."

**Product:** Real-time bidding Algorithms, a system that calculates bidding prices and probabilities of events. Key challenges are: large amount of data (10B events per day), high-performance APIs (1M RPS and 15M ads per second). I work on data infrastructure for data scientists, serving layer for algorithms, A/B testing service, algorithms' training process and feature engineering for algorithms.  
Languages: Scala, Java, Python, C#  
Databases: Aerospike, Vertica, PostgreSQL  
Stack: Kafka, Spark, Flink, Akka Streams, Netty, Vowpal Wabbit  

**Product:** Cross-Device Audience Management, a system that gives the ability to target and recognize users across their different devices. Key challenges are: new product from scratch, big data, high-load. I held the technical lead role so that all design decisions were on my conscience. We could handle 1.2M RPS with one persistent database call on 4 API nodes and 4 database nodes. Ask me how :smile: There's ubiquitous Big data, of course, 5B of user profiles, 8B of events per day, real-time streaming, event-driven distributed architecture.  
Languages: Scala, C#, Java  
Databases: Aerospike, Redis, MSSQL  
Stack: Netty, Akka, Akka Streams, Kafka, Storm    

**Product:** Real-time bidding, Demand Side Platform; A high-load and low latency platform to facilitate buying of online advertising. It handles more than 2 Million RPS with latencies below 20ms. I worked on performance, stability and new features. I witnessed the load growth from 200K to 1M RPS.  
Languages: C#, SQL  
Databases: Aerospike, Cassandra, MSSQL  

#### Jun 2012 - Mar 2014, Senior .NET developer at "Ciklum", Belarus, Minsk

>"Ciklum is a global technology partner delivering software engineering excellence and IT solutions to Fortune 500 companies and organisations alike."

**Product:** the MobileHub, UK, London. A high-load mobile affiliate network system (~1M users per day). Modules: Traffic redirector, recommendation engine, customer website with reports, Webservices for integration with 3rd parties.

I introduced design changes into the project applying CQRS, Event Sourcing design patterns following DDD approach (I was fan of it at that time). I made the system distributed using Service Bus, Worker Roles, NoSQL which improved performance and scalability. Rewrote key module (Traffic Redirector) from scratch which was driven by performance reasons.
Introduced acceptance testing into development process.
Introduced Kanban technique into development process within timid steps to Continuous Delivery.  
Stack: C#, T-SQL, MSSQL, Azure Sql/ Tables, ASP.NET MVC, Entity Framework, WCF,  

**Product:** MobJizz, UK, London. A high-load entertaining VOD portal in the adult industry (up to 2M unique users per day).
Modules: Traffic redirector, End-user website, Web services for integration with 3rd parties, Reporting system.

I made integrations with 3rd party content provider, a purchase verification service, a mobile billing service. Worked on the end-user website performance and optimizations and improved site load during peak time from ~3 seconds to ~0.5s 95%%. Improved in-house android application generation process by introducing a distributed pool of applications. Refactored code and DB models to be able to write unit tests against databases.  
Stack: C#, T-SQL, MSSQL, HTML, CSS, Javascript, jQuery, ASP.NET MVC, WCF, Entity Framework, Linq2Sql.  

#### Dec 2010 - Jun 2012, .NET developer, freelance

I worked as a freelancer for customers from various countries and developed dozens of applications: client-server WinForms apps, a module for Orchard CMS, tens of trading automation algorithms for stock exchanges.  
Stack: .NET, C#, T-SQL, Mql4, NinjaScript, MSSQL, SQL CE, WinForms, HTML, CSS, Javascript, jQuery, ASP.NET MVC.  

#### Dec 2007 - Dec 2010, Subject Matter Expert at "Ivestbank", Russia, Moscow

I worked on Automated Banking System and was involved in the entire cycle of product development, gathering and analyzing requirements, designing and developing features, testing and supporting them. I developed numerous modules from data loaders to a module that covered full accounting cycle of securities, from numerous reports to template engine for MS Word/ Excel. I worked on database optimization and refactoring.  
Stack:  Sybase ASE, MSSQL, Oracle, Postgresql, Sybase PowerBuilder PowerScript, T-SQL, PL/pgSQL, .NET 2.0  


### Credo

* I do believe in the Engineering-driven culture. The culture where engineers drive the process and achieve goals. This is the most efficient way to build high-quality software.  
* I do believe in the open-source model and enjoy contributing to open-source projects.  
* I do believe in fast feedback cycles in software development. `Pair programming -> Automated tests -> Code review -> Continuous Integration -> Continuous Deployment`, the development process is much more important than methodologies and management.  


### Open-source

I do believe in the open-source model and enjoy contributing to open-source projects. It leads to better quality, transparency and interoperability.   
I'm a co-author of [NSubstitute](https://nsubstitute.github.io/), a friendly substitute for .NET mocking frameworks.  
I'm a co-author of [strftime.js](https://github.com/samsonjs/strftime), a high-performance date and time formatting library for Javascript. I rewrote the library from scratch and improved performance by 10-20 times.  
I wrote [the fastest Bloom filter for JVM](https://github.com/alexandrnikitin/bloom-filter-scala) that is much faster than Googles's or Twitter's 😄  
[Bounded multiple producers multiple consumers queue](https://github.com/alexandrnikitin/MPMCQueue.NET) was also an interesting experience  
There are other libraries and numerous contributions on github. [TAL](https://github.com/alexandrnikitin)


### Public Fails

I write [a blog and enjoy doing it](https://alexandrnikitin.github.io/blog/).
I show up as a public speaker occasionally (I'm not a good speaker though). I've spoken several times at internal (un)conferences and at external meetups and conferences. There's even [a conference video publicly available on youtube](https://www.youtube.com/watch?v=Yp4yQQqb2VI) if you want to take a look at me.

### Hobbies & Interests

Travelling, it gives me the ability to see things, people, the world from different angles and be more objective.  
Cycling, I have a dream to travel around the world on [a bicycle](http://instagram.com/p/lCbB6mPpG7).  
Trekking, why do people climb [mountains](http://instagram.com/p/nQZoPRvpKr)?  
