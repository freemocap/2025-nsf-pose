# *POSE: PHASE II: The Free Motion Capture (FreeMoCap) Project*

## Introduction
Gap/Need/Hero statements

## Intellectual Merit
How we will advance knowledge

## Broader Impacts
How we will help the world

## Context of the OSE
### Current Context
#### Technogical context
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
#### Social context
  - Corporate mistrust
  - Privacy violations
  - Worker/social exploitation
#### Ethical context
  - Risk of future corporate conglomoration of technology
  - Need for decentralized systems
    - Clowdstrike outages
    - Openpose dead-project status
  - Rise of AI 
    - Liklihood of future violations
  - Need for decentralized user-directed  foss 
  - Inaccessiblity of science and technogy
    - Growing Gaps 
      - (See NSF Strategic plans)
##### The problem of universities
- Exclusionary by design
- Ever hungry corporate engine that driven by student debt
  - Tuition room and board
  - Overhead charges
- 'Education as a filter' \cite{arrow1970}
  - Need for expansive training methods
- The 'banking model' of education
  - Paolo friere
##### The problem of cottage industries
- Current system does not reward necessary activites to build and sustain an OSE
##### The problem of publication (cite that guy's blog)
- The story of Grease Pencil

### Need and Gap
  - Current model not fit for present and future needs
  - Need alternative models, organizations, infrastructures for science and education
    - Generative and self sustaining
      - Von Neumann machine - Sustainibility through replicability 
  - Two Loops theory of social progress
    - Not saying we should burn it all to the ground
    - It's already burning
    - We need to build a better ship
      - f-ing ASAP

## Long Term Vision
Describe the Ideal Perfect Future vision of... 

## Guiding Principles 
### Universal Design
- "When anyone can use it, everyone benefits"
- Same tool for 0XP as for professional
- "The [aspirational goal] of creating a system that serves the needs of a professional research scientist while remaining intuitive to a 13-year-old with no technical training and no outside assistance"
- **Sustainability through accessibility**
  - The key to sustainability is a growing, active, diverse, and vibrant userbase
  - Universal design attracts the widest possible userbase

### Universal Access
- **Education focus**
  - to avoid [paradox of the active user]
  - foster **long term user relationships**
  - encourage community engagement
    - Push user-student into 'zone of proximal development'
    - Provide easy access to resources (AI, static, community)
  - (see **AI Simulacrum Mentorship**)
  - Covert education:
    - Using the thing should teach you how it works
    - ZoPD & WYLTKM-bot
- **Maintain a True Minimum**
  - **Hardware**
    - Understand and maintain an option to run with the barest, most generic, and lowest-possible cost hardware,
    - Focus and maintain a [generic hardware] pipeline as the core path
      - Specialized tools (e.g. sterocam, eye trackiner, emg, forceplates) and proprietary options (e.g. iPhone, Basler/FLIR cameras, etc) added via plug-in system
      - Developed by community and/or upon client request 
  - **Software**    
    - Maintain and understand requirements for different outcomes (specific to defined use cases)     
      - Minimal requirements (to get a viable output)
      - Recommended requirements
        - Default default (for first-timers)
        - Per use case
          - Max speed (e.g. real-time, long, high-res, high-fps recordings)
          - Max accuracy (e.g. scientists, clincians, artistic/atheltic performance)
      - Maximum requirements
        - Specs beyond which you won't see an improvement in results 
        - Determined by understand technical bottlenecks
    - (see **Evaluation/Diagnostics**)
  - **Cost**
    - Methods to avoid price-barrier for paid aspects of FMC-F Activities (see #no artificial scarcity, # revenue streams)
    - [HumbleBundleModel] - Sliding scale pay options 
      - Recommended cost relative to break-even.
      - Give user option to allocate overage to different programs/departments
        - (by necessity, the recommendations will be followed if at all possible, adjustments may be made to ensure long term stability of the FMC-Org.
        - Its kinda like a voting system, but with money)
        - Support for:
          - New features
          - Specific projects
          - Scholarship/community grants program
          - Unspecified
      - Users requesting at-or-below cost must submit a request, which can be evaluated and supported via the 'communal support' scholarship/money bucket [CommunityGrantSystem]

### No artificial scarcity
- **"Knowledge is free, labor is unbelievable expensive"**
- Anything that can be duplicated infinitely is free for everyone
  - Software
  - Documentation
  - Static documentation/tutorial/educational material, etc
- Anything that is finite (or costs us money) can be charged
  - Human labor
    - Service models
      - Setup/planning
      - Dedicated technical support
    - Custom Software
  - Server side processing
    - Mocap data
    - AI LLM
  - Cloud storage
  - Camera hardware
 
### Community Focus
 - Emphasize that the core of the FMC-P is the community of users
 - The software artifacts are the fruit of the garden
 - Develop lateral connections, encourage growth, exploration, community support 


### Aggressively open source
- **"The open source community *is* what the scientific community pretends to be"**
- FOSS as a matter of moral imperative centered on the premises of Univerisal Design and Universal Access
  - Identification of strategic advantage within the contexts of FOSS being the 'right thing to do'
  - See "why open source misses the point"
- Encourage conversations around moral and ethical contexts of current context of the project and society at large
- **Morality without Zealotry**
  - We have our conversations clearly, but do not exclude those who misalign provided they aren't operating in opposition to our values
  - More about being aware, explicit, and intentional around moral and ethical decisions
  - Encourage and allow non-FOSS aligned activities through the `For-Profit` entity via B2B connections with external and spin-off entitities
    - Charge according to degree of mis-alignment with core values



## The FreeMoCap Project (FMC)
  - (include tables crossing each list with `current`, `in development`, `planned`)
 
### Artifacts
#### FreeMoCap Software(s)
- Core FreeMoCap Software(s)
    - Fully integrated FOSS platform for Laser Skeleton research/recording
      - Fully-body mocap 
        - realtime, animator and/or science focus
      - 3d Gaze
        - Webcam eye tracker
        - Plugin support for Pupil labs
        - VR/HMD support
      - Integrated laser skeleton
        - Matthis papers
      - Analysis and visualization suite
        - Blender, threeJS, R-studio support, skellymetrics reports
    - Can also serve as a generic Computer Vision platform
      - via recombination of other plugins around `skellycam` package
  - Composed of various sub-skelly repos, each of which:
    - Can operate in a standalone format or as plug-in to core software
    - Matches general architecture and CI/CD structure of parent `freemocap` software
    - Notables: 
      - SkellyCam (cameras)
      - SkellyTracker (2d tracking)
      - SkellyForge (3d reconstruction)
      - SkellyViewer (Viusualization and Observability)
      - SkellyBlender (Animation output via Blender addon)
      - SkellyMetrics (Analysis pipelines and 'report' building)
      - SkellyBot (AI and LLM support)
     
#### Documentation and Educational material
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
#### Data/Model Assets
  - See `FMC-F/Revenue/Federated and co-op datasets and models


### The FreeMoCap Community (FMC-C)
  - Broad and deep user base, integrating (>3d space):
    - User/Developers
    - Scientist/Artists
    - Student/Expert

  - Nurture long term user support, measured (consentually) via interactions with software and community spaces
    - Model User as a dynamic trajectory though the >3d space with axes:
      - User vs Developer
      - Scientist vs Artist
      - Novice vs Expert
      - also - any definable vector 
        - `Mentorship` vector
          - Defined as another user's UserStateVector (USV)
        - `Community` vector
          - Defined as median USV of users within a given community (with XP level > `threshold`)
      - Use rigid milestones, stochastic use-matching, and AI-analysis to determine each users's 'Status' relative to each sub-topic, sub-skill, sub-community
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
- Economically self-sustaining combination research/software development institute 
#### Organization
- 501c3 IRS certified public charity
- Follow bylaws
#### Governance
- Crib `numpy`'s notes
#### Responsibilities:
- Support and development for core software(s)
- Support Research in related fields (including training, mentorship, and grant support)
  - Neuroscience (human and non-human)
    - Motor control (mocap)
    - Visual/oculomotor neuroscience (eye tracking)
    - Developmental studies
  - Biomechanics
  - Applied clinical research
    - Injury rehabilitation
    - Gait and posture
    - Age-related
    - Developmental
  - Robotics
  - etc
- Manage annual workshop and conference 
  - `FreeMoCamp` is like summer camp, hackathon, workshop, education/training focus
  - `FreeMoCon` more of a conference vibe
  - Pair them up, so `FreeMoCamp` runs during the week and leads straight into `FreeMoCon` on the weekend
- Handle security, privacy of data, codebase, and user info
- Pay salaries of a core set of maintainer/developers
- Offer contract work to the FreeMoCap Community
  
#### Revenue streams
  - Federated/Co-op models and datasets
    - Federated datasets
      - e.g. Users able to 'donate' their data, while retaining ownership (earning divdends)
    - ML/AI model(s)
      - Train our own CNN Tracker and LLM via 'Federated learning' scheme
      - Architecture allows any user to train/fine-tune the FMC Base Models using their private data, OPTIONALLY contribute updated model weights to the FMC-Org (e.g. see [`Flower`](https://flower.ai))
  - For Profit sub-entity
    - `Skellytech, LLC`
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
- FreeMoCamp/Con
- Userbase analysis
- Community Challenges
### Organization and Governance
- Build administrative infrastructure
#### Development
### Continuous Development, Integration, Evaluation Model 
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
#### **"Sustainability through replicability"**
  - Maintain organizational documents, Standard Operating Procedures (SOPs), and eductional outreach to encourage others to create organizations with similar stucture to FMC-F
  - Good for other people from wildly different domains (not relevant to FMC-F mission)
  - Could spawn sub-orgs from with FMC-F (optionally existing within FMC-F umbrella, either as non-profit or for-profit org)
___ 



