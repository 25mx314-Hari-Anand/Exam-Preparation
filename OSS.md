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

# Unit - 4





