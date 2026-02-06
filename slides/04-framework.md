# The 5-Part Prompting Framework 

---

##  [Previous](03-project.md) |  [Home](../README.md) |  [Next](05-takeaways.md)

---

## The Secret Sauce

Lovable taught us 5 principles that make prompts work. Let's see each one using our Valentine's app.

---

## 1. Be Specific 

**Don't say:** 'Make the button hard to click'

**Do say:** 'When hovered, the No button grows cartoon legs and RUNS AWAY to a random position'

**Our specifics:**
- Text: 'No'  'Nope!'  'Really?'  'Think again!'  'Too slow!'  'Can't catch me!'  'Hehe!'  'NEVER!'
- Colors: purple (calm)  orange (scared)  red (panicked)
- 'Legs should animate like they're running'

*The more specific, the less the AI guesses.*

---

## 2. Add Structure 

Break your prompt into clear sections:

- **Core Concept**  What is this app?
- **Creator Flow**  How do they make a card?
- **The Card**  What does it look like?
- **The No Button Magic**  The fun part!
- **The Yes Flow**  What happens when they say yes?
- **Vibe & Aesthetics**  Colors, animations, feel
- **Technical Notes**  How should it work?

*Structure helps the AI understand relationships between parts.*

---

## 3. Give Examples 

**Visual:** 'Warm romantic gradient (pinks, magentas, soft corals)' not just 'romantic colors'

**Interaction:** 'Button grows cartoon legs and RUNS AWAY' not 'make button move'

**Technical:** 'All data stored in URL hash (base64 encoded JSON)' not 'shareable link'

*Examples eliminate ambiguity.*

---

## 4. Work in Steps 

Build incrementally:
1. Basic layout and inputs
2. Card design with static buttons
3. Yes/No logic and screens
4. The runaway animation
5. Visual polish (petals, sparkles)
6. URL sharing system

*Each step is testable. Ship early, iterate often.*

---

## 5. Refine and Repeat 

**Bad:** 'Fix the button'

**Good:** 'The runaway button should move faster and the legs should be more visible'

**Pro tips:**
- Start strong to reduce iterations
- Be surgical with feedback
- Test on mobile early
- Know when to stop!

---

## The Complete Prompt

\\\
Create a playful, romantic Valentine's Day 'Ask Out' web app...

Core Concept:
A single-page app with Creator Mode and Recipient Mode.

Creator Flow:
- 'Create Your Valentine' heading
- Input for recipient's name
- Photo upload (compress for URL storage)
- Preview and shareable link generation

The 'No' Button Magic:
- Grows cartoon legs and RUNS AWAY
- Text: 'No'  'Nope!'  'NEVER!'
- Colors: purple  orange  red
- Impossible to catch!

[Full prompt in slide notes]
\\\

*One prompt. One working app.*

---

##  [Previous](03-project.md) |  [Home](../README.md) |  [Next](05-takeaways.md)
