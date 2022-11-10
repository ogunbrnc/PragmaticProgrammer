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
Kod yazarken, yazdığımız kodların kolayca değiştirilebilir olmasını isteriz. Coupling ise değişimin düşmanıdır çünkü paralal olarak değişmesi gereken şeyleri birbirine bağlar.

**Tip 44: Decoupled Code Is Easier to Change**

İki farklı kod parçası aynı şeyi paylaştığı durumda her zaman coupling gerçekleşebilir.

Eğer ki ilişkisiz modüller arasında tuhaf bağımlılıklar görüyorsanız veya bir yerde yapılan çok ufak bir değişiklik başka bir yeri de etkiliyorsa burada kesinlikle coupling vardır. Bu da yazılımcının kodu değiştirmeye korkmasına sebep olabilir.

**Tip 45: Tell, Don’t Ask**

Bir nesnenin iç durumuna göre karar verip o nesneyi güncellememeliyiz. Bunu yapmak kapsülleme prensibini yok eder.

**Tip 46: Don’t Chain Method Calls**

Bir bilgiye erişirken, birden fazla "." kullanmamaya çalışın.

Tek nokta kuralının büyük bir istisnası var: Zincirlediğiniz şeylerin değişmesi pek olası değilse, kural geçerli değildir.

Global veriler, her metodun ekstra bir parametre kazanmasına sebep olur çünkü her metod bu global veriye erişebilir. Bu da metodlar arasında gizli bir bağlantı kurulmasına sebep olur. Bunun getirebileceği sorunlardan en bariz olanı, global veride yapılan değişiklik tüm kodu etkileyebilir. 

**Tip 47: Avoid Global Data**

Herhangi bir değiştirilebilir harici kaynak, global bir veridir. Yani database, API , datastore kullanıyorsak küreselleşme tuzağına düşebiliriz. Önemli olan, bu kaynakları her zaman kontrol ettiğimiz bir kodun arkasına sarmalamak.

**Tip 48: If It’s Important Enough to Be Global, Wrap It in an API**

## Topic 29: Juggling the Real Word

Bir olay, bilginin kullanılabilriliğini temsil eder. Bu olay kullanıcı tarafından dış etkiyle de gerçekleşebilir veya hesaplama sonucu iç etkiyle de gerçekleşebilir. Nasıl gerçekleşirse gerçekleşsin, bu olaylara yanıt veren uygulamalar geliştirirsek uygulamalar daha efektif çalışacaktır.

Bunun için 4 strateji bize yardımcı olabilir.

* 1. Finite State Machines
* 2. The Observer Pattern
* 3. Publish/Subscribe
* 4. Reactive Programming and Streams

Durum makinesi, olayların nasıl ele alınacağını sistemli bir şekilde belirler. Biri mevcut durum olmak üzere bir dizi durumu temsil eder. Her bir durum için de önemli olayları listeleriz, buradaki her bir olay yeni bir duruma sebep olur.

Gözlemci modelinde, gözlemlenebilir olarak adlandırılan bir olay kaynağı ve olaylarla ilgilenen gözlemcilerin bir müşteri listesi vardır. Gözlemci, bir fonksiyona referans ileterek kendisini gözlemlenebilir olarak kaydeder. When the event occurs, the observable iterates down its list of observers and calls the function that each passed it

But the observer pattern has a problem: because each observers has to register with the observable, it cause coupling. Also, in the typical implementation the callbacks are handled by the observable, synchronously, it can cause performance problem. This solves with Publish/Subscribe strategy.

Pubsub modelinde, yayıncılar ve aboneler vardır, bunlar her biri isimlerindirilmiş kanallar aracılığıyla birbirlerine bağlanır. Aboneler, bir veya daha fazla kanala ilgi gösterir, yayıncılar ise bu kanallara etkinlik yazar. Gözlemci modelinden farklı olarak, yayıncı ve abone arasındaki ilişki potansiyel olarak eşzamansız olarak kodumuzun dışında gerçekleşir. 

Olayların, koddaki reaksiyonları tetiklemek için de kullanılabileceği çok barizdir ancak bunları devreye sokmak her zaman kolay olmuyor. Bu durumda devreye akışlar giriyor. Akışlar, olayları bir veri koleksiyonu gibi ele almamızı sağlar. Eş zamansız olabilir ve bu da kodunuzun olay meydana geldiğinde yanıt verme fırsatı elde ettiği anlamına gelir. 
## Topic 30: Transforming Programming
**Tip 49: Programming Is About Code, But Programs Are About Data**

Dönüşüme başlamanın en kolay yolu, gereksinimleri belirlemektir, input ve output'ların ne olacağını ortaya koymaktır. Bundan sonra yapmamız gereken şey, input'tan output'a nasıl erişebiliriz bunu ortaya koymak olmalı.

**Tip 50: Don’t Hoard State; Pass It Around**
##Topic 31: Inheritance Tax

Miras'ı kullanmanın iki sebebi vardır. Birincisi base sınıftaki ortak özellikleri miras alacak çocuk sınıflara aktarmak, ikincisi ise base ve çocuk sınıf arasında ilişki kurmak. Ancak bu ikisi de beraberinde sorunlar getiriyor. Because inheritance is coupling.

Bazı insanlar kalıtımı yeni türler tanımlamanın bir yolu olarak görüyor. Ancak bir süreden sonra sınıflardaki en küçük farklılaşmayı sağlamak için yeni katmanlar eklemek gerekiyor. Yapılan değişiklikler birçok katmanı etkileyebileceğinden dolayı, uygulamayı daha kırılgan hale getiriyor.

**Tip 51: Don’t Pay Inheritance Tax**

Bir daha asla inheritance kullanmayacağınız 3 alternatif teknik; 

* Interfaces and protocols 
* Delegation
* Mixins and traits

Protocol ve arayüzleri bu kadar güçlü yapan şey, tip olarak tanımlayabilmemiz ve bu arayüzü uygulayan sınıfların bu tiple uyumlu olabilmesidir. Bir sınıf bir protocolü sağladığında, biz çok güvenli bir şekilde protocol içerisinde barınan fonksiyonu kullanabiliriz.

**Tip 52: Prefer Interfaces to Express Polymorphism**

Interface ve protocol sayesinde, inheritance kullanmadan polymorphism sağlamış oluyoruz.

**Tip 53: Delegate to Services: Has-A Trumps Is-A**

Eğer ki parent class 20 metoda sahipse ve miras alacak sınıf bunlardan sadece 2 tanesini istiyorsa, miras aldığında geriye kalan 18 fonksiyon da çağrılabilir durumda olacak. Alternatif olarak delegation kullanılabilir.

Inheritance'ın dezavantajlarından bahsetmiştik, temel fikrimiz inheritance kullanmadan sınıfları yeni işlevlerle genişletmek istiyoruz. Bunun için Mixins kullanarak, bu fonksyionların bir kümesini yazarız ve bu kümeye de bir isim veririz. Daha sonradan sınıf oluştururken, oluşturduğumuz mixins'leri ekleyebiliriz.

**Tip 54: Use Mixins to Share Functionality**

Bu gördüğümüz 3 yöntem; tür bilgisini paylaşmak, işlevsellik eklemek veya yöntemleri paylaşmak için alternatif olabilir. Duruma göre en iyisini belirlemeliyiz.
## Topic 32: Configuration
Uygulamanız; farklı müşteriler için veya farklı ortamlar'da çalıştığında, müşteriye ve ortama özgü olan spesifik bilgileri uygulama dışında saklayın.

**Tip 55:Parameterize Your App Using External Configuration**

Birçok uygulama, konfigürasyonları veritabanı tablolarında veya JSON-YAML şeklinde düz metin dosyası halinde saklanmaktadır. Hangi form olursa olsun, uygulama ilk açıldığında konfigürasyon bilgileri bir veri yapısı olarak okunur. Genelde bu veri yapısı kolay erişim için global olarak saklanır ancak bunun yerine kodumuzu konfigürasyon bilgilerinden API arkasına sarmak daha iyi bir yol olacaktır. 

* Birçok uygulama bu API'ı kullanarak konfigürasyonlara erişebilir.
* Global olarak konfigürasyon'lar değiştirilebilir.
* Konfigürasyon dosyasının devamlılığı geliştirilen bir UI ile sağlanabilir.
* Konfigürasyon verileri dinamik hale gelir.

Dinamik olması bizim için önemlidir, sadece tek bir parametre değiştiğinde uygulamayı tekrar başlatmamızı önler.
# Chapter 6: Concurrency
Eşzamanlılık, iki veya daha fazla kod parçasının aynı anda çalışıyormuş gibi çalışmasıdır. Paralellik, aynı anda çalıştıkları zamandır.

Eş zamanlılık sağlamak için thread,processes veya fibers gibi şeyler kullanarak kodun çalışırken farklı bölümlerinin yürütüldüğü bir ortam olmalıdır. Paralellik için iki işi aynı anda yapabilecek donanım gerekmektedir.
## Topic 33: Breaking Temporal Coupling
Bir sistem tasarlanırken genelde işler doğrusal olma eğilimindedir. A olayı gerçekleştikten sonra, B olayı gerçekleşecek şekilde bir çalışma mantığı ortaya koyarız. Ancak bu yaklaşım esnek değildir, eş zamanlılığa izin vermeli ve zaman bağımlılığını ortadan kaldırmalıyız.

Aynı anda neler olabileceği ve kesin bir sırayla neler olması gerektiğini modellemeli ve analiz etmeliyiz. Bunu yapmanın bir yolu, aktivite diyagramı kullanmaktır.

**Tip 56: Analyze Workflow to Improve Concurrency**

Aktivite diyagramları potansiyel eşzamanlılık alanlarını gösterir ancak bu alanın yeterli olup olmadığını söyleyemez, burada tasarım devreye girer. Eşzamanlılık tasarımı yaparken veritabanı sorgusu, harici bir servise bağlanma gibi zaman alan ancak bizim kodumuzda bulunmayan kısımları bulmayı hedefliyoruz.

Eşzamanlılık bir yazılım mekanizmasıyken, paralellik bir donanım sorunudur. Birden fazla işlemcimiz varsa, işi bunlar arasında birbirinden bağımsız parçalara bölüp her birini paralel olarak çalıştırıp ardından sonucu birleştirebiliriz.
## Topic 44: Shared State Is Incorrect State

In the case where we use the shared state, we can lead to erroneous results if we act at the same time without considering the other.

**Tip 57: Shared State Is Incorrect State**

Semafor, aynı anda yalnızca bir kişinin sahip olabileceği bir şeydir. İki kişi aynı anda aynı ortak kaynağı kullanmak istediğinde semafor kullanımı sayesinde sadece bir kişi bu istekte başarılı olabilecektir, diğeri ise beklemek zorunda kalacaktır. İlk kullanıcının işinin bittikten sonra güncellenmiş kaynağı kullanmaya devam edebilecektir.

Bu yaklaşımda da problemler vardır çünkü semafor kullanımı sadece tüm kullanıcılar bunu doğru şekilde kullanırsa çalışacaktır aksi halde yine kaos olacaktır.

**Tip 58: Random Failures Are Often Concurrency Issues**
## Topic 45: Actors and Processes
Aktörler, kendi yerel private state'i olan bağımsız bir sanal işlemcidir. Her aktörün bir posta kutusu vardır, buraya mesaj düştüğünde eğer ki aktör boşsa o mesajı işler ve yeni mesajı işlemeye geçer.

İşlem, eşzamanlılığı kolaylaştırmak için işletim sistemi tarafından uygulanan daha genel amaçlı bir sanal işlemcidir.

* Planlı şekilde yürütülmez, hiçbir şey kontrol altında değildir.
* Tek durum, mesajlarda ve aktörün local state'nde tutulur ve mesajlar alıcı tarafından okunmadıkça incelenemez, yerel duruma aktörün dışında erişilemez. 
* Tüm mesajlar tek yönlüdür, cevap yoktur.
* Bir aktör, aynı anda bir mesaj işleyecek şekilde tüm mesajları tamamlayana kadar işlemeye devam eder.

**Tip 59: Use Actors For Concurrency Without Shared State**

In the actor model, there’s no need to write any code to handle concurrency, as there is no shared state. 
## Topic 46: Blackboards
Yasal gereklilikleri kapsayan bir kural motoruyla birlikte bir kara tahta, burada bulunan zorluklara zarif bir çözümdür. Verilerin geliş sırası önemsizdir ve geri bildirim de kolayca işlenir.

**Tip 60: Use Blackboards to Coordinate Workflow**

# Chapter 7: While You Are Coding
## Topic 37: Listen to Your Lizard Brain

Yeni bir projeye başlamak sinir bozucu ve korkutucu bir deneyim olabilir, bunun altında yatan 2 problem vardır ve ikisinin de çözümü aynıdır.

* Kertenkele beynimizin, daha önceki deneyimlerimize dayanarak bize bir şeyler söylemeye çalışıyor olabilir bu da bizi isteksiz veya şüpheli hissettirebilir.
* Diğer sorun ise sadece hata yapmaktan korkuyor olabilir.

** Tip 61: Listen to Your Inner Lizard **

İlk olarak o an ne yapıyorsak onu bırakmalı ve kodu düşünmemek için klavyeden uzaklaşmalıyız, beynimizin kendini düzenlemesi için ona biraz zaman tanımalıyız. 

Eğer ki bu işe yaramazsa, beynimizin farklı bölümlerini çalıştırmak için sorunu başka birisine anlatmayı deneyebiliriz. Başka birisine anlatırken bir anda sorunun ne olduğunu kendimiz anlayabiliriz.

Eğer ki bunlar da sonuç vermiyorsa beynimize yapmaya çalıştığımız şeyin önemli olmadığını, hata yaptığımızda veya boşa gittiğinde sorun olmayacağını söyleriz. Bunu da prototip ile gerçekleştirebiliriz. Bu sayede gerginlik yerini aciliyet duygusuna bırakacak, kendimizi işi yapmak için motive hissedeceğiz. Tam bu anda,  "ben bunu yapabilirim" hissini yaşadığımızda, prototip kodlarını sileceğiz ve baştan asıl işimize başlayacağız.

## Topic 38: Programming by Coincidence
Geliştiriciler olarak, her gün yakalanabileceğimiz yüzlerce tuzağın olduğu bir mayın tarlasında çalışıyoruz bu yüzden dikkatli olmalı ve tesadüfen programlamadan kaçınmalıyız.

* Accidents of Implementation: Kodun o an ki yazım şeklinden kaynaklanan hatadır.

* Close Enough Isn’t: Yaklaşık sonuç yeterli değil, kesin sonuç gerekir.

* Phantom Patterns: Sadece belirli bir kalıbı göz önüne alıp bir sonraki adım için kod yazamayız. 

* Accidents of Context: Bulduğumuz cevabın uygun olması, bizim içeriğimiz için doğru olduğu anlamına gelmez.

* Implicit Assumptions: İnsanlar çalışırken birçok varsayımı gözönüne alırlar ancak köklü gerçeklere dayanmayan varsayımlar projenin baş belasıdır.

**Tip 62:Don’t Program by Coincidence**

Daha az hata yapan, hataları erken yakalayan bir geliştirici olmak istiyorsak kasıtlı olarak programlamalıyız:

* Always be aware of what you are doing.

* Make sure you have enough code to explain the code to someone at a junior level

* Don't code in dark. If you’re not sure why it works, you won’t know why it fails.

* Proceed from a plan

* Rely only on reliable things. Don’t depend on assumptions. 

* Document your assumptions. 

* Don’t just test your code, but test your assumptions as well.

* Prioritize your effort to make time for the important parts

*  Don’t let existing code dictate future code. 

## Topic 39: Algorithm Speed
Big-O is never going to give the actual numbers for time or space. It simply tells you how these values will change as the input changes.

You can estimate the order of many basic algorithms using common sense.

* Simple Loop: O(n) 

* Nested Loop: O(n^2)

* Binary chop: O(logn)

* Divide and Conquer: O(nlogn)

* Combinatoric: O(n^(k-1))

Kod yazarken, sayıların değer aralığının ne kadar büyüyebileceğini ve kodun çalışma süresini ne kadar etkileyeceğini hesaplayarak yazmalıyız. 

**Tip 62: Estimate the Order of Your Algorithms**

Eğer ki algoritmanın ne kadar süreceğini veya memory'de ne kadar yer kaplayacağını bilmiyorsak birçok farklı input ile algoritmayı çalıştırıp sonuçları çizdirebiliriz.

Küçük veri setlerinde efektif olarak çalışan algoritmamız büyük veri setlerinde aynı sonucu vermeyebilir.

**Tip 63: Test Your Estimates**

Burada da yine pragmatic programcı olarak düşünmemiz gereken şey, her zaman en hızlı algoritmanın en iyi olmayacağıdır. Küçük bir veri seti üzerinde çalışacaksak eğer hızdan ziyade kurulum maliyetinin süresinin kısa olması daha önemli olacaktır.
## Topic 40: Refactoring
Programın geliştirilmesi aşamasında, önceki yazılan kodlar ve verilen kararları tekrar düşünmek geliştirme sürecinin bir parçasıdır.

Refactoring is disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.

Refactoring tamamen baştan yazmak anlamına gelmez, küçük adımlar ile düşük riskli şekilde kodların temizlenmesi anlamına gelir.

Kodun davranışının değişmediğini garanti etmek için iyi ve otomatikleştirilmiş birim testine ihtiyacınız var.

Herhangi bir şey bize yanlış geldiğinde bunu değiştirmekten tereddüt etmemeliyiz. Bu yanlışlar aşağıdaki gibi olabilir.

* Duplication

* Nonorthogonal design

* Outdated knowledge

* Usage

* Performance

* The Tests Pass

Geliştirme sürecinde zaman baskısı olduğundan dolayı refactor'e zaman kalmıyor olabilir ancak düzenli olarak refactor yapmak gerekir. Yoksa proje büyüdükçe çok daha zor ve maliyetli olacaktır.

**Tip 65: Refactor Early, Refactor Often**

* Don't try to add new functionality with the same time refactoring.

* Make sure you have good test, run test as often as possible and check if your changes have broken anything.

* Take small steps and test after each steps.

## Topic 41: Test to Code
**Tip 66: Testing Is Not About Finding Bugs**

Thinking about writing a test for our method allows us to look from the outside as if we were the customer of the code, not the author. Perhaps one of the biggest benefits of test writing is that it provides feedback.

**Tip 67: A Test Is the First User of Your Code**

Ayrıca, diğer kodlarla bağlı olan fonksiyonu test etmek zordur çünkü tüm ortamı sağlamanız gerekir. Ancak test edilebilir şekilde yaparsak, bağlantıyı azaltmış oluruz.

* 1. Decide on a small piece of functionality you want to add.

* 2. Write a test that will pass when the functionality is implemented.

* 3. Run all tests. Just verify that the failure is the one you just wrote.

* 4. Write the smallest amount of code needed to pass the test, and verify that the tests now run cleanly.

* 5. Refactor your code:

**Tip 68: Build End-to-End, Not Top-Down or Bottom Up**

Birim testi aslında bir modülü çalıştıran bir kod parçasıdır. Modüldeki rutini çağırdıktan sonra dönen sonuçları bilinen değerler ile karşılaştırır ve beklendik şekilde çalışıyor mu bunu kontrol eder. Daha sonra parçaların tek tek çalıştığını bildiğimiz için tüm sistemi yine birim test olanakları ile test edebiliriz.

Birim testini sözleşmeye karşı test olarak düşünmeyi seviyoruz. Bu test bize 2 şey sunacaktır, kodun sözleşmeye uyup uymadığı ve sözleşmenin istediğimiz şeyi ifade edip etmediği. Bu tekniğin en büyük avantajı debugı kolaylaştırmasıdır, hangi modülde hata olduğunu direkt anlayabiliriz.

**Tip 69: Design to Test**

Test koduna, herhangi bir geliştirme ile aynı özeni gösterin. Keep it decoupled, clean, and robust.

**Tip 70: Test Your Software, or Your Users Will**


## Topic 42: Property-Based Testing
Bir varsayıma göre kod yazıyoruz ve yine bu varsayıma göre test yazıyoruz. Yazdığımız testin geçiyor olması, varsayımımızın doğru olduğu anlamına gelmez. Çünkü test sadece bizim varsayımımıza göre yapması gerekeni yapar.

** Tip 71: Use Property-Based Tests to Validate Your Assumptions**

Property-based testingde girdi üretmek için bazı kurallar belirliyoruz ve çıktıyı doğrulamak için de bazı iddalar oluşturuyoruz. Sonrasında ne olacağını bilemiyoruz.

Bir property-based test başarısız olduğunda, hangi değerler için başarısız olduğunu belirlemeli ve bu değerler ile unit-test yapmalıyız. Bu hatalı değeri kullanmaya zorlayarak yapacağımız birim test, hatanın gözden kaçmamasını sağlar.

Property-based testing is complementary to unit testing: they address different concerns, and each brings its own benefits

## Topic 43: Stay Safe Out There
Pragmatic Programmers have a healthy amount of paranoia about security to prevent any attack.

Saldırganın veri girebileceği, veri çıkarabileceği, veya bir hizmetin yürütülmesini başlatabileceği tüm erişim noktalarını kısıtlayın.

**Tip 72:Keep It Simple and Minimize Attack Surfaces**

* Code complexity makes attack surface larger. Less code means fewer bugs, fewer opportunities for a crippling security hole.

* Never trust data from an external entity

* Anyone can call for services that are unauthenticated, which can block any process. 

* Keep the number of authorized users at an absolute minimum. 

* Don’t give away information

* Information designed to make debugging easier can make breaking in easier as well. 

Yüksek seviyeli bir izni otomatik olarak ayarlamayın, yüksek seviye izne ihtiyaç duyulursa izin verin ancak iş bitince geri alın. Hassas kaynaklara sadece belirli izne sahip olan kişilerin erişmesine izin verin.

Uygulamadaki varsayılan ayarları en güvenilir şekilde ayarlayın.

Kişisel verileri nerede saklıyor olursanız olun asla plain text olarak saklamayın, encrypted olarak saklayın.

Bilgisayarın güvenlik yamasına ihtiyacı olduğunda bunu sonraya ertelememeliyiz. Çünkü aksi halde istismara açık hale gelebilir.

**Tip 73:Apply Security Patches Quickly**

## Topic 44: Naming Things
Naming is important because because they reveal a lot about your intent and belief.

Bir şeyleri isimlendirirken, her zaman ne demek istediğimizi düşünmeliyiz. Bu şekilde yaptığımız isimlendirmeler daha anlaşılır olacaktır.

Bunun yanında geliştirme yaptığımız ortamdaki kültür de önemlidir. Bir programlama dilinde kullanılan bazı genel isimlendirmeler başka programlama dilinde öyle kullanılmıyorsa bu da bir o kadar yanlış olacaktır.

Her projede, tutarlılık sağlamak için takımdakilerin kullandığı özel anlamı olan jargon kelimeler vardır. Tutarlılığı sağlayabilmek için takımdaki herkesin bunların anlamını bilmesi gerekir.

Kullanım amacını ifade etmeyen, yanıltıcı veya kafa karıştırıcı bir ad gördüğünüzde, onu düzeltin. Pragmatic programcı olarak, başkalarının yaptığı yanlışa katılmak yerine bunu düzeltmeliyiz. 

**Tip 74: Name Well; Rename When Needed**




