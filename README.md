# workshop-agenda

## Agenda

Time | Session
---- | -------
8:30 AM - 8:45 AM   | _Introductions & Kickoff_ [Brandon - Cerner]
8:45 AM - 9:00 AM   | _Session 0: API Lifecycle Management_ [Nuwan - WSO2](https://docs.google.com/presentation/d/1R_HXtXGPwvIMQc-3kFJmmf_tsZMr1Li4LWVDVdkv4wQ/edit?usp=sharing)
9:00 AM - 9:15 AM   | _Session 1: Prototype the API_ [Nuwan - WSO2](https://docs.google.com/presentation/d/1R_HXtXGPwvIMQc-3kFJmmf_tsZMr1Li4LWVDVdkv4wQ/edit?usp=sharing)
9:15 AM - 9:30 AM   | _Session 2: [PAS & Cloud Native]()_ [DaShaun - Pivotal] <br>1> Overview of PAS <br>2> 12 factor App
9:30 AM - 10:00 AM   | _Session 3: [App Manager Overview & Creating Services on PAS](https://github.com/cts-workshop-02-2019/creating-services#apps-manager-overview)_ [Febin - Cerner]
10:00 AM - 10:30 AM   | _Session 4: [Deploy a web app to PAS](https://github.com/cts-workshop-02-2019/angular7-m0#simple-frontend)_ [DaShaun - Pivotal] <br>[Initial Highlevel overview](https://github.com/cts-workshop-02-2019/api-design/blob/master/README.md#initial-state)
10:30 AM - 11:00 AM | _Session 5: Creating a new [Java](https://github.com/cts-workshop-02-2019/spring-employee-service-m1#session-1---hello-world) or [DotNet](https://github.com/cts-workshop-02-2019/dotnet-employee-service-m1#session-1---hello-world) App - Starting from zero_ [DaShaun - Pivotal]
11:00 AM - 12:30 PM | _Session 6: CRUD with [Java w/ Spring Data JPA](https://github.com/cts-workshop-02-2019/spring-employee-service-m2#spring-employee-service-m2) or [DotNet w/ Entity Framework](https://github.com/cts-workshop-02-2019/dotnet-employee-service-m2#dotnet-employee-service-m2)_ [Sean - Pivotal]
12:30 PM - 01:00 PM  | _Working Lunch - Hands On Help - Q&A_
01:00 PM - 02:00 PM | _Session 7: Add Configuration & Actuators/ Steeltoe Management_ [DaShaun - Pivotal]
02:00 PM - 02:30 PM   | _Session 8: Publishing and Consuming_ [Nuwan - WSO2]
02:30 PM - 03:30 PM   | _Session 9: Adding Oauth2_ <br>[Final Highlevel overview](https://github.com/cts-workshop-02-2019/api-design/blob/master/README.md#final-state)
03:30 PM - 03:45 PM   | _Break_
03:45 PM - 04:30 PM   | _Wrap-up, Q&A, Course evaluation_

# Pre Requisites

## CF CLI (2 mins)

Download and install CF CLI from the below link

https://docs.run.pivotal.io/cf-cli/install-go-cli.html

## Tools

### JDK (Only those who like to develop in Java) (5 mins)

Download and install [Java JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

To set __JAVA_HOME__, do the following:

* Right click My Computer and select Properties

* On the Advanced tab, select Environment Variables, and then edit __JAVA_HOME__ to point to where the JDK software is located, for example, C:\Program Files\Java\jdk1.6.0_02.

### IDE (5 - 10 mins)

An IDE of your choice, preferably [Spring Tool Suite](https://spring.io/tools) (for Java) and  [Visual Studio](https://visualstudio.microsoft.com/downloads/) (for .Net)

### Git (3 mins)

Download and install [Git](https://git-scm.com/downloads)


## Verify Access

Login to the PAS foundation's web portal (e.g. https://apps.sys.dev.us-west-2.cernercf.io/).

Verify that you are able to see `enterprise-services-poc` Org and a space named with your Corporate ID
