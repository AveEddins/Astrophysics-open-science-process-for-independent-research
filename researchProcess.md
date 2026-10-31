

* Plan for future work sessions: finish reading Open Science PDFs from Module 5 Lesson 5 onwards & complete/reorganize bullet point list of notes below, look into Project associated with this repo and learn to use and convert this list to the Kanban board there (just look into GitHub's capabilities in general on free tier), determine what tools for each stage want to use and is appropriate for working in astrophysics specifically, make guides for using tools expect to use (e.g. Codespaces/VS Code/GitHub/git), make templates for things like OSDMP and other things may repeat from project to project to make sure all questions have to answer about how the project will be executed are answered, compare own developed process custom to self and astrophysics and lack of institution, funding grant/agency, etc back against Open Science course and its sources and additional resources cited in the NASA Open Science course (e.g. Opensciency), determine what open science steps could be practiced on this project itself (e.g. applying license?), figure out how below changes for work did previously which was subject to potential institutional, grant, funding institute, collaborator restrictions.

## Literature reading to decide what project to do

* Reference management software: Mendeley, EndNote, Zotero

* Directory of Open Access Journals is searchable index of all open-access journals and articles

* Find articles via Google Scholar, ADS, Scopus, Web of Science, Open Knowledge Map, JSTOR, ResearchGate, ScienceCast

* Only include reputable open results sources in your own work. Determine this by noting if/how the results, code, publications are open source, if the source describes the process well, if/why any data was excluded, if expert(s) in the field are associated with the project

* If you discover an error in open results, contact the owner to get it fixed. Use mechanisms like GitHub Issues where available

* Cite the journal version over a preprint version where possible (cite DOIs over URLs)

## Choose outputs of project

* Possible products could make to consider when starting a project: proposal, data management plan, code of conduct, tutorials, contributor guidelines, raw data, metadata, analysis pipelines, code/notebooks, archives, papers, talks, blogs, videos, social media posts, conference proceedings

* You as the scientist submitting to a conference have the option to preserve your materials submitted to the conference long term (e.g. with Zenodo) even the conference isn't doing that for the submitted materials themselves

* There are non-peer-reviewed publications like Research Notes of the AAS ("a non-peer reviewed, indexed and secure record of works in progress, comments and clarifications, null results, or timely reports of observations in astronomy and astrophysics." - from iop.org). This is an alternative option for sharing open results

* Having an output for each stage of the research process that is shared publicly increases reproducibility of your project. "Ideation: Funded proposals can be shared on Zenodo and open grant platforms such as ogrants.org; Planning: Projects can be pre-registered before they begin; Project Design: Contributor guidelines or a code of conduct can be posted on Zenodo, GitHub, or team web pages; Engagement & Training: Workflow computational notebooks can be shared with the team via GitHub and released on Zenodo; Data Collection: Raw data can be shared through data repositories; Data Wrangling: Code can be shared through software repositories; Preservation: Data management plans for archiving can be posted on Zenodo; Reporting & Publication: open access peer-reviewed articles, technical reports, computational notebooks, code of conduct/contributer guidelines/publication policies, blog posts, short form videos and podcasts, social media posts, conference abstracts and presentations, forum discussions" (NASA Open Science 101 Module 5, Lesson 1)

* If have collaborators, use the CRediT taxonomy to define who is a contributor, how they contribute, and how they will be acknowledged (e.g. author/contributor on GitHub/Zenodo releases)

* Determine how will centralize all research outputs (e.g. centralized repo or GitHub Page)

* “Plan for the release of your data and results from the very beginning of your research…Obtain all permits, approvals, and/or certifications needed to ensure you can share your research products” (NASA Open Science 101 Module 1, Lesson 3)

* Don’t just put out work when successful but with any results. Prevents others from putting in effort to duplicate what you’ve already done

* Consider if there’s any information associated with the project that shouldn’t be shared, if any data needs to be anonymized, if there’s any sensitive information, anything to compromise someone’s privacy, security issues, etc

* Cite everything use and everyone who contributes, including “those who have shared resources, equipment, or knowledge” (Module 1, Lesson 2) (including code packages)

### DOIs

* Figure out when it’s best to apply DOIs, make documentation, etc since “during active research and data exploration, data, code, and ideas may be created and deleted even daily”

* Make sure all project outputs have their own unique identifiers (data/code can have multiple as an identifier can refer to a specific version)

* DOI: “a persistent identifier used to cite data, software, journal articles, presentation slides, blog posts, videos, logos, etc…Each new version of data or software..will need a new DOI…Individuals cannot typically request a DOI themselves, but rather have to go through an authorized organization that can submit the request.” (Module 2, Lesson 2)

    * GitHub documentation: “To make your repositories easier to reference in academic literature, you can create persistent identifiers, also known as Digital Object Identifiers (DOIs). You can use the data archiving tool Zenodo to archive a repository on GitHub and issue a DOI for the archive…Academics can use the data management service Figshare to publicize and cite research material. For more information, see Figshare's support site. ”

### Licenses/Intellectual Property

* Check licenses on content you want to use. If no license on the thing want to use, contact author and get explicit permission. Public domain stuff (facts, discoveries, etc) can be used without attribution, though it's still recommended

* Determine what licenses you want to use for all the outputs you create, which determines how others can use your stuff. Examples are Apache 2.0, MIT license, Creative Commons, BSD. Others can't/shouldn't use your stuff without you giving it a license. One cannot apply a license to ideas, procedures, methods, systems, processes, concepts, principles, or discoveries, only specific works.

* Double check institution's/funding agency's policies on this where applicable

## Determining appropriate tools for producing chosen outputs

* Consider how will document publicly available materials from the project

* Determine the best repository for your materials

* Use your ORCID

### Data

* Determine if you will do maintenance and for how long on released data

* Possible tools: Zenodo (data repository), FigShare

* If you want to use a large dataset that’s already in the cloud, try to use tools already built into that cloud

* Data repo tools and other open science tools: Dataverse, Dryad, Datacite, OSF, Registry of Research Data Repositories, OpenAire

* Put data in repo.

* For chosen data format (e.g. HDF, FITS), see if there’s a tool to check for compliance and readability

* Preferred data formats are community-supported, machine-readable, non-proprietary, modifiable, and open. Also use what’s common in your field.

* Give data a DOI and a license

* Identify and use the metadata standard appropriate for your domain, data repository, etc

### Code

* When starting new code, "define the project scope, its primary features and any limitations, and the intended audience" (Module 4, Lesson 3). What resources will it need to run (personal computer vs HPC)? How will it be managed (who works on it, dev best practices, how shared, how licensed)?

* Name your project something that will make it easy to find for others (e.g. avoid common names that could relate to a lot of other things)

* Choose the programming language according to the goals of the code as well as what potential collaborators would be familiar with and any special hardware/coding environment requirements

* Archiving code makes sure it is accessible for the long term and that others can reproduce your results for a long time following publication. Funding agencies or other organizations may have archiving requirements

* Check with relevant bodies (employer, organization, funding agency) with how make/use open source code

* Check for local laws and regulations that govern the sharing of intellectual property

* Decide before you start coding exactly when you'll make the code public

* Best practice options for archiving code: archive open code with an open access journal article, if in GitHub - archive with Zenodo or similar to get a DOI, other long-term repos like Software Heritage

* Use a software repo used by common package managers like Anaconda, CRAN, and PyPI

* Software can be presented at a conference, published in a journal dedicated to open software, and peer reviewed via e.g. PyOpenSci

* A GitHub repo is not sufficient for archiving code. To archive, one must have a persistent identifier. This also makes your code citable.

* Zenodo can be connected to your GitHub account/repos so that an archived version of the repo is created with each release of your repo

* Include info on how to cite the code to the README or CITATION file (for the latter, use the CFF file format)

* If you don't want to maintain a given software, consider handing off ownership so others can maintain it. If you want to use code that is no longer maintained, contact the owner and volunteer to maintain the code or take ownership

* How will you document the code? How will you test the code? How can others contribute or report bugs?

* Always use version control, even if you're not making it public immediately. Use private modes in this case.

* The README file contains info that orients users new to the project. It helps them understand a project's purpose, provides example use cases, and any other important info. At minimum, it should have the name of the project and 2 to 3 three sentences of what the code is. Also helpful to have in the README, especially if not found elsewhere: a list of dependencies, how to install/run, detailed description of the code, acknowledgements of team members or other support

* The CONTRIBUTING file gives info on how to contribute to a project, like how the contribution process works and what type of contributions are needed. Not strictly necessary but good to have.

* State in the README or contribution guidelines (if have them) if you're maintaining the code and/or accepting contributions or not to have expectations clear either way

* A CODE_OF_CONDUCT file describes rules for participants' behavior to make the project more welcoming to contribute to

* Document via comments in the code. Each function should have comments that briefly state what the function is for, its purpose in plain language. Also use comments to reference others' code you use in your own code via URLs, whether it's a code snippet from Stack Overflow or something more substantial

* Use descriptive variable names

* Documentation and variable names should be such that someone unfamiliar with the coding language should still be able to understand what it's doing

* If you want others to use your code, write a manual for how to use the code

* Document as you go, not afterwards

* Write documentation in the code itself and then use software that writes the manual automatically based off those comments (Sphinx for Python, Doxygen for everything else). Use Markdown for formatting documentation

* Set up your dev environment: IDE/text editor, package manager, virtual environment to manage dependencies and their versions

* Choose an open source license for your code (as allowed by employer, organization, funding agency, etc), which is one approved by the Open Source Initiative (OSI) and compliant with the Open Source Defintion. These licenses allow others to inspect, use, modify, and distribute the code for any purpose. Put the chosen license in a LICENSE file at the top of the repo. It's also good practice to put a one-line version of the license at the top of each file of code with directions to find the full license.

* Use your version control platform's built-in tools for public peer code review

* PyOpenSci and Journal of Open Source Software provide open peer review of scientific packages. Many publications accept papers focused on software as well

* Test your code in various ways, including scientific validation, reproducibility, built-in, and automated

* Write your code to be minimal and such that it doesn't repeat itself

* Use global variables or key managers for credentials. Don't hardcode credentials

* Use well-tested and maintained dependencies as able, and keep a list of what dependencies you're using. If you use an unsupported dependency, assess them for security risks and evaluate alternative packages to use instead

* Dependabot, OWASP are options to help secure your code and its dependencies

* "Create software with tools that provide automated scanning and auditing" (Module 4, Lesson 3)

* Tools for writing code depends on following considerations: tasks, interoperability, end-to-end application vs addressing specific gap, need something to be language/hardware/OS/etc specific? Need it to be open source? Is it malware? Could get into legal trouble for using it?

* Determine if you will do maintenance and for how long on released code

* Possible tools: GitHub/GitLab, BitBucket

* Software repositories (where packages often provided as executibles without the code itself with metadata, documentation, and licensing): Python Package Index, SourceForge, Googlecode/Google Open Source, Software Heritage, Open Source Development Network (OSDN), CRAN for R, Comprehensive Perl Archive Network

* Look to see if relevant code already exists via general search engine, papers, GitHub Code Search, Stack Overflow, etc

* Consider if there’s an existing file format and/or metadata convention you should adopt for a given product

* Computer code is considered a method from the research perspective. Sharing code is practicing open methods, allowing others to reproduce what you do

* Put code as it's being developed in public repo as long as no reason to keep it private for some period of time

* Put results (code output) in repo

* Give code a DOI and a license

* Make it clear through appropriate licensing, documentation, and contributing guidelines if you don’t want to maintain certain code past a certain time

* Give descriptions when post code and installation instructions when post code. List software dependencies for code, use continuous integration (e.g. GitHub Actions), and release a Docker image if applicable

* Sharing methodology isn’t just sharing the code used to obtain the results but how that code was used. Code can evolve past a given result set while still producing the same results

* Software repo contains actively developed code, software archives are for stable and thoroughly tested software releases

* https://swcarpentry.github.io/git-novice/

* Create README file, which explains what the software does, how to install/use it, what dependencies the code has, and usage examples for people who have limited prior knowledge

* Use security tools to check open source software you want to use for vulnerabilities (e.g. Open Worldwide Application Security Project). Can use for own code publishing as well?. Only use open source software that is actively being developed and is from reputable sources. Consider if a software tool you want to use can expose closed/secure data.

* If using open source code, use the latest stable release where possible, check for issues/bugs (test a lot and often, read release notes, check issue trackers and developer forums), and determine the origin of version you want to use

* If you need help with a piece of open source software, seek help publicly, not privately, as possible to maintain open science

* Cite open code when it played a critical part in your research and/or provided something novel. A code snippet from Stack Overflow often does not count.

* If open code directly impacts scientific results, it requires a detailed description such as with numerical modeling/simulation or automated analysis like image processing. If publishing in a journal, review what their policies on citing software is. Also check the license of the code itself

### Preprint

* OSF provides a service to search multiple preprint servers (for determining appropriate preprint server to post to if planning to write one)

* Consider preprints to “allow for swifter feedback on conclusions drawn from data once it is collected” (Module 1, Lesson 2). This also allows for partial work to be findable even if the project did not get completed.

* Do I want to include preprints in my process? Any rules for posting on arXiv that prevents independent research?

### Journal articles

* Papers should be in open access journals

* Directory of Open Access Journals is searchable index of all open-access journals and articles

* Anywhere worth considering publishing as independent researcher (i.e. no funding?)

### Talks, blog posts, etc

* Put talk slides, lectures, blog posts, etc in repo

* Where can these be published?

## Pre-Registering (not sure where this should go in pre-study work chronologically)

* Consider pre-registering, “where researchers document their research plan at the start of a study” to get “feedback from various collaborators and stakeholders…before data collection begins” (Module 1, Lesson 2)

* Pre-registration is most common prior to collection of data for a project or prior to analysis of an existing or openly available dataset

## OSDMP (not sure where this should go in pre-study work chronologically)

* Can create own template for OSDMP to update as improve at doing this

* Make an open science and data management plan (OSDMP) before starting a project. It describes how resources are to be used, the products that will be created, how those products will be shared with other researchers and the public

* An OSDMP should include sections on data management, software management, publication sharing, as well as any other outputs anticipate (reference related funding agency guidelines as can find, NASA SMD + NSF, how keep up if they update requirements?)

* DMP resources: DMPTool, ARGOS

* Refer to Module 2, Lesson 2 for a list of things typically included in an OSDMP

* Steps for a software management plan: what - description of management, preservation, and release of software or code; when - the schedule for software/code archiving and sharing; where - location where software/code will be shared and archived over the long term; how - enable reuse of software/code through assigning a DOI, license, contribution guideline, etc; who - roles and responsibilities of the team members

## Confirm project plan conforms to open science principles

* FAIR principles: https://www.go-fair.org/fair-principles/

* https://fairsharing.org/, https://www.rd-alliance.org/ have FAIR self-assessment tools

# Sources

NASA Open Science 101 course, as accessed Dec 14th 2025