---
layout: page
title: Posters
description: 
menubar: program
permalink: program/posters/
menubar_toc: true
set_last_modified: true
---

<div id="accordion">
    <div class="card">
        <div class="card-header" id="headingOne">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseOne"
                    aria-expanded="false" aria-controls="collapseOne">
                    "Research Solutions Architecture", Ben Galewsky
                </button>
            </h5>
        </div>

        <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
            <div class="card-body">
                <p>NCSA is piloting a new role, Research Solutions Architect. Common in industry settings, Solutions
                    Architecture is a novel concept in research computing. We start with a portfolio of standardized
                    hosted
                    services that address common research computing and data problems. We then apply Human Centered
                    Design
                    techniques to understand the problems facing researchers and assemble complete solutions based on
                    products from the portfolio. The result is a low-cost process for meeting the needs of many
                    researchers
                    across campus.
                </p>
                <p>
                    In this poster we will show the process we go through to design these solutions and explain some of
                    the
                    products in NCSA’s current portfolio.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingTwo">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo"
                    aria-expanded="false" aria-controls="collapseTwo">
                    "SMILE: A user friendly science gateway for social media research and collaboration", Yong Wook Kim,
                    Chen Wang
                </button>
            </h5>
        </div>

        <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordion">
            <div class="card-body">
                <p>Social Media Intelligence and Learning Environment (SMILE), a key application of the Social Media
                    Macroscope (SMM) project, is an open-source platform tailored for social media research. SMILE
                    addresses
                    the limitations of existing social media analytics tools, such as high costs and restricted access
                    to
                    data acquisition and analysis methodologies. It offers a comprehensive suite of tools via an
                    easy-to-use
                    web interface, facilitating free academic research. By maintaining open-source code, SMILE ensures
                    transparency and reproducibility of the research results. Additionally, it uses the user's
                    credentials
                    for data collection, adhering to social media platform protocols and guidelines to ensure proper
                    data
                    collection.
                </p>
                <p>
                    One notable feature of SMILE is its sentiment analysis capability, which includes the VADER (Valence
                    Aware Dictionary and sEntiment Reasoner) algorithm, SentiWordNet algorithm, and a machine
                    learning-trained sentiment model with debiased word embeddings. This makes SMILE an invaluable tool
                    for
                    researchers aiming to understand and interpret the emotional tone of social media content. Other
                    analytics offered by SMILE include natural language processing, network analysis, and machine
                    learning
                    classification, name entity recognition, and topic modeling, each incorporating multiple algorithms
                    with
                    appropriate academic citations.
                </p>
                <p>
                    SMILE's microservice architecture ensures portability and scalability. CIlogon provides secure and
                    lightweight identity management. The backend, powered by Node.js/Express and GraphQL, handles user
                    requests and social media data collection. Analytics modules run in separate containers, with
                    RabbitMQ
                    managing communication between the backend and analytics modules. MinIO is employed to provide
                    secure
                    data storage and an integration with NCSA Clowder facilitates community data sharing.
                </p>
                <p>
                    SMILE leverages Docker containers managed by Kubernetes and Helm charts for continuous integration
                    and
                    deployment. All images and deployment charts are accessible on GitHub and Docker Hub. Automation
                    scripts, leveraging GitHub Actions, are in place to simplify build, publication, and deployment
                    tasks,
                    making migration, upgrade, and deployment processes efficient and user-friendly.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingThree">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseThree"
                    aria-expanded="false" aria-controls="collapseThree">
                    "OGRRE: Enabling A Human-in-the-Loop for AI/ML Driven Oil & Gas Data Extraction", Rajshree Deshmukh,
                    Dan
                    Gunter, Michael Pesce, Greg Lackey, Mumbi Mundia-Howe, Benjamin Houghton, Jacob Shay
                </button>
            </h5>
        </div>

        <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordion">
            <div class="card-body">
                <p>This poster describes the research software engineering and user experience approaches, as well as
                    lessons learned from initial deployments, for a new open-source web UI tool, OGRRE, which enables
                    rapid
                    human review of Google Doc AI-digitized oil and gas regulatory documents.
                </p>
                <p>
                    The US has hundreds of thousands of orphaned oil and gas wells that no longer have a responsible
                    owner.
                    These wells pose an environmental and human health risk, as they can leak methane and other
                    pollutants
                    into the air and groundwater if they become compromised. In 2021, the Bipartisan Infrastructure Law
                    was
                    passed which allocated $4.7 billion for orphaned well plugging in the US. One major barrier to the
                    Herculean task of plugging these wells is providing the stakeholders doing this work with accurate
                    information about their location, construction, and status. This information is often documented in
                    regulatory paper records created during the well permitting process. While many regulatory agencies
                    have
                    scanned their paper records, they often lack the resources necessary to digitize their content.
                    Extracting this information and organizing it in computer databases will help regulatory agencies as
                    they seek to better characterize the orphaned wells under their jurisdiction and prioritize their
                    plugging.
                </p>
                <p>
                    Modern AI/ML optical character recognition (OCR) models can aid the efficient digitization of
                    historic
                    well records. However, these documents often date back over 100 years and contain handwritten fields
                    and
                    many other anomalies. This results in a significant challenge when training AI/ML algorithms to
                    accurately identify fields, and results are often imperfect. Human review of the documents is needed
                    to
                    find and correct problems. With hundreds of thousands of documents to process and limited resources,
                    an
                    efficient melding of the human-in-the-loop tasks with the AI/ML models becomes essential.
                </p>
                <p>
                    This poster will describe the Oil and Gas Regulatory Record digitizEr (OGRRE) — a custom user
                    interface
                    we developed to facilitate rapid human review of digitized oil and gas regulatory documents. OGRRE
                    uses
                    retrained AI/ML models developed by Google Document AI. The tool is designed to enable the
                    interactive
                    review and correction of AI/ML extracted data. The poster will describe the combination of Google
                    Doc AI
                    modeling, software engineering, and user experience approaches used to create the OGGRE tool and
                    software infrastructure, as well as lessons learned from our pilot deployment of the tool.
                </p>
                <p>
                    OGRRE development is supported by the United States Department of Energy’s Undocumented Orphaned
                    Well
                    Program under the CATALOG project.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingFour">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseFour"
                    aria-expanded="false" aria-controls="collapseFour">
                    "Foundational competencies of an RSE: state of the project and what comes next", Jan Philipp Thiele,
                    Toby Hodges, Florian Goth
                </button>
            </h5>
        </div>

        <div id="collapseFour" class="collapse" aria-labelledby="headingFour" data-parent="#accordion">
            <div class="card-body">
                <p>Building on discussions first started at the German RSE conference in 2023 (de-RSE23), a recent
                    pre-print, Foundational Competencies and Responsibilities of a Research Software Engineer,
                    identifies a
                    set of core competencies required for RSEng and describes possible pathways of development and
                    specialisation for RSEs. It is the first output of a group with broad interests in the teaching and
                    learning of RSEng skills.
                </p>
                <p>
                    With continuing growth in RSE communities around the world, and sustained global demand for RSEng
                    skills, US-RSE24 presents an opportunity to align international efforts towards
                </p>
                <ul>
                    <li> training the next generation of RSEs</li>
                    <li> providing high-quality professional development opportunities to those already following the
                        career
                        path</li>
                    <li> empowering RSE Leaders to further advocate for the Research Software Engineering needs and
                        expertise
                        in their teams, institutions, and communities.</li>
                </ul>
                <p>
                    Therefore, we want to give an overview of what the group has been working on so far, discuss the
                    aims of
                    our future work, and invite members of the international RSE community to contribute and provide
                    feedback. We particularly encourage members of regional groups focused on RSEng training and skills
                    to
                    attend and share their perspectives.
                </p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingFive">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseFive"
                    aria-expanded="false" aria-controls="collapseFive">
                    "Scaling Molecular Software Testing with Self-Hosted GitHub Actions Runners", Ethan Holz, David
                    Swenson
                </button>
            </h5>
        </div>

        <div id="collapseFive" class="collapse" aria-labelledby="headingFive" data-parent="#accordion">
            <div class="card-body">
                <p>Molecular software is beginning to use more GPU-accelerated compute and traditional CI solutions can
                    often be expensive when running longer GPU tests. In order to understand the existing solutions, we
                    reviewed 6 potential self-hosted GitHub Actions Runner candidates from a curated list. This poster
                    explains how the Open Molecular Software Foundation (OMSF) seeks to provide a new solution[8] for
                    cloud-based GitHub Actions Runners to make scaling of GPU compute more effective for molecular
                    software.
                    We highlight the long-term community decisions discussed, such as language selection, ability to
                    receive
                    feedback, cloud-agnostic architecture, and ease of maintainability that lead to developing a new
                    solution rather than updating existing tooling. In addition, we discuss common pitfalls in working
                    with
                    cloud-based infrastructure and how we implemented a testing strategy to mitigate the potential costs
                    of
                    untested infrastructure code.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingSix">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseSix"
                    aria-expanded="false" aria-controls="collapseSix">
                    "Collaborative Lesson Development Training for RSEs", Sarah L.R. Stevens, Toby Hodges, Aleksandra
                    Nenadic
                </button>
            </h5>
        </div>

        <div id="collapseSix" class="collapse" aria-labelledby="headingSix" data-parent="#accordion">
            <div class="card-body">
                <p>The Carpentries is a community building global capacity in essential data and computational skills
                    for
                    conducting efficient, open, and reproducible research. In addition to certified Instructors teaching
                    Data Carpentry, Library Carpentry, and Software Carpentry workshops around the world, the community
                    also
                    includes many people contributing to and maintaining Open Source lessons.
                </p>
                <p>
                    Recent years have seen enormous growth in the number and diversity of lessons the community is
                    creating,
                    including many teaching skills and concepts essential to Research Software Engineering: software
                    packaging and publication, environment and workflow management, containerised computing, etc. As
                    this
                    curriculum community has developed, demand has been growing for training opportunities, teaching how
                    to
                    design and develop Open Source curriculum effectively and in collaboration with others.
                </p>
                <p>
                    A new program launched in 2023, The Carpentries Collaborative Lesson Development Training teaches
                    good
                    practices in lesson design and development, and open source collaboration skills, using The
                    Carpentries
                    Workbench, an Open Source infrastructure for building accessible lesson websites.
                </p>
                <p>
                    As the discipline of Research Software Engineering continues to develop and mature, there is an
                    increasing need for high-quality, Open Source and community-maintained training, and for the
                    expertise
                    to develop those resources. This poster will provide an overview of the training, explain how it
                    meets
                    this need, and describe how it fits into The Carpentries ecosystem for lesson development. It will
                    also
                    explain how RSEs can enroll in the training, and give examples of lesson projects that have
                    benefited
                    from it already.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingSeven">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseSeven"
                    aria-expanded="false" aria-controls="collapseSeven">
                    "Building a performance portable land surface model using AMReX", Coleman Kendrick, Jungmin Lee,
                    David
                    J. Wiersema, David J. Gardner, Jeffrey D. Mirocha, Katie A. Lundquist
                </button>
            </h5>
        </div>

        <div id="collapseSeven" class="collapse" aria-labelledby="headingSeven" data-parent="#accordion">
            <div class="card-body">
                <p>Achieving performance portability while ensuring code sustainability is often challenging,
                    particularly
                    with research software applications. In complex codes comprised of many distinct physics modules
                    coupled
                    together to form a larger system, such as climate and weather models, the challenges are compounded.
                    The
                    individual physics components are often developed independently by domain scientists from different
                    backgrounds and designing software for performance and maintainability is sometimes a secondary
                    consideration. Utilizing software frameworks can help reduce the complexity of these large coupled
                    application codes while also providing mechanisms to help obtain performance portability and
                    accessibility to domain scientists. AMReX is a software framework for multiphysics applications
                    targeting high performance computing and is designed with multiple levels of abstractions to ease
                    software design and development. In this work, we focus on extending the Energy Research and
                    Forecasting
                    (ERF) model, built on the AMReX framework, to couple with land surface models. We present a new C++
                    implementation of the Simplified Land Model (SLM) in ERF based on the Fortran version in the System
                    for
                    Atmospheric Modeling (SAM) code. Performance and validation between the original and new SLM
                    implementation will be shown. Additionally, we will discuss the process of re-implementing SLM in
                    ERF
                    and share our experiences and lessons learned for the broader research software community.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingEight">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseEight"
                    aria-expanded="false" aria-controls="collapseEight">
                    "MARS: An Open-Source Application for Managing and Searching Scientific Metadata", Henry Burgess,
                    Robin
                    Fievet, Dave Brownell, Linda Richards
                </button>
            </h5>
        </div>

        <div id="collapseEight" class="collapse" aria-labelledby="headingEight" data-parent="#accordion">
            <div class="card-body">
                <p>When conducting scientific experiments, vast collections of data and subsequently scientific metadata
                    are
                    generated. Maintaining the set of FAIR (findability, accessibility, interoperability, and
                    reusability)
                    principles is often challenging given large datasets and various metadata standards. MARS (Metadata
                    Aggregator for Reproducible Science) aims to address this challenge as an open-source application by
                    providing a structured interface on top of database storage for the management and querying of
                    scientific metadata, particularly in the biological sciences.
                </p>
                <p>
                    MARS introduces a nomenclature for a metadata abstraction that is intended to be customizable and
                    scalable across scientific contexts. A core architectural feature of MARS is the ability to
                    granularize
                    units of metadata into single “entities”. Entities may represent a physical or digital object,
                    ranging
                    from whole animals to brain slice images from that same animal. Raw data are not stored in MARS,
                    rather
                    external links to the relevant data storage platforms are stored within entities. Graph-like
                    connections
                    can be used to establish relationships between entities, and a “project” grouping system within MARS
                    allows entities to be grouped with each other to represent contexts such as experimental output,
                    physical storage contents, or data presented in a publication.
                </p>
                <p>
                    To specify metadata associated with an entity, MARS uses key-value pairings known as “attributes”.
                    Attributes can be used to express metadata on a per-entity basis, or attribute templates can be
                    created
                    and reused across multiple entities. Attributes are named uniquely, and the values are restricted to
                    types including “date”, “string”, “number”, or a set of fixed options defined in a drop-down menu.
                </p>
                <p>
                    MARS also provides several features useful for scientists, such as an ORCID ID authentication
                    requirement for all users, metadata import from CSV, Excel, and JSON files, multiple metadata export
                    options, and the ability to construct and execute queries across all stored metadata. MARS uses a
                    React
                    frontend written in TypeScript and utilizes components from the Chakra UI library. The Node.js
                    backend
                    couples Express.js with GraphQL to exchange data with a MongoDB database, and is currently hosted on
                    Microsoft Azure.
                </p>
                <p>
                    MARS has been deployed successfully within a neuroscience laboratory, managing hundreds of unique
                    entities and 6 active users. Intuitive training for new users is incorporated within the software
                    for
                    each step required to manage entities and attributes across the platform. Potential future
                    deployment
                    targets for MARS include other laboratories and core facilities at Washington University in St.
                    Louis.
                </p>
                <p>
                    GitHub: https://github.com/Brain-Development-and-Disorders-Lab/mars</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="headingNine">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseNine"
                    aria-expanded="false" aria-controls="collapseNine">
                    "GUI based modular EEG preprocessing pipeline framework for HPC batch processing", Satkar Dhakal,
                    Shuti
                    Wang, Prasanna Koirala, Lindsey Fox, Antonia N. Kaczkurkin
                </button>
            </h5>
        </div>

        <div id="collapseNine" class="collapse" aria-labelledby="headingNine" data-parent="#accordion">
            <div class="card-body">
                <p>Electroencephalography (EEG) preprocessing is the initial and critical step for accurate brain
                    function
                    and behavior analysis. There is a pressing demand for an automatic pipeline that can process huge
                    volumes of data, yet existing commercial software solutions are expensive, have no batch processing
                    capabilities and offer limited automation. While open-source libraries in Python and R can be used
                    to
                    implement a solution, it demands extensive programming expertise in researchers who very often lack
                    knowledge of programming and batch processing. This project introduces an accessible, scalable, EEG
                    processing pipeline framework tailored for high-performance computing (HPC). It features a graphical
                    user interface (GUI) with node editor based drag and drop pipeline creator with reusable modules, a
                    Python based pipeline runner to run the serialized interpretation of pipeline leveraging MNE
                    library,
                    and SLURM integration for batch processing. The framework provides modules for commonly used
                    preprocessing steps such as filtering, epoching, artifact rejection, baseline correction and
                    advanced
                    techniques like Independent Component Analysis (ICA) and power spectral density analysis. The
                    framework
                    has been supporting diverse EEG research applications including resting state, letter flanker and
                    emotional regulation analysis at BRAINS Lab with ACCRE computing cluster at Vanderbilt University,
                    proving its flexibility and adaptability for real world use cases. By significantly advancing the
                    accessibility and increasing automation of EEG preprocessing, this system holds promise for reducing
                    barriers and accelerating research in neuroscience and related fields.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading10">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse10"
                    aria-expanded="false" aria-controls="collapse10">
                    "Metadata Analysis with EPMT", Avery Kiihne, Ian Laflotte, Jeffrey Durachta
                </button>
            </h5>
        </div>

        <div id="collapse10" class="collapse" aria-labelledby="heading10" data-parent="#accordion">
            <div class="card-body">
                <p>EPMT (Experiment Performance Management Tool) is an open source tool for aggregating metadata/metrics
                    from batch jobs of interest at GFDL's post-processing and analysis cluster (PPAN). EPMT features
                    ultra-lightweight metadata annotation capabilities, minimally impacting batch job execution. EPMT
                    scrapes a wide array of metrics, including software metadata (high-level) and process level
                    data(low-level). Data scraping occurs inside of the application, and is recorded based on how the
                    application sees itself. The goal of EPMT is to be able to easily cut through noisy data and
                    identify
                    whether issues are software or hardware related. Sometimes the same job, run on the same file, can
                    have
                    a different result. An example explored in this poster is when we used EPMT to generate of
                    histograms of
                    all metrics, which lead to the identification of a spike in read bytes at a specific value, for
                    which we
                    were able to conduct root cause analysis. EPMT can help identify these kinds of issues, detect
                    anomalies, and help predict where future hardware changes will need to be made to keep a system
                    running.
                </p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading11">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse11"
                    aria-expanded="false" aria-controls="collapse11">
                    "User Development and Support in a Community-Driven Analysis Platform for Systems Biology", Benjamin
                    Allen, Zachary Crockett, Robert Cottingham, Ellen Dow, Elisha Wood-Charlson, Mikaela Cashman
                </button>
            </h5>
        </div>

        <div id="collapse11" class="collapse" aria-labelledby="heading11" data-parent="#accordion">
            <div class="card-body">
                <p>The Department of Energy Systems Biology Knowledgebase (KBase) is a community-driven research
                    platform
                    designed for discovery, knowledge creation, and sharing. The open-access platform integrates data
                    and
                    analysis tools into reproducible notebooks called Narratives. KBase provides access to DOE computing
                    infrastructure for running applications, enables collaborative research and publishing of findable,
                    accessible, interoperable, and reusable (FAIR) analyses. KBase’s 40,000 users come from a broad
                    range of
                    experience levels and research interests, thus characterizing the user base and targeting
                    engagements is
                    crucial to grow and support the scientific communities using the platform for research. In this
                    poster
                    we share our models for enabling users through training and documentation development, social
                    platforms
                    for community communication, and education materials development.
                </p>
                <p>
                    The team works to support users to develop skills and knowledge of computational biology through
                    user
                    development and support activities in order to advance their research. User development activities
                    include hosting workshops and webinars to demonstrate the features and analytical capabilities of
                    the
                    platform. Workshops are designed to communicate scientific content knowledge, support institutional
                    research needs, and facilitate collaboration between research groups. Webinars are broadcast to a
                    global
                    audience and showcase powerful workflows, new tools and features, and speakers from community
                    developers
                    to subject matter experts.
                </p>
                <p>
                    User support is provided through a help board that allows users to report bugs or ask questions to
                    be
                    addressed by project members. User help tickets are public so that questions and answers are
                    findable by
                    future users. Users may also submit new feature requests to inform platform development to better
                    serve
                    their needs. This board is supported by dedicated staff, dedicated subject matter experts, and
                    rotating
                    developers.
                </p>
                <p>
                    Additionally, the KBase Educators Program supports professors and teachers by developing curriculum
                    for
                    computational biology. This program includes biology and data science instructors teaching students
                    at
                    community colleges, primarily undergraduate, and doctoral research institutions that represent
                    diverse
                    populations, including Minority-Serving and Emerging Research Institutions. The program uses
                    accessible
                    and reproducible modules to encourage students without programming skills or access to additional
                    computational resources.
                </p>
                <p>
                    Through each of these approaches, KBase provides a platform that ensures research software reaches
                    the
                    end-user biologists and data scientists enabling them to fully utilize these sophisticated tools and
                    share knowledge in a FAIR manner across the scientific community.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading12">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse12"
                    aria-expanded="false" aria-controls="collapse12">
                    "Towards Defining Lifecycles and Categories of Research Software", Yo Yehudi, Mikaela Cashman,
                    Michael
                    Felderer, Michael Goedicke, Wilhelm Hasselbring, Daniel S. Katz, Frank Löffler, Sebastian Müller,
                    Bernhard Rumpe
                </button>
            </h5>
        </div>

        <div id="collapse12" class="collapse" aria-labelledby="heading12" data-parent="#accordion">
            <div class="card-body">
                <p>There is a large variety of types of research software at different stages of evolution. Due to the
                    nature of research and its software, existing models from software engineering often do not cover
                    the
                    unique needs of RSE projects. This lack of clear models can confuse potential software users,
                    developers, funders, and other stakeholders who need to understand the state of a particular
                    software
                    project, such as when deciding to use it, contribute to it, or fund it. We present work performed by
                    a
                    group consisting of both software engineering researchers (SERs) and research software engineers
                    (RSEs),
                    who met at a Dagstuhl seminar, to collaborate on these ideas.
                </p>
                <p>
                    Through our collaboration, we found many of our terminologies and definitions often vary, for
                    example
                    one person may consider a software project to be early-stage or in maintenance mode, whilst another
                    person might consider the same software to be inactive or failed. Because of this, we explored
                    concepts
                    such as software maturity, intended audience, and intended future use. In this poster, we will
                    present a
                    working categorization of research software types, as well as an abstract software lifecycle that
                    can be
                    applied and customized to suit a wide variety of research software types. Such a model can be used
                    to
                    make decisions and guide development standards that may vary by stage and by team. We also are
                    seeking
                    community input on improvements of these two artifacts for future iterations.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading13">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse13"
                    aria-expanded="false" aria-controls="collapse13">
                    "Realizing a Project-Based Resource API at the Oak Ridge Leadership Computing Facility", Arthur J.
                    Ruckman, Paul Bryant, Eben Fluto, Suzanne Prentice, Tyler J. Skluzacek
                </button>
            </h5>
        </div>

        <div id="collapse13" class="collapse" aria-labelledby="heading13" data-parent="#accordion">
            <div class="card-body">
                <p>As part of the Oak the Leadership Computing Facility's (OLCF) motivation to meet modern scientific
                    demands, the OLCF is implementing a unified set of APIs that enable programmatic access to the
                    OLCF’s
                    computational and data resources. The OLCF Facility API supports classical HPC workloads involving
                    the
                    analysis and/or reduction of static datasets, and workloads falling into the two broad-class IRI
                    Science
                    Patterns outlined in the DOE's IRI ABA Report applicable to this project:
                </p>
                <p>
                    Time-sensitive workloads requiring highly reliable, real time or near-real time performance for
                    active
                    decision making, experiment steering, and/or experiment calibration.
                    Data integration–intensive workloads requiring the combination and analysis of data from a mix of
                    experiments, sensors, and/or other computational runs, possibly in real time.
                </p>
                <p>
                    Within the Facility API, we aim to develop a range of interfaces that can be consumed together in
                    code
                    to realize all common configurations of leadership-scale scientific workfloads. In this poster, we
                    demonstrate our work-in-progress experiences in building Compute, Status, Environment, and Stream
                    Management APIs across core OLCF resources, and discuss the architecture, security, and usability
                    challenges of each.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading14">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse14"
                    aria-expanded="false" aria-controls="collapse14">
                    "Codefair - Your Personal Assistant for Developing FAIR Software", Bhavesh Patel, Sanjay
                    Soundarajan,
                    Dorian Portillo, Jacob Clark
                </button>
            </h5>
        </div>

        <div id="collapse14" class="collapse" aria-labelledby="heading14" data-parent="#accordion">
            <div class="card-body">
                <p>Most research projects today involve the development of some research software. Therefore, it has
                    become
                    more important than ever to make research software reusable to enhance transparency, prevent
                    duplicate
                    efforts, and ultimately increase the pace of discoveries. The Findable, Accessible, Interoperable,
                    and
                    Reusable (FAIR) Principles for Research Software (or FAIR4RS Principles) provide a general framework
                    for
                    achieving that. Just like the original FAIR Principles, the FAIR4RS Principles are as designed to be
                    aspirational and do not provide actionable instructions. To make their implementation easy, we
                    established the FAIR Biomedical Research Software (FAIR-BioRS) guidelines, which are minimal,
                    actionable, and step-by-step guidelines that biomedical researchers can follow to make their
                    research
                    software compliant with the FAIR4RS Principles. While they are designed to be easy to follow, we
                    learned
                    that the FAIR-BioRS guidelines can still be time-consuming to implement, especially for researchers
                    without formal software development training. They are also prone to user errors as they require
                    several
                    actions with each new version release of a software.
                </p>
                <p>
                    To address this challenge, we are developing codefair, a free and open-source GitHub app that acts
                    as a
                    personal assistant for making research software FAIR in line with the FAIR-BioRS guidelines. The
                    objective of codefair is to minimize developers’ time and effort in making their software FAIR so
                    they
                    can focus on the primary goals of their software. To use codefair, developers only need to install
                    it
                    from the GitHub marketplace. By leveraging tools such as Probot and GitHub API, codefair monitors
                    activities on the software repository and communicates with the developers via a GitHub issue
                    “dashboard” that lists issues related to FAIR-compliance (updated with each new commit). For each
                    issue,
                    there is a link that takes the developer to the codefair user interface (built with Nuxt, Naive UI
                    and
                    Tailwind) where they can better understand the issue, address it through an intuitive interface, and
                    submit a pull request automatically with necessary changes to address the related issue. Currently,
                    codefair is in the early stages of development and helps with including essential metadata elements
                    such
                    as a license file, a CITATION.cff metadata file, and a codemeta.json metadata file. Additional
                    features
                    are being added to provide support for complying with language-specific standards and best coding
                    practices, archiving on Zenodo and Software Heritage, registering on bio.tools, and much more to
                    cover
                    all the requirements for making software FAIR.
                </p>
                <p>
                    In this poster, we will highlight the current features of codefair, discuss upcoming features,
                    explain
                    how the community can benefit from it, and also contribute to it. We believe codefair is an
                    essential
                    and impactful tool for enabling software curation at scale and turning FAIR software into reality.
                    The
                    application of codefair is not limited to just making biomedical research software FAIR as it can be
                    extended to other fields and also provide support for software management aspects outside of the
                    FAIR
                    Principles, such as software quality and security. We believe this work is fully aligned with the
                    US-RSE’24 topic of “Software engineering approaches supporting research”. The conference
                    participants
                    will benefit greatly from this poster as they will learn about a tool that can enhance their
                    software
                    development practices. We will similarly benefit as we are looking for community awareness and
                    contribution in the development of codefair, which is not currently supported through any funding
                    but is
                    the result of the authors aim to reduce the burden of making software FAIR on fellow developers.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading15">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse15"
                    aria-expanded="false" aria-controls="collapse15">
                    "Detecting Events from Emails using Time-based Retrieval for RAG", Minu Mathew, Ray Jeong, William
                    Ocasio, Rob Kooper
                </button>
            </h5>
        </div>

        <div id="collapse15" class="collapse" aria-labelledby="heading15" data-parent="#accordion">
            <div class="card-body">
                <p>Nowadays, a lot of decision-making occurs through email communication and online meetings. A project
                    plan
                    might change over time and the final deliverable might look different than what was planned during
                    the
                    starting phase of the project. These changes might be a result of multiple events which lead to
                    different decisions and plans. Post-project retrospectives often require understanding the guiding
                    factors behind these decisions, the timing of each decision, and the events that triggered them.
                    This
                    involves a time-based analysis of internal documents, email communications, meeting notes, and other
                    data points pertaining to the project.
                </p>
                <p>
                    We explore a time-based retrieval approach for RAG (Retrieval Augmented Generation) to detect events
                    from extensive textual knowledge bases. RAG enhances the accuracy and reliability of LLM (Large
                    Language
                    Model)-generated responses by fetching facts from external sources. Unlike traditional LLMs, which
                    rely
                    solely on pre-existing knowledge, RAG incorporates an information retrieval component that pulls
                    relevant data from external sources based on the user query. This new information, combined with the
                    LLM's training data, results in more accurate responses. A simple retrieval approach retrieves data
                    that
                    are most semantically similar to a given user query. Our approach retrieves data that are
                    semantically
                    similar and relevant to a specific time frame, performing time filtering before semantic similarity
                    matching.
                </p>
                <p>
                    We used Qdrant for our knowledge store and LangChain framework to implement document ingestion,
                    prompt
                    management, and RAG. The knowledge store included emails, internal documents, meeting transcripts,
                    and
                    in-depth interviews of team members. After some data cleaning, the email data was divided into weeks
                    (“week 1” to “week 100”) to track weekly changes. To track the decision changes and events, we used
                    a
                    chained RAG approach, wherein RAG was first applied to “week 1” and the responses were used as
                    context
                    for RAG with a filter for “week 2”. To classify the events and to extract the entities from the
                    events,
                    we use Marvin. In this poster, we will present the architecture used to track events from email data
                    leveraging time-based retrieval for RAG.
                </p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading16">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse16"
                    aria-expanded="false" aria-controls="collapse16">
                    "Better Scientific Software Fellowship Program", Elsa Gonsiorowski, Erik Palmer, Mary Ann Leung
                </button>
            </h5>
        </div>

        <div id="collapse16" class="collapse" aria-labelledby="heading16" data-parent="#accordion">
            <div class="card-body">
                <p>Software developers face increasing complexity in computational models, computer architectures, and
                    emerging workflows. In this environment Research Software Engineers need to continually improve
                    software
                    practices and constantly hone their craft. To address this need, the Better Scientific Software
                    (BSSw)
                    Fellowship Program launched in 2018 to seed a community of like-minded individuals interested in
                    improving all aspects of the work of software development. To this aim, the BSSw Fellowship Program
                    fosters and promotes practices, processes, and tools to improve developer productivity and software
                    sustainability.
                </p>
                <p>
                    Our community of BSSw Fellowship alums serve as leaders, mentors, and consultants, thereby
                    increasing
                    the visibility of all those involved in research software production and sustainability in the
                    pursuit
                    of discovery. This poster will present the BSSw Fellowship (BSSwF) Program, briefly discussing our
                    successes in developing a community around software development practices. We will highlight the
                    work of
                    recent fellowship awardees and honorable mentions, particularly those in attendance at US-RSE’24. As
                    many in the BSSwF community identify as RSEs, and BSSwF projects are of particular relevance, this
                    forum
                    will serve to amplify the connections between our communities.
                </p>
                <p>
                    The BSSw Fellowship Program has seen much success through various projects, such as tutorials,
                    webinars
                    and education materials. Fellows typically focus on creating content for scientific or minority
                    communities that they are already a part of. Topic areas include, but are not limited to:
                </p>
                <p>
                    Essential Collaborative Skills for Contributing to Open-Source Software
                    Maintaining Multi-project Continuous Integration/Development (CI/CD)
                    Guidelines for Getting Better MPI Performance
                    Collaborative Learning in Scientific Software Development
                    Reproducibility in Scientific Software
                    A Software Gardening Almanac: Applied Guidance and Tools for Sustainable Software Development and
                    Maintenance
                </p>
                <p>
                    Projects completed by Fellows are collected through blog articles, links and other content curated
                    at
                    the BSSw.io website. In this way, their work forms a growing compendium of information easily
                    accessible
                    to the wider computing community.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading17">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse17"
                    aria-expanded="false" aria-controls="collapse17">
                    "ML/NLP in the biological domain - adapting to large, complex datasets", Christopher J. Neely,
                    Marcin P.
                    Joachimiak, Gilchan Park, Dileep Kishore, Mikaela Cashman
                </button>
            </h5>
        </div>

        <div id="collapse17" class="collapse" aria-labelledby="heading17" data-parent="#accordion">
            <div class="card-body">
                <p>The Department of Energy Systems Biology Knowledgebase (KBase) explores novel machine learning and
                    natural language processing (ML/NLP) use-cases in the biological domain. Due to the scale,
                    complexity,
                    and non-uniformity of the data within the KBase platform, existing ML/NLP pipelines must be adjusted
                    to
                    meet these challenges. This work will detail several of these concerns and solutions in the context
                    of
                    biological research in DOE-centric scientific focus areas that are likely shared by many domains
                    outside
                    of biology.
                </p>
                <p>
                    While mining training data from numerous and diverse sources is a common first step in ML projects,
                    mixed data sources can complicate the interpretation of the results. In particular, KBase has
                    developed
                    a model for classifying annotated metagenomes with the environment from which they were extracted
                    using
                    gradient-boosted decision trees (Catboost1). This model was trained on the MGnify dataset, a complex
                    data source comprising many different sources of annotations, including taxonomic labels, protein
                    domain
                    and full-length functional annotations using Gene Ontology2,3 and InterPro4 annotations. Deriving a
                    meaningful interpretation of the data relies on downstream analysis after model training and
                    evaluation,
                    such as permutation and feature importance analysis.
                </p>
                <p>
                    Results from NLP classification tasks, including those of biological relevance, are often improved
                    by
                    augmenting input with domain-specific context (RAG5, etc.). This requirement can preclude the use of
                    models with small context windows. The size of the model also directs a lab’s ability to use it, as
                    very
                    large models may require prohibitively expensive pre-training or fine-tuning. In our work, we
                    explore
                    the results of using different models with varying context window sizes and their ability to improve
                    classification metrics for NLP models trained for genetic tool development and biomanufacturing
                    tasks.
                </p>
                <p>
                    Sampling bias may occur as a result of slight variations in experimental protocols and data sources.
                    These issues impact a model’s ability to generalize to data on which it was not trained. In
                    biological
                    applications, like phenotype classification, these variations can impact the predictive performance
                    for
                    out-of-clade predictions by machine learning classifiers6. Addressing these effects calls for
                    innovative
                    sampling techniques that extend beyond basic random and stratified splitting. We are developing a
                    sampling technique based on the similarity of the most important and predictive features that use
                    phenotypic similarity as a proxy.
                </p>
                <p>
                    While issues in developing a useful ML pipeline or NLP model are shared across many domains, the
                    exact
                    means of mitigating is field-dependent. KBase’s research, focusing on biological applications, is
                    also
                    subject to these issues, often requiring insight into the biological domain to guide model result
                    improvement.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading18">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse18"
                    aria-expanded="false" aria-controls="collapse18">
                    "A Proposed Approach for Certifying Machine Learning Pipelines Containing Multiple Trust
                    Objectives",
                    Michael C. Darling, Erin C.S. Acquesta, Karin M. Butler, Edward R. Carroll, Esha Datta, Reed M.
                    Milewicz, J. Jake Nichol, Mark A. Smith, Ann E. Speed
                </button>
            </h5>
        </div>

        <div id="collapse18" class="collapse" aria-labelledby="heading18" data-parent="#accordion">
            <div class="card-body">
                <p>We propose to develop methods for certifying Machine Learning (ML) models by optimizing multiple
                    trust
                    and decision objectives. By combining measures of trustworthiness with domain- specific decision
                    objectives, we aim to establish the criteria necessary to meet exacting standards for
                    high-consequence
                    applications of ML in support of national security priorities. In accordance with Executive
                    Order-14110,
                    our objective is to promote the safe, secure, and trustworthy development and use of Artificial
                    Intelligence (AI) by delivering a generalizable process that can readily inform ML certification.
                </p>
                <p>
                    Current credibility assessments for ML are developer-focused, application-specific, and limited to
                    uncertainty quantification (UQ) and validation, which are necessary but insufficient for
                    certification.
                    Whereas ML developers are primarily concerned with various measurements of model accuracy, non-ML-
                    expert stakeholders are concerned with real-world quantities such as risk, or safety; this suggests
                    that
                    a more holistic technical basis is needed. With multiple objectives, decisions may only be
                    Pareto-optimal: no objective can be improved without making another worse. Designing certification
                    processes with multi-objective design optimization allows for the balancing of requirements for
                    specific
                    applications.
                </p>
                <p>
                    The absence of evidence-based, generalizable approaches to certification restricts our ability to
                    develop and deploy credible, mature ML models. To address this gap, we will operationalize AI
                    risk-frameworks, such as the National Institute of Standards and Technology’s Risk Management
                    Framework,
                    by synthesizing important Trustworthy AI capabilities such as robustness testing and anomaly
                    detection.
                    To validate and refine our approach, we will engage in collaborative case studies applying our tools
                    to
                    real-world datasets and scenarios while gathering feedback to ensure their effectiveness and
                    usability.
                </p>
                <p>
                    Our primary research goal is to develop a process for designing certifications for trustworthiness
                    of
                    ML, particularly in high-consequence applications. Drawing inspiration from the multi-tiered
                    approach of
                    software testing, which encompasses unit to integration tests, our strategy involves assessing
                    trustworthiness throughout the ML development lifecycle and conducting system-level evaluations of
                    non-functional properties such as safety, fairness, and privacy.
                </p>
                <p>
                    If successful, our research will position ML to fulfill the requirements of high-consequence
                    domains, as
                    evidenced by a measurable improvement in the reliability properties of our exemplar models.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading19">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse19"
                    aria-expanded="false" aria-controls="collapse19">
                    "Unlocking the Power of ED2 Model on HPC Clusters: A Singularity Container Approach", Dipannita Dey,
                    Rob
                    Kooper, Marcos Longo, Michael Keller, Paul Moorcroft
                </button>
            </h5>
        </div>

        <div id="collapse19" class="collapse" aria-labelledby="heading19" data-parent="#accordion">
            <div class="card-body">
                <p>The Ecosystem Demography Biosphere Model (ED2) is an open-source, comprehensive terrestrial biosphere
                    model that integrates hydrology, land-surface biophysics, vegetation dynamics, and carbon
                    biogeochemistry. Since its inception in 2001, researchers have utilized this model to examine a
                    variety
                    of tropical and temperate ecosystems over years. ED2 presents challenges to new users due to its
                    implementation in Fortran 90 with required HDF5 libraries, necessitating specific prior knowledge.
                    Additionally, running the model over extended periods demands substantial computational resources,
                    complicating deployment across various computing platforms. High Performance Computing (HPC) cluster
                    usage requires prior knowledge about clusters and a learning curve for job submission. To lower
                    these
                    barriers for the broader ecological community, we implemented a Singularity-based containerization
                    of
                    ED2 and developed a Jupyter Notebook to simplify job submissions to HPC clusters.
                </p>
                <p>
                    The containerized version of ED2 can be easily deployed on various High-Performance Computing (HPC)
                    platforms. This container includes the ED2 binary and all necessary libraries, removing the need for
                    additional installations and allowing the capability to "run everywhere." Additionally, the Jupyter
                    notebooks enable users to seamlessly modify model configurations and run the model on both local
                    machines and different HPC clusters. This approach simplifies the process of communicating with the
                    HPC
                    cluster and managing slurm jobs. The notebook also includes features for frequently checking the
                    status
                    of ongoing jobs on the HPC cluster and transferring the output back to the local machine. We have
                    created basic demo visualizations of the output, allowing users to further visualize their results
                    using
                    Python or R as they prefer.
                </p>
                <p>
                    We ran the containerized ED2 model running on the University of Illinois Campus Cluster, TEXAS
                    Stampede
                    clusters and NCSA Delta, analyzing 20 years of model simulations over multiple sites in tropical and
                    temperate ecosystems. We are working towards testing and adding the configuration to run on
                    additional
                    clusters (such as the NASA HEC system). We have held a workshop at the ED2 community meeting at
                    Harvard
                    in 2024 where the ED2 community showed significant interest in the combination of notebooks and
                    containers.
                </p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading20">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse20"
                    aria-expanded="false" aria-controls="collapse20">
                    "Software testing in a community-driven web-based analysis platform for life science research",
                    Robert
                    W. Cottingham, Mikaela Cashman, Myra B. Cohen, Alexis L. Marsh
                </button>
            </h5>
        </div>

        <div id="collapse20" class="collapse" aria-labelledby="heading20" data-parent="#accordion">
            <div class="card-body">
                <p>Domain research, particularly in the life sciences, has become increasingly complex due to the
                    diversity
                    of types and amounts of data concomitantly with the associated analytical methods and software.
                    Simultaneously, researchers must consider the trustworthiness of the software tools they use with
                    the
                    highest regard. As with any new physical laboratory technique, researchers should test and assess
                    any
                    software they use in the context of their planned research objectives.
                </p>
                <p>
                    As examples, bioinformatics software developers and contributors to community platforms that host a
                    variety of domain-specific tools, such as KBase (the DOE Systems Biology Knowledgebase) and Galaxy,
                    should design their tools with consideration for how users can assess and validate the correctness
                    of
                    their applications before opening their applications up to the community.
                </p>
                <p>
                    More attention should be placed on ensuring that computational tools offer robust platforms for
                    comparing experimental results and data across diverse studies. Many domain tools suffer from
                    inadequate
                    documentation, limited extensibility, and varying degrees of accuracy in data representation. This
                    lack
                    of standardization in biological research, in particular, diminishes the potential for
                    groundbreaking
                    insights and discoveries while also complicating domain scientists' ability to experiment, compare
                    findings, and confidently trust results across different studies.
                </p>
                <p>
                    Through several examples of tools in the biology domain, we demonstrate the issues that can arise in
                    these types of community-built domain-specific applications. Despite their open-source nature, we
                    note
                    issues related to transparency and accessibility resulting in unexpected behaviors that required
                    direct
                    engagement with developers to resolve. This experience underscores the importance of deeper openness
                    and
                    clarity in scientific software to ensure robustness and reliability in computational analyses.
                </p>
                <p>
                    Finally, we share several lessons learned that extend to research software in general and discuss
                    suggestions for the community.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading21">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse21"
                    aria-expanded="false" aria-controls="collapse21">
                    "Web Visualization Tools for AI at the Edge: the Latest Features and Functionality", Neal Conrad,
                    Yongho
                    Kim, Francisco Lozano, Sean Shahkarami, Rajesh Sankaran, Nicola Ferrier, Pete Beckman
                </button>
            </h5>
        </div>

        <div id="collapse21" class="collapse" aria-labelledby="heading21" data-parent="#accordion">
            <div class="card-body">
                <p>Waggle/Sage cyberinfrastructure empowers researchers to deploy software-defined instrumentation at
                    the
                    edge, enabling real-time computation and AI inferencing for a wide range of applications. These
                    applications include the studies of: wildlife populations, urban flooding and traffic flow, the
                    impacts
                    of climate change, wildfire prediction, and more. In this poster, we'll focus on some of the
                    web-based
                    (TypeScript) data visualization and analysis tools available for scientists and developers. These
                    visualization components can be used for monitoring jobs, performance, and resource utilization
                    across
                    nodes; the inspection and validation of data and inferences; and, finally, ensuring the reliability
                    and
                    stability of hardware and software across the platform.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading22">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse22"
                    aria-expanded="false" aria-controls="collapse22">
                    "The value of RSEs for smaller-scale research needs: a vignette", Susan Christine Massey
                </button>
            </h5>
        </div>

        <div id="collapse22" class="collapse" aria-labelledby="heading22" data-parent="#accordion">
            <div class="card-body">
                <p>Many articles and discussions regarding the growth of Research Software Engineering (RSE) have
                    focused on
                    the importance of the field for supporting large-scale efforts with long-term support needs. That is
                    rightly so, and yet it is important not to overlook building up RSE in our institutions as a vital
                    resource for smaller projects with short-term needs, as well. As a cyberinfrastructure (CI)
                    facilitator
                    in the Cross-Institutional Research Engagement Network (CIREN; https://ciren.asu.edu), a program for
                    training and professional development of CI facilitators, including RSEs, I worked on a facilitation
                    and
                    RSE project with an ASU investigator using publicly available data from TCGA (the Cancer Genome
                    Atlas).
                    This project required some data wrangling (to make it readily usable) and a pilot analysis to assess
                    the
                    utility of using TCGA datasets to answer the particular research question at hand. While the
                    investigator and some lab members had the requisite skills to do this work, they did not have
                    sufficient
                    capacity. On the other hand, there were undergraduate students interested in pursuing the research
                    question, but they did not yet have a sufficient level of skill, having just completed an
                    introductory
                    undergraduate course to bioinformatic analysis in R. Thus, I, as an RSE, was able to bridge the
                    needs
                    gap and develop a pipeline that the undergraduate students could use to pursue the research
                    question,
                    facilitating their participation in research by lowering the barrier to entry. Additionally, and
                    importantly to the goals of CIREN, this project also provided the CI facilitator (myself) an
                    opportunity
                    to build professional skills with the assistance of a mentor, such as negotiating a workplan with
                    the
                    primary researcher to set out clear shared expectations. This example helps to illustrate the
                    advantages
                    of engaging with smaller projects for developing the professional skills of RSEs, and CI
                    professionals
                    more broadly, as well as highlight the value of CI professionals for supporting abundant
                    smaller-scale
                    research software needs on university campuses.
                </p>
                <p>
                    This work was supported by the Cross-Institutional Research Engagement Network for
                    cyberinfrastructure
                    (CI) facilitators (CIREN) NSF Award #2230108. I would also like to acknowledge and thank ASU
                    Professor
                    Melissa Wilson for giving me the opportunity to work on this project in support of her research.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading23">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse23"
                    aria-expanded="false" aria-controls="collapse23">
                    "Testing Open Source Software on Secure Hardware Using GitHub Actions", Eric Ho
                </button>
            </h5>
        </div>

        <div id="collapse23" class="collapse" aria-labelledby="heading23" data-parent="#accordion">
            <div class="card-body">
                <p>Software testing for open-sourced projects is a problem that is prevalent throughout the entire
                    software development industry. This problem has been tackled by many different programs
                    such as Jenkins, Travis CI, or Semaphore. However, these solutions are not adequate when the
                    software tests must be performed on hardware that is attractive to attackers, behind restrictive
                    networks, and is shared by numerous projects and users.
                </p>
                <p>
                    Our project, AutoTester2, aims to tackle these issues and provide a way for projects to
                    automatically test software changes from unknown developers, while ensuring the security and
                    reliability of the targeted hardware. This is done using ephemeral GitHub Self-hosted runners,
                    custom environment containers, and linux systemd services.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading24">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse24"
                    aria-expanded="false" aria-controls="collapse24">
                    "The Journal of Open Source Software", Patrick Diehl, Daniel S. Katz, Gabriela Alessio Robles,
                    Stefan
                    Appelhoff, Warrick Ball, Mojtaba Barzegari, Johanna Bayer, Juanjo Bazán, Sophie Beck, Sebastian
                    Benthall, Eloisa Bentivegna, Monica Bobra, Frederick Boehm, Sébastien Boisgérault, Josh Borrow, Teon
                    Brooks, Jed Brown, Philip Cardiff, Taher Chegini, Beatriz Costa Gomes, Pierre de Buyl, Renata Diaz,
                    Axel
                    Donath, Elizabeth DuPre, Matthew Feickert, Vissarion Fisikopoulos, Martin Fleischmann, Samuel
                    Forbes,
                    Dan Foreman-Mackey, Jarvist Moore Frost, Nikoleta Glynatsi, Jeff Gostick, Rohit Goswami, Richard
                    Gowers,
                    Hugo Gruson, Olivia Guest, Jayaram Hariharan, Gracielle Higino, Susan Holmes, Luiz Irber, Adam R.
                    Jensen, Mark A. Jensen, Prashant K Jha, Sehrish Kanwal, Vincent Knight, Olexandr Konovalov, Rachel
                    Kurchin, Paul La Plante, Oskar Laverny, Hugo Ledoux, Christopher R. Madan, Michael Mahoney, Brian
                    McFee,
                    Rocco Meli, Sarath Menon, Antonia Mey, Tristan Miller, Kevin M. Moerman, Ivelina Momcheva, Yasmin
                    Mzayek, Kanishka B. Narayan, Kyle Niemeyer, Lorena Pantano, Andrew Quinn, AHM Mahfuzur Rahman, Julia
                    Romanowska, Kelly Rowland, Anjali Sandip, Mehmet Hakan Satman, Jonny Saunders, Fabian Scheipl, Jacob
                    Schreiber, Hauke Schulz, Adi Singh, Arfon Smith, Dana Solav, Claudia Solis-Lemus, Charlotte Soneson,
                    Øystein Sørensen, Andrew Stewart, Marcel Stimberg, Fabian-Robert Stöter, Fei Tao, George K.
                    Thiruvathukal, Kristen Thyng, Ana Trisovic, Adam Tyson, Chris Vernon, Marcos Vital, Rachel Wegener,
                    Britta Westner, Lucy Whalley, Frauke Wiese, Mengqi Zhao, and Bonan Zhu
                </button>
            </h5>
        </div>

        <div id="collapse24" class="collapse" aria-labelledby="heading24" data-parent="#accordion">
            <div class="card-body">
                <p>The Journal of Open Source Software (JOSS) is an academic journal (ISSN 2475-9066) that publishes
                    short
                    articles describing open source software with a research application. The review process includes
                    checking that the software itself meets some modern standards, including having documentation, tests
                    (preferably automated), and community guidelines. This way, JOSS aims to give software creators a
                    citable artefact through which their research contribution can be recognised, and to encourage them
                    to
                    use good software practice.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading25">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse25"
                    aria-expanded="false" aria-controls="collapse25">
                    "INnovative Training Enabled by a Research Software Engineering Community of Trainers (INTERSECT)",
                    Jeffrey C. Carver, Ian A. Cosden
                </button>
            </h5>
        </div>

        <div id="collapse25" class="collapse" aria-labelledby="heading25" data-parent="#accordion">
            <div class="card-body">
                <p>To address the lack of software development and engineering training for intermediate and advanced
                    developers of research software, we present the NSF-sponsored INnovative Training Enabled by a
                    Research
                    Software Engineering Community of Trainers (INTERSECT), which delivers software development and
                    engineering training to intermediate and advanced developers of research software. INTERSECT has
                    three
                    main goals:
                </p>

                <ol>
                    <li>Develop an open-source modular training framework conducive to community contribution</li>
                    <li>Deliver RSE-led research software engineering training targeting research software developers
                    </li>
                    <li>Grow and deepen the connections within the national community of Research Software Engineers
                    </li>
                </ol>
                <p>
                    The majority of INTERSECT's funded focus is on activities surrounding the development and delivery
                    of
                    higher-level specialized research software engineering training.
                </p>
                <p>
                    In July 2023, we held our first INTERSECT-sponsored Research Software Engineering Bootcamp
                    (https://intersect-training.org/bootcamp23/) at Princeton University. The bootcamp included 35
                    participants from a broad range of US-based institutions representing a diverse set of research
                    domains.
                    The 4.5-day bootcamp consisted of a series of stand-alone hands-on training modules. We designed the
                    modules to be related, but not to rely on successful completion or understanding of previous
                    modules.
                    The primary goal of this design was to allow others to use the modules as needed (either as
                    instructors
                    or as self-guided learners) without having to participate in the entire bootcamp.
                </p>
                <p>
                    The topics covered in the bootcamp modules were: Software Design, Packaging and Distribution,
                    Working
                    Collaboratively, Collaborative Git, Issue Tracking, Making Good Pull Requests, Documentation,
                    Project
                    Management, Licensing, Code Review & Pair Programming, Software Testing, and Continuous
                    Integration/Continuous Deployment.
                </p>
                <p>
                    We are organizing a second INTERSECT bootcamp in July 2024. We expect to again have approximately 35
                    attendees from a wide range of institutions covering a diverse set of research areas. Because the
                    format
                    and content of the first bootcamp was well-received, we plan to follow a very similar format for the
                    second workshop.
                </p>
                <p>
                    In this poster we will provide an overview of the INTERSECT project. We will provide more details on
                    the
                    content of the bootcamp. We will discuss outcomes of both editions of the bootcamp, including
                    curriculum
                    specifics, lessons learned, participant survey results, and long term objectives. We will also
                    describe
                    how people can get involved as contributors or participants.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading26">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse26"
                    aria-expanded="false" aria-controls="collapse26">
                    "Securing Research Software: A Proposal for Threat Modeling", Matthew Armstrong, Jeffrey Carver,
                    Reed
                    Milewicz
                </button>
            </h5>
        </div>

        <div id="collapse26" class="collapse" aria-labelledby="heading26" data-parent="#accordion">
            <div class="card-body">
                <p>Research software today plays an integral role in the practice of science, and as the complexity and
                    wide-ranging impact of that software continues to grow, so too do concerns about software security.
                    In
                    industry, much attention has been paid to the concept of "shifting security left,” that is,
                    considering
                    security earlier in the software development life cycle (SDLC) rather than at the end. Developers
                    —RSEs
                    included— are non-experts in security, and a major aim of shifting security left is to introduce
                    security-enhancing practices that fit into ordinary developers' workflows. Case in point, threat
                    modeling is a security activity that identifies weaknesses and vulnerabilities during software
                    design
                    that serves as the foundation for the security life cycle. Compared to more complex security
                    activities,
                    threat modeling can be performed by non-security experts if given the proper guidance and support.
                </p>
                <p>
                    In the RSE space, security resources are limited and typically focused on more complex security
                    issues.
                    With the proper resources, we propose that RSEs can perform threat modeling with minimal extra
                    effort,
                    thus alleviating pressure on existing security resources and increasing the overall security posture
                    of
                    the team and organization. This poster presents the findings of a rapid literature review on the
                    applicability of threat modeling techniques during the software development lifecycle.
                </p>
                <p>
                    We performed a review of the relevant evidence, combining gray and peer-reviewed sources, focusing
                    on 22
                    high-quality works. Given that RSEs are underrepresented in the software engineering literature, we
                    analyzed available evidence on threat modeling in conventional software development and made a
                    preliminary assessment of the transferability of those findings to RSE contexts. In our review, we
                    answered the following research questions:
                </p>
                <ol>
                    <li>How is threat modeling incorporated into the development process?</li>
                    <li>How is the security impact of threat modeling during the software development process measured?
                    </li>
                    <li>What is the definition of threat modeling when performed during the software development
                        process?</li>
                    <li>What challenges do software developers face when threat modeling during the software development
                    </li>
                    process?
                    <li>How effective is threat modeling when performed during software development by non-experts in
                        security?</li>
                    <p>
                        The findings of this review will be used to develop a quick reference guide and educational
                        workshop for
                        RSEs to support their threat modeling efforts. This poster allows RSEs to learn more about
                        threat
                        modeling and our work. We invite participants to provide feedback to guide our future work.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading27">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse27"
                    aria-expanded="false" aria-controls="collapse27">
                    "Research Software Engineering as a Service: Scientific Software Engineering Center (SSEC) @
                    University
                    of Washington", Niki Burggraf, Cordero Core
                </button>
            </h5>
        </div>

        <div id="collapse27" class="collapse" aria-labelledby="heading27" data-parent="#accordion">
            <div class="card-body">
                <p>The Scientific Software Engineering Center (SSEC) at the University of Washington’s eScience
                    Institute works with researchers across various disciplines to build robust software that bolsters
                    inquiry and builds community. The resulting tools are open source, maintainable and reusable,
                    designed to sustain and lead to scientific breakthroughs.
                </p>
                <p>
                    The poster we propose to present would highlight not just our model of engaging as software
                    engineers with the research community, but also highlight several of our successfully graduated
                    projects, spanning diverse research domains from neurobiology to seismology to conservation
                    efforts and beyond.
                </p>
                <p>
                    By demonstrating prior successes and discussing how we achieve them, we hope to spark
                    conversations about our approach to supporting researchers and show an interesting approach
                    to research software engineering.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading28">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse28"
                    aria-expanded="false" aria-controls="collapse28">
                    "Software Stewardship at DOE/ASCR and the Role of RSEs within it", Keith Beattie, Dan Gunter, Anshu
                    Dubey, Rinku Gupta, David E. Bernholdt, Greg Watson
                </button>
            </h5>
        </div>

        <div id="collapse28" class="collapse" aria-labelledby="heading28" data-parent="#accordion">
            <div class="card-body">
                <p>The U.S. Department of Energy Office of Advanced Scientific Computing Research (ASCR) has launched a
                    new
                    initiative called the Next-Generation Scientific Software Technologies (NGSST) program for
                    scientific
                    software stewardship which is the first of its kind for the office. Under this initiative, several
                    software stewardship organizations (SSOs) have been funded and a couple are waiting in the wings.
                    These
                    include COLABS, CORSA, PESO, S4PST, STEP, and SWAS, together with the FASTMath and RAPIDS SciDAC
                    Institutes. The SSOs are in the process of standing up a "Consortium for the Advancement of
                    Scientific
                    Software” (CASS) with the mission of stewarding and advancing the current and future ecosystem of
                    scientific computing software, including products developed or enhanced as part of the Exascale
                    Computing Project (ECP) Software Technologies.
                </p>
                <p>
                    One of the SSOs in CASS, COLABS is tasked with activities that are of direct interest to US-RSE such
                    as
                    building a community of practice for RSEs engaged in software-related activities at the national
                    laboratories. Additional activities of common interest include training and workforce development.
                    These
                    activities include the determination of skills needed to create and maintain high-quality software
                    that
                    is well tested and carefully stewarded throughout its lifecycle, curating available training
                    resources
                    and creating new resources where none exist, understanding and formulating pathways for training
                    that
                    not only prepare the workforce for the task at hand but also expand the recruitment pool by enabling
                    training modules to fill the gap in skills where needed.
                </p>
                <p>
                    In this poster, we will explain the motivation and vision for NGSST and CASS, and also the role that
                    CASS would play in the broader scientific software community. We will also describe our vision for
                    how
                    CASS in general and COLABS, in particular, will conduct activities related to their mission, and how
                    they will engage with US-RSE in these activities.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading29">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse29"
                    aria-expanded="false" aria-controls="collapse29">
                    "Better Architecture, Better Software, Better Research", Nasir Eisty, Myra B. Cohen, Neil Chue Hong,
                    Ryan C. Cocking, Stephan Druskat, Michael Felderer, Samuel Grayson, Lars Grunske, Wilhelm
                    Hasselbring,
                    Sarah Harris, Jan Linxweiler, Colin C. Venters
                </button>
            </h5>
        </div>

        <div id="collapse29" class="collapse" aria-labelledby="heading29" data-parent="#accordion">
            <div class="card-body">
                <p>Research software requires flexible and modular architectures to accommodate rapid evolution
                    and interdisciplinary collaboration. Software architectures are fundamental to the
                    development of technically sustainable software systems as they are the primary carrier of
                    architecturally significant requirements, such as extensibility and maintainability, and influence
                    how developers are able to understand, analyse and test a software system. Hence, research
                    software engineering should focus on architectural metrics to evaluate and improve their code.
                    Architectural metrics in research software ensure the software's scalability, performance,
                    maintainability, and overall quality, facilitating reproducible and reliable research outcomes.
                    We already have many metrics and tools to measure and improve the quality of software
                    architecture. However, we hypothesize that research software is often built using limited
                    resources and without a long-term vision for maintainability, which leads to a range of rotten
                    symptoms, including software rigidity, fragility, immobility, and viscosity, which results in
                    high-maintenance and evolution costs, which are the foundation for software decay and death in
                    all software investment.
                </p>
                <p>
                    In a recent Dagstuhl seminar, we, the authors (consisting of software engineers, software
                    engineering researchers, and research software engineers), discussed key software metrics
                    such as code smells, duplication, test coverage, cyclomatic complexity, etc., and how these can
                    be used to improve research software. We explored our hypothesis by applying existing static
                    analysis tools to a few open-source research software repositories. We discovered high
                    cyclomatic complexity, large God classes, cyclic dependencies, improper inheritance, modularity
                    violations, propagation error-prone and change-prone issues, and low test coverage, which
                    confirmed non-trivial maintenance and evolution costs. We concluded that we should explore
                    this idea further and that there may be an opportunity to build better tools and techniques to
                    help research software engineers improve the architecture of their software, which in turn can
                    improve its quality.
                </p>
                <p>
                    In this poster presentation, we will demonstrate the critical role of software architecture in
                    ensuring software quality. We will explore its importance for research software and how it can
                    significantly enhance the quality of these systems. Research software can become more
                    maintainable, scalable, and reliable by adopting software architecture principles. We will
                    illustrate the tangible benefits and practical applications of adopting robust software architecture
                    principles through detailed example analyses of real research software projects. Attendees will
                    gain insights into best practices and strategies for integrating architectural frameworks into their
                    research software development processes.
                </p>
                <p>
                    Our goal is to spread appropriate software architecture knowledge among research software
                    engineers, highlighting its transformative impact on research outcomes and the sustainability of
                    software projects. By adopting these principles, research teams can ensure their software is
                    better equipped to handle future challenges, fostering innovation and collaboration in the
                    research software community.</p>
            </div>
        </div>
    </div>

    <div class="card">
        <div class="card-header" id="heading30">
            <h5 class="mb-0">
                <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse30"
                    aria-expanded="false" aria-controls="collapse30">
                    "Exploring the RSE-verse: visualizing the complexity of RSE taxonomy beyond the “research vs
                    software”
                    binary", Ludovico Bianchi, Mikaela Cashman
                </button>
            </h5>
        </div>

        <div id="collapse30" class="collapse" aria-labelledby="heading30" data-parent="#accordion">
            <div class="card-body">
                <p>For many people who identify themselves as one, the term "Research Software Engineer” (RSE) often
                    feels,
                    almost paradoxically, both immediately recognizable and hard to define at the same time. Most if not
                    all
                    of the common definitions share a sense of RSEs as existing "somewhere in the middle” between
                    research
                    and software engineering. If we imagine a 1-dimensional axis with "pure researcher” on one end and
                    "pure
                    software engineer” on the other, classifying any of the countless RSE flavors [*] would only be a
                    matter
                    of finding the right set of points along this axis. However, while this model is generally
                    successful in
                    representing the core aspect of the RSE role, its limitations become apparent when examined more
                    closely. How should such "RSE coordinates” be chosen? Can a quantitative, or at least clearly
                    defined,
                    set of categories be defined at all? Are the "researcher” and "software engineer” really so distinct
                    and
                    unambiguously mutually exclusive that they can be used as opposite ends of a spectrum? Can the
                    complexity of the RSE-space be captured to a useful degree by a single dimension? When does one
                    cross
                    from one polar end of the spectrum to an RSE? Can one exist in multiple dimensions?
                </p>
                <p>
                    We believe that beyond the abstract intellectual curiosity driving the desire for more effective RSE
                    taxonomies, these limitations also lead to concrete challenges for the inclusiveness of our
                    community,
                    as people who don't see themselves as fitting neatly within these restrictive boundaries might
                    interpret
                    the existing definitions (consciously or subconsciously) as a sign that they don't belong in it. Our
                    poster will be centered around exploring the limitations of the "research vs software engineering”
                    spectrum described above, and what possible alternatives might be used instead, building on a
                    multi-year
                    ongoing interest in this question, including participation in a recent Dagstuhl seminar bringing
                    together RSEs and software engineering researchers (SERs)[1], as well as personal experiences from
                    ourselves, collaborators, and professional networks.
                </p>
                <p>
                    [*] RSE flavors: There exist many flavors of interests tangent to RSEs either actively involved in
                    the
                    community or should be such as: software engineering, research in software engineering, RSE
                    research,
                    training & education, funding, community building, and user experience. Simultaneously, there are
                    many
                    flavors within RSEs such as team size, team dynamics (single RSE to many RSEs), job titles, phase of
                    software developed (prototype to production), research domain (fixed or variable).</p>
            </div>
        </div>
    </div>
</div>
