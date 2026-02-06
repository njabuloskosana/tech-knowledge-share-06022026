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
Create a playful, romantic Valentine's Day "Ask Out" web app where anyone can create a personalized Valentine's card to share with their crush.
Core Concept:
A single-page app with two modes: Creator Mode (make your card) and Recipient Mode (view the card via shared link).
Creator Flow:

Landing page with "Create Your Valentine 💕" heading
Input field for recipient's name
Photo upload area (drag & drop or click) - compress image for URL storage
"See Preview" button → shows fully interactive preview
Preview has a subtle "← Back" button (top corner) to edit
"Get Shareable Link" button at bottom generates a URL with all data encoded in the hash (no backend needed)
Copy link button with satisfying feedback

The Fun Part - The Card:

Sweet header: "Hey [Name] 💕" with romantic subtitle
Circular photo frame with soft shadow
"Will you be my Valentine? 🌹" question
Two buttons side by side: "Yes! 💖" and "No"

The "No" Button Magic (this is the star feature!):

When hovered or clicked, the No button grows little cartoon legs and RUNS AWAY
Legs should animate like they're running
Button moves to random position each time
Text changes progressively: "No" → "Nope!" → "Really?" → "Think again!" → "Too slow!" → "Can't catch me!" → "Hehe!" → "NEVER!"
Color evolves: starts calm (purple), becomes scared (orange/yellow), then panicked (red) - legs match!
Impossible to actually click it successfully

The "Yes" Flow:

First Yes → "Wait really?! 🥺 You love me that much?" with two confirmation buttons
Second Yes → Celebration screen with "I Love You!" and animated hearts

Vibe & Aesthetics:

Warm romantic gradient background (pinks, magentas, soft corals)
Floating rose petals animation
Twinkling sparkles scattered around
Rose emoji as card decoration
Soft, rounded card with subtle shadow
Playful but heartfelt - cute not cheesy
Mobile responsive

Technical Notes:

Pure frontend, no backend - all data stored in URL hash (base64 encoded JSON)
Compress uploaded images to keep URLs manageable
Works on mobile (touch events for the runaway button)

Make it delightful, whimsical, and impossible to say no to! 💕
\\\

*One prompt. One working app.*

---

##  [Previous](03-project.md) |  [Home](../README.md) |  [Next](05-takeaways.md)
