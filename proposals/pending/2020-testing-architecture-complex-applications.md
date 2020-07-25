# Title: Testing Architecture for Complex Applications

## Meta

| | |
|-|-|
| **Conference** | PyCon Estonia 2020 |
| **Timing** | 30min |
| **Status** | pending |

## Description

It is hard to find information about how to set up testing for the big application. Most of the time what you can find - is either put everything in `tests.py` module or dividing everything by test type - unit, integration and functional. This approaches might work for some applications and they have use-cases, however in this talk, I will show an approach that worked very well for me working in an agency with mostly big Django-powered sites and complex logic.

## Audience (Who and Why)

This talk will be useful for people who know a bit about
autotests and want to see other approaches for
structuring them and also people working on big Django
projects.

## Outline

1. Introduction (2min)
    - About me
1. Tests structure approaches (10min)
    - Default Django approach for small applications
    - Tests as a separate python package
    - Dividing tests by type
    - What if we take the default Django approach and add gradual division?
1. Risk-Based Testing approach (5min)
    - 100% coverage is not a goal
    - Identifying the most crucial parts of the codebase to cover with tests
1. Working with legacy code (5min)
    - There are no apps without legacy
    - Acceptance testing
1. Easy to implement (there is literally no reason to skip them) test examples (5min)
    - Testing Models Methods Without DB Access
    - Testing Forms
    - Testing Permissions
    - Testing Management Commands
    - Testing Celery Tasks
1. Conclusion (2min)
    - A summary of my approach for testing big Django applications
    - Additional resources
    - Thanks!

## Notes

This talk is based on personal experience, frustration and
mistakes are done while writing tests for more than 4 years for
different projects and setups.

Best resources out there about testing (specifically python applications):

- https://testandcode.com
- https://automationpanda.com
- https://www.obeythetestinggoat.com

## BIO

I am a full-stack developer at Thorgate - a digital agency
focused on helping industry companies automate internal processes.
