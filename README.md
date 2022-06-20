# Easy R Tutorials with Dev Containers

This is the repository supporting the presentation "Easy R Tutorials with Dev Containers".

* Presenter: [David Smith](https://www.linkedin.com/in/dmsmith/), Cloud Advocate at Microsoft
* Presented at: [UseR!2022, June 21, 2022](https://user2022.r-project.org/program/talks/#session-10-building-the-r-community-1) 
* Presentation slides: PDF
* Presentation recording: (pending)

You can recreate the demos in the talk using the steps outlined below.

## Dev Containers in GitHub Codepaces

If you have access to GitHub CodeSpaces, click the green "Code <>" button at the top right on this repository page, and then select "Create codespace on main". (GitHub CodeSpaces is available with [GitHub Enterprise](https://github.com/enterprise) and [GitHub Education](https://education.github.com/).)

Once the Dev Container has started, browse to the file [intro-regression-R-tidymodels/solution/Challenge-regression.ipynb](intro-regression-R-tidymodels/solution/Challenge-regression.ipynb). This will launch a Jupyter Notebook.

## Dev Containers on a local machine

You can use Linux, Mac or Windows (including Windows Subsystem for Linux). Just make sure your machine has the following necessary software installed:
- [Visual Studio Code](https://code.visualstudio.com?WT.mc_id=academic-55190-ornella), and the [Remote-Containers extension](https://code.visualstudio.com/docs/remote/containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Git](https://git-scm.com/downloads)

**Note**: you do not need to install R, Python, or anything like that. These will all be provided by the Dev Container. 

Copy the contents of this repository to your machine. An easy way to do this is with the command: 
```
git clone https://github.com/revodavid/devcontainers-r
```

Launch Visual Studio Code, and open the directory containing this downloaded repository. An easy way to do this is:
```
cd devcontainers-r
code .
```

Open the VS Code command palette (Control-Shift-P) and run the command **Remote-Containers: Reopen in Container**. (You can also use the pop-up dialog that automatically prompts you do this.) The first time you try this, you will need to wait a few minutes for the container to build. After this first time, startup will be near-instantaneous.

Now, browse to the file [intro-regression-R-tidymodels/solution/Challenge-regression.ipynb](intro-regression-R-tidymodels/solution/Challenge-regression.ipynb). Work through the Jupyter Notebook.

# Resources and Links

* [Dev Containers](https://containers.dev/) - Overview and specification
* [Dev Containers in Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) - Remote-Containers extension 
* [Visual Studio Code](https://code.visualstudio.com/) - Free editor available for Windows, Mac and Linux
* [GitHub Codespaces](https://github.com/features/codespaces) - Available with GitHub Enterprise and GitHub Education
* [Microsoft Workshop Library](https://github.com/microsoft/workshop-library
) - The source of the workshop "Introduction to regression models by using R and Tidymodels" included in this presentation

# Feedback

If you have any comments or suggestions about this presentation, please leave an issue in this repository.