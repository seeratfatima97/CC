# Fatima Jinnah Women University, Rawalpindi

## CC Assignment_1
### Git, Gitea, GitHub, Git LFS, and GitHub Pages

**Submitted By:** Seerat Fatima  
**Reg. No:** fa24b1-se-020  
**Subject:** Cloud Computing  
**Course Code:** -  
**GitHub username:** seeratfatima97  
**Session:** 2024–2028  
**Section:** B  
**Submitted To:** Sir Waqas Saleem  

**Department of Software Engineering**  
**Semester V**

---

# Task 1: Docker Compose, Gitea, and PostgreSQL

This task sets up a self-hosted local Git service using Gitea and PostgreSQL via Docker Compose. The container environment and network parameters are verified through standard terminal commands. A local Git repository is initialized, configured with student credentials, and staged with a README file. Finally, the initial commit is pushed to the Gitea server and verified through the Gitea web dashboard.

## Sub-step 1.1: Docker Compose Service Deployment

Executes `docker compose up -d` to launch Gitea and PostgreSQL containers in detached mode, followed by container status and IP network verification.

**Screenshot**  
*[Insert Figure 1.1 screenshot here]*

*Figure 1.1: Docker Compose Service Deployment and Network Verification for Gitea.*

## Sub-step 1.2: Repository Initialization and Initial Push

Configures global Git user credentials, links the local Gitea remote URL, creates `README.md`, and pushes the initial commit to the `main` branch.

**Screenshot**  
*[Insert Figure 1.2 screenshot here]*

*Figure 1.2: Git Repository Initialization and Initial Push to Local Gitea Server.*

## Sub-step 1.3: Gitea Web Interface Verification

Displays the Gitea web dashboard showing the uploaded `README.md` file and commit history for the `Assignment01` repository.

**Screenshot**  
*[Insert Figure 1.3 screenshot here]*

*Figure 1.3: Verification of Repository Contents on Local Gitea Web Interface.*

---

# Task 2: Multi-Remote Synchronization with GitHub

This task demonstrates configuring multi-remote synchronization between local Gitea and remote GitHub repositories. A secondary remote endpoint pointing to GitHub is added to the local Git repository alongside Gitea. The codebase and commit history are pushed to GitHub using Personal Access Token authentication. The successful synchronization is then confirmed directly on the public GitHub repository dashboard.

## Sub-step 2.1: Adding Secondary GitHub Remote

Adds GitHub as a secondary remote target using `git remote add` and verifies configured fetch/push URLs with `git remote -v`.

**Screenshot**  
*[Insert Figure 2.1 screenshot here]*

*Figure 2.1: Configuring Dual Remotes for Gitea and GitHub.*

## Sub-step 2.2: Pushing Codebase to GitHub

Executes `git push -u github main` with GitHub user credentials to upload the main branch commit history to the remote platform.

**Screenshot**  
*[Insert Figure 2.2 screenshot here]*

*Figure 2.2: Pushing Repository Code Base to Remote GitHub Repository.*

## Sub-step 2.3: GitHub Dashboard Verification

Displays the `seeratfatima97/Assignment01` GitHub repository interface, verifying that `README.md` and commit details match the local repository.

**Screenshot**  
*[Insert Figure 2.3 screenshot here]*

*Figure 2.3: GitHub Repository Dashboard Confirming Multi-Remote Sync.*

---

# Task 3: Git Large File Storage (Git LFS)

This task covers tracking and managing large binary files in Git using Git Large File Storage (LFS). Git LFS is initialized locally to automatically track binary files matching the `*.bin` pattern. Three dummy binary files of approximately 100 MB each are created using terminal commands and staged alongside `.gitattributes`. Finally, the LFS pointer objects and binary payloads are pushed successfully to the GitHub remote repository.

## Sub-step 3.1: Initializing Git LFS and File Tracking

Runs `git lfs install` to initialize the extension and configures automatic tracking for `*.bin` files inside `.gitattributes`.

**Screenshot**  
*[Insert Figure 3.1 screenshot here]*

*Figure 3.1: Initializing Git LFS and Setting Up File Tracking.*

## Sub-step 3.2: Binary File Generation and LFS Staging

Generates three large binary files using the `truncate` command and lists tracked LFS files using `git lfs ls-files --size`.

**Screenshot**  
*[Insert Figure 3.2 screenshot here]*

*Figure 3.2: Generating Dummy Binary Files and Inspecting LFS Tracking.*

## Sub-step 3.3: Pushing LFS Objects to Remote Repository

Commits the large binary files and uploads the pointer references and payload data to GitHub using `git push github main`.

**Screenshot**  
*[Insert Figure 3.3 screenshot here]*

*Figure 3.3: Committing and Pushing Git LFS Pointer Objects to GitHub.*

---

# Task 4: Deploying a Portfolio Website with GitHub Pages

This task involves building and deploying a custom personal portfolio website hosted live on GitHub Pages. The HTML layout, CSS styling, media assets, and CV file are pushed to the `<username>.github.io` repository. GitHub Pages build settings are enabled under repository settings targeting the `main` branch root folder. The live website deployment is then verified directly in the browser via the public `github.io` URL.

## Sub-step 4.1: Repository Structure and Source Uploads

Displays the root directory of `seeratfatima97.github.io` on GitHub, confirming the presence of required source files (`index.html`, `style.css`), image assets, and CV PDF.

**Screenshot**  
*[Insert Figure 4.1 screenshot here]*

*Figure 4.1: GitHub Portfolio Repository File Structure Overview.*

## Sub-step 4.2: GitHub Pages Build Configuration

Configures GitHub Pages settings to deploy from the `main` branch root directory and verifies the successful live build banner.

**Screenshot**  
*[Insert Figure 4.2 screenshot here]*

*Figure 4.2: GitHub Pages Build Configuration and Deployment Status.*

## Sub-step 4.3: Verification of Live Portfolio Site

Confirms the fully rendered live portfolio website in the browser at [https://seeratfatima97.github.io/](https://seeratfatima97.github.io/), displaying navigation links, hero section, personal profile photo, and responsive UI layout.

**Screenshot**  
*[Insert Figure 4.3 screenshot here]*

*Figure 4.3: Verification of Live Portfolio Web Page on Browser.*

---

**---------- THE END ----------**
