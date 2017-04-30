# Springing into action

* DI & AOP are the key Spring ideas.
* Rod Johnson is the author of Spring (2002).
* Bean is synonymous with POJO, at least throughout this book.

### How Spring tends to simplify Java development?

* Lightweight and minimally invasive development with POJOs
* Loose coupling through DI and interface orientation
* Declarative programming through aspects and common conventions
* Eliminating boilerplate code with aspects and templates

In a Spring application, an application context loads bean definitions and wires them
together. 

ClassPathXmlApplicationContext
AnnotationConfigApplicationContext

But if you want even more DI, I encourage you to
look at Dhanji R. Prasanna’s Dependency Injection (Manning, 2009, www.manning.com/
prasanna/), which covers DI in fine detail.

 (AOP) enables you to capture functionality that’s used
throughout your application in reusable components.

### Separation of concerns
### Cross-cutting concerns

Spreading concerns across multiple components introduces two level of complexity:

* The code is duplicated across multiple components. 
* Your components are littered with code that isn’t aligned with their core func-
tionality.


With AOP, you can then cover your core application with layers of functionality thus keeping the security, transaction, and logging concerns from littering the application’s core business logic.

### AspectJ pointcut expression language:

* before advice
* after advice

Spring attacks complexity in Java development using POJO-oriented development, DI, aspects, and templates.