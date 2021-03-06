
layout: markdown_page
title: "GitLab Handbook Usage"
---

At GitLab our handbook is extensive and keeping it relevant is an important part of everyone's job. The reasons for having a handbook are:
在GitLab我们的手册涉及范围很广，让它与每个人的工作关联起来是工作中非常重要的一部分，制作手册的原因是：

1. 阅读比听更快。
1. 阅读是异步的，你不需要去打扰别人或等他们有空。
1. 更容易招聘到员工：人们可以知道我们代表什么和我们如何运作。
1. 这样更容易留下员工：在入职前可以让他们知道他们会进入什么样的公司。
1. 因为可以找到所有相关的信息，所以培训会更简单。
1. 团队合作更简单：根据这个手册可以知道公司其他部门是如何工作的。
1. 讨论变更更容易：因为可以获取到目前的进展情况。
1. 沟通变更更简单：只要看一下代码差异(diff)就可以了。
1. 每个人都可以做出贡献：大家都可以在合并请求上提出建议。

编写手册用了很长时间和思考。它能在较长的时间内节省时间，对我们的组织进行规模化和调整是非常必要的。请遵循这个指南，并提醒他人。

1. If you need to discuss with a team member for help please realize that probably the majority of the community also doesn't know, be sure to **document** the answer to radiate this information to the whole community. After the question is answered, discuss where it should be documented and who will do it. You can remind other people of this by asking "Who will document this?"
1. When you discuss something in chat always try to **link** to a URL where relevant, for example, the documentation you have a question about or the page that answered your question. You can remind other people of this by asking "Can you please link?"
1. To change a guideline or process, **suggest an edit** in the form of a merge request.
After it is merged you can talk about it during the team call if applicable. You can remind other people of this by asking "Can you please send a merge request for the handbook?"
1. Communicate process changes by linking to the **diff** (a commit that shows the changes before and after). Do not change the process first, and then view the documentation as a lower priority task. Planning to do the documentation later inevitably leads to duplicate work communicating the change and to outdated documentation. You can remind other people of this by asking "Can you please update the handbook first?"
1. Remember, the handbook is not what we hope to do, what we should formally do, or what we did months ago. **It is what we do right now.** So if you want to change a process change the handbook in order to change it. To propose a change to a process make a merge request to change the handbook. Don't use another channel to propose a handbook change (email, Google Doc, etc.).
1. Like everything else, our processes are always in flux. Everything is always in draft, the initial version should be in the handbook, too. If you are proposing a change to the handbook, whenever possible, skip the issue and submit a merge request. Mention the people that affected by the change in the merge request. In many cases, merge requests are easier to collaborate on since you can see the proposed changes.
1. To propose a change a merge request is preferred over an issue description. A merge request allows people to see the context of your change.
1. If something is a limited test to a group of users, add it to the handbook and note as such. Then remove the note once the test is over and every case should use the new process.
1. When communicating something always include a link to the relevant (and up to date) part of the **handbook** instead of including the text in the email/chat/etc. You can remind other people of this by asking "Can you please link to the relevant part of the handbook?"
1. If you copy content please remove it at the origin place and replace it with a link to the new content. Duplicate content leads to updating it in the wrong place, keep it [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself).
1. Make sure to always cross-link items if there are related items (elsewhere in the handbook, in docs, or in issues).
1. The handbook is structured by function to ensure every item in it has a clear owner and location. Please cross-link liberally but avoid unstructured content like lists of links, FAQ's, and company wide glossary since these are very hard to keep up to date. Instead put the link, the answer, and the definition in the most relevant place.
1. Use headers liberally. Add a Table of Contents ([ToC](https://gitlab.com/gitlab-com/www-gitlab-com/merge_requests/7141/diffs#f054d0f855ebef2a11559c362a356a2f9e010b99_6_6)) if a page is longer than one screen. Headers should have normal capitalization (don't use [ALL CAPS](https://en.wikipedia.org/wiki/All_caps) nor [TitleCase](http://www.grammar-monster.com/glossary/title_case.htm)).
1. If someone inside or outside GitLab makes a good suggestion invite them to add it to the handbook. Send the person the url of the relevant page and section and offer to do it for them if they can't. Having them make and send it will make the change and review reflect their knowledge.
1. All documentation that also applies to code contributions from the wider community should be in the GitLab CE project (for example in [CONTRIBUTING](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/CONTRIBUTING.md) or the [code review guidelines](https://docs.gitlab.com/ce/development/code_review.html), not the handbook that is only for team members.
1. Learn how to edit the [handbook using git](/handbook/git-page-update). Please read through the [Writing Style Guidelines](https://about.gitlab.com/handbook/communication/#writing-style-guidelines) before contributing.
1. When you submit a merge request, make sure that it gets merged quickly. It should not take more than a few days to get a merge request approved to the handbook. Mention people in the merge request or reach them via Slack. If you get a suggestion for a large improvement on top of the exiting one consider doing that separately. Create an issue, get the exiting MR merged, then create a new merge request. Getting your merge requests approved quickly may prevent merge conflicts from happening.
1. Only mark a merge request as "WIP" (Work in Progress) if it will negatively affect the company if merged too early. That can be the case for application code but is almost not possible for handbook MRs. 
1. The handbook is for things concerning (future) GitLab team members only. If something concerns users of GitLab, it should be documented in the [GitLab documentation](http://doc.gitlab.com/), the [GitLab Development Kit (GDK)](https://gitlab.com/gitlab-org/gitlab-development-kit), the [CONTRIBUTING file](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/CONTRIBUTING.md) or the [PROCESS file](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/PROCESS.md).
