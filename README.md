**Q1:** What are the main features in spring boot?  
**Q2:** What is difference between bean and component?  
**Q3:** What are the starter types in java spring boot?  
**Q4:** What is inversion of control?  
**Q5:** What is difference between controller and rest controller?  
**Q6:** What is parent object file in spring boot?  
**Q7:** What is spring boot actuator?  
**Q8:** What are stereotype annotation in java spring boot?  
**Q9:** What are the annotation types in the spring boot?  
**Q10:** What is junit testing in spring boot?  
**Q11:** What is hibernate ORM?  
**Q12:** What is spring mvc?  
**Q13:** What is spring boot profiling?  
**Q14:** Is it possible to build non web application through
spring boot?
**Q15:** What is marker interface?  
```
It provides run time information about objects
and contain no methods and fields.
```
**Q16:** What is lambda expression?  
**Q17:** What is functional interface in spring boot?  
**Q18:** Can we declare a static keyword inside method in java?  
**Q19:** What is value annotation in spring boot?  
**Q20:** What is lombok?  
**Q21:** Can we write component annotation instead of service, restController and repository?  
**Q22:** What is dynamic insertion?  
**Q23:** What is lazy loading and eager loading?  
**Q24:** What is rest and soap?  
**Q25:** What is cascade delete?  
**Q26:** What is impedance mismatch?  
**Q27:** What is assert?
```
test your assumption about the program
```
**Q28:** what is graceful shutdown in spring boot?
**Q29:** How many spring boot have embedded servlet containers?  
```
there are 3: tomcat, jetty and undertow
```
**Q30:** What is meta annotation?  
**Q31:** What does spring web starter do?  
```
it adds tomcat and spring mvc
```
**Q32:** What is uber jar?  
```
contain java program as well as other dependencies
that it needs to be executed
 ```
**Q33:** What is custom classifier for executable jar?  
**Q34:** What is jruby?  
```
when we need use one project as a dependency into another
we will use this custom classifier with the repackage goal
```
**Q35:** What is aspect oriented programming in spring boot?  
**Q36:** What is neo 4g graph database?  
**Q37:** What if we do not use spring boot annotations in the main class?  
```
We will then use enable autoconfiguration and entity scan
```
**Q38:** What is difference between stringBuilder and StringBuffer?  
**Q39:** What is stream of data?  
**Q40:** What is list, arraylist and linkedList in java?   
**Q41:** What is heroku (paas = platform as a service)?
```
It provides developer to build and deploy their entire
application on the cloud and the another is cloud foundry
```
**Q42:** What is imperative and declarative approach in the programming?  
```
Imperative means defining the detail logic, declarative means just show
the basic concepts and we achieve through lambda expressions especially
```
**Q43:** what is finalize in java?  
**Q44:** What is predicate in java?  
**Q45:** Can we have a default and static methods in interface?  
**Q46:** What is functional interface in java?  
**Q47:** What is difference between default and static methods in interface?  
**Q48:** Abstract class and interface difference?  
```
Abstract class can have abstract methods and non-abstract as well but interface has only
abstract methods, means these are not defined just declared if we want
only some of the methods of the class in the implementing class, we
will make the class abstract and use the specific method of the
class.
```
**Q49:** What is difference between maven and gradle?  
```
gradle uses current cachefor project developing tools,
works on the current dependencies that
current project in the running state needs, while maven not
```
**Q50:** Why and how to use environmental variables in IDE?  
**Q51:** What is spring dispatcher servlet?  
**Q52:** What is difference between requestParam and
path variable in spring boot annotations?  
**Q53:** What is the default capacity of arraylist in java?  
**Q54:** What are static members?
```
Static members are the part of class where they can
access direclty via class name we dont need to instantiate the class.
Jvm executes the static block code before the loading of main class.
```
**Q55:** What are positional access operators?
```
get, set, add, remove
```
**Q56:** What is arraylist and list?  
```
List is an interface and arrayList is its implementation.
The List refers to a collection of various
elements in a sequence, in which every element is basically
an object. Also, we can access these elements by their
positions (index). On theother hand, an ArrayList creates
an array (dynamic) of the objects thatcan easily reduce
or increase in size as and when required.
```
**Q57:** What is difference between arraylist and linkedList?
```
Main difference between arraylist and linkedlist:
adding elements in the middle of an ArrayList is relatively
expensive because all the elements after the index where the
new element is added must be shifted over to make room.
Therefore, if you need to frequently add elements in the
middle of a list, LinkedList might be a better choice.
It will not move all the elements because these are
connected through nodes.
```
**Q58:** What is elk stack?  
**Q59:** What is OIDC and Oauth authentication protocol?  
**Q60:** What is transport layer security(TLS)?  
**Q61:** What is IS-A and HAS-A in java relations?  
```
--> IS-A relationship represents inheritance, where one class is a
    specialized version of another class.
--> HAS-A relationship represents composition or aggregation,
    where one class contains or is composed of another class.

 -- Aggregation is known asweak association between the two
    classes.
 -- Composition are more tightlycoupled means they have
    strong association.
```    

**Q62:** What is difference between hashmap and hashtable?   
**Q63:** What is micronaut framework?  
```
for implementing microservices with java, micronaut handles
dependency injection at compile time right when we are
writing the code where as spring boot handles
it during runtime.
```
**Q64:** What is jsr?  
```
it is a java specification request annotations like inject,
post construct etc, it is mostly used by micronaut framework.
Micronaut takes less time for run as well uses half
of the memory of the spring boot.
```
**Q65:** What is ldap and saml?  
```
ldap = lightweight directory protol
saml = security assertion markup language
both are used for spring boot security.
```
**Q66:** What is difference between static and final keyword in java?  
```
static method means it belongs to itself rather than
any instance of the class, means we can access static
method by just calling the method, likeclassName.methodName
where as final means impossible to inherit or override
we cannot override final and static methods.
We can use abstract keyword with class if we dont want
to make objects of it, and if one method is abstract
the whole class should be declared abstract, but we use
interfaces for this scenarios as now.
```
**Q67:** What is spring boot caching?  
**Q68:** Is CRUD repository a marker interface?  
```
NO.
Repository is a marker interface
jpaRepository-\>
pagingandsortingrepository-\>
crudrespository-\>
repository
```
**Q69:** What is difference between oop and functional programming?  
```
oop is imperative and functional programming is declerative
```
**Q70:** Why java is not pure object-oriented?  
**Q71:** What is difference between RequestParam and
PathVariable annotations in spring boot?  
**Q72:** What is serializable in java?  
```
Serializable interface in java is a
special interface to be implemented by data classes in java.
It is also called marker interface. When a class implements
this interface, it can be persisted in a database.
(means we can perform operations in the
database by using these types of collections like ArraysList,
LinkedLists etc.)
```
**Q73:** What is volatile, transient and synchronized keyword in java?  
**Q74:** What is java generics?  
**Q75:** What is order and unordered collection in java?  
**Q76:** Can ConcurrentHashMap and hashmap allow duplicate keys and duplicate values?  
**Q77:** what is set?
```
A Set is a generic set of values with no duplicate elements.
A TreeSet is a set where the elements are sorted.
A HashSet is a set where the elements are not sorted or ordered.
```
**Q78:** Can we have a duplicate values in list?  
**Q79:** What is websocket and polling?  
**Q80:** what is java writer?  


**Q81:** What's the purpose of a wrapper class?  
```
To use it in the generics becuase
generics dont allows primitive types
```
**Q82:** What is difference between primitive and wrapper objects in java?  
```
Wrapper is class used to convert primitive into object where
as primitive is predefined keywords and reserved keywords
```
**Q83:** What is autoboxing and unboxing in java?  
**Q84:** Why to use wrapper classes in java?   
```
To achieve java program be completed object oriented
```
**Q85:** Why java is not completely object-oriented?  
```
Because it uses some of the primitive data
types that are not object based
```
**Q86:** What is buffered reader in java?  
**Q87:** What is spring aop?  
**Q88:** What is afcon?  
**Q89:** What is hashing in java?  
```
Hashing in Java is a technique for mapping data
to a secret key, that can be used as a unique identifier
for data.
Hashmap is faster than Hashset because values are associated
with the unique key.
```
**Q90:** What is java stream api?  
```
Streams were introduced in java 8. Stream API
is used to process collections of objects. A stream is a
sequence of objects that supports various methods which
can be pipelined to produce the desired result.
It follows funtional programming style.
```
**Q91:** What is inversion of control meaning in spring?  
```
Inversion of Control is a principle which transfers the
control of objects or portions of a program to a container
or framework.
```
**Q92:** What is java "record" keyword?  
**Q93:** What is urn, url and uri?  
**Q94:** what is difference between put and post?  
```
Put is idempodent means that if we send a lot of same
requests, the only initial request cause a change
(multiple requests produce same result) In contrast,
calling a POST request repeatedly have side effects
of creating the same resource multiple times.
```
**Q95:** What are the codes for client side error and server error?  
```
100 means process, 200 ownwards means success,
400 ownwards means client error and 500 means server error
```
**Q96:** Why should we use String builder in loops instead of String?  
```
Strings are immutable objects, so concatenation doesn't
simply add the new String to the end of the existing string.
Instead, in each loop iteration, the first String is converted
to an intermediate object type, the second string is appended,
and then the intermediate object is converted back to a String.
Further, performance of these intermediate operations degrades
as the String gets longer. Therefore, the use of StringBuilder
is preferred.
```
**Q97:** What is raw type in java?
```
It is generic type like
List names = new Arraylist(),  
instead of parameterized type like:
List<String> names = new ArrayList<>()
```

**Q97:** What is base64 encoding?  
**Q98:** What is native image or spring native?  
```
A native image is a technology to build Java code to a
standalone executable.
```
**Q99:** What is difference between jdk, jre and jvm?  
```
jdk is the main library kit that provides all necessary files
and executable environment along with jre and jvm.
jvm tells the compiler to convert the source code(in text form)
into byte code(01 form). jre provides the environment where the
source code run and executed.
```
**Q100:** Why java is called better memory management language?  
```
Because it automatically performs the garbage collection, thus it is
memory efficient language
```
**Q101:** What is javac?
```
It is java compiler in that converts
source code(text form, .java file) into bytecode(.class file)
```
**Q102:** How to implement method of interface?  
```
It is must to implement the abstract methods of interface in the
implementing class whether abstract keyword is written or not,
but not necessary to implement default and static methods.
```
**Q103:** What are checked and unchecked exceptions?  
**Q104:** Can we have more than one public class in same file?  
```
No, only one class should be public that
matches the file name, other should be without public keyword
```
**Q105:** Is JDBC is part of java EE or java SE?  
**Q106:** What is difference between actual and formal parameters?  
**Q107:** What are literals?  
**Q108:** What is String constant pool(scp)?  
**Q109:** How garbage collector works?  
```
When String is not referring to the object, then the object is
automatically collected by GC. String is a reference type,
String name = "khan"; here name is not storing the value like
int = 5; etc., name is only referring or pointing towards "khan"
object not storing the value.
```
**Q110:** What is supplier interface in java?  
**Q111:** What is consumer interface in java?  
**Q112:** What is predicate?  
**Q113:** What are fail fast and fail safe iterator?  
**Q114:** What is the result of character concatenation in java?  
```
like 'j' + 'a' + 'v' +'a';
it will generate numeric output
```
**Q115:** What is difference between jdbc and jpa?  
**Q116:** What is factory design pattern in java?  
**Q117:** What is metaspace in java?  
```
Metaspace is a new memory space -- starting
from the Java 8 version; it has replaced the older PermGen memory
space. The most significant difference is how it handles memory
allocation. Specifically, this native memory region grows
automatically by default.
```
**Q118:** What is try with resources in java?  
**Q119:** What is idempotent in api?  
**Q120:** Can we override a method multiple times in java?  
```
No, only subclass can implement the parents class method
``` 
**Q121:** What are the rules for method overloading?  
* Must:  
  * The method names must be the same.
  * The parameter types must be different.
* May differ:  
  * The return types can be the same or different.
  * The access modifiers can be the same or different.
  * The exceptions can be the same or different.

**Q122:** What is difference between == and .equals()?  
**Q123:** Is java pass by value or pass by reference?  
```
In summary, Java uses "pass by value" for primitive
types and "pass by value of the reference" for objects.
but overall java is strictly pass by value.
``` 
**Q124:** What is difference between stack and heap memory?  
**Q125:** Is String builder, String buffer and String all are immutable?  
**Q126:** What is serialization and deserialization in java?  
```
Serialization is a mechanism of converting the state of an object
into a byte stream. Deserialization is the reverse process where
the byte stream is used to recreate the actual Java object in
memory. This mechanism is used to persist the object. The byte
stream created is platform independent.
```
**Q127:** What is byte stream in java?  
```
Byte streams are used to perform input and output of 8-bit bytes.
```
**Q128:** What is difference between static and transient in java?  
**Q129:** What is static block in java?  
```
In Java, a static block executes code before the object
initialization, and it runs without creating instance of that
class, it runs when the class loads into the memory. The static
blocks always execute first before the main() method in Java
because the compiler stores them in memory at the time of class
loading and before the object creation.
```

Can we define a method in main class method? What is difference between
substring and subsequence? What is the use of transactional annotation
in spring boot? the @Transactional annotation ensures that the for
example updateUserDetails method runs within a transaction. If an
exception is thrown during the execution of this method, the transaction
will be rolled back, and any changes made to the database will be
undone. Should we use transaction annotation on a private method? What
is propagation in transactional?

What is the git command that is used to rollback and dicard changes to
specific commit? it is git reset --hard \[commit-hash\]

What is super keyword meaning in the constructor? extending class
constructor contains super invokes the parent class constructor and if
it is not extending then it is calling object class that is the parent
of all java classes

Very important feature Passing interface as a parameter in method call
in java is lead to polymorphism What is workload automation? What is
spring batch? How to create infinite loops in java? (for, while, do)

What is association? An Association can be defined as a relationship
that has no ownership over another. For example, a person can be
associated with multiple banks, and a bank can be related to various
people, but no one can own the other. What is aggregation? The term
aggregation refers to the relationship between two classes best
described as a "whole/part" and "has-a" relationship. It contains the
reference to another class and is said to have ownership of that class.

What is classloader? When java program runs it is first loaded by
classloader in jvm Can a thread restart after dead state? no a thread
cannot be restarted after dead state Java virtul machine is a platform
and a specification provides runtime environment for java code to be
executed independent of an operating system(means it is platform
independent) and jre is an implementation fo that specification. jre
provides class tools and libraries and contain standalone jvm. jre
provides run time environment for code to be executed. Where a class
code converted into bytecode and runs. jre includes toolkits, libraries
etc. java development kit includes jre and code libraries and compilers
JDK │ ├── JRE │ ├── JVM │ └── Core Java Libraries │ └── Java Compiler &
Development Tools

What are the types of garbage collectors in jvm? Serial garbage
collector, Parallel garbage collector, Concurrent Mark and Sweep Garbage
collector, G1 garbage collector, Z garbage collector. What are the
important concepts in jvm? In addition to garbage collectors, the Java
Virtual Machine (JVM) encompasses several important concepts and
components that play a crucial role in the execution of Java programs.
Here are some of the key concepts: Classloader: Responsible for loading
classes into memory. The JVM uses different classloaders (e.g.,
Bootstrap, Extension, Application) to load classes from different
sources (e.g., system libraries, classpath directories). Just-In-Time
(JIT) Compiler: Transforms Java bytecode into native machine code for
improved execution performance. It dynamically compiles parts of your
program that are frequently executed. Java Heap: The runtime data area
where objects are allocated. It's divided into the Young Generation, Old
Generation, and Metaspace (or PermGen in older versions of Java). Java
Stack: Stores method-specific data like local variables and method call
information. Each thread has its own stack. Native Interface (JNI):
Allows Java code to call native methods written in other languages
(e.g., C or C++). Java Native Interface (JNI): Enables Java applications
to interact with native libraries and code written in other programming
languages. Thread Management: The JVM is responsible for managing
threads, allowing for concurrent execution of Java programs. Execution
Engine: Executes compiled Java bytecode. It includes the Interpreter
(which directly executes bytecode) and the JIT Compiler (which compiles
bytecode into native code for improved performance). Method Area (or
PermGen or Metaspace): Stores metadata about classes and methods. It
also stores static fields and constants. Runtime Data Areas: These
include the Method Area, Java Heap, Java Stack, and Native Method Stack.
They represent the memory spaces where data and code are stored during
program execution. Java Virtual Machine Tool Interface (JVMTI): Provides
a way for tools to monitor and instrument running Java applications.
It's used for profiling, debugging, and monitoring. Security Manager:
Controls access to system resources by untrusted code. It's used for
security and sandboxing. Memory Management: The JVM handles memory
allocation and garbage collection to manage the lifecycle of objects.
Exception Handling: Java's exception handling mechanism is an integral
part of the JVM. It allows programs to gracefully handle errors and
exceptional conditions. Profiler: A tool used for monitoring the
performance of a Java application. It can provide insights into CPU
usage, memory allocation, and other metrics.

What is performance tuning in jvm? what are Bootstrap class loader
Extensions class loader System class loader in jvm? our code that is
written in english like syntax is loaded by system class loader Boot
class loader is main parent of the class loading hirarichy What is race
condition in threads? What is deadlock, livelock, starvation, thread
interference, priority inversion and atomicity violations in threads?
What is concurrent and synchronized?

What are the important concepts of design patterns? Singelton: only one
instance will be created Factory: Factory Pattern is focused on object
creation, providing a flexible way to create objects without specifying
their concrete classes. for example shape is interface Shape shape = new
square(); Shape shape = new circle(); etc Adapter: like two chargers,
one is compitable and other is not so a basic interface and two classes
one is compitable other is not so not compitable class calls the method
of compitable class Strategy: it is used most for algorithms one
interface and different classes that implements and have their own
methods for example sorting

File not found checked exceptions subclasses are: FileNotFoundException
IOException EOFException SocketException SQLException

What is dependency injection using constructor in java? What are three
primary dependency injection types in java? 1 constructor injection(when
needed for the whole class) 2 setter injection(when needed for partial
dependency in the classes) 3 method injection(when needed in the method
scope only) pom dependency is relatively different because it provides
the external libraries that are needed to use in our project Why should
we use setter methods or constructors?

Important steps that are required in microsevices: Load balancers
Service registry failed fast api gateway

What is difference between spring jpa and spring data jpa? We use rest
controller that is composed of (controller and response body) for
response in json or xml and if we simply use controller annotation with
no response body it will send response in string that is resolved by
view resolver What are the main important features in java 17? 1 Records
2 Stream.toList() 3 new switch expressions 4 text blocks for long
strings and remove "+" on every line break.

What are the sealed classes and interfaces in java? What is "permit"
keyword in java? What is view resolver in spring mvc? Eureka server
provided by netflix to discover each other services in an ecosystem
either by hardcoding service urls or by using third party tools or
service discovery mechanism like DNS What is diff between instance
variables and class variables? What is rest assured? What is meant by
coding/programming to the interface? What is method chaining? What is
time complexity and space complexity?

How to pick a commit from one branch and add it to another? Through
cherry-pick Which spring boot annotation is used to handle global
exceptions? Controller advice When to use constructor initialization and
when to getter and setter methods? Can we keep the methods inside
interface private and protected? Serialization when exchanging data from
java object to swagger/api: when a response is sent to the
Swagger/OpenAPI endpoint, it typically involves the serialization of
Java objects. Typically through java pojo or DTOs The process of
converting Java objects to JSON or XML is known as serialization.

What is field and constructor injection? this is field injection and do
not need final modifier, we can keep them with private to follow the
encapsulation principles: @Autowired private UserService userService;
and this is constructor injection: private final UserService
userService; and then define the constructor for that

How to stash the untracked files also (new files that are added)?
through command: git stash -u What is fluent interface in java? If we
cannot make object of interface then how we can autowired the repository
interface? When you use @Autowired with a repository interface in
Spring, you're not directly creating an instance of the interface
itself. Instead, Spring creates a proxy object that implements the
repository interface for you. This proxy object delegates method calls
to the actual implementation provided by Spring Data JPA.

Can we make top level class in java static? In Java, you cannot declare
a top-level class as static. The static keyword is only allowed for
nested classes, interfaces, methods, and variables, but not for
top-level classes. Can we make instance of java static class?

Command to get visual representation and graph of git commits and
changes: gitk Can we pass method as a parameter in java method? Yes
through functional interface, example =
processMethod(ReadLines::printHello);

Define stack, queue, list, set, maps, graph and tree? What is difference
between alter and update in sql? what is clone method in java? What is
comparator and comparable in java? The linkedList that is built in java
that is implementing list interface is singly or doubly? What is a
method that we use to clear the screen? System.out.flush();

Which method is used to start a thread? for establishing a thread we use
start() and for execution we use run() How to connect two or more data
bases in one spring boot application?

What is big O of n (O(n)), big O of n square (O(n\^2)) , (O(1)) and
O(log n)? Explain the difference between linear search and binary search
in terms of time complexity? What is the maximum capacity of arraylist
in java? What is OUTPUT, DELETED, INSERTED in sql? Can we define a class
inside java method? If we have parent and 4 multilevel child classes, we
make the object of lowest child class, whose constructor will execute
first? What is compile time polymorphism and run time polymorphism? What
is early binding and late binding? What is composite key in database?
What is the query to set foriegn key into the table? What is parent
class of all exceptions? Define bi arguments variants of functional
interfaces. How to change git branch name? What is clustered and non
clustered in indexing in database?

What are the important features and uses of kubernetes in microservices?
1 Container Orchestration 2 Service Discovery and Load Balancing 3
Automated Rollouts and Rollbacks 4 Self-Healing 5 Resource Management 6
Configuration and Secret Management 7 Networking and Security 8 Logging
and Monitoring 9 Environment Consistency Summary: Kubernetes enhances
the deployment, scaling, management, and operational efficiency of
microservices by providing a comprehensive container orchestration
platform. It automates many tasks associated with microservice
management, improves resource utilization, ensures high availability,
and supports continuous delivery practices, making it an essential tool
for modern microservice architectures.

what is the role of docker in microservices? 1 Containerization 2
Portability 3 Dependency Management 4 Microservice Scalability 5
Development and Testing

What is feignclient in microservices? what is the query to select
coulumn names where the column contains letter a and b? What is java API
throttling? What is snake case, pascal case, kebab case and camel case
in naming conventions? What are projections in spring boot? What is
elastic search? What is meant by caching the value? What is orchestrator
approach in SRP? What is flatMap in java streams?

What is Supplier, Accumulator, Combiner and Consumer in java? These are
functional interfaces we use in streams that performs: Supplier:
Supplies initial objects (e.g., new ArrayList\<\>()). Accumulator: Adds
elements into a mutable result container. Combiner: Combines two partial
results (used in parallel streams). Consumer: Processes elements without
returning a value.

Techniques to make less paramters in method call: 1. Encapsulation with
Objects 2. Using Builder Pattern 3. Method Overloading 4. Use of
Optional and Default Values 5. Dependency Injection 6. Functional
Interfaces and Lambdas 7. Separation of Concerns

New features introduced in java 17: sealed classes record classes
pattern matching for instance of text blocks enhanced switch expression

New features introduced in java 21: virtual threads more advanced
pattern matching for switch conditions more advanced record patterns
string templates

What is parameter pollution?

Basic git workflow: git switch feature \# Switch to the feature
(working) branch from main branch git stash \# Stash any uncommitted
changes (after doing changes) git pull --rebase origin main \# Pull and
rebase with the latest main git stash pop \# Restore the stashed changes
git add . \# Stage all changes git commit -m "Message" \# Commit the
changes git push origin feature \# Push the branch to remote And then
create a Merge/Pull request to merge working branch to main branch

Spring boot microservices security architecture: 🔍 The Role of
AuthenticationWebFilter and ServerAuthenticationConverter 🧱 What Spring
Security Does (Traditional Flow) When you use SecurityWebFilterChain in
WebFlux: Incoming HTTP requests go through a chain of filters. One of
these filters must: Extract the credentials (e.g., the JWT token). Wrap
them in an Authentication object. Pass them to a
ReactiveAuthenticationManager to authenticate. But by default, this
filter doesn't exist unless you explicitly add it. That's where the
AuthenticationWebFilter comes in.

🚫 What Happens Without It If you only set:
.authenticationManager(jwtReactiveAuthenticationManager) ...but don't
wire up the AuthenticationWebFilter, then: ✅ You have a way to validate
a token. ❌ But there is no filter to intercept the request, extract the
token, and actually call the authentication manager. The token stays
hidden in the HTTP header. Nobody picks it up. So Spring thinks the
request is anonymous, and authorization fails.

🔥 Result: You always get Access Denied --- even with a valid token.

✅ What AuthenticationWebFilter and
ServerBearerTokenAuthenticationConverter Do Here's what they accomplish:
🔄 AuthenticationWebFilter Sits in the security filter chain. Calls the
ServerAuthenticationConverter to extract credentials. Passes them to the
ReactiveAuthenticationManager. 🔍
ServerBearerTokenAuthenticationConverter Extracts Authorization: Bearer
`<token>`{=html} header. Converts it into a
BearerTokenAuthenticationToken or UsernamePasswordAuthenticationToken.
Allows the authentication manager to validate and authenticate the
token.

Together, they bridge the gap between incoming HTTP requests and your
custom authentication logic. Imagine you built a perfect lock
(ReactiveAuthenticationManager) for your house, but you never connected
the doorknob (AuthenticationWebFilter) to the lock. People try to open
the door with the right key (the token), but the lock is never even
touched. So they stay locked out.

What is difference between spring mvc and spring webflux? What is
reactive programming? What is mono and flux in reactive programming?

Every new important changes in every java LTS version: LTS Version Focus
Areas Java 8 Lambdas, Streams, Time Java 11 Modularization, HTTP, var
Java 17 Sealed, Records, Pattern Matching, Text Blocks Java 21 Virtual
Threads, Pattern Matching (switch), Structured Concurrency

What are the principles of reactive programming? Publisher: A Publisher
is an entity that produces a stream of data. In a reactive system, this
could be a service generating events or data over time. Subscriber: A
Subscriber consumes data emitted by a Publisher. It reacts to data as it
arrives, without blocking or waiting for it all to be available at once.
Subscription: This represents the link between a Publisher and a
Subscriber. It is how the Subscriber subscribes to the Publisher and
starts receiving data. Processor: A Processor acts as both a Publisher
and a Subscriber. It allows for data to be transformed as it flows
through the stream. Backpressure: Reactive systems handle backpressure,
which ensures that the system does not get overwhelmed by an excessive
amount of data.

Important Regex Concepts and Patterns to Learn: 1. Basic Matching: .
(Dot): Matches any character except newlines. Example: a.b matches acb,
axb, a b, etc.

\^ and \$: Anchors that match the start \^ and end \$ of a string.
Example: \^abc matches "abc" only at the start of a string.

2.  Character Classes: \[a-z\]: Matches any lowercase letter.

`\d:`{=tex} Matches any digit (same as [0-9](Matches%20any%20digit.)).

`\w`{=tex}: Matches any word character (letters, digits, or
underscores).

`\s`{=tex}: Matches any whitespace character (spaces, tabs, etc.).

3.  Quantifiers: \*: Matches 0 or more occurrences of the previous
    character.

+: Matches 1 or more occurrences of the previous character.

?: Matches 0 or 1 occurrence of the previous character.

{n,m}: Matches between n and m occurrences of the previous character.
Example: `\d{2,4}`{=tex} matches between 2 to 4 digits.

4.  Grouping and Alternation: (): Groups patterns together. Example:
    (abc\|def) matches either "abc" or "def".

\|: Alternation (OR). Example: a\|b matches either "a" or "b".

5.  Assertions: Positive Lookahead (?=...): Matches a group only if it
    is followed by another group. Example: `\d(`{=tex}?=`\D`{=tex})
    matches a digit only if it's followed by a non-digit.

Negative Lookahead (?!...): Matches a group only if it is NOT followed
by another group. Lookbehind (?\<=...): Matches a group only if it's
preceded by another group. Negative Lookbehind (?\<!...): Matches a
group only if it's NOT preceded by another group.

6.  Escape Characters: Use  to escape special characters like ., \*, +,
    etc. Example: . matches a literal dot (.), not any character.

What are private methods in java interfaces and when were they
introduced?

Example illustration of Static method and instance variables of a class:
Static method: Think of a teacher standing in front of the class giving
a lecture. The teacher is not associated with any specific student but
is there for the class as a whole. Instance variable: A student's grade
or name is an instance variable because it's unique to that student.
Static Variable: Think of a classroom's total attendance count, which is
shared by all students in the class, and it's the same for every
student. The total attendance count is not unique to any individual
student, but it's relevant to the entire class. A teacher (static
method) cannot directly access the grades of students (instance
variables) without asking each student individually (i.e., referencing
each student's instance).

Can a class has default methods? What is completeable future in java?
What is callable and runnable? What is executor services in java? What
is life cycle of threads? NEW → RUNNABLE → RUNNING → (BLOCKED / WAITING
/ TIMED_WAITING) → TERMINATED What is keyClock in java?

Rules for catching blocks in try catch statement: Catch blocks are
checked top to bottom, and Java uses the first matching catch block. So
if you put the general catch (Exception e) before a more specific one
(like catch (IOException e)), the specific one will be unreachable ---
and the compiler will throw an error.

🔷 Key Techniques & Design Patterns in Java (especially Java 8+) 🔸 1.
Factory Pattern (Creational) Purpose: Object creation is abstracted.
Where used: DriverManager.getConnection() Executors.newFixedThreadPool()
Calendar.getInstance()

🔸 2. Builder Pattern Purpose: Create complex objects with a
step-by-step approach. Where used: StringBuilder Stream.Builder
HttpRequest.newBuilder() (Java 11+)

🔸 3. Singleton Pattern Purpose: Ensure only one instance of a class
exists. Where used: Runtime.getRuntime() Logger.getLogger()
Desktop.getDesktop()

🔸 4. Strategy Pattern Purpose: Select an algorithm at runtime. Where
used: Comparator and Collections.sort(list, comparator) Lambdas in
Stream.sorted(Comparator) --- Java 8 onward Custom ThreadFactory for
ExecutorService

🔸 5. Decorator Pattern Purpose: Add behavior dynamically without
modifying the object. Where used: InputStream, OutputStream (e.g.,
BufferedInputStream, DataInputStream) Collections.unmodifiableList(),
synchronizedList() (adds behavior like immutability or thread-safety)

🔸 6. Observer Pattern Purpose: One-to-many dependency --- observers get
notified of state changes. Where used: java.util.Observer (now
deprecated, but still illustrative) PropertyChangeListener in JavaBeans
GUI event listeners (Swing/AWT)

🔸 7. Command Pattern Purpose: Encapsulate a request as an object. Where
used: Runnable (Runnable is a command object --- you pass it and execute
later) Executors / Thread Pools GUI event handling

🔸 8. Adapter Pattern Purpose: Allow incompatible interfaces to work
together. Where used: Arrays.asList() (adapts array to List)
InputStreamReader (adapts InputStream to Reader)

🔸 9. Template Method Pattern Purpose: Define the program skeleton but
allow subclasses to fill steps. Where used: AbstractList, AbstractMap,
AbstractSet HttpServlet.doGet() and doPost() (Java EE)

🔸 10. Proxy Pattern Purpose: Control access to another object. Where
used: java.lang.reflect.Proxy (dynamic proxies --- common in Spring,
AOP) RMI (Remote Method Invocation) JDBC connection pools (wrap/monitor
actual connections)

Streams API (Java 8) Java 8 Streams --- how they work + intermediate vs
terminal? The Streams API (a major Java 8 feature) applies several
patterns: Builder Pattern -- via Stream.Builder Pipeline Pattern --
stream.filter().map().collect() Strategy Pattern -- via custom
Comparator, Predicate, etc. Iterator Pattern -- internally abstracts
traversal

Java SE and Java EE: If Java SE is your toolbox, Java EE is your
workshop for building large-scale systems. Java SE includes: 1. Basic
language features: String, Collections, Exceptions 2. I/O: File,
InputStream, Reader, etc. 3. Concurrency: Thread, ExecutorService,
synchronized, etc. 4. Networking: Socket, URL, etc. 5. JDBC: Connect to
databases 6. JavaFX or AWT/Swing (for GUI) 7. Java 8+ features: Streams,
Lambdas, Optional, etc.

Java EE includes: 1. Servlets (Web APIs) 2. JSP (JavaServer Pages) and
JSF (JavaServer Faces) 3. EJB (Enterprise JavaBeans) (older component
model) 4. JPA (Java Persistence API) -- ORM (like Hibernate) 5. JMS
(Java Messaging Service) -- messaging between apps 6. JAX-RS / JAX-WS --
REST and SOAP web services 7. CDI (Contexts and Dependency Injection) 8.
Bean Validation, Security, and more

Example of encapsulation in java OOP design: Think of a Real-World
Analogy: Imagine a vending machine: You can't open it and take snacks
directly (like accessing public fields). Instead, you press buttons and
insert money (like calling methods). The machine controls what happens
--- it checks if you paid, if the item is available, etc. That's
encapsulation in action. You're interacting with a system, but you don't
get to break or misuse it just because you can see it. so that means
Encapsulation is not about restricting access completely --- it's about
controlling behavior when access happens.

Concept of class loader in JVM: Think of the .java → .class compilation
as baking a cake (you prepare the file ahead of time). This is done
through java compiler (javac) The ClassLoader just takes the finished
cake (the .class file) and serves it to the JVM --- it does not do any
baking (compilation). So it loads the .class files into JVM

In Java, Method Overloading depends solely on: 1. Same method name 2.
Different parameter list, which includes: Number of parameters Types of
parameters Order of parameters (if types differ) Overloading Does Not
Depend On but may have different: Return type Access modifier Exceptions
thrown Parameter names

What is covariant return in method overriding? What is difference
between generic type and unknown type in java generics? What is server
thread pool?

Example: Two Apps with the Same Logic App A: Spring MVC (blocking) App
B: WebFlux (non-blocking) Both call a slow API or DB that takes 300ms
Both return JSON response after the call Both will take \~300ms to
return the response ❗ WebFlux won't make that faster --- but it will
let more users be served during that time through server thread pool
system in a server. By default, Spring WebFlux uses Netty as its
embedded server.

What is servlet? A Servlet is a Java object that handles HTTP requests
and generates responses. It's part of the Java Servlet API --- a core
part of Java EE (now Jakarta EE). In spring mvc, the servlet container
is tomcat So Spring MVC is Servlet-based and Spring WebFlux is Reactive

Runnable thread: Method: void run() Usage: with Thread or
ExecutorService Limitations: Cannot return a result or throw a checked
exceptions

Callable thread: Method: v call() throws execption Usage:
ExecutorService.submit() with returns future Can return a result and
throw checked exceptions

Future: Methods: get() : blocks until result is available Usage:
Returned by submitting a Callable to an ExecutorService

CompleteableFuture: Can be manually completed Supports chaining like
thenApply(), thenAccept(), thenCompose()

Type Returns Result Can Throw Exception Asynchronous Cancelable
Introduced In Type Runnable No No Yes No Java 1.0 Interface
Callable`<V>`{=html} Yes Yes Yes Yes (via Future) Java 5 Interface
Future`<V>`{=html} Yes (via get) No (itself doesn't throw) Yes Yes Java
5 Interface CompletableFuture`<V>`{=html} Yes Yes Yes Yes Java 8 Class
