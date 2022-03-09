## When is Basic Authorization used vs. Bearer Authorization?

> ***I use basic authoraization to check the user valid or not , if the user was valid we will give him a virtual token and this token will enabel him to access to API's sources and the process that verify of token called bearer authoraization because I send the token as bearer shape (Bearer <token>)***  

## What does the JSON Web Token package do?  
***We use it to prevent unauthenticated users access to api sources***  
## What considerations should we make when creating and storing a SECRET?  
***When we make a secret part , it should be inside env file because I use it to provide more security for token***  

Trem|Def
---|---
encryption| Encryption is a way of scrambling data so that only authorized parties can understand the information. In technical terms, it is the process of converting human-readable plaintext to incomprehensible text, also known as ciphertext.
token| equence of characters having a collective meaning. The character sequence forming a token is called the Lexeme.
bearer| is an HTTP authentication scheme that involves security tokens called bearer tokens.
secret| the secret is a symmetric key that is known by both the sender and the receiver.
JSON Web Token| JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.  


# RBAC
## Role-Based Access Control RBAC
### It is the idea of assigning system access to users based on their role in an organization. It’s important to remember that not every employee needs a starring role.

## What is RBAC?
> ***It’s idea of assigning system access to users based on their role within an organization.***

##### The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment.

## Benefits of RBAC?
> it is much easier to audit user rights, and to correct any issues identified.
> easy to implement

- RBAC vs ABAC vs ACL

- Access control lists ACL: is a means of defining access rights by a given user or user group, to a specific object, such as a document.

- Attribute-based access control ABAC:sometimes known as policy-based access control, can use a variety of attributes, including user department, time of day, location of access,….



## Benefits of RBAC?
> ***With the proper implementation of RBAC, the assignment of access rights becomes systematic and repeatable. Further, it is much easier to audit user rights, and to correct any issues identified.***



- RBAC vs. ABAC vs. ACL
There are some alternatives for/variations of RBAC, including:

- Access control lists (ACL) — An ACL is a means of defining access rights by a given user or user group, to a specific object, such as a document.  As a simple example, an ACL could be used to allow users from one department to make changes to a document, while only allowing users from other departments to read the document.

- Attribute-based access control (ABAC) — ABAC, sometimes known as policy-based access control, can use a variety of attributes, including user department, time of day, location of access, type of access required, etc. to determine whether a user’s access request should be granted.

#### Both of these options provide additional granularity of controls beyond the basic concept of RBAC, but can also greatly expand the effort required to create and maintain the necessary permissions.  RBAC arguably offers a more simplified and manageable approach, given that the privileges of a user in a given position are granted with a simple effort, to all others in the same role.  These methods can, however, be used in tandem to increase control.