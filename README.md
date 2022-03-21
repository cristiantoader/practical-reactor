# Practical Reactor

Welcome to practical Project Reactor and reactive programming workshop! 100+ unique exercise offers you to gain production like experience or to improve existing Project Reactor Skills by teaching best practices for building a reactive applications.

## Table of Contents

* [Reactive programming and Reactive systems](#reactive-programming-and-reactive-systems)
    * [Why now?](#why-now)
    * [Spring WebFlux (web reactive) module](#spring-webflux-web-reactive-module)
        * [Server side](#server-side)
            * [Annotation based](#annotation-based)
            * [Functional](#functional)
        * [Client side](#client-side)
    * [Spring Reactive data](#spring-reactive-data)
      * [CI with Travis](#ci-with-travis)
      * [Running instructions](#running-instructions)
    * [Run the application by Maven:](#run-the-application-by-maven)
    * [Run the application on Cloud Foundry](#run-the-application-on-cloud-foundry)
    * [Run the application by Docker](#run-the-application-by-docker)
        * [Manage docker swarm with Portainer](#manage-docker-swarm-with-portainer)
        * [Manage docker swarm with CLI](#manage-docker-swarm-with-cli)
            * [List docker services](#list-docker-services)
            * [Scale docker services](#scale-docker-services)
            * [Browse docker service logs](#browse-docker-service-logs)
        * [Swarm mode load balancer](#swarm-mode-load-balancer)
    * [Browse the application:](#browse-the-application)
      * [Load testing with Gatling](#load-testing-with-gatling)
      * [Log output](#log-output)
      * [References and further reading](#references-and-further-reading)


##Who is this workshop for?

Workshop is designed for relative beginners in Project Reactor, that already has some theory knowledge but lack hands-on experience.
If you are absolute beginner in Project Reactor, this is also fine, but this workshop just offers tasks to improve your skills and does not explain all the concepts used in exercises.
If you are absolute beginner, you might want to start with some theory what asynchronous, reactive programming is and how Project Reactor can help you with that.

If you are already familiar with Project Reactor, this workshop is for you.

###What do I need to start?
As stated its expected that you have at least some basic knowledge about concepts of Project Reactor and reactive programming.
Knowing what Project Reactor is, what are Mono and Flux is enough to get you started!
Other than that you will need a nice IDE, like Intellij or Eclipse, time and Project Reactor reference guide!
No books and online courses needed, all chapters and exercises are linked to particular section in [reference guide](https://projectreactor.io/docs/core/release/reference/).

##How to start?

- Start by building this repo with simple `mvn clean install`.
- All the exercises are located in `exercises/src/test/java` package.
- All exercises are in the form of unit tests. If you run the test and test passes, that means you solved exercise successfully!.
- All chapters are enumerated with number: c${chapter}. Starting with 1. (eg: c1_Introduction)
- Every chapter contains read me documentation at the beginning of the file that describes what is the chapter and important links in reference guide that you should read before starting the chapter.
- Every exercise has written implementation requirements and `todo` markers that will point you where to start.

###How to run?

- Navigate to chapter and exercise
- Do the changes required in the exercise
- Run the test
- If test passes, you are done with the exercise!

todo video here

###Are you stuck?
Are you stuck? Sometimes it gets hard to find the right answer. Just a nudge might help.
While in `exercises/` folder you can execute `mvn hint:{name_of_execrice}` and it will offer help how to solve execrice without giving out full solution.

![](http://www.giphy.com/gifs/VYEWRM6wMCGVm4O9wj)

###Still stuck? (in progress)
Hints are just a nudge to steer you in the right direction.
If you are just stuck and can' solve the exercise, or you want to compare your solution with authors solution navigate to `/solutions` branch.