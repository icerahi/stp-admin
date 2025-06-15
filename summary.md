
# Human-Computer Interaction Design  
## Summary  

---

## Content  
- Usability Principles  
- GUI Recommendations  
- PACT Analysis  
- Design Interaction Systems  

---

## Definition  
3  
**ISO CD 9241-11.3, Version 8.8, 1993**  
Usability is the extent to which a product can be used by specified users to achieve specified goals with:  
- **Effectiveness** (accuracy and completeness of goals achieved)  
- **Efficiency** (resources expended in relation to the results achieved)  
- **Satisfaction** (comfort and acceptability of use).  

---

## Concepts, Principles, Guidelines  
4  
- No "cookbooks" or simple universal checklists exist.  
- Many concepts, principles, and guidelines must be understood.  
- Higher-level principles apply across situations and display types.  
- Standards and guidelines should be implemented.  

---

## Usability Metrics (ISO 9241)  
5  
| Usability Goals       | Effectiveness Measures       | Efficiency Measures       | Satisfaction Measures       |  
|-----------------------|------------------------------|---------------------------|-----------------------------|  
| Compliance with task  | % of users reaching the goal | Task execution time       | Satisfaction rating         |  
| Suitability for advanced users | Use of accelerators       | Relative efficiency       | Ranking with experienced users |  
| Learnability          | % of features learned        | Time to learn             | Learnability rating scale   |  
| Resistance to errors  | % of successfully corrected errors | Error correction time | Error tolerance rating     |  

---

## Usability Principles (Donald Norman)  
6  
- **Visibility**  
- **Constraints**  
- **Mapping**  
- **Consistency**  
- **Feedback**  
- **Affordance**  

Source: Norman, Donald A. (2002). *The Design of Everyday Things*. New York: Basic Books.  

---

### Visibility Principle  
7  
- Hidden functionality leads to usability problems.  
- Users cannot find or use invisible features.  
- Controls and operations must be visible.  

---

### Constraints Principle  
8  
- Prevent inappropriate choices in a given context.  
- Types of constraints:  
  - **Physical** (e.g., disk shape and size)  
  - **Logical** (e.g., inactive actions)  
  - **Cultural** (e.g., color meanings)  

---

### Mapping Principle  
9  
- Relationship between controls and their effects.  
- Intuitive mappings require no explanation.  

10  
**Example of Poor vs. Good Mapping:**  
- (a) Confusing interface with 24 options.  
- (b) Clear interface with 4 options.  

---

### Consistency Principle  
11  
- Ensures interface elements behave predictably.  
- Similar features should look and act similarly.  
- Avoids unnecessary confusion and frustration.  

---

### Feedback Principle  
12  
- Provides information about actions performed.  
- Must choose appropriate feedback methods (e.g., visual, auditory).  

---

### Affordance Principle  
13  
- Perceived properties of an object that suggest how it can be used.  
- Example: A button should look clickable.  

---

## Usability Principles (Dix, Finlay, Abowd, Beale)  
14  
1. **Learnability**  
2. **Flexibility**  
3. **Robustness**  

---

### Learnability  
15  
Support for users at all levels:  
- **Predictability** (expected outcomes)  
- **Synthesizability** (assessing past actions)  
- **Familiarity** (leveraging prior knowledge)  
- **Generalizability** (extending knowledge to similar systems)  
- **Consistency** (within system, platform, and metaphors)  

16  
**Predictability**  
- Users should anticipate action outcomes.  
- Operation visibility (available actions should be visible).  

17  
**Synthesizability**  
- Users should assess the impact of past actions on the current state.  
- Each action’s effect should be visible.  

18  
**Familiarity**  
- Leverage users' existing knowledge.  
- Use metaphors (e.g., desktop, trash can).  

19  
**Generalizability**  
- Knowledge of one system should apply to similar systems.  
- Example: Cut & paste works across applications.  

20  
**Consistency**  
- Similar tasks should behave similarly.  
- Exceptions break consistency and hinder learning.  

---

### Flexibility  
21  
Multiple ways for users and systems to exchange information:  
- **Dialogue Initiative** (user vs. system control)  
- **Multithreading** (handling multiple tasks)  
- **Task Migratability** (transferring tasks between user and system)  
- **Substitutivity** (flexible input/output methods)  
- **Customizability** (user or system modifications)  

22  
**Dialogue Initiative**  
- **User-preemptive**: User initiates actions (more flexible).  
- **System-preemptive**: System prompts, user responds (necessary in some cases).  

23  
**Multithreading**  
- Allows users to perform multiple tasks simultaneously.  
- Example: Text editing while receiving email notifications.  

24  
**Task Migratability**  
- Transfer tasks to the entity (user or system) best suited for them.  
- Examples: Autopilot, spell-checking.  

25  
**Substitutivity**  
- Flexible interaction methods (e.g., inches/cm, input alternatives).  

26  
**Customizability**  
- Users can modify the interface (individualization).  
- Systems can adapt the interface (adaptivity).  

---

### Robustness  
29  
Support for users in achieving goals:  
- **Observability** (understanding system state)  
- **Recoverability** (correcting errors)  
- **Responsiveness** (timely feedback)  
- **Task Confirmation** (approval for risky actions)  

30  
**Observability**  
- Users should infer the system state from its display.  
- Example: Scroll bars show position in a document.  

31  
**Recoverability**  
- Users should correct errors easily.  
- **Forward recovery**: Fix errors without undoing.  
- **Backward recovery**: Undo actions.  

32  
**Error Prevention**  
- Make errors hard to commit (e.g., graying out inactive options).  

33  
**Responsiveness**  
- Users should perceive prompt feedback (<100 ms for actions).  
- Error messages should be helpful (e.g., "Missing apostrophe in line 30").  

34  
**Task Confirmation**  
- Risky operations require explicit approval.  
- Use sparingly to avoid habituation.  

---

## GUI Recommendations  

### Window Components  
40  
- **Window border/frame**  
- **Title bar**  
- **Toolbar**  
- **Menu bar**  
- **Status bar**  
- **Scroll bars**  
- **Resize tool**  
- **Controls button**  

41  
**Types of Windows**  
- **Primary windows**: Essential functions.  
- **Secondary windows**: Supplemental information.  
- **Dialog boxes**: User input.  
- **Message boxes**: Notifications.  
- **Properties windows**: Object settings.  

42  
**Window Presentation Styles**  
- **Tiled windows**: Side-by-side, resizable.  
- **Overlapping windows**: Stacked like papers.  

43  
**Choosing Window Styles**  
- **Tiled**: Best for single tasks, beginners.  
- **Overlapping**: Best for multitasking, experts.  

44  
**Modal vs. Non-Modal Windows**  
- **Modal**: Blocks interaction until dismissed.  
- **Non-Modal**: Allows interaction with other windows.  

---

### Command Buttons  
49  
**Styles of Buttons**  
- Command buttons  
- Toolbar buttons  
- Symbol buttons  

50  
**Standard Command Buttons**  
- **OK**: Save and close.  
- **Cancel**: Close without saving.  
- **Apply**: Save without closing.  
- **Help**: Open help.  

51  
**Button Labels**  
- Use standard labels where possible.  
- Meaningful, concise (1-3 words).  
- Mixed-case (e.g., "Save As").  

52  
**Button Size**  
- Large enough, consistent dimensions.  
- Minimum height: 25 pixels.  

53  
**Button Placement**  
- Exit buttons: Bottom-center.  
- Feature buttons: Right-side.  
- Group related buttons.  

---

## PACT Analysis (People, Activities, Context, Technologies)  

### Vision Abilities  
77  
- **Rods**: Night vision, grayscale.  
- **Cones**: Color vision.  
- Sensitivity to blue is lowest in the center of the eye.  

78  
**Color Sensitivity**  
- Avoid blue text/lines (low visibility).  
- Warm colors for actions, cold colors for status.  

79  
**Avoid Clashing Colors**  
- Opposite spectrum colors (e.g., red/green) cause strain.  
- Reduce brightness to mitigate.  

80  
**Use of Colors**  
- Limit to 5 colors per interface.  
- Warm colors: Actions requiring response.  
- Cold colors: Status information.  

---

### Memory and Attention  
83  
**Human Processor Model (Card, Moran, Newell, 1983)**  
- **Long-term memory**: Stores knowledge.  
- **Short-term memory**: Holds ~7 items for ~20 sec.  
- **Perceptual buffers**: Sensory input (visual, auditory).  

84  
**Short-Term Memory**  
- Fast access (~70 ms) but fleeting (~200 ms).  
- Chunk information (e.g., "617-459-1765" vs. "6174591765").  

85  
**Recognition Over Recall**  
- Menus show options (recognition).  
- Lists aid memory (e.g., airport codes).  

86  
**Time Limits**  
- Important messages should persist (>10 sec).  

---

## Design Interaction Systems  

### Prototyping  
109  
**Types of Prototypes**  
- **Storyboards**: Visual narratives.  
- **Paper prototypes**: Low-fidelity, quick.  
- **Wireframes**: Structural plans.  
- **High-fidelity prototypes**: Near-final appearance.  

110  
**Prototyping Process**  
1. Sketch > Prototype > Evaluate > Redesign.  
2. Simulate interactions.  
3. Involve non-technical stakeholders.  

111  
**Wireframes**  
- Outline interface structure.  
- Focus on layout, not details.  

112  
**High-Fidelity Prototypes**  
- Mimic final product (no coding).  
- Test learnability and acceptability.  

---

## Sources  
- Norman, Donald A. (2002). *The Design of Everyday Things*.  
- Dix, A., Finlay, J., Abowd, G., Beale, R. (2003). *Human-Computer Interaction*.  
- Schneiderman, B., Plaisant, C. (2004). *Designing the User Interface*.  

--- 

This documentation retains all original English content while removing Lithuanian text and organizing it into a structured format. Let me know if you'd like any modifications!
