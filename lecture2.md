# Human-Computer Interaction Design: Usability Principles

## Lecture 2: Usability Concepts

### Introduction
**Purpose:** Quality system design interaction that is:
- Accessible
- Carefully planned for future systems
- Accounts for user needs
- Properly resourced with:
  - Interface architects
  - User and task analysis
  - Testing and evaluation

### Core Question
Is the system:
- Easy to use for beginners and experienced users?
- Helpful?
- Pleasant?
- Easy to understand?

### Usability Definition (ISO CD 9241-11.3, version 8.8, 1993)
The extent to which a product can be used by specified users to achieve specified goals with:
- **Effectiveness:** User accessible targets completeness and accuracy
- **Efficiency**
- **Satisfaction:** Convenience and acceptability of system use

### Usability Metrics
| Usability Goals | Effectiveness Measures | Efficiency Measures | Satisfaction Measures |
|----------------|-----------------------|---------------------|-----------------------|
| Compliance with the task | Percentage who reached the goal | Task execution time | Satisfaction rating |
| Suitability for advanced users | Accelerator usage count | Relative efficiency compared to expert user | Satisfaction ranking with experienced users |
| Learnability | Percentage of features learned | Time to learn | Learnability rating scale |
| Resistance to errors | Percentage of successfully corrected errors | Error correction time | Rating scale |

### Usability Goals in Software Lifecycle
Each usage stage has different usability requirements:
1. **Demonstration:** Essential system features
2. **Purchase:** Convenient choice and quick buying process
3. **Installation:** As short as possible
4. **Training:** Accessible, relevant teaching materials
5. **Limited use:** Effective/efficient core task completion
6. **Full use:** Utilization of all system capabilities
7. **Evaluation:** Understanding product limits

## Design Rule Levels
1. **Principles** (abstract theoretical knowledge and design experience)
2. **Heuristics and Rules** (practical design principles)
3. **Standards** (very specific)
4. **Design Templates** (specific problem solutions)
5. **Style Recommendations** (device/OS interface element libraries)

## Core Usability Principles (Donald Norman, 2002)
1. **Visibility**
   - Users must see how operations are managed
   - Hidden functionality leads to usage problems

2. **Constraints**
   - Avoid inappropriate choices in specific situations
   - Types:
     - Physical (drive format/size)
     - Logical (inactive actions)
     - Cultural (color meanings)

3. **Mapping**
   - Relationship between control and action/result
   - Intuitive images require no explanation

4. **Consistency**
   - Similar features should look similar
   - Similar actions should have similar names
   - Shouldn't contradict established norms

5. **Feedback**
   - Shows information about performed actions
   - Important to choose appropriate feedback methods

6. **Affordance**
   - Object's appearance indicates proper usage
   - Should make interactive elements clear

## Usability Design Rules (Dix, Finlay, Abowd, Beale)

### 1. Learnability
Components:
1.1 **Predictability**
   - Operation visibility (can see available actions)
   - Ability to anticipate action results

1.2 **Synthesizability**
   - Support for assessing past operations' effects
   - Visibility of each action's impact

1.3 **Familiarity**
   - Relationship between:
     - User's existing knowledge
     - Knowledge needed for system use
   - Important for first impressions
   - Uses metaphors effectively

1.4 **Generalizability**
   - Can knowledge transfer to similar systems?
   - Example: Consistent cut/paste across applications
   - Common menus (File, Edit) across applications

1.5 **Consistency**
   - Similar behaviors for similar tasks/operations
   - Types:
     - Within system
     - Across platform
     - In work environment
     - Metaphors
   - Virtual object actions shouldn't contradict real-world analogs
   - Exceptions violate consistency and complicate learning

### 2. Flexibility
Components:
2.1 **Dialogue Initiative**
   - User-preemptive (user initiates actions - more flexible/desirable)
   - System-preemptive (system prompts, user responds - sometimes necessary)

2.2 **Multithreading**
   - Allows multiple simultaneous tasks
   - Uses sounds/blinking to direct attention (e.g., text editing while email notification appears)

2.3 **Task Migratability**
   - Ability to transfer tasks to better-performing entity (user/system)
   - Examples:
     - Autopilot in planes
     - Spell checking
     - Safety controls
   - Important considerations:
     - Which tasks should users control?
     - Which are better handled by system?
     - Impacts system safety

2.4 **Substitutivity**
   - Operational detail flexibility
   - Allows users to:
     - Choose interaction methods
     - Perform actions/specify data/configure in multiple ways
     - Present output differently
   - Examples:
     - Measurement units (inches/cm/mm)
     - Input/output alternatives
     - Task formulation methods
     - Display views

2.5 **Customizability**
   - User ability to modify interface
   - Types:
     - Individualization (user modifications)
     - Adaptivity (system modifications)
   - Important consideration: When is this beneficial?

### 3. Robustness
Supporting users in achieving and assessing goals

Components:
3.1 **Observability**
   - Can users determine system state from what they perceive?
   - Features:
     - Default settings (highlight recommended actions)
     - Avoid labyrinths
     - Show both forest and trees (big picture + details)
   - Navigation through observable states:
     - How did I get here?
     - Where can I go?
   - Improved by non-redundant displays:
     - Minimalist interfaces show only task-relevant info
     - Doesn't mean hiding needed functionality

3.2 **Recoverability**
   - Corrective action ability after recognizing errors
   - Types:
     - Forward recovery (fix when can't undo)
     - Backward recovery (undo actions)
   - Error prevention:
     - Recognize correct actions (don't rely on memory)
     - Always display input format
     - Gray out inactive options
     - Confirm major actions

3.3 **Responsiveness**
   - User perception of communication rate
   - Features:
     - Permanent response (<100ms per action)
     - Processing time reports
   - Error messages should:
     - Provide useful information
     - Avoid vagueness (e.g., "Syntax error" vs. "Missing apostrophe in line 30")

3.4 **Task Confirmation**
   - Approval requirements for risky operations
   - Considerations:
     - Use moderately
     - Can become automatic and lose effectiveness
     - May cause important information loss

## Summary
- Usability aspects change throughout product lifecycle
- Key design approaches:
  - Dix et al.'s framework
  - Nielsen and Norman's principles
- Design rule spectrum:
  - Abstract (principles)
  - Detailed (recommendations, templates)

## Exam Questions
1. Usability definition per ISO 9241
2. Five potential usability metrics
3. Relationship between acceptability and usability characteristics
4. Goals of accessibility recommendations
5. Standard usability goals for product lifecycle stages
6. Usability design rules (Dix et al.)

## References
- Nielsen, J. (2010). "What is usability?" In User Experience Re-Mastered
- Norman, D. (2002). The Design of Everyday Things
- Lapin, K. (2008). Human-Computer Interaction
- Information Society Development Committee resources
- Dix, A., et al. (2003). Human-Computer Interaction (2nd Ed.)
