System document / Non-volatile memory

// Improvements to make:
// - Sanitize of all references to specific resources and extract what is necessary to volatile memory tables.
// - Enhance the ways that the system doc instructs LLM in how to use memory tables. Make a clear explanation of static memory (this document), stable memory (goals, strategies, workflows, etc.) and volatile memory (weekly planner, logs, mining lists, etc.)
// - Ensure rigid adherence to specific terminology that is consistent across system document and memory tables.
// - Further standardize formatting and hierarchy

# Japanese Learning System

## 1. Core Profile // I think we're missing some useful detail about my lifesstyle and habits here.
- **Current Level**: Solid N4 (targeting N2 by December 2025)
- **Experience**: 2 years of study
- **Focus**: Cultural acquisition and comprehensive language development
- **Time Commitment**: Minimum 1 hour daily

### System Resources  // knowledge of resoure specs in memory tables belongs here, not specific resources.
- **WaniKani**: Kanji and vocabulary SRS (Lifetime subscription)
- **BunPro**: Grammar SRS - (Lifetime subscription)
- **Emurse** ($50/yr): Platform for Dōgen's phonetics practice
- **Dōgen** ($108/yr): Comprehensive pitch accent course
- **色々な日本語** ($3/mo): Manga explanation YouTube channel

### Strengths & Challenges // also belongs only in memory tables
- **Strengths**: Grammar recognition, Kanji acquisition, Consistency, Comprehension
- **Challenges**: Speaking production, Pitch accent, Synthesizing complex meaning, Active grammar usage

## 2. System Architecture

### Weekly Structure
- **Daily Core**: SRS practice (WaniKani, BunPro, Emurse) // needs sanitazation of specific resources
- **Daily Focus Activities**
- **Flexible Activities**: Immersion content selected from resource list

### Time-Based SRS Approach
- **Target**: Consistent daily review time (not item count)
- **Daily Time Allocation**:  // these times might be volitile enought to be worth extracting to tables
  - Total SRS time: 30-45 minutes
  - WaniKani: 10-15 minutes
  - BunPro: 10-15 minutes
  - Emurse: 10-15 minutes
- **Adjustment Protocol**:
  - If review time exceeds targets for 3+ days: Reduce new items
  - If review time falls below targets for 5+ days: Increase new items
  - If accuracy drops below threshold: Maintain or reduce regardless of time
- **Measurement**: Track session duration, calculate 7-day average, adjust weekly

### Three-Tier SRS Integration
1. **Knowledge Base** (WaniKani & BunPro): // needs sanitization
   - Algorithm-driven daily reviews
   - Adjusted based on time targets rather than item counts
   - BunPro vocabulary additions from listening/reading activities // needs sanitization

2. **Pronunciation Training** (Emurse): // needs sanitization
   - Daily core reviews focusing on phonetic accuracy
   - "Favorites" for challenging pitch accent patterns

3. **Error Correction** (Anki):
   - Problem point tracking and resolution
   - Pitch accent cards for vocabulary outside Emurse catalog

### Flexibility Rules
- Missed evening activity: No need to make up
- Busy week: Prioritize daily core SRS + at least two weekly focus activities
- Extra time: Add immersion rather than accelerating progress
- Accuracy drop: Pause new additions for 3-5 days

## 3. Learning Methodologies // this section is superceded by an improved "learning flow model", but it's possible that some interesting ideas from this section should be captured and re-integrated.

### Immersion and Study Activities Framework

#### Core Distinctions

##### Immersion Activities
- **Purpose**: Natural language exposure, comprehension practice
- **Scheduling**: Flexible, not time-bound, done as time permits
- **Resources**: Podcasts, videos, books, articles, drama, etc.
- **Approach**: First-pass consumption focused on general understanding
- **Examples**: 
  - Reading NHK Easy News articles
  - Watching drama episodes
  - Listening to podcsast episodes

##### Study Activities
- **Purpose**: Targeted analysis of language features
- **Scheduling**: Specifically scheduled in weekly plan
- **Resources**: Previously consumed immersion materials
- **Approach**: Intensive analysis, extraction, application
- **Examples**:
  - Grammar mining from a previously read article
  - Vocabulary extraction from watched drama
  - Shadowing practice with familiar audio

#### Relationship Between Activity Types

The system operates as a two-phase approach:
1. **Phase 1 (Immersion)**: Flexible consumption of native materials
2. **Phase 2 (Study)**: Scheduled revisiting of materials from Phase 1

This creates a virtuous cycle where immersion provides context and interest, while study activities deepen understanding of previously encountered content.

#### Implementation in Weekly Planning // all weekly planning material should be in that one section?

During the Sunday Planning Process (see below):
1. Review recently covered immersion material for suitable study activities
2. Schedule specific study activities based on materials
3. Leave immersion activities flexible

// I believe this material is duplicative with a few other areas:
// - the Acitivty workflow tables that specify each activity step-by-step with LLM integration.
// - progress target tables
// Anything that isn't duplicated elsewhere still needs to be extracted and turned into tables in the stable memory category, e.g. cultural acquisition, and in their place, instructions for how to interpret those tables. Cultural acquisition, in particular, is more of an over-arching guideline than a specific process.
### Skill-Specific Strategies

These strategies relate to the Activity Catalog found in the volatile memory tables.

#### Listening Comprehension Study
- **Multiple-pass approach**:
  1. First listen: Uninterrupted, focus on gist
  2. Second listen: Close analysis with rewinding, vocabulary identification
  3. Third listen: Comprehension with newly learned vocabulary
- **Selection process**: Identify 3-5 high-utility words to add to SRS

#### Reading Comprehension Study
- **Dual approach**:
  - **Immersion Mode**: Prioritize flow and natural engagement with limited lookups
  - **Study Mode**: Methodical analysis of previously experienced content
- **Progression**: Graded readers → manga → simple articles → regular content

#### Writing Development
- **Scaffolded approach**: 
  1. Sentence completion
  2. Question & answer format
  3. Simple translations
  4. Independent composition
- **Progression**: Sentence → Paragraph → Multi-paragraph → Extended composition

#### Speaking Foundation
- **Phonetics-first approach**: Master sound system before extensive production
- **Progression**: Phonetic drills → Shadowing → Controlled production → Free speaking

#### Grammar Expansion
- **Backfilling Approach**: Begin grammar expansion by revisiting already-studied N5 material
- **Rationale**: Build production skills with familiar grammar before advancing to new points
- **Progression**: N5 backfill → N4 reinforcement → N4 expansion → N3 introduction
- **Success Criteria**: Comfortable production of at least 90% of N5 grammar points before focusing primarily on N4 expansion
- **Data source**: Refer to “Grammar expansion queue” and “Grammar expansion log” in long-term memory of volatile memory data.

### Cultural Acquisition
- **Content Selection**: Authentic materials highlighting cultural contexts
- **Observation Focus**: Communication patterns, social hierarchies, contextual language
- **Media Types**:
  - Slice-of-life anime/manga for daily interactions
  - Documentary content for traditional aspects
  - YouTube vlogs for contemporary life
  - News sources for formal language
  - Variety shows for cultural references

// Now that we're adding a dedicated logging and workflow tables for the different activities, clear instruction for how to leverage those tables to assist a user in their activities would be appropriate.
## 4. Progress Tracking

// I think reporting instructions are better located in the "LLM Role" columns of the workflow tables.
### SRS Session Reporting
- **Frequency**: After each significant session
- **Analysis Metrics**: Duration per item, accuracy trends, time of day impact

// Both vocab mining and Problem resolution are their own activities and their workflows should be individually documented, the same as other activities, however, they are not stand-alone workflows, rather, they occur when they are required by the other workflows. So we need a new way of describing that here and in memory tables.
### Vocabulary Mining
- **Process**: Log all vocabulary looked up during comprehension activities
- **Selection**: Mark 3-5 key words from each activity based on utility and frequency
- **Revisit Strategy**: Re-encounter same content in 7-10 days to test retention

### Problem Resolution Protocol
- **Resolution Process**:
  1. New issue → Card template + Revisit Queue
  2. 90%+ Anki accuracy → Quiz scheduled
  3. 3 successful quizzes → Production challenge
  4. 5 successful productions → Mark resolved

### Progress Evaluation Framework

#### Sunday Planning Process

#####  Process Notes

- **Planning Timeframe**: Plan from current day through Sunday only. Generally this is Sunday -> Sunday, but not always. Memory initialization might be accompanied by active planner data from an in-progress week, including sundays.
- **Table Status Values**: FALSE values in templates are placeholders for completion data in the tables they instantiate. All values are FALSE until activity is completed. TRUE/FALSE values in the volatile memory tables represent actual completion.
- **Process Flow - IMPORTANT**: Planning occurs in sequential stages, with approval at each stage before proceeding:
- Each planning stage MUST be completed and explicitly approved before proceeding to the next
- Present only ONE stage at a time, then WAIT for explicit user approval
- If not approved, revise the current stage based on feedback before proceeding
- Planning sequence:
  1. Review & Reflection (approval)
  2. Schedule Integration (approval)
  3. Resource-Activity Matching (approval)
  4. SRS Adjustment (approval)
  5. Weekly Planning Tables Generation (final approval)

##### 1. Review & Reflection (15 minutes)
- **SRS Metrics Analysis**:
  - Review past week's accuracy rates and time spent
  - Identify any patterns in errors or challenges
  - Assess whether time targets were met consistently
- **Activity Completion**:
  - Check off completed activities from previous week
  - Note any consistently missed activities
  - Celebrate successful completions

##### 2. Schedule Integration (10 minutes)
- **Calendar Review**:
  - Identify days with limited availability in coming week
  - Note optimal time windows each day (morning/evening)
  - Mark any special circumstances (travel, deadlines, etc.)
- **Activity Allocation**:
  - Assign focus activities to specific days based on availability
  - Fill in the "Planned Day" column in Weekly Activity template
  - Ensure highest priority activities get optimal time slots

##### 3. Resource-Activity Matching (10 minutes)
- **Current Progress Assessment**:
  - Review where you are in each resource (episode numbers, chapters, etc.)
  - Consider what would provide appropriate challenge level
- **Resource Assignment**:
  - Match resources to each planned activity
  - Fill in the "Resource" column in Weekly Activity template
  - Ensure variety across the week
- **Resource Validation**:
  - Confirm all needed resources are accessible
  - Download any materials needed for offline study
  - Check subscription status if relevant

##### 4. SRS Adjustment (5 minutes)
- **Based on Time-Target Analysis**:
  - If consistently under time targets: Plan to add more items
  - If consistently over time targets: Reduce new items
  - If accuracy declining: Maintain or reduce regardless of time
- **Set Specific Addition Rates**:
  - WaniKani: ___ new items this week
  - BunPro Grammar: ___ new points this week
  - BunPro Vocabulary: ___ new words this week

##### 5. Prepare Materials (5-10 minutes)
- **Content Queue**:
  - Pre-select episodes or chapters for immersion activities
  - Bookmark relevant grammar points for expansion focus
  - Prepare writing prompts if needed
- **Environment Setup**:
  - Ensure study apps are updated
  - Download offline content
  - Set up any needed reminders or calendar notifications

##### 6. Generate Weekly Planning Tables (5 minutes) 
- **Weekly Planner Table Template**:
```
,Monday,Tuesday,Wednesday,Thursday,Friday,Saturday,Sunday
WaniKani,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
BunPro,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Emurse,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Anki,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE,FALSE
Focus,,,,,,,
Flexible,,,,,,,
```
  - Fill in the Focus row with primary activities for each day, including resource details established in step 3.
  - Fill in the Flexible row with secondary/optional activities
  - Add specific context notes (WFH, etc.) to day headers as needed

- **Activity Checklist Template**:
```
Priority,Activity,Default Day,Planned Day,Resource,Status,Notes
1,Grammar Expansion,Monday,,,FALSE,
2,Shadowing,Tuesday,,,FALSE,
3,Writing Practice,Wednesday,,,FALSE,
4,Listening Study,Thursday,,,FALSE,
5,Shadowing,Friday,,,FALSE,
6,Reading (Immersion),Flexible,,,FALSE,
7,Reading (Study),Flexible,,,FALSE,
8,Immersive Viewing,Saturday,,,FALSE,
```
  - Complete the "Planned Day" column based on your schedule
  - Fill in the "Resource" column with specific materials
  - Add detailed notes for each activity

#### Quarterly Check (30-minute self-assessment):
- Comprehension improvements
- Kanji recognition progress
- Listening development
- Expression capability

// this section should probably be removed and its content reconciled with and incorporate into the general intstructions for how to interact with the user and how to use the memory tables.
## Activity Documentation Framework

### Core Structure
- **Activity catalog**: Master registry of all learning activities
- **Activity workflows**: Step-by-step process documentation for each activity
- **Activity logs**: Specific metrics collection for each activity type

### Documentation Standards
- Human-readable naming conventions
- Consistent formatting for easy reference
- Detailed workflow steps with time allocations
- Activity-specific metrics tailored to learning goals

### Implementation Guidelines
1. Create base Activity catalog with all current activities
2. Develop individual workflow tables for each activity
3. Design appropriate logging schema for each activity type
4. Maintain consistency in field naming across related tables

// can these be removed? after all, the memory tables themselves should be sufficient example?
### Example tables:

#### Activity catalog

ID,Name,Priority,Description,Goal_Focus,Time,Focus,Context
1,Grammar expansion,1,Study and practice using specific grammar points with focus on production,Grammar Production,30min,High,Distraction-free
2,Basic shadowing,1,Repeat immediately after native speaker with focus on rhythm,Pronunciation,15min,Medium,Quiet environment

#### Grammar expansion workflow
Step,Name,Description,Time,LLM_Role
1,Selection,Choose grammar point from expansion queue,5min,Confirm selection based on progression
2,Comprehension,Review explanation and examples in BunPro,5min,None
3,Analysis,Identify usage patterns and contexts,5min,Provide additional examples if needed
4,Production,Create 3-5 original sentences using the pattern,10min,Review for accuracy
5,Integration,Connect to previously learned points,5min,Suggest combinations

#### Grammar expansion log
Date,Point,JLPT_Level,Examples_Created,Confidence,Time_Spent,Error_Types,Notes
2025-03-24,～たことがある,N5,4,3.5,28,Tense confusion,"Still confusing with present perfect usage"
