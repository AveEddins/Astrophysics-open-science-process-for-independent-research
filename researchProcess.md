*Porting notes from Google Doc*

*Plan for future work sessions: finish reading Open Science PDFs from Module 4 onwards, complete bullet point list of notes below, organize notes list by phase of open science process and/or topic, determine what tools for each stage want to use and is appropriate for working in astrophysics, make git in VS Code guide, make templates for things like OSDMP and other things may repeat from project to project to make sure all questions have to answer about how the project will be executed are answered, compare own developed process custom to self and astrophysics and lack of institution, funding grant/agency, etc back against Open Science course and its sources and additional resources (e.g. Opensciency).

*Notes derived from NASA Open Science course, as accessed Dec 14th 2025:

  *Put data, code, results, talk slides, lectures, blog posts, etc in repo. Papers should be in open access journals

  *Cite everything use and everyone who contributes, including “those who have shared resources, equipment, or knowledge” (Module 1, Lesson 2)

  *Consider pre-registering, “where researchers document their research plan at the start of a study” to get “feedback from various collaborators and stakeholders…before data collection begins” (Module 1, Lesson 2) and preprints to “allow for swifter feedback on conclusions drawn from data once it is collected” (Module 1, Lesson 2). This also allows for partial work to be findable even if the project did not get completed.

  *Computer code is considered a method from the research perspective. Sharing code is practicing open methods, allowing others to reproduce what you do

  *Don’t just put out work when successful but with any results. Prevents others from putting in effort to duplicate what you’ve already done

  *Intellectual property - changes based on employment and funding

    *Have copyright of an original work as soon as it’s recorded in some form

    *Copyright.gov: “copyright protects expression, and never ideas, procedures, methods, systems, processes, concepts, principles, or discoveries.”

    *Facts and discoveries are public domain (can be used freely without permission or other requirements, though attribution is still recommended. The derivative work you author based on public domain material still has regular copyright rules apply)

    *Licensing is something a copyright owner can choose to do; specifies “under what conditions, if any, others can use, build upon, or distribute your work. It is also a method to ensure your work is appropriately credited” (Module 1, Lesson 3)

    *“It is generally illegal and may be a form of academic misconduct to reuse content without a license, even if the content can be found on the internet…If you don’t license your work, others can’t and shouldn’t reuse it - even if you want them to.” (Module 1, Lesson 3)

    *“Licenses can be applied to data, code, reports, publications and almost any other ‘creative’ output.” (Module 1, Lesson 3)

    *“Permissive Licenses allow users a wide range of rights including the ability to use, modify, and distribute the work with no or minimal restrictions…includ[ing] open source software licenses such as Apache 2.0, the MIT license, or the Creative Commons licenses” (Module 1, Lesson 3)

  *“Plan for the release of your data and results from the very beginning of your research…Obtain all permits, approvals, and/or certifications needed to ensure you can share your research products” (Module 1, Lesson 3)

  *Check licenses on content you want to use

  *Consider if there’s any information associated with the project that shouldn’t be shared, if any data needs to be anonymized, if there’s any sensitive information, anything to compromise someone’s privacy, security issues, etc

  *Give data/code a DOI and a license

  *Make it clear through appropriate licensing, documentation, and contributing guidelines if you don’t want to maintain certain code past a certain time

  *Determine if you will do maintenance and for how long on released code/data

  *Determine the best repository for your materials

  *Figure out when it’s best to apply DOIs, make documentation, etc since “during active research and data exploration, data, code, and ideas may be created and deleted even daily”. Code can just live openly in a version control repo though

  *Make an open science and data management plan (OSDMP) before starting a project. It describes how resources are to be used, the products that will be created, how those products will be shared with other researchers and the public

  *Possible products could make to consider when starting a project: proposal, data management plan, code of conduct, tutorials, contributor guidelines, raw data, metadata, analysis pipelines, code/notebooks, archives, papers, talks, blogs, videos, social media posts, conference proceedings

  *Possible tools: GitHub/GitLab, Zenodo (data repository), FigShare, BitBucket

  *Consider if there’s an existing file format and/or metadata convention you should adopt for a given product

  *Give descriptions when post data/code and installation instructions when post code. List software dependencies for code, use continuous integration (e.g. GitHub Actions), and release a Docker image if applicable

  *Sharing methodology isn’t just sharing the code used to obtain the results but how that code was used. Code can evolve past a given result set while still producing the same results

  *Make sure all project outputs have their own unique identifiers (data/code can have multiple as an identifier can refer to a specific version)

  *Use your ORCID

  *DOI: “a persistent identifier used to cite data, software, journal articles, presentation slides, blog posts, videos, logos, etc…Each new version of data or software..will need a new DOI…Individuals cannot typically request a DOI themselves, but rather have to go through an authorized organization that can submit the request.” (Module 2, Lesson 2)

    *GitHub documentation: “To make your repositories easier to reference in academic literature, you can create persistent identifiers, also known as Digital Object Identifiers (DOIs). You can use the data archiving tool Zenodo to archive a repository on GitHub and issue a DOI for the archive…Academics can use the data management service Figshare to publicize and cite research material. For more information, see Figshare's support site. ”

  *Identify and use the metadata standard appropriate for your domain, data repository, etc

  *Own idea: when complete a given step in a project, review the relevant sections of NASA Open Science course materials for anything missing or can improve

  *Consider how will document publicly available materials from the project

  *Pre-registration is most common prior to collection of data for a project or prior to analysis of an existing or openly available dataset

  *An OSDMP should include sections on data management, software management, publication sharing, as well as any other outputs anticipate (reference related funding agency guidelines as can find, NASA SMD + NSF, how keep up if they update requirements?)

  *Refer to Module 2, Lesson 2 for a list of things typically included in an OSDMP

  *Can create own template for OSDMP to update as improve at doing this

  *FAIR principles: https://www.go-fair.org/fair-principles/

  *DMP resources: DMPTool, ARGOS

  *Data repo tools and other open science tools: Zenodo, Dataverse, Dryad, Datacite, OSF, Registry of Research Data Repositories, OpenAire

  *For chosen data format (e.g. HDF, FITS), see if there’s a tool to check for compliance and readability

  *https://fairsharing.org/, https://www.rd-alliance.org/ have FAIR self-assessment tools

  *https://swcarpentry.github.io/git-novice/

  *If you want to use a large dataset that’s already in the cloud, try to use tools already built into that cloud

  *Software repo contains actively developed code, software archives are for stable and thoroughly tested software releases

  *OSF provides a service to search multiple preprint servers

  *Directory of Open Access Journals is searchable index of all open-access journals and articles

  *Reference management software: Mendeley, EndNote, Zotero

  *Preferred data formats are community-supported, machine-readable, non-proprietary, modifiable, and open. Also use what’s common in your field.

  *If no license on the thing want to use, contact author and get explicit permission
