# Building Android applications with Maven and IntelliJ

A starter project for Android based on Maven for IntelliJ IDEA.

I picked the code from this [great blog post by Christian Bauer](http://4thline.org/articles/Building%20Android%20applications%20with%20Maven%20and%20IntelliJ.html) describing the process to build an Android app with Maven and IntelliJ IDEA. The post is a bit outdated now but the project structure is very clean to start from scratch.

With latest version of IntelliJ IDEA, the build process is even simpler than what's described in the blog post:

1. Clone the repository
2. Open IntelliJ
3. Click on "Create New Project"
4. Check "Create project from existing sources" then "Next"
5. Browse to the directory of the cloned repo
6. **Important:** Unmark all source files (otherwise it's going to change the build properties later) then "Next" then "Finish"
7. Your project is set up, now click on the tab "Maven Projects"
8. Click on the refresh icon "Reimport All Maven Projects", this will automatically build your project
9. Run & Code!
