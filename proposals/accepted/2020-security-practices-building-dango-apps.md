# Title: Security Practices for Building Django Applications

## Meta

| | |
|-|-|
| **Conference** | PyCon Estonia 2020 |
| **Timing** | 30min |
| **Status** | accepted |

## Description

Django community has a misconception that Django applications are pretty secure and security of the application is often neglected. This talk tries to show the most common types of vulnerabilities and attacks related to Django and has in the end key takeaway checklist, that is easy to start using right now to improve the security of developed applications.

## Audience (Who and Why)

For developers building modern python applications and interested in lowering security risks in their applications. This talk has some in-depth details about Django-specific problems, but I hope to add more graphs, real-life examples and use simplified explanations so this talk could be also interesting for project managers.

## Outline

1. Introduction (2min)
    - About me
1. Statistic graphs + examples about hacked Django applications per years and common security risks (10min)
1. Django built-in tools that you can use now, to improve the security of your site (5min)
    - Django admin site
    - Django check framework (A built-in tool that not many people know of)
    - Recommendations from the Django team
1. Tools you can use to check your site (5min)
    - Mozilla Observatory
    - Pycharm Python security plugin
    - Django-security app
1. A Summary about most common security risks and ways to fix them (5min)
    - Django admin security
    - XSS (Cross-site scripting)
    - Brute-force attacks (Django-defender)
    - CSP (for external scripts and resources linked in your site)
1. Conclusion (2min)
    - Easy to follow steps/checklist to start thinking about security (Key takeaways from the talk)
    - Additional resources
    - Thanks!

## Notes

This talk is based on the multiple articles and videos and is a bit of a compilation + learning more about security practices.

## BIO

I am a full-stack developer at Thorgate - a digital agency
focused on helping industry companies automate internal processes.