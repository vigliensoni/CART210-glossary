## Version Control

Version Control Systems (VCS) are a type of [software](#software.md) used in programming. Their purpose is to help manage code during the development of a project so as to ensure a proper workflow and effort coordination in the development team.

Namely, it keeps track of every change made in the project and by whom, it allows the possibility to protect certain versions of the code from being edited directly and lets the code updates get reviewed by at least another person before being merged into the rest of. It's also useful when trying to find bugs in the code that appear in later versions by comparing it to older ones.[^Atlassian-VCS]

Version control systems are split between two distinct categories: Centralized Version Control Systems (CVCS) and Distributed Version Control Systems (DVCS). The main difference between the two is how the file repository is managed, CVCS using a unique centralized server as its name implies, while DVCS have each user keep a local repository on their computers.[^Zolkifli-VCS]

DVCS are the most commonly used, namely because it allows users to work without network connection, altough uploading and sharing the files requires being online, and the decentralized infrastructure allows for remote work from many different locations. Most systems in this category are free and [open-source](#opensource.md).

Alternatively, CVCS require a constant connection to the server to have access to the project files, and the single connection points means that, should server access be unavailable, work cannot be done and it is possible for changes to be lost. However, it does save space on the programmer's local machine considering they don't need to copy the full code on it, which is useful for complex and heavy projects.[^Gitlab-VCS]

Some examples of version control systems include:
- [Git](#git.md) - DVCS
- Bitbucket - DVCS
- Mercurial - DVCS
- Subversion - CVCS
- Perforce - CVCS

Version control systems are also known as Source Code Management (SCM) or Revision Control Systems (RCS).

![critical-one-page-collage](../images/version-control-dudemaine.png)[^Carreon-img-VCS]

[^Atlassian-VCS]: Atlassian. "What Is Version Control | Atlassian Git Tutorial." Atlassian. Accessed January 28, 2024. [https://www.atlassian.com/git/tutorials/what-is-version-control](https://www.atlassian.com/git/tutorials/what-is-version-control)

[^Gitlab-VCS]: Gitlab. "What Is A Centralized Version Control System." Gitlab. Accessed January 28, 2024. [https://about.gitlab.com/topics/version-control/what-is-centralized-version-control-system/](https://about.gitlab.com/topics/version-control/what-is-centralized-version-control-system/)

[^Zolkifli-VCS]: Zolkifli, Nazatul Nurlisa, Amir Ngah, and Aziz Deraman. 2018. "Version Control System: A Review." *3rd International Conference on Computer Science and Computational Intelligence*: 408-415. [https://www.sciencedirect.com/science/article/pii/S1877050918314819](https://www.sciencedirect.com/science/article/pii/S1877050918314819)

[^Carreon-img-VCS]: Carreon, Hector, and Fevrier Valdez. 2022. "A new mycorrhized tree optimization nature-inspired algorithm." Scientific Figure on ResearchGate. Accessed February 9, 2024. [https://www.researchgate.net/figure/Symbiosis-between-tree-roots-and-fungi_fig1_358897496](https://www.researchgate.net/figure/Symbiosis-between-tree-roots-and-fungi_fig1_358897496)
