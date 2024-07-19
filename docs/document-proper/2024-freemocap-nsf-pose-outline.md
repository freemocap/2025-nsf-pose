# 2024 FreeMoCap NSF POSE 

## **Title**: *POSE: PHASE II: The Free Motion Capture (FreeMoCap) Project*

## Project Description 

### The FreeMoCap Project
#### Specific Product/artifact(s)
   - FreeMoCap Software
     - Poly-repo structure
     - Composed of various sub-skelly repos, each of which:
       - Can operate in a standalone format
       - Matches general architecture and CI/CD structure of parent `freemocap` software 
   - Federated datasets
     - e.g. Users able to 'donate' their data, while retaining ownership (earning divdends) 
   - Co-op ML/AI model(s)
     - Train our own CNN Tracker and LLM via 'Federated learning' scheme 
     - Architecture allows any user to train/fine-tune the FMC Base Models using their private data, OPTIONALLY contribute updated model weights to the FMC-Org (e.g. see [`Flower`](https://flower.ai))
   - Educational materials and documentation
     - Providing best-available educational materials, tutorials, and demos for related areas
       - Tech (e.g. Computer vision, Cameras, CNNs, etc)
       - Math (e.g. Linear algebra, timeseries analysis, computational geometry, kinematic/kinetic analysis)
       - Visualization (e.g. data visualization, animation, etc)
       - Science (e.g. human/animal movement, perception/action, etc )
#### Guiding Principles
  - Universal Design
    - When anyone can use it, everyone benefits
    - Same tool for 0XP as for professional
    - "The [aspirational] goal of creating a system that serves the needs of a professional research scientist while remaining intuitive to a 13-year-old with no technical training and no outside assistance"
#### Current Context
- Technical landscape
- Social landscape
- Current FreeMoCap OSE status
#### Long-term vision
- Fully integrated FOSS platform for Laser Skeleton research/recording
  - Fully-body mocap
  - 3d Gaze
  - Integrated laser skeleton
  - Can also serve as a generic Computer Vision platform
- Global community of freemocap student/educators and user/developers
- Economically self-sustaining combination research/software development institute supporting:
  - Support and development for core software(s)
  - Research in related fields
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

#### Potential impact
- Lots!

### The FreeMoCap Foundation
- Organizational structure 
  - Worker oriented structure (co-op of some kind)
    - e.g. Haber, Michael, The New Activist Non-Profits: Four Models Breaking from the Non-Profit Industrial Complex (May 15, 2019). University of Miami Law Review, Vol. 73, 2019, Hofstra Univ. Legal Studies Research Paper No. 2019-07, Available at SSRN: https://ssrn.com/abstract=3388752
- Governance
  - 501c3 incorporation documents and bylaws for org
  - Explicitly crib from numpy or other big project for their gov/docs 
- Community Engagement 
- Transparency
- Finances (e.g. Backyard Brains 'open finances' model)
- 
    

### Building the FMC OSE
#### Ecosystem establishment and growth plan
  - Current community
  - growth plans/metrics
#### Organizational governance structure
  - FMC Org governance
    - Official 501c3 bylaws 
    - Non-profit coop stuff (from the tiktok guy's references)
  - FMC FOSS governance
    - explicitly crib from numpy, and other bigg'ns
  - Licensing model
    - AGPLv3 for all repos owned by FMC-Foundation
    - Exclusive sub-licensing rights to SkellyTech
      - SkellyTech handles B2B license agreement, whereby we offer software using non-AGPLv3 license
        - Cost dependent on 'distance' from AGPLv3 (AGPL -> GPL -> LGPL -> Apache/MIT -> ... -> Proprietary)
      - Can offer sub-license agreement for existing software, or to create custom software solutions
    
#### Methods for evaluating OSE's effectiveness
  - Community growth metrics
    - Raw numbers (more users is good)
    - Global distribution and spread should match popultion density
    - Individual user trajectories
      - Minimize 'bounce' (Single pings)
      - Maximize 'velocity' (`extracted user growth` non-stagnant, e.g. anti-paradox-of-active-user protocols)
  - Software quality
    - Generic validation metrics should be strictly monotonically increasing
      - i.e. global measure of 'goodness' of mocap data should ALWAYS increase over time
#### Security and Privacy 
- Fully offline local processing
- Google Cloud Platform for secrets management
- Matrix homeserver for privacy, security, consistency 
- Full instruction set on how to duplicate infrastructure with documentation and tutorials
#### Community building  
- Users
  - Students
  - Artists
  - Scientists
  - Clinicians
- Intellectual Content Creators
  - Software developer
    - Core
    - Visualization
    - Analysis
  - Creator Users
    - Artistic
      - Animation
      - Video Games
      - Performance (dance)
  - Community helpers 
    - Moderation
    - Troubleshooting and technical support
    - Encouraging newcomers 
- OS Community building components:
  - recruitment
  - motivation
  - mentoring
  - managing
  - mediating disputes
  - 
#### Activities to Sustain the Ecosystem
##### Annual Workshop: FreeMoCamp 💀⛺
- Inspirations: 
  - Neuromatch (for virtual component)
  - Cold spring harbor (short term research project/workshop timeline)
  - Get an example of a hackathon from the Endurance crew
- In person & Virtual
  - Held at YMCA summer camp, or similar
    - All inclusive ticket - lodging and food handled by summer camp facilities
  - Online component via dedicated Element space (with Slack/Discord bridges)
  - ANYONE can view all online materials, and follow along activities (encouraging conversationin public server)
  - Paid online participants may engage directly in the dedicated event space, and will get direct engagement with folks at the in-person event (for troubleshooting/planning/etc)
  - Pricing
    - Corpo pricing ->  100% standard price (Set high enough to make the lowest pay tiers make sense)
    - Academic pricing -> 50% standard price
    - Community members (defined by badges and community participation) -> 25% Standard price 
    - Additional **STEEP** discounts and scholarship programs for students, educators, researchers, artists, etc
      - Minimum price w/o scholarship = break-even price per participant
  - Combination hackathon, training workshop, and scientific conference on 'fully body movement research'
- Participants in teams
  - Plan and collect a data set
  - Analyze and present results 
  - Encourage collaboration and data sharing between teams
  - Offer training/presentation 'tracks' for
    - Data collection
      - Understand and use the core software
    - Data analysis 
      - Analyze and computationally model data
    - Data visualization (and animation/art)
      - Create visualizations and animations from freemocap data

##### Community Challenges
- Offer a prompt for a kind of movement/activity to record
  - Community works to record the best entry, submitted via Discord/Element/Freemocap.org
    - Community votes in 'Eurovision style'
      - i.e. each member has a fixed number of voting points to distribute among entries
      - Maybe **Badges** provide additional voting points?

##### Gamified documentation/software training

  - Offer **Badges** and stuff in discord for milestones, i.e.
    - First contact - open the software
    - First record - Anything recorded
    - First success - Successful recording
    - e.g. also calibration, data analysis, PR, etc
  - Apply badges in Discord/Element server (associated with a `freemocap.org` account?)
    - Badges offer ability to send 'top level' messages to otherwise view-only channels (i.e technical spaces) 
      - Anyone can create a **thread** from a top-level message though
      - The idea would be to create spaces where higher XP folk can talk about complicated stuff without distraction [WorkingInPublic]
      - But also LowerXP folk can still see the conversations and ask questions (Maybe make it easy to summon SkellyBot to explain a message/conversation 🤔)
    - 




###  A Fully Developed OSE
- The Product
- Governance
- Documentation
- Core Maintainers 
- Onboarding
  - Users
  - Developers
  - Community managers
- Developer Community
- Distributed development model
    - Feature development
    - Defect management
    - Core architecture
    - Community maintenance
    - Testing and evaluation
      - Stability (automatic test framework)
      - Diagnostics
        - Validation of core measurements
        - Resources needed (minimal hardware specs to run minimal, default, and max settings)
    - 
