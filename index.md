---
title: Exercise Instructions
permalink: index.html
layout: home
---

# MS-4018: Draft, analyze, and present with Microsoft 365 Copilot

## Course Description

This course directs users to learn common prompt flows in Microsoft 365 apps including PowerPoint, Word, Excel, Teams, and Outlook. It also introduces Microsoft 365 Copilot Chat and discusses the difference between work and web grounded data.

# Exercises

 **Note**: To complete these exercises, you must choose an appropriate Microsoft 365 Copilot plan:
 - **For individuals:**
    - To use Copilot features in Microsoft 365 apps, customers must purchase a Microsoft 365 Personal or Family subscription and be signed into their Microsoft account.
  - **For business and enterprise customers:**
    - Microsoft 365 Copilot Chat is available at no extra cost for Microsoft 365 business and enterprise customers.
    - To purchase Microsoft 365 Copilot, customers must have a qualifying Microsoft 365 plan for enterprise or business. For more information, see the eligibility prerequisites question in the FAQ section of the following sites: Microsoft 365 Copilot for [enterprise](https://www.microsoft.com/en-us/microsoft-365-copilot/enterprise#FAQ) or [business](https://www.microsoft.com/en-us/microsoft-365-copilot/business#FAQ).

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}

{% for activity in labs  %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{% endfor %}

