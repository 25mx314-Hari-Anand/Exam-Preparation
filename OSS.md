# Unit 1

## Open Source Software
1. Free to Use
2. Publicly Available
3. Viewed
4. Modified by Anyone
5. Shared

### Why ?
1. No Cost
2. Community Driven
3. Flexibility
4. Promote collabration
5. Transparency

### Philosophy
1. Transparent
2. Collabrative
3. Community Driven
4. Flexibility

## Licensing
- Licensing is legal permission granted by an authority to use a product, service or intelectual property
- Licensing helps to protect the rights of the developers and organization

### Types of Licensing in Open Source Software

Licensing in open-source software defines the rules and permissions for using, modifying, and distributing software. Open-source licenses ensure that software remains legally accessible and usable by the public.

#### Main Types of Open Source Licenses

1. Permissive Licenses

Permissive licenses allow users to freely use, modify, and distribute the software with very few restrictions. These licenses are simple and flexible.
- Features
  * Allows commercial use
  * Allows modification and redistribution
  * Modified versions can be closed source
- Examples
  * MIT License
  * Apache License 2.0
  * BSD License

2. Copyleft Licenses

Copyleft licenses require that modified versions of the software must also remain open source and use the same license.

- Features
  * Source code must remain open
  * Modified versions must use the same license
  * Encourages software freedom

- Examples
  * GNU General Public License (GPL)
  * GNU Affero General Public License (AGPL)

3. Weak Copyleft Licenses

Weak copyleft licenses provide a balance between permissive and strong copyleft licenses. They allow linking with proprietary software under certain conditions.

- Features
  * Some parts can remain closed source
  * Modifications to the original open-source code must remain open
  * More flexible than strong copyleft

- Examples
  * GNU Lesser General Public License (LGPL)
  * Mozilla Public License (MPL)
 
## Open Source Software vs Closed Source (Proprietary) Software

Software can generally be classified into two categories: Open Source Software and Closed Source (Proprietary) Software. Both differ in terms of source code accessibility, licensing, cost, customization, and control.

| Feature                | Open Source Software                                                | Closed Source (Proprietary) Software                                          |
| ---------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| **Definition**         | Software whose source code is publicly available.                   | Software whose source code is private and controlled by the owner or company. |
| **Source Code Access** | Users can view and modify the source code.                          | Users cannot access or modify the source code.                                |
| **Cost**               | Usually free or low cost.                                           | Usually paid and requires a license purchase.                                 |
| **Customization**      | Highly customizable according to user needs.                        | Limited customization options.                                                |
| **Licensing**          | Distributed under open-source licenses such as MIT, GPL, or Apache. | Distributed under proprietary licenses.                                       |
| **Development**        | Community-driven or collaborative development.                      | Developed and maintained by a company or organization.                        |
| **Security**           | Security issues can be identified and fixed by the community.       | Security fixes depend on the company’s updates.                               |
| **Support**            | Community support through forums and contributors.                  | Professional customer support provided by the company.                        |
| **Examples**           | Linux, Mozilla Firefox, Python, Blender                             | Microsoft Windows, Adobe Photoshop, macOS                                     |

## Advantages of Open Source Software

* Free to use and modify
* Greater transparency
* Flexible and customizable
* Encourages learning and collaboration

## Advantages of Closed Source Software

* Professional technical support
* User-friendly interfaces
* Regular official updates
* Better integration with company products

## Disadvantages of Open Source Software

* May require technical knowledge
* Limited official support
* Documentation can sometimes be incomplete

## Disadvantages of Closed Source Software

* Expensive licensing costs
* Limited flexibility
* Users depend on the vendor for updates and bug fixes

## Types of Freedom
- Freedom 0 : freedom to run the software for any purpose without restrictions
- Freedom 1 : Freedom to Study How the Program Works
- Freedom 2 : Freedom to Modify the Program
- Freedom 3 : Freedom to Redistribute Copies

## Bazaar Model and Cathedral Model

The Bazaar Model and Cathedral Model are two different approaches to software development in Open Source Software (OSS). These models were popularized by Eric S. Raymond in his essay *“The Cathedral and the Bazaar.”*

## 1. Cathedral Model

The Cathedral Model follows a centralized and controlled method of software development. In this model, the source code is developed by a small group of developers and released only after thorough testing and completion.

### Characteristics of Cathedral Model

* Development is done by a limited group of developers.
* Source code is not released frequently.
* Changes are carefully planned and controlled.
* Users have little involvement during development.
* Emphasis is placed on stability and structured design.

### Advantages

* Better control over the project
* Stable and well-tested releases
* Easier project management

### Disadvantages

* Slower development process
* Limited community contribution
* Bugs may take longer to identify and fix

### Examples

* Traditional proprietary software development
* Early versions of UNIX

## 2. Bazaar Model

The Bazaar Model follows an open and collaborative approach where development happens publicly with contributions from a large community of developers.

### Characteristics of Bazaar Model

* Source code is released frequently.
* Anyone can contribute to development.
* Community participation is encouraged.
* Bugs are identified and fixed quickly.
* Development is decentralized and collaborative.

### Advantages

* Faster innovation and improvement
* Quick bug detection and fixing
* Large community support
* Encourages collaboration and learning

### Disadvantages

* Can be difficult to manage large contributions
* Quality control may become challenging
* Requires active coordination among contributors

### Examples

* Linux
* Mozilla Firefox
* Apache HTTP Server


## Difference Between Cathedral Model and Bazaar Model

| Feature             | Cathedral Model           | Bazaar Model     |
| ------------------- | ------------------------- | ---------------- |
| Development Style   | Centralized               | Decentralized    |
| Contributors        | Small group of developers | Large community  |
| Source Code Release | Infrequent                | Frequent         |
| User Participation  | Limited                   | High             |
| Bug Fixing          | Slower                    | Faster           |
| Flexibility         | Less flexible             | Highly flexible  |
| Management          | Strictly controlled       | Community-driven |


## Bug Fixing Life Cycle

The Bug Fixing Life Cycle is a process followed in software development to identify, report, fix, test, and close software bugs or defects. It helps maintain software quality and ensures that issues are resolved systematically.

## Stages of Bug Fixing Life Cycle

## 1. Bug Identification

A bug is discovered by testers, developers, or users while using the software.

### Example

A login page crashes when an incorrect password is entered.

---

## 2. Bug Reporting

The identified bug is documented and reported in a bug tracking system.

### Information Included

* Bug ID
* Description of the issue
* Steps to reproduce the bug
* Severity and priority
* Screenshots or logs

### Common Bug Tracking Tools

* Jira
* Bugzilla
* Redmine

---

## 3. Bug Verification

The testing team verifies whether the reported issue is valid and reproducible.

### Outcomes

* Valid Bug → Assigned to developer
* Invalid Bug → Rejected or closed

---

## 4. Bug Assignment

The project manager or team lead assigns the bug to a developer for fixing.

### Purpose

Ensures accountability and proper tracking.

---

## 5. Bug Fixing

The developer analyzes the root cause and modifies the source code to fix the issue.

### Activities

* Debugging the code
* Correcting logic errors
* Updating affected modules

---

## 6. Retesting

After fixing the bug, testers retest the software to confirm that the issue has been resolved.

### Goal

Ensure the bug no longer exists.

---

## 7. Regression Testing

Testing is performed to verify that the new fix has not affected other parts of the application.

### Importance

Prevents introduction of new bugs after fixing an existing one.

---

## 8. Bug Closure

If the bug is successfully fixed and verified, it is marked as closed.

### Final Status

* Closed
* Resolved

---

## Bug Status Flow

```text
New → Assigned → Open → Fixed → Retest → Verified → Closed
```

Possible alternative states:

* Rejected
* Duplicate
* Deferred
* Reopened


## Importance of Bug Fixing Life Cycle

* Improves software quality
* Helps track defects efficiently
* Ensures systematic problem resolution
* Increases software reliability and user satisfaction

---
# Unit - 2
# Client Side vs Server Side

## Introduction

In web applications, processing can occur either on the **client side** or the **server side**. The client side refers to operations performed on the user's device, while the server side refers to operations performed on a remote server.

---

# Client Side

The **client side** is the part of an application that runs on the user's device (browser or mobile application). It is responsible for displaying content and handling user interactions.

## Characteristics

* Executes on the user's device.
* Provides the user interface (UI).
* Handles user interactions such as clicks and form validation.
* Reduces the load on the server.
* Depends on the user's browser capabilities.

## Technologies Used

* HTML
* CSS
* JavaScript
* Angular
* React
* Vue.js

## Examples

* Form validation before submission.
* Image sliders and animations.
* Dynamic page updates without reloading.
* User interface rendering.

---

# Server Side

The **server side** is the part of an application that runs on a web server. It processes requests, performs business logic, interacts with databases, and sends responses back to the client.

## Characteristics

* Executes on a remote server.
* Handles business logic and data processing.
* Communicates with databases.
* Provides security and authentication.
* Generates responses for clients.

## Technologies Used

* Python (Flask, Django)
* Java (Spring Boot)
* JavaScript (Node.js, NestJS)
* PHP
* ASP.NET

## Examples

* User authentication and authorization.
* Database operations (Create, Read, Update, Delete).
* Payment processing.
* Generating reports and APIs.

---

# Difference Between Client Side and Server Side

| Feature             | Client Side                           | Server Side                             |
| ------------------- | ------------------------------------- | --------------------------------------- |
| Execution Location  | User's device/browser                 | Web server                              |
| Main Purpose        | User interface and interaction        | Business logic and data processing      |
| Technologies        | HTML, CSS, JavaScript, Angular, React | Flask, Django, Spring Boot, NestJS, PHP |
| Access to Database  | No direct access                      | Direct access                           |
| Security            | Less secure                           | More secure                             |
| Performance         | Faster for UI operations              | Depends on server resources             |
| Internet Dependency | Some functions may work offline       | Requires communication with server      |
| Examples            | Form validation, animations           | Authentication, database queries        |

---

# Working Example

### Client Side

```javascript
if (password.length < 8) {
    alert("Password must contain at least 8 characters");
}
```

This validation happens in the browser before sending data to the server.

### Server Side

```python
@app.route('/login', methods=['POST'])
def login():
    username = request.form['username']
    password = request.form['password']
    
    # Verify credentials from database
    return "Login Successful"
```

This verification occurs on the server after receiving the request.


## R Programming

# 1. Introduction to R

## What is R?

R is an open-source programming language and software environment used for:

* Statistical Computing
* Data Analysis
* Data Visualization
* Machine Learning
* Scientific Research

### Features of R

* Free and Open Source
* Cross Platform
* Large Package Ecosystem
* Excellent Visualization Capabilities
* Supports Statistical Analysis

### Applications

* Data Science
* Business Analytics
* Bioinformatics
* Artificial Intelligence
* Financial Analysis

---

# 2. R Programming Environment

## Components

### R Console

Interactive environment where commands are executed.

```r
print("Hello World")
```

### R Script

Files with `.R` extension.

```r
x <- 10
y <- 20
print(x+y)
```

### RStudio

Popular IDE for R Programming.

Features:

* Script Editor
* Console
* Environment Window
* Plot Window
* Package Manager

---

# 3. Basic Language Elements

## Variables

```r
name <- "Lalit"
age <- 22
```

## Data Types

```r
num <- 10
dec <- 12.5
txt <- "Hello"
flag <- TRUE
```

| Type      | Example |
| --------- | ------- |
| Numeric   | 10      |
| Integer   | 10L     |
| Character | "Hello" |
| Logical   | TRUE    |
| Complex   | 2+3i    |

## Operators

### Arithmetic

```r
10+5
10-5
10*5
10/5
10^2
```

### Relational

```r
10 > 5
10 == 5
10 != 5
```

### Logical

```r
TRUE & FALSE
TRUE | FALSE
!TRUE
```

---

# 4. Data Structures

## Vector

Stores same datatype elements.

```r
marks <- c(80,90,95,100)
print(marks)
```

## Matrix

```r
m <- matrix(c(1,2,3,4), nrow=2)
print(m)
```

## Array

```r
arr <- array(1:12, dim=c(2,3,2))
```

## List

```r
student <- list(
  name="Lalit",
  age=22,
  marks=95
)
```

## Data Frame

```r
df <- data.frame(
  Name=c("A","B"),
  Marks=c(90,95)
)
```

---

# 5. Data Input and Output

## Reading CSV

```r
data <- read.csv("student.csv")
```

## Writing CSV

```r
write.csv(data,"output.csv")
```

## Reading Text File

```r
readLines("sample.txt")
```

## Writing Text File

```r
writeLines("Hello R","sample.txt")
```

---

# 6. Data Storage Formats

## CSV

```r
read.csv("file.csv")
```

## TXT

```r
read.table("file.txt")
```

## RData

```r
save(x,file="data.RData")
load("data.RData")
```

## RDS

```r
saveRDS(x,"data.rds")
readRDS("data.rds")
```

---

# 7. Subsetting Objects

## Vector Subsetting

```r
x <- c(10,20,30,40)

x[1]
x[2:3]
```

## Matrix Subsetting

```r
m[1,2]
```

## Data Frame Subsetting

```r
df[1,]
df[,2]
```

## Logical Subsetting

```r
x[x > 20]
```

Output

```r
30 40
```

---

# 8. Vectorization

Vectorization performs operations on entire vectors.

## Without Vectorization

```r
x <- c(1,2,3)

for(i in 1:3){
 print(x[i]*2)
}
```

## With Vectorization

```r
x*2
```

Output

```r
2 4 6
```

Advantages:

* Faster
* Cleaner Code
* Less Memory Usage

---

# 9. Control Structures

## If Statement

```r
x <- 10

if(x > 5){
 print("Greater")
}
```

## If Else

```r
if(x > 5){
 print("Greater")
}else{
 print("Smaller")
}
```

## Nested If

```r
if(x > 0){
 if(x > 10){
   print("Large")
 }
}
```

## Switch

```r
switch(
 "a",
 a="Apple",
 b="Ball"
)
```

---

# 10. Loops

## For Loop

```r
for(i in 1:5){
 print(i)
}
```

## While Loop

```r
i <- 1

while(i <= 5){
 print(i)
 i <- i+1
}
```

## Repeat Loop

```r
i <- 1

repeat{
 print(i)
 i <- i+1

 if(i > 5)
  break
}
```

---

# 11. Functions

## Creating Function

```r
add <- function(a,b){
 return(a+b)
}
```

## Calling Function

```r
add(10,20)
```

Output

```r
30
```

## Default Arguments

```r
square <- function(x=2){
 x*x
}
```

---

# 12. Scoping Rules

R uses Lexical Scoping.

```r
x <- 100

f <- function(){
 print(x)
}

f()
```

Output

```r
100
```

Example:

```r
make.power <- function(n){

 function(x){
   x^n
 }

}

cube <- make.power(3)

cube(2)
```

Output

```r
8
```

---

# 13. Loop Functions

## apply()

```r
m <- matrix(1:9,nrow=3)

apply(m,1,sum)
```

## lapply()

```r
x <- list(1:5,6:10)

lapply(x,sum)
```

## sapply()

```r
sapply(x,sum)
```

## tapply()

```r
marks <- c(80,90,70,95)

group <- c("A","A","B","B")

tapply(marks,group,mean)
```

---

# 14. Graphics and Visualization

## Scatter Plot

```r
x <- c(1,2,3,4)
y <- c(10,20,30,40)

plot(x,y)
```

## Line Chart

```r
plot(x,y,type="l")
```

## Bar Chart

```r
barplot(c(10,20,30))
```

## Histogram

```r
hist(rnorm(100))
```

## Pie Chart

```r
pie(c(10,20,30))
```

---

# 15. Grammar of Data Manipulation

Using dplyr package

```r
library(dplyr)
```

## select()

```r
select(df,Name)
```

## filter()

```r
filter(df,Marks > 80)
```

## arrange()

```r
arrange(df,Marks)
```

## mutate()

```r
mutate(df,
 Total=Marks+10)
```

## summarize()

```r
summarize(df,
 Avg=mean(Marks))
```

---

# 16. Debugging

## traceback()

```r
traceback()
```

## browser()

```r
browser()
```

## debug()

```r
debug(function_name)
```

## undebug()

```r
undebug(function_name)
```

---

# 17. Profiling

Measures performance.

```r
Rprof("profile.out")

# Code

Rprof(NULL)

summaryRprof("profile.out")
```

---

# 18. Statistical Simulation

## Random Numbers

```r
runif(10)
```

## Normal Distribution

```r
rnorm(10)
```

## Binomial Distribution

```r
rbinom(10,5,0.5)
```

## Sampling

```r
sample(1:100,10)
```

### Monte Carlo Simulation

```r
n <- 10000

x <- runif(n)

estimate <- mean(x^2)

estimate
```

---

# 19. Case Study: R as a Scripting Language

R can automate tasks.

## Example: Reading Data and Creating Report

```r
data <- read.csv("sales.csv")

summary(data)

png("sales_plot.png")

plot(data$Sales)

dev.off()
```

### Benefits

* Automation
* Reporting
* Data Analysis
* Statistical Modeling
* Visualization

---

# Important Viva Questions

1. What is R?
2. Explain vectors and lists.
3. Difference between matrix and data frame.
4. What is vectorization?
5. Explain lexical scoping.
6. Difference between lapply() and sapply().
7. What is a data frame?
8. Explain apply() family functions.
9. What is profiling?
10. What is Monte Carlo Simulation?

---

# Frequently Asked University Exam Programs

### Program 1: Factorial

```r
fact <- function(n){

 if(n==0)
   return(1)

 return(n*fact(n-1))
}

fact(5)
```

### Program 2: Fibonacci

```r
fib <- function(n){

 if(n<=1)
   return(n)

 fib(n-1)+fib(n-2)
}

fib(6)
```

### Program 3: Mean of Vector

```r
x <- c(10,20,30,40)

mean(x)
```

### Program 4: Largest Number

```r
x <- c(10,50,20,100)

max(x)
```

### Program 5: Sorting

```r
sort(c(5,3,8,1))
```




---

# Unit - 3

## Two-Phase Commit (2PC)

## Introduction

**Two-Phase Commit (2PC)** is a distributed transaction protocol used to ensure that all participating systems in a distributed database either **commit** a transaction successfully or **rollback** the transaction completely. It guarantees **atomicity** in distributed environments.

The protocol involves a **Coordinator** and one or more **Participants (Cohorts)**.

---

# Need for Two-Phase Commit

In distributed systems, a transaction may involve multiple databases or servers. If one server commits the transaction while another fails, the data becomes inconsistent.

The Two-Phase Commit protocol ensures that:

* All participants commit the transaction, or
* All participants abort (rollback) the transaction.

Thus, consistency is maintained across all systems.

---

# Phases of Two-Phase Commit

## Phase 1: Prepare Phase (Voting Phase)

The coordinator asks all participants whether they are ready to commit the transaction.

### Steps

1. Coordinator sends a **PREPARE** message to all participants.
2. Each participant performs necessary checks and writes the transaction information to a log.
3. Participants reply with:

   * **YES (Vote Commit)** if ready to commit.
   * **NO (Vote Abort)** if unable to commit.

### Outcome

* If all participants vote **YES**, the protocol proceeds to Phase 2.
* If any participant votes **NO**, the transaction is aborted.

---

## Phase 2: Commit Phase (Decision Phase)

The coordinator makes the final decision based on the votes received.

### Case 1: All Participants Vote YES

1. Coordinator sends a **COMMIT** message.
2. Participants commit the transaction.
3. Participants send an acknowledgment (ACK).
4. Coordinator completes the transaction.

### Case 2: Any Participant Votes NO

1. Coordinator sends an **ABORT/ROLLBACK** message.
2. Participants rollback their changes.
3. Participants send an acknowledgment (ACK).
4. Coordinator terminates the transaction.

---

# Working Diagram

```text
            Coordinator
                 |
      -----------------------
      |          |          |
Participant1 Participant2 Participant3

Phase 1 (Prepare)
Coordinator → PREPARE
Participants → YES / NO

Phase 2 (Decision)
If all YES:
Coordinator → COMMIT
Participants → ACK

If any NO:
Coordinator → ABORT
Participants → ACK
```

---

# Advantages

* Ensures data consistency across distributed systems.
* Guarantees atomic transactions.
* Prevents partial commits.
* Widely used in distributed databases and transaction processing systems.

---

# Disadvantages

* Can be slow because it requires multiple communication rounds.
* Coordinator failure may block the transaction.
* High network overhead in large distributed systems.
* Participants may remain locked while waiting for the coordinator's decision.

---

# Applications

* Distributed databases
* Banking systems
* E-commerce transactions
* Microservices requiring distributed transactions
* Enterprise resource planning (ERP) systems

---

## MongoDB
- No SQL Database (Not Only SQL) because it allows unstructured or semi-structured data to store
- Relevant Data are Combined
- Data are stored in `BSON(Binary JSON)` format which very similar to `JSON (JS Object Notation)`
- BSON stores in binary format so it can be faster
- Alternatives
  - Firebase - also No SQL (Backed Google)
  
| RDBMS                                       | No SQL                                                 |
|---------------------------------------------|--------------------------------------------------------|
| Row(Record of Single User)                  | Document(Record of Single User)                        |
| Multiple row can combined to create a table | Multiple documents are combined to create a Collection |
| Database - Collection of Tables             | Database - Collection of Collections                   |
| Fixed Schema                                | No Fixed Schema (Flexible)                             |

- MongoDB follows the concept called Sharding (Splitting the data into multiple parts to access quickly)

**Note:** We can use MongoDB in two different ways
- Vertical Scaling
- Horizontal Scaling

- **Replication:** Creates duplicates for managing the Fault Tolerance

## Setup
- Install MongoSH (Shell Edition) -> Set Environment Variable (Path)
- Install MongoDB (Community Edition with Compass)


## Commands in Mongo Shell

| Command                                                         | Explanation                                                            |
|-----------------------------------------------------------------|------------------------------------------------------------------------|
| *use* db_name                                                   | Used to create database or Used to use the existing database           |
| *show dbs*                                                      | Used to show all the databases                                         |
| *db.createCollection("courses")*                                | Used to create the collection                                          |
| *db.courses.drop()*                                             | Used to drop the collection                                            |
| *db.dropDatabase()*                                             | Used to drop the database                                              |
| *db.courses.insertOne({name: "Hari", age:22})*                  | Used to insert the document into collection                            |
| *db.courses.insertMany([{} , {}])*                              | Used to insert multiple document into the collection                   |
| *db.courses.find()*                                             | Used to display all the document in the collection                     |
| *db.courses.find({name:"DSA"})*                                 | Used to display the documents in the collection which has the name DSA |
| *db.courses.find({age:22} ,{_id:false, name:true, staff:true})* | Used to display only specified data (Like a projection in SQL)         |

### Update Commands Mongo Shell

- **Note:** Courses is name of the collection
- Syntax: `db.courses.updateOne({For Query}, {$set:{attributeName:"value"}})`
```
db.courses.updateOne({name : "Hari}, {$set:{age: 22}})
```
- Like this We have one more function called `updateMany()`
- By using this we can update multiple documents at a time 
- Like we have `$unset` to delete the field, `$inc` to increment the value.
- To add element to array we can use `$push` and delete element `$pull` and `$pop` with -1 will delete top and 1 will delete bottom
```
db.courses.updateOne({name : "Hari}, {$unset:{age: ""}})
db.courses.updateMany({$exists :{age : true}}, {$set:{age: 10 }})  // age: 32
db.courses.updateOne({name: "Hari"}, {$push:{skills: "MongoDB"}})
db.courses.updateOne({name: "Hari"}, {$pull:{skills: "MongoDB"}})
db.courses.updateOne({name: "Hari"}, {$pop:{skills: 1 }})
db.courses.updateOne({name: "Hari"}, {$pop:{skills: -1 }})
```
- **Note:** Instead of using true and false we can also use 0 and 1

### Upsert Command
- It will search for the document to update if the document is not available then it will insert a new document
- Syntax:
```
db.courses.updateOne({name : "Hari"}, {$set:{age: 22}}, {upsert:true})
```

### Delete Command
- Used to delete the document like other command delete also has two methods `deleteOne()` and `deleteMany()`
```
db.courses.deleteOne({name:"Hari"})
```

### Comparison and Logical Operators
```
db.courses.find({age:{$gte : 20}, {_id: false, name:true})
```
- `$gte` - Greater than or Equal to 
- `$lte` - Lesser than or Equal to 
- `$gt` - Greater than 
- `$lt` - Lesser than 
- `$eq` - Equal to

```
db.courses.find({$and:[{age: 22},{name: "Hari"}]}, {_id: false, name:true})
```
- like `$and` we have `$or` and `$nor`

### Limit and Skip Functions
- Limit used to limit number of document to query
- Skip used to skip the number of document specified

```
db.courses.find().skip(2)
db.courses.find().limit(1)
```

### Aggregate Functions
- It is like a GROUP clause in SQL
**Syntax:**
```
db.courses.aggregate([
  { $match: { name: "Hari" } },
  { $sort: { name: 1 } },   // ascending
  { $skip: 2 },
  { $limit: 1 }
]);

db.courses.aggregate([
  {$group:{_id: "$name", avg:{$avg: "$age"}}}  // $group like GROUP CLAUSE
  {$out: "AverageAge"}
])
```

### Lookup Function
- It is a part of aggregate Function
- It performs like joins in SQL
- If your application uses more lookups, Using SQL will be a better option
```
db.orders.aggregate([
  {$lookup:{
        from: "customers",
      	localField: "customer_id",
      	foreignField: "_id",
      	as : "customer"
  }}
])
```

### Schema Validation
- This how we have to specify the schema and its datatype to store data

```
db.createCollection(
    "orders", {
        validator:{
          $jsonSchema:{
            bsonType: "object",
            required : ["item", "price", "customer_id"],
            properties: {
              item: {
                bsonType: "string",
                description: "Stores the Item Name - Required"
              },
    
              price:{
                bsonType: "number",
                description: "Price of the Item - Required"
              },
    
              customer_id:{
                bsonType: "objectId",
                description: "ID of Customer"
              }
            }
          }
        }
      }
)
```


---
# Unit - 4

# Selenium – Detailed Explanation
## Introduction
**Selenium** is an open-source automation testing tool used for testing web applications. It allows testers and developers to automate browser actions such as clicking buttons, entering text, navigating pages, and validating outputs.

Selenium is mainly used for **web application testing** and supports multiple programming languages and browsers.
---

# Features of Selenium

## 1. Open Source Tool
## 2. Cross Browser Testing
It supports multiple web browsers such as:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari
## 3. Multiple Language Support

Selenium supports programming languages like:

* Java
* Python
* C#
* JavaScript
* Ruby
## 4. Platform Independent
It can run on operating systems such as:
* Windows
* Linux
* macOS

---

# Components of Selenium

## 1. Selenium IDE
A browser extension used for record-and-playback testing.

---
## 2. Selenium WebDriver
The most important component used for browser automation through programming.

---

## 3. Selenium Grid

Used for running tests on multiple machines and browsers simultaneously.

---


# Advantages of Selenium

* Free and open source
* Supports multiple browsers
* Supports multiple languages
* Strong community support

---

# Disadvantages of Selenium

* Supports only web applications
* Cannot automate CAPTCHA directly

---

# Ruby on Rails – Detailed Explanation

## Introduction

**Ruby on Rails**, commonly called **Rails**, is an open-source web application framework written in the **Ruby** programming language. It is used for developing dynamic and database-driven web applications quickly and efficiently.

Ruby on Rails follows the **Model-View-Controller (MVC)** architecture and emphasizes rapid application development with less coding.


---

# Features of Ruby on Rails

## 1. Open Source Framework

Rails is free to use and supported by a large developer community.

---

## 2. MVC Architecture

Ruby on Rails follows the **Model-View-Controller (MVC)** pattern:

* **Model** → Handles database operations
* **View** → Handles user interface
* **Controller** → Handles application logic

This architecture improves code organization and maintenance.

## 3. Built-in Testing Support

Rails provides tools for:

* Unit testing
* Functional testing
* Integration testing

---

## 4. Database Connectivity

Rails supports databases like:

* MySQL
* PostgreSQL
* SQLite

---

## 5. Security Features

Rails provides built-in security against:

* SQL Injection
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)


# Advantages of Ruby on Rails

* Faster web development
* Less coding required
* Easy database integration
* Good security features
* Clean and organized code
* Large community support
* Rapid prototyping support


# Disadvantages of Ruby on Rails

* Slower performance compared to some frameworks
* High memory usage
* Learning Ruby language may take time
* Not ideal for very large-scale high-performance systems


# Applications of Ruby on Rails

Ruby on Rails is used for developing:

* E-commerce websites
* Social networking sites
* Content management systems
* Business applications
* Online marketplaces

### Popular Websites Built Using Rails

* GitHub
* Shopify
* Airbnb


# OpenXava – Detailed Explanation

## Introduction

**OpenXava** is an open-source framework used for developing Enterprise Web Applications quickly using the **Java** programming language. It helps developers create business applications with less coding by automatically generating user interfaces from Java classes.

OpenXava is mainly used for developing:

* ERP systems
* Inventory management systems
* Banking applications
* School management systems
* Business management software

It is based on Java technologies such as:

* JPA (Java Persistence API)
* Hibernate
* Java EE / Jakarta EE

## Features of OpenXava

## 1. Rapid Application Development

OpenXava allows developers to create applications quickly with minimal coding.


## 2. Automatic User Interface Generation

Forms, tables, and views are automatically generated from Java model classes.


## 3. MVC Architecture

It follows the **Model-View-Controller (MVC)** design pattern for organized development.



## 4. Database Integration

Supports databases like:

* MySQL
* PostgreSQL
* Oracle
* SQL Server


## 5. Web-Based Framework

Applications developed using OpenXava run directly in web browsers.


## 6. Java-Based Framework

Developers can use Java concepts and object-oriented programming.


## 7. Built-in CRUD Operations

OpenXava automatically provides:

* Create
* Read
* Update
* Delete operations


## 8. Report Generation

Supports report generation in formats like:

* PDF
* Excel


## 9. Security Support

Provides:

* User authentication
* Role-based access control



## Advantages of OpenXava

* Faster development process
* Reduces coding effort
* Easy database connectivity
* Automatic UI generation
* Supports enterprise applications
* Reusable components
* Open-source and free


## Disadvantages of OpenXava

* Limited flexibility in UI customization
* Requires Java knowledge
* Smaller community compared to Spring Framework
* Not suitable for highly customized frontend applications



## Applications of OpenXava

OpenXava is used for:

* Enterprise Resource Planning (ERP)
* Customer Management Systems
* Accounting software
* Inventory systems
* Employee management systems


## Technologies Used with OpenXava

OpenXava commonly works with:

* Java
* Hibernate
* MySQL
* Apache Tomcat



## Git – Detailed Explanation

## Introduction

**Git** is a **Distributed Version Control System (DVCS)** used to track changes in source code during software development. It helps multiple developers work together on projects efficiently by maintaining versions of files and enabling collaboration.

Git was created by Linus Torvalds in 2005 for Linux kernel development.

Git is widely used in software development for:

* Source code management
* Team collaboration
* Version tracking
* Backup and recovery


## Features of Git

## 1. Distributed Version Control

Every developer has a complete copy of the repository including project history.

---

## 2. Fast Performance

Git performs operations like commit, branch, and merge very quickly.

---

## 3. Branching and Merging

Developers can create separate branches for features or bug fixes and later merge them into the main project.

---

## 4. Data Integrity

Git uses hashing algorithms (SHA) to maintain data consistency and security.

---

## 5. Open Source

Git is free and supported by a large developer community.

---

## 6. Collaboration Support

Multiple developers can work on the same project simultaneously.

---

## 7. Offline Working

Most Git operations work without internet connectivity.

---

# Common Git Commands

| Command      | Purpose                             |
| ------------ | ----------------------------------- |
| `git init`   | Create a new repository             |
| `git clone`  | Copy an existing repository         |
| `git add`    | Add files to staging area           |
| `git commit` | Save changes permanently            |
| `git push`   | Upload changes to remote repository |
| `git pull`   | Download latest changes             |
| `git branch` | Create/manage branches              |
| `git merge`  | Merge branches                      |

---

# Git Architecture

Git architecture mainly consists of four areas:

## 1. Working Directory

This is the local project folder where developers create and modify files.

### Functions

* Contains current project files
* User edits files here

---

## 2. Staging Area (Index)

The staging area stores changes temporarily before committing them.

### Functions

* Tracks selected changes
* Prepares files for commit

### Command Used

```bash
git add filename
```

---

## 3. Local Repository

The local repository stores committed project history in the local system.

### Functions

* Maintains versions of files
* Stores commits permanently

### Command Used

```bash
git commit -m "message"
```

---

## 4. Remote Repository

A remote repository is hosted on servers for sharing code with teams.

### Popular Remote Platforms

* GitHub
* GitLab
* Bitbucket

### Command Used

```bash
git push origin main
```


## Working Flow of Git Architecture

```text
Working Directory → Staging Area → Local Repository → Remote Repository
```

## Step-by-Step Process

1. Developer modifies files in Working Directory.
2. Files are added to Staging Area using `git add`.
3. Changes are saved in Local Repository using `git commit`.
4. Commits are uploaded to Remote Repository using `git push`.

## Advantages of Git

* Easy version tracking
* Faster development
* Supports teamwork
* Backup of source code
* Efficient branching and merging
* Open source and secure

## Disadvantages of Git

* Learning curve for beginners
* Complex commands at advanced levels
* Large repositories may consume storage


## Applications of Git

Git is used for:

* Software development
* DevOps projects
* Open-source contribution
* Continuous Integration/Deployment
* Team collaboration

# Eclipse, Joomla, and Apache Server

## 1. Eclipse

**Eclipse** is a free and open-source Integrated Development Environment (IDE) used for software development. It provides tools for writing, debugging, and testing applications.

### Features

* Supports multiple programming languages such as Java, C++, Python, and PHP.
* Provides code completion and debugging tools.
* Extensible through plugins.
* Cross-platform support (Windows, Linux, macOS).

### Advantages

* Free and open source.
* Large developer community.
* Rich plugin ecosystem.

### Common Uses

* Java application development.
* Web application development.
* Enterprise software development.

---

## 2. Joomla

**Joomla** is a free and open-source Content Management System (CMS) used to create and manage websites without extensive programming knowledge.

### Features

* User-friendly administration panel.
* Template and extension support.
* Built-in user management.
* Multilingual support.

### Advantages

* Easy website management.
* Large collection of extensions and templates.
* Strong community support.

### Common Uses

* Business websites.
* Educational portals.
* E-commerce websites.
* News and blog sites.

---

## 3. Apache Server

**Apache HTTP Server** is a free and open-source web server software developed and maintained by the **Apache Software Foundation**. It is one of the most widely used web servers in the world.

### Features

* Supports HTTP and HTTPS protocols.
* Highly configurable.
* Supports modules and extensions.
* Cross-platform compatibility.

### Advantages

* Reliable and secure.
* Open-source and free.
* Large community support.
* Flexible configuration options.

### Common Uses

* Hosting websites and web applications.
* Serving static and dynamic web pages.
* Supporting web services and APIs.

---

# Difference Between Eclipse, Joomla, and Apache Server

| Feature       | Eclipse                | Joomla                          | Apache Server                |
| ------------- | ---------------------- | ------------------------------- | ---------------------------- |
| Type          | IDE (Development Tool) | Content Management System (CMS) | Web Server                   |
| Purpose       | Software Development   | Website Creation and Management | Hosting and Serving Websites |
| Users         | Developers             | Website Administrators          | System Administrators        |
| Open Source   | Yes                    | Yes                             | Yes                          |
| Main Function | Coding and Debugging   | Content Management              | Web Page Delivery            |

---






