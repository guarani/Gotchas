
#GOTCHAS

### ACID (Atomicity, Consistencym Isolation, Durability)

ACID is a set of properties that guarantee database transactions are processed reliably.



### ARC

Automatic Reference Counting (ARC) is a garbage collector for Swift and Objective-C where `retain` and `release` messages are added automatically at compile time so that the programmer does not need to do this manually.

 
### Bitcode

Bitcode is an intermediate representation of a compiled program in iOS, tvOS, and watchOS.
The app store and operating system optimize the installation of apps by only downloading the necessary parts of the app for the user's particular device.

### Clang

Clang is a compiler "front-end" for many languages of the C family. 

### Database Migrations

Database migration is the process of transferring data between storage types (i.e. changing database schema) in a consistent and easy way.

### DRY (Don't Repeat Yourself Principal) 



### Duck Type

Duck typing refers to a runtime type checking system where if a type has the required method or property for a particular type, the operation is allowed. The checking is done using dynamic typing or reflection.

### Factory

A software **_factory_** refers to the way software can be produced using a set of related software assets.

### First-Class Functions

A programming languages is said to have **_first-class functions_** if it allows functions to be treated as any other type. This means that functions can be passed as arguments to other functions, returned from functions, stored in variables or data structures.

### git rebase

Git's main job is to make sure you never lose a commited change. Sometimes however, you want to remove commits, and this is what rebasing if for. Rebasing is the process of moving a branch to a new base commit.
e.g. Let's say that while working on your own branch, the remote repo master branch has new changes. Since you want to always keep your branch up-to-date, you can switch to your local master branch, pull in the new changes, switch back to your own branch, and run git rebase master to add the new changes to your branch. 

### git stash show

List your stashed changes.

### HTTP Verbs

1. **GET** - Fetch a resource.
2. **POST** - Replace a resource.
3. **HEAD** - Get information about a resource without getting the resource itself.
4. **PUT** - Requests that the enclosed resource be saved at the supplied URI.
5. **DELETE** - Delete the specified resource.
6. **TRACE** - Echoes the request back to the client.
7. **OPTIONS** - Returns the HTTP methods the server supports for the given URI.
8. **CONNECT** - Opens a TCP/IP tunnel.
9. **PATCH** - Applies partial modifications to a resource.

Q: **PUT** vs. **PATCH**?  
A: **PUT** is used to save a resource to a specific location while **PATCH** is used to modify an existing resource.

### LLVM

LLVM is a collection of modular and reusable language-agnostic compiler and toolchain technologies.

### ORM (Object-Relational Mapping)

ORM is the process of converting data between two incompatible types (e.g. from objects to scalar values in a database).


### Singleton

A **_singleton_** is a software pattern that restricts the instantiation of a class to a single object.


### SOAP

The **SOAP** (Simple Object Access Protocol) is a well-defined messaging framework based on XML. All operations are explicitly defined, as well as the XML structure of the operation's request and response.

### Object vs. Class 

An object is an instance of a reference type (i.e. a class or array), while a value is an instance of a primitive type (i.e. int or double).

### OS X Server

**_OS X Server_** was formerly a separate, unix based, server operating system, but is now an OS X app run just like any other app on OS X.

### Polymorphism

**_Polymorphism_** refers to the ability of code (e.g. methods or classes) to work with values of multiple types, or the ability of different instances of the same data structure to contain elements of different types. Polymorphism allows for code re-use; programmers only need to implement a data structure such as a list or a dictionary once, rather than once for each type of element they wish to use it for.

### Push Notifications

Push notifications allow your application to notify a user of new messages or events even when the user is not actively using the application.

**Apple Push Notification Service** allows apps to notify their users through badges, sounds, newsstand updates, or custom text alerts.

**Google Cloud Messaging** allows apps to send messages between servers and client apps.

### Referential Integrity

Referential integrity is the requirement in relational databases for all values of one column of a table to represent primary keys of another column of another table (or the same table).

### Reflection

Reflection is the ability to determine an object's type at runtime without knowing this information at compile time.

### Stack vs. Heap

The stack is the memory set aside by the operating system for an application for local variables, while the heap is the memory set aside by the OS for any other objects.

### SOLID (Object-Orientated Design Principals)

| Letter | Principal             |
| ------ | :---------------------|
| S      | Singe Responsibility  |
| O      | Open/Closed           |
| L      | Liskov Substitution   |
| I      | Interface Segregation |
| D      | Dependency Inversion  |

### Type Coercion

**_Type coercion_** (a.k.a casting) refers to differnt ways of, implicitly or explicitly, changing and entity of one data type to another. In object-orientated programming, type conversion allows programs to treat objects of one type as one of their ancestor types to simplify dealing with them.

### Type Systems

The main purpose of types are to reduce the possibilities for bugs in programs. This is done by defining interfaces between different parts of a program, and then checking that the parts have been connected in a consistent way.  
This checking can happen statically (at compile time) or dynamically (at run time), or in a combination of the two. Other advantages are compiler optimizations, multiple dispatch, documentation, etc.  
A type system associates a type with each computed value and, by examining the flow of these values, attempts to ensure or prove that no type errors can occur.

Languages that make it easy to use a value of one type as if it were another type are often referred to as **_weakly-typed_**.
Languages that throw a compile time error when a value of a type different to the expected type is used are often referred to as **_statically-typed_**.

### Type Inference

**_Type inference_** is the ability of the compile to deduct a type from context at compile time.

### Kernel Space vs. User Space

The kernel (i.e. operating system) runs in kernel space while user programs run in user space. This is a form of sandboxing, the kernel has access to all memory but user programs get a piece of memory assigned to them.

### Kernel Call

A computer program requests a service from the kernel via a **_kernel call_**.


### Higher-Order Functions

A **_higher-order function_** is a function that takes one or more functions as arguments and returns a function as its result. All other types of functions are first-order functions.

