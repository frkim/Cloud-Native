# Azure DevOps and GitHub Resources

This page gathers a lot of resources to start with **[Azure DevOps](https://azure.microsoft.com/en-us/products/devops/)** and **[Github](https://www.github.com)**

## DevOps Overview

DevOps combines development (Dev) and operations (Ops) to unite people, process, and technology in application planning, development, delivery, and operations. DevOps enables coordination and collaboration between formerly siloed roles like development, IT operations, quality engineering, and security.

Teams adopt DevOps culture, practices, and tools to increase confidence in the applications they build, respond better to customer needs, and achieve business goals faster. DevOps helps teams continually provide value to customers by producing better, more reliable products.

![What is DevOps](./media/devops-lifecycle.png)

[Source: What is DevOps?](https://learn.microsoft.com/en-us/devops/what-is-devops)

### Azure DevOps

Azure DevOps supports a collaborative culture and set of processes that bring together developers, project managers, and contributors to develop software. It allows organizations to create and improve products at a faster pace than they can with traditional software development approaches.

### GitHub

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

GitHub Actions goes beyond just DevOps and lets you run workflows when other events happen in your repository. For example, you can run a workflow to automatically add the appropriate labels whenever someone creates a new issue in your repository.

### Azure DevOps or GitHub

How to choose between Azure DevOps and GitHub?
![AzDO GH How to choose](./media/AzDO-GH-HowToChoose.png)

### Features comparison by solutions

| DevOps Phase | Area | Azure DevOps | GitHub | Comments |
|:---:|:---:|:---:|:---:|:---:|
| Plan | Plan & Track | Boards | Issues & Projects | Azure Boards provides a rich set of capabilities for project management including native support for Agile, Scrum, and Kanban processes, calendar views, configurable dashboards, and integrated tasks planning and reporting. Whereas GitHub provides Projects an adaptable, flexible spreadsheet for planning and tracking work that integrates issues and pull requests to help you work effectively. Key Gaps: Hierarchical Relationships, Plan in Sprints, Saved Issue Queries. For Sprint Planning use Azure Boards integrated with GitHub. For Basic Planning: GitHub Issues & Projects |
| Collaborate | Group Think |  | Discussions | Organize conversations into a threaded format.  Only available in GitHub.  |
| Develop | Source Control Management | Repos | Repos | Use GitHub to get value   today from Advanced Security features, Innersource, developer familiarity w/   GitHub.  |
|  | Advanced Coding | (Azure DevBox) | CodeSpaces + Copilot | Available natively only in GitHub |
|  | Security Coding | (3rd party with extensions) | Advanced Security | Available natively in   GitHub. Azure DevOps needs 3rd party extensions but there is a coming feature   " GitHub Advanced Security for Azure DevOps". This shifts security   to the left! |
| Deliver | Packages | Artifacts | Packages | GitHub Packages if you are using GitHub Repos. Otherwise, use Azure   Artifacts |
|  | CI/CD | Pipelines | Actions | Both Azure DevOps and   GitHub Action provides rich capabilities to runs your CI/CD pipelines |
|  | Worklow Automation |  | Actions | GitHub Actions can be used for a lot more than just CI/CD and performs   other workflows. |
|  | Manual testing | Test Plans |  | Azure Test Plans is only   available in Azure DevOps. |
| Operate,   Monitor & Learn | Dashboard &   Reporting | Dashboard &   Reporting | Insights | Azure DevOps provides customizable dashboard with widgets and GitHub   insights gives valuable information  |
| All | Mobile Access |  | Mobile App | First class mobile   experience for iOS and Android. Only available for GitHub. |

## Azure DevOps + GitHub

There is an another alternative by connecting Azure Boards with GitHub repositories, you enable linking between GitHub commits, pull requests, and issues to work items. You can use GitHub for software development while using Azure Boards to plan and track your work.

![DevSecOps](./media/devsecops.png)

## Github Architecture Sample

![GitHub Architecture](./media/github-architecture.png)
[Source: DevSecOps with GitHub Security](https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/devsecops-in-github)

## Links

This sections lists a lot of links to start with **[Azure DevOps](https://azure.microsoft.com/en-us/products/devops/)** and **[Github](https://www.github.com)**

## Tutorials / Workshops

### DevOps tutorials

- [What is DevOps?](https://learn.microsoft.com/en-us/devops/what-is-devops)
- [DevOps Resource Center](https://learn.microsoft.com/en-us/devops/)
- [DevOps Consideration and Landing Zone](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/devops-principles-and-practices)
- [DevOps Dojo](https://devblogs.microsoft.com/devops/intro-of-devops-dojo/)
- [The DevOps Best Practices List](https://gist.github.com/jpswade/4135841363e72ece8086146bd7bb5d91)
- [The DevOps Awesome List](https://github.com/wmariuss/awesome-devops)

### GitHub Tutorials

#### GitHub Learning Pathways:

- [GitHub Learning Pathways Overview](https://resources.github.com/learn/pathways/)
- [Automate to innovate with GitHub Actions](https://resources.github.com/learn/pathways/automation/)
- [Secure at every step with GitHub Advanced Security](https://resources.github.com/learn/pathways/security/)
- [Smooth scaling with governance](https://resources.github.com/learn/pathways/administration-governance/)

#### Other Github Learning resources:

- [GitHub Learning Lab · GitHub Marketplace](https://github.com/marketplace/github-learning-lab)
- [Microsoft Learn for GitHub](https://learn.microsoft.com/en-us/training/github/)
- [GitHub Skills](https://skills.github.com/)
- [GitHub Documentation](https://docs.github.com/en)

### Azure DevOps Tutorials

- [Azure DevOps on Microsoft Learn](https://learn.microsoft.com/en-us/training/browse/?expanded=azure&products=azure-devops)
- [Azure DevOps Labs](https://www.azuredevopslabs.com/)

### DevSecOps tutorials

- [Microsoft Defender for DevOps - the benefits and features](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-devops-introduction)

### Hand's on Labs / MicroHacks

- [What The Hack – Azure DevOps (microsoft.github.io)](https://microsoft.github.io/WhatTheHack/010-AzureDevOps/)
- [What The Hack – DevOps with GitHub (microsoft.github.io)](https://microsoft.github.io/WhatTheHack/031-DevOpsWithGitHub/)

## Videos

- [DevOps on Azure](https://www.youtube.com/@AzureDevOps)
- [Azure DevOps Tutorial For Beginners](https://www.youtube.com/playlist?list=PLaFzfwmPR7_Ifxq-udm66fhReFeGOe2x_)
- [Houssem Dellai - Azure DevOps CI/CD](https://www.youtube.com/playlist?list=PLpbcUe4chE7_J_la3FlruUfAN1ec7H_bR)
- [Houssem Dellai - Learn GitHub Actions](https://www.youtube.com/playlist?list=PLpbcUe4chE7-6zbykHL9ASi3zlP5PHROo)

## Blogs

- [Azure DevOps Blog Updates](https://devblogs.microsoft.com/devops/category/community/)
- [GitHub Blog](https://github.blog/)

## eBooks

- [Empowering developers to build secure software faster with GitHub Advanced Security](https://resources.github.com/security/secure-software-faster-ebook/)
- [How static application security testing (SAST) can help you fix bugs at the speed of development?](https://resources.github.com/security/sast/?submitted=true)
- [Azure DevOps Explained (published by Packt)](https://github.com/PacktPublishing/Learning-Azure-DevOps---B16392)

## Migration Tools

### DevOps

- [Migrate and integrate work tracking data in Azure Boards](https://learn.microsoft.com/en-us/azure/devops/boards/extensions/migrate-integrate?view=azure-devops)
- [Migration Tools for Azure DevOps - Naked Agility](https://marketplace.visualstudio.com/items?itemName=nkdagility.vsts-sync-migration)
- [OpsHub Azure DevOps Migrator](https://www.opshub.com/products/opshub-azure-devops-migrator/)
- [Migrating Git Source Code](https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository)
- [From classic to yaml pipeline](https://learn.microsoft.com/en-us/azure/devops/pipelines/migrate/from-classic-pipelines?view=azure-devops#export-your-classic-pipeline)
- [Convert Azure Pipelines to YAML in one click](https://dev.to/n3wt0n/classic-to-yaml-new-export-azure-pipelines-feature-26ca)

### GitHub

- [GitHub Actions Importer](https://github.com/github/gh-actions-importer)
- [GitHub Enterprise Importer CLI - Octoshift](https://github.com/github/gh-gei)
