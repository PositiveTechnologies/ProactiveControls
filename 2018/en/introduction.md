# INTRODUCTION

The OWASP Top Ten Proactive Controls 2018 is a list of security techniques that should be considered for every software development project. This document is written for developers to assist those new to secure development.

One of the main goals of this document is to provide concrete practical guidance that helps developers build secure software. These techniques should be applied proactively at the early stages of software development to ensure maximum effectiveness.

## The Top 10 Proactive Controls

The list is ordered by importance with list item number 1 being the most important:
* __C1__: [Define Security Requirements](c1.md)
* __C2__: [Leverage Security Frameworks and Libraries](c2.md)
* __C3__: [Secure Database Access](c3.md)
* __C4__: [Encode and Escape Data](c4.md)
* __C5__: [Validate All Inputs](c5.md)
* __C6__: [Implement Digital Identity](c6.md)
* __C7__: [Enforce Access Controls](c7.md)
* __C8__: [Protect Data Everywhere](c8.md)
* __C9__: [Implement Security Logging and Monitoring](c9.md)
* __C10__: [Handle All Errors and Exceptions](c10.md)

## How this List Was Created

This list was originally created by the current project leads with contributions from several volunteers. The document was then shared globally so even anonymous suggestions could be considered. Hundreds of changes were accepted from this open community process.

## Target Audience

This document is primarily written for developers. However, development managers, product owners, Q/A professionals, program managers, and anyone involved in building software can also benefit from this document.

## How to Use this Document

This document is intended to provide initial awareness around building secure software. This document will also provide a good foundation of topics to help drive introductory software security developer training. These controls should be used consistently and thoroughly throughout all applications. However, this document should be seen as a starting point rather than a comprehensive set of techniques and practices. A full secure development process should include comprehensive requirements from a standard such as the OWASP ASVS in addition to including a range of software development activities described in maturity models such as [OWASP SAMM](https://www.owasp.org/index.php/OWASP_SAMM_Project) and [BSIMM](https://www.bsimm.com/).

## Link to the OWASP Top 10 Project

The OWASP Top 10 Proactive Controls is similar to the OWASP Top 10 but is focused on defensive techniques and controls as opposed to risks. Each technique or control in this document will map to one or more items in the *risk based* OWASP Top 10. This mapping information is included at the end of each control description.