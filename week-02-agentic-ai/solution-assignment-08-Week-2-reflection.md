# Assignment 8 — Week 2 Reflection Blog

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

# Purpose

In this assignment, you will reflect on your Week 2 learning journey and write a short blog capturing your experience working with Agentic AI tools such as Claude Code, Skills, Subagents, MCP, Hooks, Permissions, and Memory.

You will also publish a LinkedIn post summarizing your learning and share both links for evaluation.

---

# Task 1 — Write Your Reflection Blog

## Goal

Write a reflection blog covering your Week 2 learning experience.

### Blog Requirements

Your blog must include:

* Title: **Reflection – Week 2**
* Minimum 300 words
* At least 2–3 topics from Week 2 (Claude Code, Skills, Subagents, MCP, Hooks, Permissions, Memory)
* Honest personal reflection (learning, challenges, mindset)
* One habit/system you plan to implement
* Your full name clearly visible

### Allowed Platforms

You can publish your blog on:

* Hashnode
* Medium
* Dev.to
* LinkedIn Article
* GitHub Markdown file
* Substack

---

### Evidence

#### Screenshot 1 — Blog published and visible

[Screenshot 47](screenshots/Screenshot_047.png)


---

### Submission Field

Blog Link:

https://medium.com/@kanyevictoray/agentic-ai-the-future-vs-the-process-8d0300b1aa50?sharedUserId=kanyevictoray

---

# Task 2 — Create LinkedIn Post

## Goal

Share your Week 2 learning publicly on LinkedIn.

---

### LinkedIn Post Requirements

Your post must include:

* One screenshot from any Week 2 assignment
* Short reflection (what you learned or built)
* Required P.S. line exactly as given below

---

### Required P.S. Line (Must Include Exactly)

P.S. This post is a part of DevOps Micro Internship with Agentic AI Cohort-3 by Pravin Mishra. You can start your DevOps journey by joining this Discord community ( [https://discord.pravinmishra.com/](https://discord.pravinmishra.com/) ).

---

### Suggested Hashtags

#DMIByPravinMishra #AgenticAI #ClaudeCode #DevOps #LearningInPublic

---

### Evidence

#### Screenshot 2 — LinkedIn post published

[Screenshot 48](screenshots/Screenshot_048.png)


---

### Submission Field

LinkedIn Post Content (copy-paste here):

Agentic AI in DevOps: Trust Nothing. Verify Everything.


For more than four hours last week. I was sure my safety hook was blocking destructive commands in Claude Code. It wasn’t. It had been failing on every single tool call the entire time, and Claude Code though helpful, obedient, terrifying Claude Code — had been quietly continuing anyway.

The hook existed. It was executable. It was registered in settings.json at the right lifecycle event with the right matcher. When Claude Code started my session, it dutifully invoked the script on every prompt. And the script errored out immediately, because jq wasn't installed on my system.[A different one anyway] Claude Code caught the non-zero exit code, logged a friendly PreToolUse:Bash hook error — failed with non-blocking status code, and kept going.


Most times failures are silent by default. No red banner. No fatal error. No abort. Just a system that looks like it’s working from the outside, and isn’t.

This is the discipline gap. It’s not about whether you know what a hook is. It’s about whether, after you write the hook, you tail the log and issue a test command and watch it fire. 
It’s about whether, after you set a permission rule, you actually try to break past it. It’s about whether you cat the file after saving to confirm the edit landed. It's about assuming your guards are broken until you've seen them stop something.

*Agentic AI didn’t make DevOps easier. It made the discipline gap wider — because the tools are now generous enough that shipping fast doesn’t require competence, but shipping safely absolutely does. If you’re not verifying, you’re not doing DevOps. You’re just watching a machine work, and hoping the machine is doing what you meant.*

Hard Lesson: I don’t hope anymore. I tail the log.



---

### LinkedIn Post Link:


https://www.linkedin.com/posts/kanyevictor_dmibypravinmishra-agenticai-claudecode-share-7481621134371635200-PAp4/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADH20d0B8qKJFUAVinR-kBgKcqfOxZov8RA

# Submission Instructions

* Blog must be publicly accessible
* LinkedIn post must be visible (public or unlisted where applicable)
* All required fields must be filled
* Screenshot proofs must be added to GitHub repository
* Do not include sensitive information in blog or post

---

# Completion Checklist

* [x] Blog written with required structure
* [x] Blog includes at least 2–3 Week 2 topics
* [x] Blog is publicly accessible
* [x] LinkedIn post created
* [x] Required P.S. line included
* [x] LinkedIn post content copied in submission field
* [x] Blog link added
* [x] LinkedIn post link added
* [x] Screenshots added to GitHub repo

---

# About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory), focused on real-world execution, systems thinking, and agentic AI workflows.

It helps learners build strong DevOps foundations through hands-on experience.

---

# Resources

* 🌐 DMI Official Website: [https://pravinmishra.com/dmi](https://pravinmishra.com/dmi)
* 🎓 DevOps for Beginners (Udemy): [https://www.udemy.com/course/devops-for-beginners-docker-k8s-cloud-cicd-4-projects/](https://www.udemy.com/course/devops-for-beginners-docker-k8s-cloud-cicd-4-projects/)
* 🎓 Agentic AI DevOps with Claude Code: [https://www.udemy.com/course/ultimate-agentic-ai-devops-with-claude-code/](https://www.udemy.com/course/ultimate-agentic-ai-devops-with-claude-code/)
* 🎓 DevOps with Claude Code: Terraform, EKS, ArgoCD & Helm: [https://www.udemy.com/course/devops-with-claude-code-terraform-eks-argocd-helm/](https://www.udemy.com/course/devops-with-claude-code-terraform-eks-argocd-helm/)
* ▶️ YouTube Playlist: [https://www.youtube.com/playlist?list=PLFeSNDtI4Cho](https://www.youtube.com/playlist?list=PLFeSNDtI4Cho)
* 🔗 Pravin Mishra (LinkedIn): [https://www.linkedin.com/in/pravin-mishra-aws-trainer/](https://www.linkedin.com/in/pravin-mishra-aws-trainer/)
* 🏢 CloudAdvisory (LinkedIn): [https://www.linkedin.com/company/thecloudadvisory/](https://www.linkedin.com/company/thecloudadvisory/)

