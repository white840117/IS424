Purpose
This assignment gives you practical experience collaborating with Git and GitHub as a two-person team using Visual Studio Code (VSCode). You will practice the normal collaboration cycle, use a branch, merge work, and intentionally create and resolve one conflict.
The goal is not to create a complicated Git history. The goal is to show that both partners can work safely in the same repository and understand what to do when changes collide.
Important - VSCode Only: Complete all Git actions for this assignment through the VSCode interface demonstrated in class, including initializing/cloning, staging, committing, pulling/syncing, pushing/publishing, creating/switching branches, merging, and resolving conflicts. Do not use Terminal or typed Git commands.
Before You Start
•	Download and unzip the A2 Starter Code from Canvas. It contains index.html and README.md.
•	Choose Student A and Student B. Both students must complete hands-on Git work.
•	Use one shared GitHub repository for the pair. Do not use your term-project repository.
•	Open the project/repository in VSCode for all Git work.
•	Before starting a new step, read the full step together so you know who should sync/pull, edit, commit, and push.
•	Do not place private or sensitive information in the repository.
Participation rule: Each student must make at least 3 meaningful commits. Tiny duplicate commits made only to reach the minimum do not count.
Part 1 - Set Up the Shared Repository (8 points)
1.	Student A opens the starter project folder in VSCode.
2.	Using VSCode's Source Control tools, Student A initializes the folder as a Git repository, commits the starter files, and publishes/connects the repository to GitHub using the method demonstrated in class.
3.	Student A gives Student B collaborator access using the class procedure. Student B accepts the invitation before continuing.
4.	Student B uses VSCode to clone/open the shared repository on their computer.
5.	Both students confirm that index.html and README.md are present and that both can access the shared repository.
6.	Student A edits README.md in VSCode and adds their name and GitHub username. In Source Control, Student A stages the change, enters a clear commit message, commits, and pushes/syncs the change.
7.	Student B pulls/syncs the latest version in VSCode before editing. Student B then adds their name and GitHub username to README.md, commits through Source Control, and pushes/syncs.
8.	Student A pulls/syncs once more and confirms the completed README.md appears locally.
Part 2 - Practice Pull, Commit, and Push (8 points)
Complete these steps in order. The purpose is to practice the normal shared-repository workflow without a conflict.
•	Student A: In VSCode, update the paragraph under Project Status in index.html with one new sentence. Stage the file in Source Control, commit with a clear message, and push/sync to main.
•	Student B: Before editing, pull/sync the latest version in VSCode. Then update the About the Team section. Stage, commit, and push/sync the change.
•	Student A: Pull/sync again and verify that Student B's change appears in the local file.
•	Together: Use the repository/history view demonstrated in class to confirm that commits from both students are visible.
Part 3 - Branch and Merge (8 points)
9.	Student B pulls/syncs the latest main branch in VSCode.
10.	Using VSCode's branch controls, Student B creates and switches to a new branch named feature-about.
11.	On feature-about, improve the About the Team section by adding at least two meaningful lines or elements.
12.	Stage and commit the branch change using VSCode Source Control.
13.	Publish/push the feature-about branch through VSCode.
14.	Merge feature-about into main using the VSCode branch/merge workflow demonstrated in class.
15.	Student A pulls/syncs main and confirms that the merged change appears locally.
16.	Complete the Branch Work section in README.md.
Part 4 - Intentionally Create and Resolve a Conflict (10 points)
Follow this sequence carefully. For this part only, Student B will intentionally edit an older local version before bringing in Student A's new change. This creates a controlled conflict for practice.
17.	Both students first pull/sync main in VSCode so they begin from the same version.
18.	Student A changes <h2>Original Decision</h2> to <h2>Student A recommends SaaS</h2>. Student A stages, commits, and pushes/syncs the change through VSCode.
19.	Student B does NOT pull/sync Student A's new commit yet. Student B changes that same heading locally to <h2>Student B recommends Hybrid</h2> and commits the change through VSCode.
20.	Student B now tries to push/sync. VSCode should indicate that the remote repository contains changes that Student B does not yet have.
21.	Student B brings in the latest remote changes using the VSCode workflow demonstrated in class. Because both students changed the same line differently, VSCode should identify a merge conflict.
22.	Student B resolves the conflict using VSCode's conflict-resolution interface (for example, the Merge Editor or the conflict actions shown in class). The final heading must be: <h2>Final team decision: Evaluate SaaS and hybrid options</h2>.
23.	Student B confirms that no conflict markers remain, stages the resolved file, commits the resolution, and pushes/syncs through VSCode.
24.	Student A pulls/syncs the final version and confirms that the resolved heading appears correctly.
Part 5 - Explain What Happened (6 points)
Together, complete the Conflict Reflection section in README.md:
•	Why did the intentional conflict happen?
•	How did you resolve it in VSCode?
•	Give two practices that can reduce unnecessary Git conflicts on a real team.
Final Check
•	The repository contains index.html and README.md.
•	Both students appear in the repository's commit history.
•	Each student has at least 3 meaningful commits.
•	feature-about was created and merged into main.
•	The intentional conflict was resolved and no Git conflict markers remain in index.html.
•	README.md is complete.
•	All Git actions were completed through VSCode; no Terminal commands were required.
Submission
Each student must submit individually in Canvas, even though you worked as a pair. Submit the shared GitHub repository URL, your partner's name, and your own GitHub username. Both students may submit the same repository URL. Individual participation will be verified using the repository history.
