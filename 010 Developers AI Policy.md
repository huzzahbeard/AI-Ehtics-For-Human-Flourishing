# Introduction

When you use a tool, something is lost and something is gained. With AI (LLMs / Claude / GPT), you get vast access to quick, precise answer searching that is then curated to answer your specific question. With things like Claude Code, Windsurf, or Cursor, you get access to a system that can literally write your code for you. This can be a time-saving tool and help fill in the gaps on tedious work.

# Development Goals 

When you are a developer, we expect you to be able to write, understand, and support the systems that are created. We do not want to close the door behind us on younger developers, so we are a department focused on teaching, helping, and sharing knowledge amongst ourselves. To share knowledge, you must have it and understand it. The goal of using A.I. in our work should always be to improve your own skills and knowledge, not to offload the meaningful portion of your work. 

# Approved AI Usage

AI (LLMs) are an incredible and useful technology and should be utilized both in integrations into software and to help with your job. However, you should always understand and support the code A.I. produces. Having A.I. write your code can be time-saving, especially for tedious work. However, it should not be writing a large percentage of your code and should be utilized more often than not as a consultant or a documentation assistant. 

### Features vs Tedious Necessary Work
When writing and creating a new feature or refactoring existing functionality, a good rule of thumb is 20 - 30% can be written by an LLM. The 20-30% guideline is directional rather than precisely measurable. Developers should apply this in good faith, erring on the side of writing more code themselves when uncertain. The goal being that even if you use an LLM to write a boilerplate form potentially writing 80% of your document, the meaningful business logic of that form would be written mostly by you. When thinking of features, consider things that are unique to the project as well as CRUD operations and data structure implementation. Things that would be considered unique to the project like search engines, business logic, business processes, CRUD operations, reporting, and data structure implementations would fall into this category. In these cases, A.I. usage as a consultant and for documentation search is encouraged. 

Tedious but necessary work includes things like documentation, initial database seeder setups, readmes, and commit messages. In these cases, it is acceptable to have an LLM write this code for you; however, all code must be reviewed by you to confirm it does indeed do as expected and that you understand it. 

#### A note on CRUD
CRUD operations, while often formulaic, require hands-on work to ensure developers understand data structures, relationships, and how backend decisions influence frontend implementation. In a full-stack environment, this foundational understanding is critical.

#### Test Suites 
While AI can generate initial test scaffolding, test creation requires understanding edge cases, business logic, and system behavior. Developers should review AI-generated tests critically and add cases the AI may have missed. Tests are a learning tool as much as a quality assurance tool.

#### Documentation
Documentation like Pdocs should be written after the developer has implemented and understands the functionality. AI handles formatting and phrasing while the developer ensures technical accuracy.

### Examples of appropriate usage
- Spell checking.
- Set me up a boilerplate X.
- What does this error mean?
- Write me a basic test suite for X class. (These test suites should be reviewed and updated by any developer using an LLM to write tests. Tests are critical thinking exercises and should have human development to ensure they are effective and of quality.)
- Any questions about the code in consulting mode.
- How might I optimize this code?
- Write me a commit message for the staged files.
- Update the readme files.
- Write me Pdocs for this class.
- What are the parameters for this function?
- Are there any other functions that might be used to accomplish X goal?
- I wrote this function over here. I need it adapted to this model but updated to account for that models fillable fields.

**The goal of using A.I. in our work should always be to improve your own skills and knowledge, not to offload your work.** 

# Usage Disclosure

We do not hide our A.I. usage. If we are asked about how we use A.I., this policy explains how and under what circumstances we use it. In code, if you have A.I. write whole sections of code, it should be commented what LLM wrote the code, something like: 
- // Claude
- // GPT

Additionally you may choose to disclose at the top of a file what you used the AI For
```php 
/** 
I use Claude to proof the spelling and punctuation on this project
 @author Aaron Blakeley*/
```

The LLMs should not be mentioned in git commit messages at all. Later, code that is maintained or updated can have the disclosure comments removed. The goal is that the historical commits would reflect that the code was initially generated by an LLM, but as the code is updated and changed by human developers, these disclosures can be removed. Additionally, during code reviews or when consulting with one another, it should be mentioned when A.I. is used heavily and how.

When speaking with clients, it is okay to mention our use and how we use it. Following this policy ensures that our clients are receiving development work from the developers they are interacting with.

# Approved Tools
Currently approved LLMs: 
- GPT
- Claude

# How We Measure Success 

This policy doesn't rely on tracking percentages or monitoring tool usage. Instead, we measure success by team competency: the ability to understand, explain, and solve complex problems independently. Developers who use AI as a learning amplifier will grow in capability. Those who use it as a replacement for thinking will see their skills stagnate. Over time, this becomes evident in code reviews, problem-solving discussions, and client work quality.

# Conclusion

LLMs are an incredible tool, and with proper usage, we can grow our team's skill base and leave open the door for new developers. If the policy is followed, then core competency and learning abilities will be maintained in the team, as that is the ultimate measure of the team: the competency and creativity with which we approach our clients' problems.