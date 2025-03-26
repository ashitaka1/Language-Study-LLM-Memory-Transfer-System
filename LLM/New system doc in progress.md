# Japanese Learning System Overview

## 1. System Foundations

### 1.1 Core Profile
*Conceptual framework defining learner characteristics - implemented in Stable Memory*

### 1.2 Terminology Framework

#### 1.2.1 Core Terminology
- **Aspiration Goal**: A broader, real-world objective providing context and motivation
  - Example: "Travel independently in Japan using Japanese"
  - Relationship: Guides selection of Capability Goals

- **Capability Goal**: A specific, measurable linguistic capability the learner aims to develop
  - Example: "Comprehend N3-level grammar in natural speech"
  - Relationship: Achieved through Activities

- **Target**: A specific, measurable milestone within a resource, content type, or skill area. Targets include concrete metrics, technique progression steps, or specific completion points.

  - **Note on Goals vs. Targets**: In this system, goals represent broad capability or aspiration statements (what you want to achieve), while targets represent specific, measurable milestones tied to individual resources or techniques (how you'll get there). Goals and targets work hierarchically—targets contribute to capability goals, which support aspirational goals.

- **Activity**: A discrete learning task undertaken to work towards capability goals
  - Example: "Sentence Writing Practice", "Shadowing"
  - Relationship: Implemented via Workflows

- **Resource**: Any external learning material or tool used during activities
  - Example: Textbooks, audio files, SRS systems
  - Relationship: Utilized within Activities

- **Workflow**: The step-by-step process for completing a specific activity
  - Example: Standard procedure for vocabulary mining
  - Relationship: Standardizes Activity execution

- **Skill Area**: A fundamental language capability category
  - Example: Reading, Writing, Listening, Speaking, Grammar, Vocabulary, Phonetics
  - Relationship: Groups related Activities and Capability Goals

- **Focus Area**: A specific aspect of language learning targeted for improvement
  - Example: Particle usage, Pitch accent, Kanji recognition
  - Relationship: Refines Skill Areas for targeted practice

- **SRS System**: Any spaced repetition system used to review and retain language elements
  - Example: WaniKani, Anki, BunPro
  - Relationship: Supports multiple Activities as a Resource

- **Queue**: An ordered list of items planned for future activities
  - Example: Grammar points to study, vocabulary to add to SRS
  - Relationship: Organizes content for upcoming Activities

#### 1.2.2 Expanded Terminology Framework

##### Activity Classification
- **Focus Activity**: Primary Activity directly aligned with Capability Goals
- **Foundation Activity**: Essential daily Activities maintaining progress during busy periods
- **Support Activity**: Secondary Activity enhancing other activities
- **Assessment Activity**: Activity designed to evaluate progress

##### Activity Components
- **Objective**: Specific learning goal of the Activity
- **Specific Steps**: Concrete actions to complete a particular Activity instance
- **Resources**: Materials and tools required for an Activity
- **Outcome Measures**: Metrics used to evaluate Activity success

##### Process Terminology

###### Structural Elements
- **System**: The overall learning framework and principles.
  - Relationship: Contains all other elements

- **Task Implementation**: The application of a Workflow to a specific learning instance.
  - Relationship: Specific instance of a Workflow

- **Protocol**: A standardized procedure for handling specific situations.
  - Relationship: Ensures consistency across Workflows

#### Planning Terminology

##### Time Frames
- **Planning Cycle**: The recurring time unit for organizing Activities (weekly).

- **Session**: A single continuous period of learning Activity.

##### Organization Elements
- **Priority Tier**: A priority classification level for Activities.

- **Skill Area**: A grouping of related Activities by language competency.
  - Same as Core Skill Area

- **Learning Domain**: Broader classification of knowledge areas.
  - Example: Grammar, Vocabulary, Cultural Context

### 1.3 Learning Modalities
- **Input**
  - Immersion activities (flexible)
  - Intensive study activities (scheduled)
  - Key focus: Comprehension development

- **Knowledge**
  - Grammar expansion
  - Vocabulary/Kanji acquisition
  - Phonetics/Pitch accent study
  - Key focus: System understanding

- **Output**
  - Writing practice
  - Speaking practice
  - Key focus: Production skills

## 2. Operational Framework

### 2.1 Learning Flow Model

#### 2.1.1 Core Framework
- **Goal-Driven Structure**: All learning efforts directed toward capability and aspiration goals
- **Dual-Mode Engagement**: All language content is engaged through two complementary modes:
  - **Study Mode**: Deliberate, structured interaction with language elements for conscious acquisition
  - **Immersion Mode**: Natural, contextual exposure to language for unconscious acquisition and reinforcement


#### 2.1.2 Core Pathways
The learning system operates through three fundamental pathways that reflect how language acquisition naturally occurs:
#### Systematic Study → Recognition (Top-Down Path)
This pathway begins with deliberate study of language components and builds toward recognition in authentic contexts.
- Study grammar patterns → Recognize them in natural input
- Learn vocabulary → Identify words in authentic contexts
- Study pronunciation rules → Recognize nuances in native speech
- Documentation: Occasional notation of recognition moments in activity logs

#### Natural Input → Resource Building (Bottom-Up Path)
This pathway begins with exposure to authentic language and extracts patterns for systematic reinforcement.
- Revisit material first encountere in immersion → Extract unfamiliar material for study
- Notice recurring vocabulary → Add to SRS system
- Observe natural speech patterns → Create shadowing materials
- Documentation: Mined patterns to evaluate for SRS system incorporation

#### Knowledge → Production (Application Path)
This pathway transforms passive knowledge into active language use through graduated challenges.
- Understand grammar → Apply in controlled exercises → Use in spontaneous communication
- Recognize vocabulary → Retrieve words in exercises → Employ in original sentences
- Comprehend audio → Shadow recordings → Participate in conversations

#### 2.1.3 Activity Categories
- **Natural Input Activities**: Authentic language exposure
- **Knowledge Building Activities**: Develop systematic understanding of language components and patterns.
- **Production Activities**: Active language use practice
- Many activities naturally fulfill more than one cateogry

#### 2.1.4 Progression Framework
Learning advances through structured progression on three levels:
1. **Within Activities**: Internal progression mechanisms
2. **Between Activities**: Sequencing of related activities
3. **Across Skill Areas**: Balanced advancement across linguistic domains

#### 2.1.5 Activity-Resource-Goal Interconnection
Activities serve as the operational unit of the learning program with three key mappings:

1. **Goal Support**: Each activity explicitly supports specific capability goals
2. **Resource Requirements**: Activities require specific resource categories for implementation
3. **Workflow Implementation**: Activities are executed through standardized workflows


### 2.2 Planning Framework

#### 2.2.1 Core Planning Concepts
- **Priority Tiers**: Ranked categorization system for activities
  - Tier assignment based on:
    - Direct alignment with priority goals
    - Enabling function for other high-value activities  
    - Current proficiency gaps
    - Resource availability

- **Planning Cycle**: Recurring time-bound framework (weekly, with daily sub-cycles)
  - Each planning cycle includes:
    - Activity selection and scheduling
    - Balance assessment across skill areas
    - Progress evaluation against goals
    - Adjustment based on previous cycle outcomes

### 2.3 Workflow System

#### 2.3.1 Workflow Template
- **Prerequisites**: Resources, knowledge, system conditions needed
- **Steps**: Numbered sequence of specific actions
- **Completion Indicator**: Clear description of successful completion

#### 2.3.2 Workflow Documentation
- **Main Workflow Metadata Table**: Workflow_id, Name, Prerequisites, Completion indicator
- **Individual Workflow Step Tables**: Step, Name, description, time, LLM Role

## 3. System Architecture

### 3.1 Memory System Architecture

#### 3.1.1 Static Memory (System Document)
- **Purpose**: Defines core system architecture, processes, and principles
- **Update Frequency**: Rarely (quarterly revisions)
- **Components**:
  - Learning methodology
  - Memory architecture
  - Workflow frameworks
  - Terminology Framework:
    - Core Terminology (foundational concepts)
    - Expanded Terminology (operational classifications)
- **LLM Usage**: Reference as foundational guidance that overrides conflicting information

#### 3.1.2 Stable Memory
- **Purpose**: Contains semi-permanent learning structures and strategies
- **Update Frequency**: Monthly or when strategy changes
- **Table Patterns**:
  - **Core Profile**: Learner-specific characteristics and constraints
  - **Activity Catalog**: ```Activity catalog``` (including activity classifications)
- **Workflow Templates**: ```[Activity name] workflow```
  - **Capability Goals**: ```[Skill area] capability goals```
  - **Strategies**: ```[Focus area] strategy```
  - **Aspiration Goals**: ```Aspiration goals```
  - **Resource Catalog**: ```Resource catalog```

#### 3.1.3 Volatile Memory
- **Purpose**: Tracks ongoing activities and immediate learning state
- **Update Frequency**: Daily/weekly updates
- **Table Patterns**:
  - **Planning Tables**: 
    - ```Weekly schedule [week-of date]``` (Foundation Activities with checkboxes + Focus Activities)
    - ```Weekly activity checklist [week-of date]``` (Focus Activities with completion tracking)
  - **Activity Logs**: ```[Activity name] log``` (including Outcome Measures)
  - **SRS Metrics**: ```[SRS system] metrics```
  - **Activity Queues**: ```[Activity name] queue```
  - **Mining Lists**: ```[Content type] mining list```
  - **Adjustment Log**: ```Activity adjustments``` (tracking modifications)

### 3.1.4 Memory Transfer Temporal Context

#### 3.1.4.1 Initialization Context Types
The memory transfer system must handle three distinct initialization scenarios:

1. **Mid-Week Initialization (With Existing Plan)**
   - Occurs on any day Monday through Saturday
   - Contains partially completed current week data
   - Continues in-progress week

2. **Mid-Week Initialization (Without Existing Plan)**
   - Occurs on any day Monday through Saturday
   - Contains completed previous week data
   - Requires "catch-up planning" from current day through Sunday

3. **Sunday Initialization**
   - Occurs specifically on planning day (Sunday)
   - Contains completed previous week data
   - Requires setup of entirely new week

#### 3.1.4.2 Temporal State Indicators
Each memory transfer includes an explicit temporal context header:
initialization_date,<date>
week_start_date,<date>
planning_mode,<mode>
planning_status,<status>

Where:
- `initialization_date`: Current system date (YYYY-MM-DD)
- `week_start_date`: Sunday date of current tracking week (YYYY-MM-DD)
- `planning_mode`: Either "sunday" or "mid-week"
- `planning_status`: Either "planned" or "unplanned" (for mid-week only)

#### 3.1.4.3 Weekly Table Interpretation Guidelines

**For Mid-Week Initialization (With Existing Plan):**
- TRUE values in current week tables = Completed activities
- FALSE values in current week tables = Planned but not yet completed
- No new planning required

**For Mid-Week Initialization (Without Existing Plan):**
- Previous week tables show completion status for analysis
- System should prompt for catch-up planning (current day → Sunday)
- Generate new tables with condensed planning process

**For Sunday Initialization:**
- Previous week tables show completion status for analysis
- New week tables should be generated with all FALSE values
- System should prompt for planning cycle for upcoming week

### 3.2 Resource Framework

#### 3.2.1 Core Resource Categories
- **SRS Systems**: Spaced repetition tools for retention
- **Grammar Resources**: Structural explanation and practice
- **Comprehension Resources**: Reading and listening materials
- **Production Resources**: Speaking and writing practice platforms
- **Phonetics Resources**: Pronunciation and pitch accent training
- **Reference Materials**: Dictionaries and lookup tools

#### 3.2.2 Resource Selection Guidelines
1. **Authenticity Principle**: Prefer authentic materials when level-appropriate
2. **Cultural Integration**: Value materials that naturally incorporate cultural context
3. **Resource Integration Principles**: A single resource may fulfill multiple roles

#### 3.2.3 Resource Documentation
- **Resource Catalog**
  - Comprehensive list of all approved resources
  - Documents resource attributes:
    - Access method and cost
    - Appropriate skill level range
    - Update frequency
    - Cultural context level
  - **Activity Suitability**: Lists specific activities each resource supports

#### 3.2.4 Resource Tracking
- **Resource Usage Logs**: Track engagement with each resource
- **Resource State Information**: Current position in progressive resources


## 4. Implementation Guidelines

### 4.1 Weekly Planning Process

#### 4.1.1 Process Overview
- **Planning Timeframe**: Plan from current day through Sunday. Generally Sunday→Sunday, but memory initialization might include an in-progress week.
- **Table Status Values**: FALSE values in templates are placeholders until activity completion. TRUE/FALSE in volatile memory tables represent actual completion.
- **Required Duration**: 45-50 minutes total for complete planning cycle

#### 4.1.2 Sequential Planning Stages
Each stage must be completed and explicitly approved before proceeding to the next:

1. **Review & Reflection** (15 minutes)
   - **SRS Metrics Analysis**:
     - Review past week's accuracy rates and time spent
     - Identify patterns in errors or challenges
     - Assess whether time targets were met consistently
   - **Activity Completion**:
     - Check off completed activities from previous week
     - Note any consistently missed activities
     - Celebrate successful completions

2. **Schedule Integration** (10 minutes)
   - **Calendar Review**:
     - Identify days with limited availability
     - Note optimal time windows each day
     - Mark special circumstances (travel, deadlines, etc.)
   - **Activity Allocation**:
     - Assign focus activities to specific days based on availability
     - Fill in "Planned Day" column in Weekly Activity template
     - Ensure highest priority activities get optimal time slots

3. **Resource-Activity Matching** (10 minutes)
   - **Current Progress Assessment**:
     - Review current position in each resource
     - Consider appropriate challenge level
   - **Resource Assignment**:
     - Match resources to each planned activity
     - Fill in "Resource" column in Weekly Activity template
     - Ensure variety across the week
   - **Resource Validation**:
     - Confirm all needed resources are accessible
     - Download materials needed for offline study
     - Check subscription status if relevant

4. **SRS Adjustment** (5 minutes)
   - **Based on Time-Target Analysis**:
     - If under time targets: Plan to add more items
     - If over time targets: Reduce new items
     - If accuracy declining: Maintain or reduce regardless of time
   - **Set Specific Addition Rates**:
     - WaniKani: ___ new items this week
     - BunPro Grammar: ___ new points this week
     - BunPro Vocabulary: ___ new words this week

5. **Prepare Materials** (5-10 minutes)
   - **Content Queue**:
     - Pre-select episodes or chapters for immersion activities
     - Bookmark relevant grammar points for expansion focus
     - Prepare writing prompts if needed
   - **Environment Setup**:
     - Ensure study apps are updated
     - Download offline content
     - Set up needed reminders or calendar notifications

6. **Generate Weekly Planning Tables** (5 minutes)
   - Complete Weekly Planner Table
   - Fill in Activity Checklist with details from previous steps
   - Add specific context notes to day headers as needed

#### 4.1.3 Planning Templates

##### Weekly Planner Table Template
```
,Monday,Tuesday,Wednesday,Thursday,Friday,Saturday,Sunday
WaniKani,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
BunPro,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Emurse,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Anki,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Focus,,,,,,,
```
##### Activity Checklist Template
```
Priority,Activity,Planned Day,Resource,Status,Notes
```

#### 4.1.4 Context-Aware Planning Variations

**For Mid-Week Planning (With Existing Plan):**
- Review completion status of current week up to initialization date
- Plan only remaining days of current week
- Maintain existing resource assignments for continuity
- Do not reset SRS targets mid-week

**For Mid-Week Planning (Without Existing Plan):**
- Abbreviated Review & Reflection (5-10 minutes):
  - Focus only on SRS metrics and previous week patterns
  - Skip detailed activity completion analysis
- Condensed Schedule Integration (5 minutes):
  - Focus only on days from current day through Sunday
  - Prioritize highest-value activities for shortened week
- Expedited Resource-Activity Matching (5 minutes):
  - Select immediately available resources
  - Ensure at least one high-priority activity per remaining day
- SRS Adjustment (Standard 5 minutes)
- Prepare Materials (Standard 5-10 minutes)
- Generate Partial Week Planning Tables (3 minutes)

**For Sunday Planning:**
- Perform complete week retrospective
- Generate entirely fresh planning tables
- Set new SRS targets for full upcoming week
- Enable comprehensive resource reassignment

## 5. Future Elaborations

This section documents planned improvements to the learning system that have been identified but not yet implemented. These items should be considered during periodic system reviews.

### 5.1 Analytics Enhancements

#### 5.1.1 Long-Term Metrics Tracking
- Develop quarterly aggregation of weekly performance data
- Implement visualization formats for trend identification
- Create progress metrics against long-term fluency goals
- Integrate interval-based retention scoring across SRS systems

#### 5.1.2 Adaptive Goal Setting
- Algorithm for adjusting daily SRS targets based on performance history
- Milestone tracking against JLPT and other external benchmarks
- Integration of speaking/listening balance metrics

### 5.2 System Evolution

#### 5.2.1 Periodic Review Protocol
- Establish quarterly system evaluation process
- Define criteria for planning process adjustments
- Document historical changes to the system

#### 5.2.2 Resource Lifecycle Management
- Track resource effectiveness ratings over time
- Protocol for retiring versus recycling learning materials
- Integration of spaced repetition principles into resource selection

### 5.3 Advanced Planning Features

#### 5.3.1 Specialized Learning Modes
- Intensive preparation modes for tests/travel
- Recovery protocols after extended breaks
- Simplified maintenance mode for busy periods

#### 5.3.2 Multi-Modal Integration
- Balance between reading, listening, speaking, writing
- Output practice scheduling patterns
- Immersion activity tracking
