* Plan for future work sessions: finish reading Open Science PDFs from Module 4 Lesson 3 onwards & complete/reorganize bullet point list of notes below, determine what tools for each stage want to use and is appropriate for working in astrophysics specifically, make guides for using tools expect to use (e.g. Codespaces/VS Code/GitHub/git), make templates for things like OSDMP and other things may repeat from project to project to make sure all questions have to answer about how the project will be executed are answered, compare own developed process custom to self and astrophysics and lack of institution, funding grant/agency, etc back against Open Science course and its sources and additional resources (e.g. Opensciency), determine what open science steps could be practiced on this project itself (e.g. applying license?), figure out how below changes for work did previously which was subject to potential institutional, grant, funding institute, collaborator restrictions.

* Notes derived from NASA Open Science course, as accessed Dec 14th 2025:

# Pre-Study Work

## Literature Reading

* Reference management software: Mendeley, EndNote, Zotero

## Choose outputs of project

* Possible products could make to consider when starting a project: proposal, data management plan, code of conduct, tutorials, contributor guidelines, raw data, metadata, analysis pipelines, code/notebooks, archives, papers, talks, blogs, videos, social media posts, conference proceedings

* “Plan for the release of your data and results from the very beginning of your research…Obtain all permits, approvals, and/or certifications needed to ensure you can share your research products” (Module 1, Lesson 3)

* Determine if you will do maintenance and for how long on released code/data

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

* OSF provides a service to search multiple preprint servers (for determining appropriate preprint server to post to if planning to write one)

* Use your ORCID

* If you want to use a large dataset that’s already in the cloud, try to use tools already built into that cloud

* Directory of Open Access Journals is searchable index of all open-access journals and articles

* Possible tools: GitHub/GitLab, Zenodo (data repository), FigShare, BitBucket

* Data repo tools and other open science tools: Dataverse, Dryad, Datacite, OSF, Registry of Research Data Repositories, OpenAire

* Look to see if relevant code already exists via general search engine, papers, GitHub Code Search, Stack Overflow, etc

* Tools for writing code depends on following considerations: tasks, interoperability, end-to-end application vs addressing specific gap, need something to be language/hardware/OS/etc specific? Need it to be open source? Is it malware? Could get into legal trouble for using it?

* Software repositories (where packages often provided as executibles without the code itself with metadata, documentation, and licensing): Python Package Index, SourceForge, Googlecode/Google Open Source, Software Heritage, Open Source Development Network (OSDN), CRAN for R, Comprehensive Perl Archive Network

## Pre-Registering (not sure where this should go in pre-study work chronologically)

* Consider pre-registering, “where researchers document their research plan at the start of a study” to get “feedback from various collaborators and stakeholders…before data collection begins” (Module 1, Lesson 2)

* Pre-registration is most common prior to collection of data for a project or prior to analysis of an existing or openly available dataset

## OSDMP (not sure where this should go in pre-study work chronologically)

* Can create own template for OSDMP to update as improve at doing this

* Make an open science and data management plan (OSDMP) before starting a project. It describes how resources are to be used, the products that will be created, how those products will be shared with other researchers and the public

* An OSDMP should include sections on data management, software management, publication sharing, as well as any other outputs anticipate (reference related funding agency guidelines as can find, NASA SMD + NSF, how keep up if they update requirements?)

* DMP resources: DMPTool, ARGOS

* Refer to Module 2, Lesson 2 for a list of things typically included in an OSDMP

## Confirm project plan conforms to open science principles

* FAIR principles: https://www.go-fair.org/fair-principles/

* https://fairsharing.org/, https://www.rd-alliance.org/ have FAIR self-assessment tools

# Project Outputs (consider collapsing this section into the previous Pre-Study Work as some points here still pertain to selecting tools, file formats, licensing, etc - before the work starts, you make the plan, then after the work starts, you just follow the plan)

## Data

* Consider if there’s an existing file format and/or metadata convention you should adopt for a given product

* For chosen data format (e.g. HDF, FITS), see if there’s a tool to check for compliance and readability

* Put data in repo.

* Preferred data formats are community-supported, machine-readable, non-proprietary, modifiable, and open. Also use what’s common in your field.

* Give data a DOI and a license

* Identify and use the metadata standard appropriate for your domain, data repository, etc

## Code

* Computer code is considered a method from the research perspective. Sharing code is practicing open methods, allowing others to reproduce what you do

* Put code as it's being developed in public repo as long as no reason to keep it private for some period of time

* Put results in repo

* Give code a DOI and a license

* Make it clear through appropriate licensing, documentation, and contributing guidelines if you don’t want to maintain certain code past a certain time

* Give descriptions when post data/code and installation instructions when post code. List software dependencies for code, use continuous integration (e.g. GitHub Actions), and release a Docker image if applicable

* Sharing methodology isn’t just sharing the code used to obtain the results but how that code was used. Code can evolve past a given result set while still producing the same results

* Software repo contains actively developed code, software archives are for stable and thoroughly tested software releases

* https://swcarpentry.github.io/git-novice/

* Create README file, which explains what the software does, how to install/use it, what dependencies the code has, and usage examples for people who have limited prior knowledge

* Use security tools to check open source software you want to use for vulnerabilities (e.g. Open Worldwide Application Security Project). Can use for own code publishing as well?. Only use open source software that is actively being developed and is from reputable sources. Consider if a software tool you want to use can expose closed/secure data.

* If using open source code, use the latest stable release where possible, check for issues/bugs (test a lot and often, read release notes, check issue trackers and developer forums), and determine the origin of version you want to use

* If you need help with a piece of open source software, seek help publicly, not privately, as possible to maintain open science

* Cite open code when it played a critical part in your research and/or provided something novel. A code snippet from Stack Overflow often does not count.

* If open code directly impacts scientific results, it requires a detailed description such as with numerical modeling/simulation or automated analysis like image processing. If publishing in a journal, review what their policies on citing software is. Also check the license of the code itself

## Preprint

* Consider preprints to “allow for swifter feedback on conclusions drawn from data once it is collected” (Module 1, Lesson 2). This also allows for partial work to be findable even if the project did not get completed.

* Do I want to include preprints in my process? Any rules for posting on arXiv that prevents independent research?

## Journal articles

* Papers should be in open access journals

* Anywhere worth considering publishing as independent researcher (i.e. no funding?)

## Talks, blog posts, etc

* Put talk slides, lectures, blog posts, etc in repo

* Where can these be published?