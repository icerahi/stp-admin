
### **GUI Components: Selection and Arrangement**  
**Lecture 11 - Human-Computer Interaction Design**  

#### **1. Text Boxes**  
##### **Types**:  
- **Single-line**: For short inputs (e.g., names, search queries).  
- **Multi-line**: For paragraphs (e.g., comments, messages).  

##### **Design Principles**:  
- **Labels**:  
  - Place captions **left-aligned** for single-line boxes (e.g., "Username:").  
  - Use **colons (:**) after labels (e.g., "Email: [textbox]").  
  - For read-only fields, center labels above the text.  
- **Size**:  
  - Match box width to expected input length (e.g., 20 chars for phone numbers).  
  - Enable **scrolling** for long text in multi-line boxes.  
- **Formatting**:  
  - Use `word-wrap` for multi-line text.  
  - Segment long inputs with delimiters (e.g., slashes for dates: `DD/MM/YYYY`).  

##### **Best Practices**:  
- Use for **unstructured data** (e.g., free-text responses).  
- Avoid for **categorical data** (use dropdowns/radio buttons instead).  

---

#### **2. Radio Buttons & Checkboxes**  
##### **Radio Buttons**:  
- **Purpose**: Single selection from 2–8 options.  
- **Example**: "Choose payment method: ☑ Credit Card ☐ PayPal".  
- **Rules**:  
  - Default-select the safest/most common option.  
  - Group related options vertically.  

##### **Checkboxes**:  
- **Purpose**: Multiple selections (e.g., "Select interests: ☑ Sports ☑ Music").  
- **Max recommended**: 8 options per group.  

##### **When to Use**:  
| **Component**      | **Use Case**                          |  
|---------------------|---------------------------------------|  
| **Radio Buttons**   | Mutually exclusive choices (1 answer) |  
| **Checkboxes**      | Multiple selections allowed           |  

---

#### **3. Psychological Principles**  
##### **Memory & Attention**:  
- **Miller’s Law**: Display **5–9 items** per group (e.g., menu items).  
- **Recognition > Recall**: Use dropdowns for hard-to-remember data (e.g., airport codes).  

##### **Error Prevention**:  
- **Visibility**: Show active/disabled states (e.g., grayed-out buttons).  
- **Feedback**: Highlight errors in red with clear instructions (e.g., "Password must be 8+ chars").  

##### **Color & Perception**:  
- Limit to **5 colors** max per screen.  
- Avoid high-contrast colors for backgrounds.  

---

#### **4. Information Design**  
##### **Visual Hierarchy**:  
- Group related elements (e.g., billing info in a bordered box).  
- Use **progressive disclosure**: Show basics first, details on demand (e.g., "Advanced Options" toggle).  

##### **Data Visualization**:  
- **Example**: Stock market maps use:  
  - **Color**: Red/green for price changes.  
  - **Size**: Block size = company size.  
  - **Interaction**: Hover for details.  

---

#### **5. Common GUI Errors**  
1. **Overcrowding**: Too many options in one view.  
   - **Fix**: Use tabs/accordions.  
2. **Ambiguous Labels**: e.g., "Click here" → "Download PDF".  
3. **Poor Feedback**: No confirmation after submission.  
   - **Fix**: Show "Success!" messages.  

---

### **Key Takeaways**  
- **Text Boxes**: Optimize for input type (single/multi-line).  
- **Selections**: Radio buttons for 1 choice; checkboxes for multiple.  
- **Psychology**: Design for limited memory (chunk info) and attention (highlight key actions).  

**Search Terms**: `GUI text boxes`, `radio vs checkbox`, `Miller’s Law UI`, `error prevention design`.  

Let me know if you'd like to dive deeper into any section!
