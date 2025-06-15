# Cognitive Walkthrough Evaluation Methodology

## Introduction to Usability Evaluation Methods

### Types of Usability Evaluations

1. **Empirical Methods**
   - Involve real users in assessment
   - Examples: User testing, field studies

2. **Analytical Methods**
   - Formal simulations of user behavior
   - Measure specific usability metrics

3. **Expert-Based Methods**
   - Conducted by usability experts
   - Utilize heuristics and professional experience
   - Includes:
     - Heuristic evaluation
     - Cognitive walkthrough

4. **Automatic Methods**
   - Software-based evaluations using models

## Cognitive Walkthrough Overview

### Definition
A procedural evaluation method that assesses system learnability by examining whether a new user can easily understand the interface.

### When to Use
- Early design stages
- With low-fidelity prototypes (paper or digital mockups)
- Before user testing to identify obvious issues

### Required Materials
1. **User and Task Characteristics**
   - Description of target users
   - Typical tasks they need to perform

2. **Usage Scenarios**
   - Set of target tasks to evaluate

3. **Interface Mockup**
   - Prototype or design to evaluate
   - Clear action sequence visible

## Cognitive Walkthrough Process

### Step 1: Preparation
1. Define user characteristics
   - Example: "Macintosh users working with MacPaint"

2. Conduct hierarchical task analysis
   - Break down tasks into subtasks
   - Develop user action plans

3. Prepare low-fidelity prototype
   - Paper sketches or digital wireframes

### Step 2: Evaluation
For each task step, evaluators answer three key questions:

1. **Will users know what to do?**
   - Does the interface make the correct action obvious?
   - Consider user characteristics and experience

2. **Will users recognize the correct action?**
   - Does the interface provide clear cues about available actions?
   - Are controls properly labeled and arranged?

3. **Will users understand the feedback?**
   - After performing the action, is the result clear?
   - Does the system provide understandable confirmation?

### Step 3: Problem Identification
- Any "no" answer indicates a potential usability issue
- Document all identified problems
- Note severity based on:
  - Likelihood of occurrence
  - Impact on user experience

## Example: Saving a File with New Name

### Task Steps
1. Open menu containing "Save As" function
2. Select "Save As" command
3. Choose save location
4. Enter new filename
5. Confirm save

### Evaluation of Step 1: Open Menu
1. **Obvious action?**
   - Yes, menus or icons are standard UI elements

2. **Recognizable action?**
   - Yes, "File" menu is conventional location

3. **Understandable feedback?**
   - Yes, menu visually opens showing file-related commands

### Evaluation of Step 2: Select Command
1. **Obvious action?**
   - Yes, menu shows available file operations

2. **Recognizable action?**
   - Yes, "Save As" clearly matches desired function

3. **Understandable feedback?**
   - Yes, dialog window opens with appropriate title

## Successful Action Characteristics

1. **User knows how to proceed**
   - Action matches current user activities
   - System provides clear instructions

2. **User sees available actions**
   - From past experience
   - Through visible controls with matching labels

3. **User understands action is appropriate**
   - Interface provides clear confirmation
   - Other options appear less relevant

4. **User recognizes progress toward goal**
   - System provides clear feedback
   - Response matches user expectations

## Common Usability Problems

1. **Unclear initial actions**
   - Example: Form fields requiring special clearing action
   - Solution: Make required actions more visible

2. **Hidden functionality**
   - Example: Double-click actions not discoverable
   - Solution: Provide better affordances

3. **Jargon or unclear terms**
   - Example: Technical menu items
   - Solution: Use user-friendly language

4. **Missing feedback**
   - Example: No confirmation of actions
   - Solution: Add clear system responses

## Case Study: Ticket Machine Interface

### Task: Purchase Round-trip Ticket to Kaunas

**Identified Issues:**
1. **Travel type selection ambiguity**
   - Problem: Users might select destination before specifying trip type
   - Solution: Reorder steps or make sequence clearer

2. **Payment feedback missing**
   - Problem: No display of amount paid
   - Solution: Add "Amount received" display

3. **No money return option**
   - Problem: Users can't cancel transaction
   - Solution: Add "Return money" button

## Reporting Findings

### Report Structure
1. **Task Description**
   - Name and purpose of evaluated task

2. **Hierarchical Task Decomposition**
   - Breakdown of task steps

3. **Evaluation Results Table**
   - For each step:
     - Whether users would know what to do
     - Whether feedback would be understood
     - Screenshots of problematic areas

4. **Defects and Recommendations**
   - List of identified issues
   - Suggested improvements

## Advantages of Cognitive Walkthrough

1. **No users required**
   - Can be conducted early in design process

2. **Works with low-fidelity prototypes**
   - Doesn't require finished interface

3. **Identifies interaction problems**
   - Focuses on learnability issues

4. **Helps formulate user goals**
   - Clarifies design assumptions

## Limitations

1. **Can be monotonous**
   - Repetitive nature of evaluation

2. **Risk of inappropriate task selection**
   - May evaluate unrealistic scenarios

3. **Focuses on low-level items**
   - May miss higher-level usability issues

## Simplified Walkthrough Rules

1. **Document questionable areas**
   - Don't try to design solutions during evaluation

2. **Avoid defensive design**
   - Designers shouldn't defend their decisions

3. **Usability expert leads session**
   - Ensures objective evaluation

## Comparison with Heuristic Evaluation

| Aspect               | Cognitive Walkthrough       | Heuristic Evaluation        |
|----------------------|----------------------------|----------------------------|
| **Focus**            | Learnability of task flows  | Compliance with usability principles |
| **Best Stage**       | Early design               | Mid-to-late design         |
| **Participants**     | 1-4 usability experts      | 3-5 evaluators             |
| **Preparation**      | Task analysis, prototypes  | Heuristics list            |
| **Output**           | Task-specific issues       | General usability violations |

## Conclusion

Cognitive walkthrough is particularly valuable for:
- Evaluating prototypes and mockups
- Assessing complex core tasks
- Measuring limited-use stage effectiveness
- Identifying learnability issues before user testing

Key components include:
- User characteristics
- Task descriptions and mockups
- Report documenting comprehension issues and fixes
