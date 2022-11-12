# Chapter 1: A Pragmatic Philosophy 
## Topic 1:  It’s Your Life 
There are many software developers who think that they cannot improve themselves in their current job, who complain about the bad conditions at work, and they are disappointed. The real question here is why can't you change jobs under these circumstances when our profession is so glamorous, a sought-after profession for any company?

**Tip 3: You Have Agency**

If your current working environment is not good try to fix it but not forever

## Topic 2: The Cat Ate My Source Code 
Bugs or delays can happen even in projects that have been tested and have very good documentation. The important thing here is that we accept our shortcomings and mistakes and try to solve them professionally.

We should feel a sense of mutual trust with our teammates, we should be able to speak our ideas openly and listen to their ideas.

While working within the project, we take responsibility actively, do our best and make risk analysis for situations that may develop beyond our control. While taking responsibility, we need to take responsibility wisely, we have the right not to take responsibility for situations whose outcome we cannot predict.

**Tip 4: Provide Options, Don’t Make Lame Excuses.**

We should not blame anyone for a problem that is under our responsibility, we should not make excuses and we should be solution-oriented

## Topic 3: Software Entropy 
Even if the best plans are made and the best developers are worked on, rot can occur in a project.

**Tip 5: Don’t Live with Broken Windows**

Psychologically, hopelessness is contagious, and negative thoughts spread among the team members have the same effect. So when we see a bad decision, badly written code in the project, we cannot ignore it.

When we find ourselves in an environment with broken windows, that is, among badly written codes, we should not continue in that way, considering that the rest of the project is like that. Or on the contrary, in an environment where good code is written, don't be afraid to think that the whole project is like this and be the first to make a mistake.

## Topic 4: Stone Soup and Boiled Frogs 
**Tip 6: Be a Catalyst for Change**

When people see continued success, they can join you more easily, so give them an achievement and rally around for change.

**Tip 7: Remember the Big Picture**

Projects slowly spiral out of control, start small enough to go unnoticed, and eventually become completely unmanageable one day.

## Topic 5: Good-Enough Software 
It is not possible for us to develop perfect, error-free software. However, we don't need to worry too much about it, we should focus on making the software we develop good enough for the users, for the developers who will work on the project later, and for ourselves. In this way, you will realize that you are more productive.

**Tip 8 : Make Quality a Requirements Issue**

We must meet user requirements such as performance, privacy and security. It would be unprofessional to promise impossible deadlines or simply ignore these user requirements to meet the deadline.

Programming is like painting. You start with a blank canvas and some raw materials, draw and paint shapes, then fill in the details. Artists say you can ruin the picture if you don't know where to stand, it's the same with programming. There is no need for excessive refinement and embellishment to make the code perfect, because it will never be perfect.

## Topic 6: Your Knowledge Portfolio
Our current knowledge is temporary, as new techniques and new languages develop, they will become obsolete. That's why our habit of learning will be our greatest weapon. We need to make learning a habit, it should be a learning routine that we apply until our brain internalizes it, and then it will come by itself.

* Invest Regularly: Invest a small amount in yourself every day.
* Diversify: Change happens fast, so the more tech-related you are, the better you can adapt to change.
* Manage Risk: Technology is risky, so don't focus all of your focus on one place, spread your risk.
* Buy low, sell high: It is difficult to learn an emerging technology without becoming popular, but the payoff can be very high.
* Review and rebalance: We are in a rapidly changing industry, sometimes we need to sit down and review the technologies we use.

**Tip 9: Invest Regularly in Your Knowledge Portfolio**

**Tip 10: Critically Analyze What You Read and Hear**

We must make sure that the information in our portfolio is correct, that we are not swayed by just a moment of media hype.

## Topic 7: Communicate! 
As long as we can communicate well with other people, our ideas, the code we write, or having pragmatic thinking matters.

**Tip 11: English is Just Another Programming Language**

Our communication with people depends on the audience. That's why it's very important that we know the audience's requirements because it affects the way we present, our ideas may be good but the way we present is also important.

It is important to get feedback from the audience to improve communication.

Being a listener is also very important, if we want to rest, we must listen first.

Never leave questions unanswered, even if it's your job, give an answer that I'll be back later.

**Tip 12: It’s Both What You Say and the Way You Say It**

Pragmatic Programmers know documentation as an integral part of the development process.

**Tip 13: Build Documentation In, Don’t Bolt It On**

# Chapter 2: A Pragmatic Approach 
## Topic 8: The Essence of Good Design 
If we can easily change something, it is well designed.

**Tip 14 : Good Design Is Easier to Change Than Bad Design**

## Topic 9 : DRY—The Evils of Duplication 
The needs in the project can change from day to day, and the main problem arises while this change is happening because if we change an information in one place, we have to change it in another place. 

Each piece of information must be a single, unambiguous, authoritative representation within a system.

**Tip 15: DRY—Don’t Repeat Yourself**

DRY is not just copy-pasting the code, it is serving the represented information in two different places in two different ways.

When creating document, we should not explain how the code works in the comments lines, because the code already tells it. 

When creating data that represent information, there is no need for a second data expressing the same data.

**Tip 16: Make It Easy to Reuse**
## Topic 10: Orthogonality
If a change in one does not affect the other, these two things are orthogonal. In a well-designed system, Database codes and interface codes will be orthogonal, that is, they will not affect each other. nonorthogonal systems are more complex, more difficult to control and change.

**Tip 17: Eliminate Effects Between Unrelated Things**

We want to write independent components that do not affect each other, when they are isolated from each other, a change in one does not cause an error in the other.

In this way, development time and testing time will be shortened.

* Gain Productivity: In addition, since each component has a task, they can be used repeatedly and combined with other components, so they do not overwhelm each other.
* Reduce Risk: Since the problem part is isolated, it does not spread to the whole system. In this way, the system will be less fragile and the problem will be solved with minor fixes. 

The layered approach is a powerful way to design an orthogonal system. Thanks to layering, we can change applications with great flexibility without affecting the code much.

We must be careful when using third-party tools, maintain the orthogonal nature of the system, and choose wisely.

* Keep your code decoupled : We should write code that does not depend on other models and does not introduce unnecessary things to other modules.
* Avoid global data: As soon as we use a global data, we become dependent on other modules that use this data. We should avoid it.
* Avoid Similar functions: If the codes are repetitive, there is a structural problem.

It is easier to test an orthogonal system because individual (unit test) tests are done because the components have limited access to each other.

In an orthogonal documentation, we should be able to easily change the view without changing the content, for this we use Markdown.

## Topic 11: Reversibility

Sudden changes may occur while the project is being developed, we must accept this situation and be prepared.

**Tip 18: There Are No Final Decisions**

**Tip 19: Forgo Following Fads**

We do not know what will happen in the future so we must be ready for change.

## Topic 12: Tracer Bullets
If you are working on a project that has not been built before, that is, you are actually trying to hit a target in the dark. In this case, users' needs may be somewhat unclear as they have not seen such a system before. In this case Pragmatic Programmers use the software equivalent of tracer-bullets. That is, we aim to develop in a fast, visible and repeatable way.

**Tip 20: Use Tracer Bullets to Find the Target**

In Tracer development, there will always be changes and new functionality to be added. It is an incremental approach.

* Users get to see something working early : They will be able to contribute during the development phase of the project.
* Developers build a structure to work in : After solving the entire structure of the application from end to end, coding will not be that difficult.
* You have an integration platform : The effect of each new change is more pronounced and interactions are more limited, so debugging and testing is faster and more accurate.
* You have something to demonstrate : Project sponsors will want to see demos, so we can always show something.
* You have a better feel for progress : It will be better to measure performance when one task is finished and another is started.

We should not be surprised when we fail the first time, we should make changes and get closer to the goal.

When developing prototypes, we only code certain parts that the user can use functionally. While writing Tracer code, we are trying to prepare an architectural framework for developers.

Prototyping generates one-time use code. The audience code is simple yet complete and forms part of the skeleton of the final system.

## Topic 13: Prototypes and Post-it Notes
Prototyping is used to analyze, uncover and reduce risk at low cost.

**Tip 21: Prototype to Learn**

Prototyping is a learning experience. Its value lies not in the code produced, but in the lessons learned.

We can ignore the following when prototyping
* Correctness
* Completeness
* Robustness
* Style

## Topic 14: Domain Languages
**Tip 22: Program Close to the Problem Domain**
## Topic 15: Estimating
**Tip 23: Estimate to Avoid Surprises**

### HOW ACCURATE IS ACCURATE ENOUGH?
The units we use when estimating make a difference in the interpretation of the result. There is a big difference between saying an approximate and an exact value. So we have to choose the unit correctly.

| Duration       | Quote estimate in                        |
|------------    |--------------------------------------    |
| 1-15 days      | days                                     |
| 3-8 weeks      | weeks                                    |
| 8-30 weeks     | months                                   |
| 30+ weeks      | think hard before giving an estimate     |

Research someone who has been in a similar situation in the past. See how their problems are solved.

* Understand What’s Being Asked 
* Build a Model of the System 
* Break the Model into Components 
* Give Each Parameter a Value 
* Calculate the Answers 
* Keep Track of Your Estimating Prowess 

The following should be applied incrementally.
* Check requirements 
* Analyze risk (and prioritize riskiest items earlier) 
* Design, implement, integrate
* Validate with the users 

**Tip 24: Iterate the Schedule with the Code**

# Chapter 3: The Basic Tools 
## Topic 16: The Power of Plain Text 
Pragmatic Programmers collect the requirements as information, express the information in design, implementation, tests and documents. The best way to store this information is “plain-text”.

**Tip 25: Keep Knowledge in Plain Text**

Human-readable and self-describing data formats will outlast any other data format.

Almost any tool in the computing universe, from version control systems to editors and command line tools, can run on plain text.

If we produce data in the form of plan text for the test, we will be able to do the test more easily. We can also easily analyze the output from the command line.

## Topic 17: Shell Games
For programmers, the workbench is the command line. Apart from every operation we do using the interface, we can do many different operations from here.

Using the interface is fast, easy, but it limits us, we miss many features in our working environment when we use the interface. The reason for this is that the person who developed the interface is limited to what they offer us.

**Tip 26: Use the Power of Command Shells**

Also, we can customize our workbench.
* We can set a theme.
* We can configure commands.
* We can use aliases and shell functions
* We can use the command completion feature.

## Topic 18: Power Editing
**Tip 27: Achieve Editor Fluency**

The things we do while using the editor must have become habits, that is, we do things without thinking and this gives us a serious speed. As Pragmatic Programmers, we need to know the commands that make our life easier by heart. For this, we should look for a shorter way of what we do constantly while using the editor, and when we learn that new feature, we should make it a habit by repeating it constantly.

There are plugins provided by the editor we use, apart from these, we can get the ones we need later. If we can't find what we need, we can develop it and present it to other people. If we need it, they can too.

## Topic 19: Version Control

VCS is like a time machine that stores every change we make in the code and documentation, who made the change, where and how much of the changes, the difference between new and old versions, and allows us to navigate through the changes. In this way, it allows more than one person to work on the same project or even on the same file.

**Tip 28: Always Use Version Control**

One of the most important benefits is that by creating a Branch, it allows everyone working on the project to do parallel development in isolation from each other.

Many teams configure VCS so that tests are run automatically and put into production when successful.

## Topic 20: Debugging
We should know that debugging is just solving a problem and act accordingly.

When you find someone else's mistake, you should not blame him, but focus on solving the problem.

**Tip 29: Fix the Problem, Not the Blame**

**Tip 30: Don't Panic**
Finding bugs can be a more stressful task, especially when the deadline is approaching or when we feel pressure from people. In this case, we should not panic and focus on the solution and think about what caused the bug.

The best way to start a bug fixe is to make it reproducible. If we can't make it reproducible, we'll figure out how to solve it?

**Tip 31: Failing Test Before Fixing Code**

**Tip 32: Read the Damn Error Message**

The program doesn't always crash, we may get wrong results. In this case, we need to trigger this wrong result in the debugger. In this case, we can proceed by taking a pen and paper with us and taking notes in order to control it.

* Logging and/or Tracing : Tracing statements are small diagnostic messages that we insert into the flow of the code and express what is happening at that moment. Although it is seen as a primitive method, it is a very effective method. Tracking statements must be consistent and regular so that they can be automatically parsed later. With the scripts we will write, we can automatically understand where the error is.
* Rubber Ducking : One of the simple but effective ways to find out where the error is is to try to explain the code to someone else.
* Process Of Elimination: In many projects, you may need to debug the project with code written by others. The bug can be in the OS, it can be in the software you are using 3rd party but these should not be our first thought, most likely the bug is in the application code under development.

**Tip 33: “select” Isn’t Broken**

If you just changed one thing and the system is not working, then something is directly or indirectly responsible.

When an error occurs, our first reaction is “No, it can't be” because our surprise is proportional to our confidence in the code we wrote. So when the error occurs, we must admit that we made a mistake. If we're sure it works, we can't do it hypothetically, we have to prove it.

**Tip 34: Don’t Assume It—Prove It**

Finally, is there anywhere else in the code that could cause the same error? fix if any. If it took a long time to fix the error, why did it take so long, what can be done to make it easier? Try to find that for next time.

## Topic 21: Text Manipulation
Pragmatic Programmers process text the same way woodworkers sculpt wood. It can quickly put data into shape.

**Tip 35: Learn a Text Manipulation Language**

## Topic 22: Engineering Daybooks 
We use daybooks to take notes at the meeting, write down variable values ​​while debugging, record our ideas, leave reminders.

Main benefits of daybook: 
* It is more reliable than our memory, we can look it up and remember it right away.
* We can continue to work by jotting down the ideas that come to our mind at that moment, we know that we will not forget them later.
* When we start to write, we can question the thought in our mind and realize that maybe it is false-nonsense.
# Chapter 4: Pragmatic Paranoia
**Tip 36: You Can’t Write Perfect Software** 

Pragmatic Programmers build a defense against their own mistakes, knowing that no one, including themselves, writes perfect code
## Topic 23: Design by Contract
The contract defines our rights and responsibilities bilaterally, and the consequences of non-compliance are also specified in the contract. Can we use this in software modules as well?

A simple but effective technique that attempts to identify the rights and responsibilities of software modules to ensure program accuracy.
* Preconditions: Requirements required for the routine to be called, should not be called if not provided.
* Postconditions: What the routine guarantees to do when called.
* Class Invariants: A class ensures that this condition is always true for the caller.

In summary, the routine ensures that postconditions and invariants will be completed when preconditions are provided by the caller. If not provided, an error may be thrown or the program may terminate. So have a clear idea of what to accept and what to give in return at first.

**Tip 37: Design with Contracts**

## Topic 24: Dead Programs Tell No Lies 
When there is an error in the program, it is very easy to get the idea that "it can't be". All the mistakes tell us what the problem is, as the pragmatic programmer he admits that when there is a mistake, something goes wrong. We must not forget to read the error messages.

**Tip 38 : Crash Early**

The best thing to detect the problem early is to be able to crash the program early. Crashing is usually the best thing we can do. Otherwise, we may continue and cause it to malfunction.

The basic principle is clear, if something happens in the program that you think will never happen, the program is no longer reliable. End the program as soon as possible.

## Topic 25: Assertive Programming 
**Tip 39: Use Assertions to Prevent the Impossible**

An assertion would be the easiest way to check when you have a place in the program where you say, “Of course this can never happen”.

There is a misunderstanding about Assertion; The assertion adds overhead to the code, so this can be removed after testing. However, this is wrong, we can only test a very, very small percentage of problems that can occur in real life, so we cannot pretend that there are no errors. Every time it is run in a live environment, there is a possibility that an error will occur. So yes, it comes with a burden, but we must take care of our code. If you're worried about performance loss, you might want to consider removing assertions that really impact it.

## Topic 26: How to Balance resources
We use resources when coding, but many developers do not have a fixed plan for allocation and deallocation.

**Tip 40: Finish What You Start**

A function or object that allocates is also responsible for deallocation.

**Tip 41: Act Locally**

For routines that want to access the same resource at the same time, there is a model as follows;
* Deallocate resources in the reverse order of allocate.
* When allocating the same resource group to different places in your code, always allocate them in the same order. It will reduce the possibility of dead-lock. 

If you're doing object-oriented programming, you can put resources inside the class. Thus, after using an object, when it goes out of scope or is retrieved by the garbage collector, the resource is released.

How do we make sure resources are returned when an error is thrown? We can use variable scope for this, when it goes out of scope, the resource is returned. Second, we can use finally in try-catch blocks, we can return the source at the end with or without an error.

Since Pragmatic Programmers don't trust anyone, including ourselves, we always think it's a good idea to create code that really checks that resources are properly freed.

## Topic 27 : Don’t Outrun Your Headlights 
We don't know what will happen in the future, the further we try to look, the more uncertainty will increase. That's why Pragmatic Programmers always take small steps and get feedback instead of taking big steps.

**Tip 42: Take Small Steps—Always**

Pragmatic Programmers make their code changeable instead of predicting for an uncertain future.

**Tip 43: Avoid Fortune-Telling: The future will look like our present, but we should not rely on it.**

# Chapter 5: Bend, or Break
## Topic 28: Decoupling
We write code to be easily changeable. Coupling is the enemy of change because it connects things that need to change in parallel.

**Tip 44: Decoupled Code Is Easier to Change**

Coupling can always occur when two different pieces of code share the same thing.

If you see strange dependencies between unrelated modules, or if a slight change in one place affects another, you definitely have coupling here. This can cause the programmer to be afraid to change the code.

**Tip 45: Tell, Don’t Ask**

We should not decide based on the internal state of an object and update that object. Doing so destroys the encapsulation principle.

**Tip 46: Don’t Chain Method Calls**

When accessing information, more than one "." try not to use it.

There is one big exception to the one-point rule: If the things you chain are unlikely to change, the rule doesn't apply.

Global data causes each method to gain an extra parameter because each method can access this global data. This causes a hidden connection between the methods. The most obvious of the problems this can bring is that a change to the global data can affect the entire code.

**Tip 47: Avoid Global Data**

Any modifiable external source is global data. In other words, if we use database, API, datastore, we can fall into the trap of globalization. The key is to wrap these resources behind code that we always control.

**Tip 48: If It’s Important Enough to Be Global, Wrap It in an API**

## Topic 29: Juggling the Real Word

An event represents the availability of information. This event can be realized by the user with an external effect, or it may occur with an internal effect as a result of the calculation. No matter how it happens, applications will work more effectively if we develop applications that respond to these events.

For this, 4 strategies can help us.

* 1. Finite State Machines
* 2. The Observer Pattern
* 3. Publish/Subscribe
* 4. Reactive Programming and Streams

The state machine systematically determines how to handle events. It represents a set of states, one of which is the current state. For each situation we also list the important events, where each event causes a new situation.

In the observer model, there is an event source, called an observable, and a client list of observers that deal with events. An observer registers itself as an observable by passing a reference to a function. When the event occurs, the observable iterates down its list of observers and calls the function that each passed it

But the observer pattern has a problem: because each observers has to register with the observable, it cause coupling. Also, in the typical implementation the callbacks are handled by the observable, synchronously, it can cause performance problem. This solves with Publish/Subscribe strategy.

In the Pubsub model, there are publishers and subscribers, each connected through named channels. Subscribers show interest in one or more channels, and publishers post events on those channels. Unlike the Observer model, the relationship between publisher and subscriber happens outside of our code, potentially asynchronously.

It's obvious that events can also be used to trigger reactions in code, but it's not always easy to activate them. This is where flows come into play. Streams allow us to treat events like a collection of data. It can be asynchronous, which means your code gets the opportunity to respond when the event occurs.
## Topic 30: Transforming Programming
**Tip 49: Programming Is About Code, But Programs Are About Data**

The easiest way to start the transformation is to identify the requirements, to lay out what the inputs and outputs will be. The next thing we need to do is to reveal how we can access the output from the input.

**Tip 50: Don’t Hoard State; Pass It Around**

##Topic 31: Inheritance Tax
There are two reasons to use inheritance. The first is to transfer the common features of the base class to child classes that will inherit, and the second is to establish a relationship between the base and the child class. However, both come with problems. Because inheritance is coupling.

Some people see inheritance as a way of identifying new species. However, after a while, it is necessary to add new layers to ensure the smallest differentiation in classes. It makes the application more fragile as the changes can affect many layers.

**Tip 51: Don’t Pay Inheritance Tax**

3 alternative techniques that you will never use inheritance again;

* Interfaces and protocols 
* Delegation
* Mixins and traits

Protocol ve arayüzleri bu kadar güçlü yapan şey, tip olarak tanımlayabilmemiz ve bu arayüzü uygulayan sınıfların bu tiple uyumlu olabilmesidir. Bir sınıf bir protocolü sağladığında, biz çok güvenli bir şekilde protocol içerisinde barınan fonksiyonu kullanabiliriz.

**Tip 52: Prefer Interfaces to Express Polymorphism**

Thanks to interface and protocol, we provide polymorphism without using inheritance.

**Tip 53: Delegate to Services: Has-A Trumps Is-A**

If the parent class has 20 methods and the inheriting class only wants 2 of them, then the remaining 18 functions will be callable when it inherits. Alternatively, delegation can be used.

We talked about the disadvantages of Inheritance, our basic idea is we want to extend classes with new functions without using inheritance. For this, we write a set of these functions using Mixins and give this set a name. Later when we create the class, we can add the mixins we have created.

**Tip 54: Use Mixins to Share Functionality**

These are the 3 methods we see; it can be alternative to share type info, add functionality or share methods. We have to determine the best according to the situation.
## Topic 32: Configuration
Your application; When working for different customers or in different environments, store specific customer and environment specific information outside the application.

**Tip 55:Parameterize Your App Using External Configuration**

Many applications have their configurations stored in database tables or as plain text files as JSON-YAML. Regardless of the form, the configuration information is read as a data structure when the application is first opened. Usually this data structure is stored globally for easy access but instead a better way would be to wrap our code behind the API from the configuration information.

* Many applications can access configurations using this API.
* Globally configurations can be changed.
* Continuity of the configuration file can be provided with an improved UI.
* Configuration data becomes dynamic.

It is important for us that it is dynamic, it prevents us from restarting the application when only a single parameter changes.
# Chapter 6: Concurrency
Concurrency is when two or more pieces of code run as if they were running at the same time. Parallelism is when they work at the same time.

There should be an environment where different parts of the code are executed as it runs, using things like threads, processes or fibers to ensure concurrency. For parallelism, hardware that can do two jobs at the same time is required.
## Topic 33: Breaking Temporal Coupling
Things tend to be linear when designing a system. After event A happens, we put forward a working logic so that event B happens. But this approach is inflexible, we must allow synchronicity and remove time dependency.

We must model and analyze what can happen at the same time and what should happen in a precise order. One way to do this is to use an activity diagram.

**Tip 56: Analyze Workflow to Improve Concurrency**
Activity diagrams show potential areas of concurrency but cannot tell if this area is sufficient, this is where design comes into play. While designing concurrency, we aim to find parts that take time, such as database query, connecting to an external service, but not in our code.

Concurrency is a software mechanism while parallelism is a hardware issue. If we have more than one processor, we can divide the work between them into independent parts, run each one in parallel, and then combine the result.
## Topic 44: Shared State Is Incorrect State

In the case where we use the shared state, we can lead to erroneous results if we act at the same time without considering the other.

**Tip 57: Shared State Is Incorrect State**

A semaphore is something that only one person can have at a time. When two people want to use the same common resource at the same time, only one person will be able to succeed in this request, thanks to the use of semaphores, while the other will have to wait. After the first user's job is finished, they will be able to continue using the updated resource.

There are also problems with this approach because the use of semaphores will only work if all users use it correctly, otherwise it will still be chaos.

**Tip 58: Random Failures Are Often Concurrency Issues**
## Topic 45: Actors and Processes
Actors are an independent virtual processor with its own local private state. Every actor has a mailbox, when a message is sent there, if the actor is empty, it processes that message and starts processing the new message.

The compute is a more general purpose virtual processor implemented by the operating system to facilitate concurrency.

* It is not carried out in a planned way, nothing is under control.
* Single state is kept in messages and actor's local state and messages cannot be inspected unless read by the receiver, local state cannot be accessed outside of the actor.
* All messages are one-way, no reply.
* Continues processing until an actor has completed all messages, processing one message at a time.

**Tip 59: Use Actors For Concurrency Without Shared State**

In the actor model, there’s no need to write any code to handle concurrency, as there is no shared state. 
## Topic 46: Blackboards
A Blackboards with a rule engine covering legal requirements is an elegant solution to the challenges found here. The order of arrival of data is unimportant and feedback is easily handled.

**Tip 60: Use Blackboards to Coordinate Workflow**

# Chapter 7: While You Are Coding
## Topic 37: Listen to Your Lizard Brain
Starting a new project can be a frustrating and frightening experience, there are 2 underlying problems and both have the same solution.

* Our lizard brain may be trying to tell us something based on our previous experiences, which can make us feel reluctant or suspicious.
* The other problem may be just afraid of making mistakes.

**Tip 61: Listen to Your Inner Lizard **

First of all, we should let go of what we were doing at that moment and move away from the keyboard to not think about the code, we should give our brain some time to organize itself.

If that doesn't work, we can try explaining the problem to someone else to get different parts of our brain to work. While we are telling it to someone else, we can suddenly understand for ourselves what the problem is.

If that doesn't work, we tell our brain that what we're trying to do isn't important, that it's okay if we make a mistake or go to waste. We can also do this with a prototype. In this way, tension will be replaced by a sense of urgency, and we will feel motivated to do the work. At this very moment, when we have the feeling of "I can do this", we will delete the prototype code and start the main work from the beginning.

## Topic 38: Programming by Coincidence
As developers, we work in a minefield where there are hundreds of traps we can catch every day, so we must be careful and avoid accidental programming.

* Accidents of Implementation: It is an error caused by the current writing style of the code.

* Close Enough Isn't: Approximate result is not enough, exact result is required.

* Phantom Patterns: We can't just consider a certain pattern and write code for the next step.

* Accidents of Context: Just because the answer we found is appropriate does not mean it is correct for our content.

* Implicit Assumptions: People consider many assumptions while working, but assumptions that are not based on fundamental facts are the bane of the project.

**Tip 62:Don’t Program by Coincidence**

If we want to be a developer who makes fewer mistakes and catches them early, we must program deliberately:

* Always be aware of what you are doing.

* Make sure you have enough code to explain the code to someone at a junior level

* Don't code in dark. If you’re not sure why it works, you won’t know why it fails.

* Proceed from a plan

* Rely only on reliable things. Don’t depend on assumptions. 

* Document your assumptions. 

* Don’t just test your code, but test your assumptions as well.

* Prioritize your effort to make time for the important parts

* Don’t let existing code dictate future code. 

## Topic 39: Algorithm Speed
Big-O is never going to give the actual numbers for time or space. It simply tells you how these values will change as the input changes.

You can estimate the order of many basic algorithms using common sense.

* Simple Loop: O(n) 

* Nested Loop: O(n^2)

* Binary chop: O(logn)

* Divide and Conquer: O(nlogn)

* Combinatoric: O(n^(k-1))

When writing code, we must calculate what the value range of the numbers might be and how much it will affect the code's execution time.

**Tip 62: Estimate the Order of Your Algorithms**

If we do not know how long the algorithm will take or how much space it will occupy in memory, we can run the algorithm with many different inputs and draw the results.

Our algorithm, which works effectively on small data sets, may not give the same result in large data sets.

**Tip 63: Test Your Estimates**

Here again, what we have to think about as pragmatic programmers is that the fastest algorithm will not always be the best. If we are going to work on a small dataset, it will be more important that the setup cost is shorter than the speed.
## Topic 40: Refactoring
During the development of the program, rethinking the previous written codes and decisions is a part of the development process.

Refactoring is disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.

Refactoring doesn't mean completely rewriting, it means cleaning code in small steps with low risk.

You need good, automated unit testing to guarantee that the behavior of the code hasn't changed.

When something feels wrong to us, we should not hesitate to change it. These errors may be as follows.

* Duplication

* Nonorthogonal design

* Outdated knowledge

* Usage

* Performance

* The Tests Pass

There may be no time to refactor due to time pressure in the development process, but it is necessary to refactor regularly. Otherwise, as the project grows, it will be much more difficult and costly.

**Tip 65: Refactor Early, Refactor Often**

* Don't try to add new functionality with the same time refactoring.

* Make sure you have good test, run test as often as possible and check if your changes have broken anything.

* Take small steps and test after each steps.

## Topic 41: Test to Code
**Tip 66: Testing Is Not About Finding Bugs**

Thinking about writing a test for our method allows us to look from the outside as if we were the customer of the code, not the author. Perhaps one of the biggest benefits of test writing is that it provides feedback.

**Tip 67: A Test Is the First User of Your Code**

Also, it is difficult to test the function that depends on other code because you have to provide the whole environment. But if we do it in a testable way, we reduce the link.

* 1. Decide on a small piece of functionality you want to add.

* 2. Write a test that will pass when the functionality is implemented.

* 3. Run all tests. Just verify that the failure is the one you just wrote.

* 4. Write the smallest amount of code needed to pass the test, and verify that the tests now run cleanly.

* 5. Refactor your code:

**Tip 68: Build End-to-End, Not Top-Down or Bottom Up**

A unit test is essentially a piece of code that runs a module. After calling the routine in the module, it compares the returned results with known values and checks if it works as expected. Then we can test the whole system again with unit testing facilities, since we know that the parts work one by one.

We like to think of unit testing as testing against contract. This test will give us 2 things, whether the code complies with the convention and whether the contract expresses what we want. The biggest advantage of this technique is that it facilitates debugging, we can directly understand which module has an error.

**Tip 69: Design to Test**

Give test code the same care as any development. Keep it decoupled, clean, and robust.

**Tip 70: Test Your Software, or Your Users Will**


## Topic 42: Property-Based Testing
We write code based on an assumption and we write tests based on that assumption. Just because the test we wrote passes does not mean that our assumption is correct. Because the test only does what it's supposed to do according to our assumption.

**Tip 71: Use Property-Based Tests to Validate Your Assumptions**

In property-based testing, we set some rules to generate input and create some claims to validate the output. We don't know what will happen next.

When a property-based test fails, we must determine for which values it failed and unit-test with those values. By forcing this bad value to be used, unit testing will ensure that the error is not overlooked.

Property-based testing is complementary to unit testing: they address different concerns, and each brings its own benefits

## Topic 43: Stay Safe Out There
Pragmatic Programmers have a healthy amount of paranoia about security to prevent any attack.

Restrict any access points through which an attacker can enter data, extract data, or initiate execution of a service.

**Tip 72:Keep It Simple and Minimize Attack Surfaces**

* Code complexity makes attack surface larger. Less code means fewer bugs, fewer opportunities for a crippling security hole.

* Never trust data from an external entity

* Anyone can call for services that are unauthenticated, which can block any process. 

* Keep the number of authorized users at an absolute minimum. 

* Don’t give away information

* Information designed to make debugging easier can make breaking in easier as well. 

Don't automatically set a high-level permission, if the high-level permission is needed, allow it but retract it when the job is done. Only allow access to sensitive resources by people with certain permissions.

Set the default settings in the application in the most reliable way.

No matter where you store personal data, never store it in plain text, keep it encrypted.

When the computer needs a security patch, we shouldn't put it off until later. Because otherwise, it may become vulnerable to abuse.

**Tip 73:Apply Security Patches Quickly**

## Topic 44: Naming Things
Naming is important because because they reveal a lot about your intent and belief.

When naming things, we should always consider what we mean. In this way, the naming we make will be more understandable.

In addition, the culture in the environment in which we develop is also important. If some general naming used in one programming language is not used in another programming language, this will be just as wrong.

Every project has jargon words with specific meanings that those on the team use to ensure consistency. To ensure consistency, everyone on the team needs to know what they mean.

When you see a name that doesn't express its intended use, is misleading or confusing, correct it. As pragmatic programmers, we should fix it instead of agreeing with others' mistake.

**Tip 74: Name Well; Rename When Needed**




