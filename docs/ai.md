---
layout: default
title: AI Policy
nav_order: 20
---

# AI policy (draft, rapidly changing)
{: .no_toc }

{: .no_toc .text-delta }

---

**What is not permitted:**
- Never paste private information into a commercial public AI tool as this information will likely be kept by the tool developer and could be leaked to other users
- Do not write papers from scratch using AI
- Do not generate ideas for grants from AI (more details below)
- Do not use code, references, writing etc. without checking it
- Do not use AI that you are reviewing a paper for a journal or a submitted grant for a study section. Similar care should be taken for any other confidential material obtained from a third party source.

**What is permitted (and encouraged!):** 
- Where possible use AI for tedious tasks (example: reformatting text into a table, developing comments and unit tests for code) 
- Improving writing style, grammar and spelling checks, cutting and reformatting text.
- Supporting the development of code and analysis scripts to be human checked and evaluated. 
- Summarizing searches of public domain data sources and references to be human curated and evaluated.
- Providing meeting summaries (e.g., Zoom AI)  
- [See this cheatsheet for information about everyday AI uses:](https://www.ottrproject.org/cheatsheets/ai_everyday_uses.html) 

**Research**
- Track when you use AI and what you use it for (including the tool and version), as we will need to acknowledge that. See this attribution toolkit for how to acknowledge usage: https://aiattribution.github.io/
- This includes usage for writing code, editing writing, or anything that might impact the reproduction or integrity of your research
- Always check any citations given to you from AI
- Do not use AI to do tasks themselves, but rather help you with code to do a task

**Code**
- You should understand the fundamentals of coding before starting to work with LLM generated code. Once lab members are comfortable with foundations and being able to code or implement analysis methods independently, AI usage is highly encouraged to enhance efficiency. 
- AI can help you refactor, translate, understand, and document  your code: https://github.com/fhdsl/AI_for_Efficient_Programming 
- You can use AI to help you write code from scratch, but you need to understand what the code is doing and be able to hand check the components of the script
- AI can help to generate robust unit tests and enhance the error checking / modularization of processes
- Scripts should be checked by hand to ensure they do not contain any malware or other sources that could inadvertently leak datasets inadvertently. 

**Grants**
- Grants are considered university IP, and should only be supported using approved university LLMs to protect lab information. 
- AI can help you write grants, however, it should be used for specific tasks rather than writing large sections of the proposal such as drafting a letter of support for a collaborator, helping you understand what is required in the grant announcement, reworking text into a table or other format, understanding a new topic (check all references as AI hallucinates references)
- Be aware that your ideas will no longer be private if you paste them into a public AI tool
- AI can help inspire idea generation, but should not be used to generate ideas, for example you can ask how about a particular topic or how two things relate to one
[This is because the NIH has policies against using AI for generating ideas](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-25-132.html)
- Be aware of AI policies of the funder and grant before using AI to generate any materials for grant writing

**Datasets and data analysis**
- Never upload internal datasets or datasets obtained from protected sources (e.g., dbGAP, with data use agreement from other sites, etc) into a commercial public AI tool as this information will likely be kept by the tool developer and could be leaked to other users.
- Human datasets obtained through dbGAP or not otherwise made publicly available in GEO may require use of special secure university AI-approved implementations, and whenever possible analyses should avoid relying on private LLMs unless that is an explicit and approved research goal. Please note this may constitute a HIPAA violation. 
- AI can be used to generate analysis scripts to analyze datasets on protected, university compute resources. 

**Papers**
- Draft papers are considered university IP, and should only be supported using approved university LLMs to protect lab information. 
- AI should not be used for writing papers from scratch. This is because many journals have policies against this. While other journals do not have these policies, it can be difficult to tell exactly where we might submit, as we may need to submit to several journals. Most journals do allow AI for editing, however, check the journal’s policies ahead of time (that we plan to submit to)
- Be aware that if you copy paste your writing into a commercial AI tool, that content may be kept by the tool and possibly even leaked to other users
- Again be careful to check all references suggested by AI - many models hallucinate fake or incorrect references

**Reviewing papers**
- AI can help you understand the context of a field but should never be used to help you review a paper.
- Copy and pasting text into a commercial tool is a violation of the privacy restrictions. 

**Discussion of AI usage as part of lab usage**

- AI usage is expected as a routine part of group practice. It is encouraged that you discuss your personal use of AI and ask for guidance on that process as part of regular meetings with Elana and senior lab members.
- The university varies in reimbursement and IT policies around AI tools. Paid subscriptions for tools will be supported by the lab as part of core equipment as allowed by University IT and procurement policies, and should be discussed with Elana and departmental IT. 

**Resources**
- [UMB policies](https://www.umaryland.edu/media/umb/procedures/UMB-Artificial-Intelligence-Guidelines.pdf)
- [See this video on current policies regarding AI use for publications and grant writing:] (https://fredhutch.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=8eeb3bd0-ac16-4dba-858d-b38b016cff76) 
- [Here are the associated slides: Navigating AI ethics for scientific research](https://docs.google.com/presentation/d/15RmlGNAontco7VF4EdtQFeaOl_1QKc1TVMCb79vKKz0/edit?usp=sharing)

**Content adapted from template lab policies developed by [Carrie Wright](https://carriewright11.github.io) 

<!-- just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "tests" collection
    tests:
      # Give the collection a name
      name: Tests
      # Exclude the collection from the navigation
      # Supports true or false (default)
      # nav_exclude: true
      # Fold the collection in the navigation
      # Supports true or false (default)
      # nav_fold: true  # note: this option is new in v0.4
      # Exclude the collection from the search
      # Supports true or false (default)
      # search_exclude: true -->
