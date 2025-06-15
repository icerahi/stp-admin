# Interactive System Design  
## 4th Lecture  

## Basics of Analyzing Interactive Systems  
### PACT Framework:  
- **People**  
- **Activities**  
- **Context**  
- **Technologies**  

## Interaction Between Activities and Technologies  
- **Requirements**  
- **Possibilities**  
- **People operate technologies within contextual activities**  

## Goals  
1. Understand the importance of:  
   - Memory  
   - Attention  
   - Perception  
   in designing interactive products  

## Physical Differences Among Users  
- Height variations  
- Sensory sensitivity differences  
- 8% of population has red-green color blindness  
- Vision impairments (nearsightedness/farsightedness)  
- Motor precision limitations  

## Sensory Channels for Information Input  
### Five Primary Senses:  
1. Vision  
2. Hearing  
3. Touch  
4. Smell  
5. Taste  

**Design Impact:**  
- Vision remains the dominant channel for HCI  
- Current systems underutilize smell/taste  

## Visual Perception  
### Eye Anatomy:  
- **Rods (~125M):**  
  - Night vision  
  - Detect grayscale  
- **Cones (6-7M):**  
  - Color vision (daylight)  
  - Concentrated in fovea  

### Color Sensitivity:  
- Lowest sensitivity for blue in central vision  
  → Avoid blue text for critical information  
- Highest sensitivity for edges/contrast  

## Color Theory for Interfaces  
### Chromatic vs. Achromatic:  
| Type | Use Case | Example |  
|-------|----------|---------|  
| Achromatic | Edge highlighting | Black/white UI borders |  
| Chromatic | Attention-grabbing | Warning buttons |  

### Contrast Effects:  
- Hermann Grid illusion demonstrates edge enhancement  
- Background colors alter foreground perception  

### Warm vs. Cool Colors:  
- **Warm (red/orange):**  
  - Perceived as closer  
  - Faster user response  
- **Cool (blue/green):**  
  - Background/status info  
  - Perceived as distant  

## Color Accessibility  
- 8% males have red-green color deficiency  
- **Design Solutions:**  
  - Avoid red/green combinations  
  - Use [Colorblind Web Page Filter](http://colorfilter.wickline.org/) for testing  
  - Ensure sufficient brightness contrast  

## Optical Illusions in Design  
Common perceptual traps:  
1. Hering Illusion (curved line distortion)  
2. Jastrow Illusion (size misjudgment)  
3. Müller-Lyer Illusion (line length distortion)  
4. Zöllner Illusion (parallel line misperception)  

## Cultural Color Associations  
| Color | Western | Japan | China | Arab Countries |  
|-------|---------|-------|-------|----------------|  
| Red | Danger/Joy | Happiness | Luck | Caution |  
| Yellow | Caution | Grace | Royalty | Happiness |  
| Green | Safety | Future | Infidelity | Fertility |  
| Blue | Masculinity | Villainy | Strength | Truth |  
| White | Purity | Death | Mourning | Death |  

## Attention Management  
### Key Principles:  
1. **Selective Attention:**  
   - Humans process ~1 conscious signal at a time  
   - Demonstrated by:  
     - Aircraft cockpit incidents (e.g., Eastern Air Lines Flight 401)  
     - Magic tricks relying on misdirection  

2. **Design Implications:**  
   - Avoid parallel task demands  
   - Use progressive disclosure  
   - Signal delays with animations/sounds  

### Attention Guidance Techniques:  
| Location | Method | Example |  
|----------|--------|---------|  
| Central | Color/Brightness | Error messages |  
| Peripheral | Flashing/Motion | Notification badges |  

## Memory Systems  
### Human Processor Model (Card et al., 1983):  
1. **Perceptual Buffers:**  
   - Sensory input (70ms access)  
2. **Working Memory:**  
   - 7±2 chunks  
   - 10-20s retention  
3. **Long-Term Memory:**  
   - Unlimited capacity  
   - Slow retrieval (~100ms)  

### Design Recommendations:  
- **Recognition > Recall:**  
  - Use menus/icons over memorized commands  
- **Chunk Information:**  
  - Group digits (617-459-1765 vs. 6174591765)  
- **Avoid Modes:**  
  - Users forget temporary states (e.g., Caps Lock)  

## Activity Characteristics  
### Key Dimensions:  
1. **Temporal:**  
   - Frequency (regular vs. rare)  
   - Duration (continuous vs. interruptible)  

2. **Collaboration:**  
   - Single vs. multi-user coordination  

3. **Complexity:**  
   - Structured (step-by-step) vs. exploratory  

4. **Safety-Critical:**  
   - Error prevention/recovery requirements  

5. **Content Requirements:**  
   - Input/output data specifications  

## Contextual Factors  
1. **Physical Environment:**  
   - Lighting/noise conditions  

2. **Social Context:**  
   - Cultural norms  

3. **Organizational Setting:**  
   - Workflow integration  

4. **Technological Infrastructure:**  
   - Device capabilities  

## Emerging I/O Technologies  
### Input Methods:  
- Voice recognition  
- QR codes  
- Microsoft Kinect  

### Output Methods:  
- Flexible OLED displays  
- 3D printing  

## Summary  
Interactive system design requires analysis of:  
1. **User Capabilities:**  
   - Physical/psychological characteristics  

2. **Activity Requirements:**  
   - Task structures and flows  

3. **Contextual Constraints:**  
   - Environmental/organizational factors  

4. **Technological Possibilities:**  
   - Input/output/processing capabilities  

## Key Design Principles:  
- Extend human capabilities  
- Compensate for limitations  
- Prioritize recognition over recall  
- Manage attention effectively  

## Sources  
1. Norman, D. (2002). *The Design of Everyday Things*  
2. Card, S.K. et al. (1983). *The Psychology of Human-Computer Interaction*  
3. Benyon, D. (2014). *Designing Interactive Systems*  
