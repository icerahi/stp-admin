# Usability Testing with Users Documentation

## Evaluation Methods with Users

### Core Approaches
1. **Observation**
   - Direct monitoring of user activities
   - Activity logging/protocol creation
   - Incident diaries recording events
   - Feature checklists (list of properties)

2. **Surveys**
   - Suitable for:
     - Interface descriptions
     - Prototypes
     - Real systems

### Testing Formats
- **Direct Evaluation**
  - At workplace
  - In usability laboratories
- **Indirect Evaluation**
  - Remote assistance tools
  - Interoperability protocols
  - Property lists

## Usability Test Reports (ISO/IEC 25062:2006 CIF Format)

### Report Structure
1. **Document Metadata**
   - Title page information

2. **Executive Summary**
   - Key findings overview

3. **Introduction**
   - Product description
   - Research objectives

4. **Assessment Method**
   - Participant details (number, recruitment, characteristics)
   - Product context description
   - Evaluation tasks
   - Testing environment
   - Administration method

5. **Usability Measures**
   - Effectiveness metrics
   - Efficiency metrics
   - Satisfaction metrics

6. **Results**
   - Analysis of obtained results
   - Evaluation environment details
   - Administration method review

## Why Conduct User Testing?

### Benefits
- Early problem identification
- User evaluation of layouts
- Validation throughout development:
  - Requirements formulation
  - Design phase
  - Development/testing
  - Product release

### Key Findings
- 80% of ATM users take their first withdrawal within 1-3 minutes
- Essential for iterative design processes
- Verifies prototype alignment with user requirements

## Observation Techniques

### Approaches
1. **Real Environment Observation**
   - Challenges:
     - Difficult to organize
     - Time-consuming
     - Hard to generalize
   - Process:
     - Users receive tasks
     - Observers monitor
     - Action motivations may remain unclear

2. **Laboratory Observation**
   - 1-2 participants performing tasks
   - Video recorded sessions
   - Data/actions systematically recorded
   - Organized by experts

### Participant Numbers
- Research shows 5 participants reveal 80% of defects
- Simple projects: 5 participants sufficient
- Complex systems: May require more

## Testing Process

1. **Planning**
2. **Participant Selection**
3. **Task Formulation**
4. **Pilot Testing**
5. **Test Execution**
6. **Data Analysis**
7. **Reporting**

## Think Aloud Method

### Process
- Users verbalize their thoughts during tasks
- Sessions monitored and recorded
- Post-test participant feedback collected

### Advantages
- Eliminates need for constant questioning
- Clearly reveals what works well and what doesn't
- Provides direct insight into user thought processes

### Disadvantages
- Feels unnatural to some participants
- Slows down testing process
- Can fatigue participants

### Enhanced Version: Constructive Interaction
- Two participants collaborate while speaking
- Overcomes unnaturalness of solo think-aloud
- Generates more comments and insights

## Test Organization Protocol

1. Prepare and verify test tasks
2. Welcome participants
3. Complete consent documentation
4. Provide introductory information
5. Administer pre-test questionnaires
6. Begin recording (if applicable)
7. Monitor and note impressions (via assistant)
8. Conduct post-test interviews

## Common Research Objectives

### Measurable Metrics
- **Time**
  - Task completion duration
  - Website finding speed
- **Error Rates**
  - Per task
  - Over time
  - By error type
- **Help Requests**
  - Number of assistance referrals
- **Completion Rates**
  - Percentage successfully completing tasks
  - Reasons for task abandonment

## Data Analysis Framework

### Effectiveness Metrics
- Error counts
- Missed actions
- Unnecessary actions
- Successful participant counts
  - Who required help
  - Who completed unaided

### Time Metrics
- Average duration
- Shortest completion
- Longest completion

## Testing Documentation

### Required Materials
1. Informed Consent Forms
2. Task Descriptions
3. Pre-Test Questionnaires
4. Post-Test Questionnaires
5. Final Report

### Consent Form Components
- Participation request
- Recording disclosure
- Questionnaire notification
- Data usage permissions
- Confidentiality assurance
- Right to pause/stop
- Break availability notice

## Survey Integration

### Pre-Test Questions
- Participant IT competence
- Relevant tool experience
- Usage frequency/duration

### Post-Test Questions
- Overall system rating
- Difficulties encountered
- Most/least liked features
- General impressions

## Problem Severity Classification

### Difficulty Levels
| Grade | Description | Definition |
|-------|------------|------------|
| 4 | Unused | User cannot/will not use feature due to design |
| 3 | Heavy | User struggles significantly with feature |
| 2 | Middle | User manages but with extra effort |
| 1 | Annoying | Intermittent, easily avoidable issues |

### Frequency Assessment
| Grade | Occurrence Rate |
|-------|-----------------|
| 4 | ≥90% of usage time |
| 3 | 51-89% of usage time |
| 2 | 11-50% of usage time |
| 1 | ≤10% of usage time |

## Error Prioritization
**Danger Score = Difficulty + Frequency**
Examples:
- Severe but rare (4+1=5)
- Minor but frequent (1+4=5)

## Laboratory Setup

### Equipment Requirements
**Testing Room:**
- Computer, desk, chair
- 1-3 cameras + microphones

**Observation Room:**
- Monitoring computer
- Recording equipment
- Video synchronization tools

## Reporting Standards

### Common Industry Format (ISO/IEC 25062:2006)
1. **Summary**
   - Test strategy and results
   - Research questions overview

2. **Methods**
3. **Participants**
4. **Results**
5. **Recommendations**

### Sample Findings
- "50% of participants found tools easily, but navigation proved complex"
- "Half of participants questioned product value proposition"

## Protocol Analysis

### Approaches
1. **Automated Logging**
   - Records system commands/timing
   - Creates session-specific records
   - Server-based analysis

2. **Usage Statistics**
   - Frequency of function use
   - Command patterns
   - Optimization opportunities

### Limitations
- Cannot verify user honesty
- Only shows system-side actions
- Lacks contextual cues (facial expressions, spontaneous comments)

## Incident Diaries

### Implementation
- Users document product experiences
- Can be:
  - Physical journals
  - Digital logs
  - Remote testing tools

### Diary Components
1. Problem emergence timing
2. Problem origin description
3. Assistance tools used:
   - System help
   - Documentation
   - Colleagues
4. Solution effectiveness
5. Resolution duration

## Feature Checklists

### Basic Format
| Command | Awareness | Usage |
|---------|-----------|-------|
| Copy | ✓ | ✓ |
| Paste | ✗ | ✗ |

### Enhanced Version
Adds learning method tracking:
1. Menu discovery
2. Documentation
3. Training
4. Peer learning

## Effective Testing Practices

### Best Practices
- Maintain impartiality
- Control voice/body language
- Avoid direct questions
- Understand root causes
- Provide appropriate assistance when:
  - User appears uncomfortable
  - Ready to give up
  - Stuck in interface
  - Actions lead to errors

### What NOT to Say
- "This isn't a test" (repeatedly)
- "Others failed too"
- "Nobody has ever succeeded at this"
- Surprised reactions to user actions
- Doubting user competence

## Comparative Evaluation Methods

### Cognitive Walkthrough
- Focus: Learnability
- When: Early prototypes
- Participants: Experts
- Prep: Task scenarios
- Output: Usability issues

### Heuristic Evaluation
- Focus: Compliance with heuristics
- When: Mid-development
- Participants: 3-5 evaluators
- Prep: Heuristics list
- Output: Violation report

### User Testing
- Focus: Real user experience
- When: Functional prototypes
- Participants: 5+ users
- Prep: Test environment
- Output: Performance metrics
