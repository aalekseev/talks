# Title: Testing Architecture for Complex Applications

## Meta

| | |
|-|-|
| **Conference** | PyCon Estonia 2020 |
| **Timing** | 30min |
| **Status** | draft |

## Description

It is hard to find information about how to setup testing for big application. Most of the time what you can find - is either put everything in `tests.py` module or deviding everything by test type - unit, integration and functional. This approaches might work for some applications and they definately have usecases, however in this talk I will show approach that worked very well for me working mostly on big Django-powered sites with complex logic.

## Audience (Who and Why)

This talk will be usefull for people who know a bit about
auto tests and want to see other approaches for
structuring them and also people working on big Django
projects.

## Outline

1. Introduction (2min)
    - About me
1. Tests structure approaches (10min)
    - Default Django approach for small applications
    - Tests as a separate python package
    - Dividing tests by type
    - What if we take default Django approach and add gradual division?
1. Risk Based Testing approach (5min)
    - 100% coverage is not a goal
    - Indentifying the most crutial parts of the codebase to cover with tests
1. Working with legacy code (5min)
    - There is no apps without legacy
    - Acceptance testing
1. Easy to implement (there is no reason to skip them) test examples (5min)
    - Testing Models Methods Without DB Access
    - Testing Forms
    - Testing Permissions
    - Testing Management Commands
    - Testing Celery Tasks
1. Conclusion (2min)
    - Brief summary of structure approach
    - Additional resources
    - Thanks!

## Notes

This talk is based on personal experience, frustration and
mistakes done while writing tests for more than 3 years for
different projects and setups.

Best resources out there about testing (specifically python applications):

- https://testandcode.com
- https://automationpanda.com
- https://www.obeythetestinggoat.com

## BIO

I am a fullstack developer at Thorgate - a digital agency
focused on helping industry companies automate internal processes. I am passionate about testing and making
writing tests efiicient and part of the daily routine.
