# *POSE: PHASE II: The Free Motion Capture (FreeMoCap) Project*

## Introduction
Gap/Need/Hero statements

### Intellectual Merit
How we will advance knowledge

### Broader Impact
How we will help the world

### Context of the OSE
#### Context
- The problem of universities
  - Exclusionary by design
  - Ever hungry corporate engine that driven by student debt
    - Tuition room and board
    - Overhead charges
  - 'Education as a filter' \cite{arrow1970}
    - Need for expansive training methods
  - The 'banking model'
- 'The open source community *is* what the scientific community pretends to be'
  - The problem of cottage industries
  - The problem of publication (cite that guy's blog)
  - The story of Grease Pencil
#### Vision
- Guiding Principles and Long Term Vision for the OSE
  - Universal Design
  - Knowledge is Free
  - No artificial scarcity
- Societal or National Need for the OSE
  - Current model not fit for present and future needs
  - Need alternative models, organizations, infrastructures for science and education
    - Generative and self sustaining
      - Von Neumann machine - Sustainibility through replicability 
  - Two Loops theory of social progress
- Anticipated Broader Impacts of the OSE

## Long Term Vision for
Describe the Ideal Perfect Future vision of... 

### The FreeMoCap Project (FMC-P)
  (include tables crossing each list with `current`, `in development`, `planned`)
#### Artifacts
##### FreeMoCap Software(s)
  - Core FreeMoCap Software(s)
    - Composed of various sub-skelly repos, each of which:
      - Can operate in a standalone format
      - Matches general architecture and CI/CD structure of parent `freemocap` software
##### Documentation and Educational material
  -  Providing best-available educational materials, tutorials, and demos for related areas (link to existing educational material for general topics, focus on our specific use case)
    - Tech (e.g. Computer vision, Cameras, CNNs, etc)
    - Math (e.g. Linear algebra, timeseries analysis, computational geometry, kinematic/ kinetic analysis)
    - Visualization (e.g. data visualization, animation, etc)
    - Science (e.g. human/animal movement, perception/action, etc )
  - Static Docs
    - freemocap.org/documentation
    - Tutorials
    - Recorded lectures and live streams
  - AI-assisted documentation
    - SkellyBot
      - Lives on freemocap.org chat
      - Lives in Community server (summonable, requests consent before interacting with new users)
      - Lives in local app (either connect to existing API via API key, run a local model, or use the FMC-F SkellyModel endpoint (requires account))
      - See [Simulacrum Support]()
  
  - Infrastructure Table:
      - Technical Capacities 
      - Infrastructure
      - Tools and Frameworks
      - Documentation and covert education
  
### The FreeMoCap Community (FMC-C)
  - Broad and deep user base, integrating (<3d space):
    - User/Developers
    - Scientist/Artists
    - Student/Expert
    - Any definable vector 
      - `Mentorship` vector
        - Defined as another user's UserStateVector (USV)
      - `Community` vector
        - Defined as median USV of users within a given community (with XP level > `threshold`)
  - Nurture long term user support, measured (consentually) via interactions with software and community spaces
    - Model as a trajectory though the 3d space defined above
      - User state on each level: 
        - Proficiency
        - Interest
        - Experience
      - Mis-matches define 'gentle pressure' vectors
      - PID controller with stochastic noise encouraging exploration into 'zones of proximal development' (ZoPD)
    - Active social community space where users can share progress and ask questions
    - Simulacrum support - AI assistant (SkellyBot)
      - AI modeled to provide a SIMULATION of real human support 
      - Explicitly AI at all times, intended to provide infinitely duplicable simulation of replicable text based emotional labor
      - SkellyBot
        - Onboarding-Bot
          - Goals:
            - Primary: Introduce new users to software
              - Onboarding tutorials
              - WYLTKM-bot
              - RTFM-bot
            - Secondary: Encourage engagement with community
              - Community Server spaces
              - Community Activitities
              - FreeMoCamp/Con
        - ReadTheManualBot (RTFM-bot)
          - Goals:
            - Primary: Help them learn and run the software
            - Secondary: Avoid 'paradox of active user' (offer quicker paths to victory)
          - RAG model
            - Docs (FreeMoCap Technical Docs)
            - Logs (User current and past logs, Github Issues, Server `Help Requests` channel)
            - Images (e.g. from cameras, videos, or screenshots)
            - Data (`npy`, `csv`, `sql`, `json`, with helper readers)
        - WouldYouLikeToKnowMoreBot (WYLTKM-Bot)
          - RAG model
            - Docs (FreeMoCap Educational Docs, blog, YT transcripts, Server chat records)
            - Wikipedia
            - Search Engine Request (SerPAPI)


### The FreeMoCap Foundation (FMC-F)
  - 501c3
  - Indpendently support FreeMoCap Project/Community
  - Handle security, privacy of data, codebase,  and user info
  - Paying a core set of maintainer/developers
#### Revenue streams
  - Federated/Co-op models and datasets
    - Federated datasets
      - e.g. Users able to 'donate' their data, while retaining ownership (earning divdends)
    - ML/AI model(s)
      - Train our own CNN Tracker and LLM via 'Federated learning' scheme
      - Architecture allows any user to train/fine-tune the FMC Base Models using their private data, OPTIONALLY contribute updated model weights to the FMC-Org (e.g. see [`Flower`](https://flower.ai))
  - For Profit sub-entitie(s) 
    - `Skellytech`
      - B2B connections and sub-licensing of:
        - Core-software 
        - Derivative models (co-op data ownership)
      - Any arrangement that does not fall under the 'charitable activities' allowed by 501c3 guidelines
    - Spin-off companies (FreeMoCap as tech incubator)
      - Incubator support for FMCF member/students who want to start businesses or organizations based on freemocap related technology and tools
      - Offer umbrella support (we support them with our org infrastructure, e.g. grant support), or
      - Launchpad support (pathway to independence)
      - Offer exit (any time) and re-entry (if possoible) mechanisms
  - Manage grants, both for org (e.g. NSF POSE) and individual research grants for members of FMCF (e.g. R01's and F32's)
    - Offering extremly low overhead costs, relative to universities. e.g. 10-15%
  - Selling hardware/cameras
    - first, dropship standard cameras and packages (low-to-high quality)
    - later, develop custom cameras (including education focused cameras)
  - Donation drives 
    - Direct pushes
    - On checkout
  - Clients (Contracting from FMC community)
    - Custom code/software
    - Project planning and consultation 
    - Technical support
    - Direct teaching/training
  - Annual Workshop (FreeMoCamp)
  - Annual Conference (FreeMoCon)
  - Server-side processing
  - Cloud data storage


## Proposed actvitities
Activities to bring us from current status towards the Ideal Perfect status described above
### Ecosystem establishment and Growth
### Organization and Governance
### Continuous Development, Integration, Evaluation Model 
#### Development
  - Core:
    - Architecture
    - Functionality 
    - Observability
    - Usability
    - Accessibility
  
  - Bug Fixing
    - GH Issues and Comminity server
    - Encourage newcomers to assist with: 
      - Triage
      - RTFM requests
      - Sleuthing
  - Roadmaps
    - Skelly Enhancement Proposals (SEP's)
      - Like PEP system
      - Post in public forum (GH Discussion board? Bridge/sync with Community space)
      - Topics
        - Core
        - Feature request
        - Quality of Life request
        - Protocol change request (i.e. style guide, naming conventions)
        - Data model change
  - Add-on support
    - Plug-in system
      - Alternative to an existing core sub-skelly package
        - Must interoperate with existing architecture invisibly
      - Additional add-on extending core functionality 
        - Extends functionality from existing API
    - Templates provided per-sub-skelly-repo
      - Maintain consistent style-guide and consistent naming standards
       
#### Integration
  - Automated versioning/release cycle
  - `Git flow` version control model `CONTRIBUTING.md`
  - Backwards compatibility, deprecation and Long Term Support (LTS) versions
  
#### Evalution
- Testing 
  - Automated tests framework
    - Quick tests on commit to PR
    - Full tests on merge to `main`
    - Testing for:
      - stability (unit tests)
      - security (e.g. dependabot),
      - replicability (e.g. test datasets)
  - Validation
    - Is the core tool providing accurate measurements of world?
    - External Validation
      - Against 'Gold Standard' marker-based mocap (e.g. Qualisys)
      - Ideally using standard mocap validation techniques from clinical biomechanics (ISB?)
    - Internal Validation 
      - Validation within a given dataset via error residuals,i.e. 
        - Reprojection error (2d tracker validation)
        - Rigid body correction residuals (3d data validation)
  - Diagnostics
    - Minimal requirements to maximize accessibility
      - Understanding and clearly defining 'minimum  specs' to achieve viable output
      - Strive to decrease these minimums while remining mindful of trade-offs
      - Minimum reqs also define max speed, relevant to realtime applications 
    - High-water marks and benchmarks
      - What is the best performance possible with unconstrained time and resources?
        - Speed (real-time processing)
          - FPS on standardized PCs at Min, Rec, Max setttings
        - Accuracy (scientific applications)
          - Validation score on Min, Rec, Max settings


### Community Building

### Sustainability 
#### Definitions, Strategies, and Goals 
#### Metrics
___ 

# SCRATCH
- Sociotechnical landscape
- Technogical context
  - Capacities
    - Cutting Edge (Established methods)
    - Bleeding Edge (Promising advances)
    - Likely futures 
  - Related projects
    - Michael Black 
    - R. James Cotton 
    - MMPose
    - Deeplabcut
    - etc
- Social context
  - Corporate mistrust
  - Privacy violations
  - Worker/social exploitation
- Ethical context
  - Future conglomoration 
  - Need for decentralized systems
    - Clowdstrike outages
    - Openpose dead-project status
  - Rise of AI 
    - Liklihood of future violations
  - Need for decentralized user-directed  foss 
  - Inaccessiblity of science and technogy
  - Growing Gaps 
    - (See NSF Strategic plans)


