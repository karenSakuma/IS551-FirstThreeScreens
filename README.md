# [App Name]: IS551 First Three Screens

**Live Prototype:** https://karensakuma.github.io/IS551-FirstThreeScreens/
**Repo:** https://github.com/karenSakuma/IS551-FirstThreeScreens

## 1. Need, Persona, Capability, Value

**Need:** Busy college students don't have the time or energy to figure out what they can cook with what's already in the fridge, so they order takeout or repeat the same easy meal every day, spending money and letting other groceries go to waste.

**Persona:** Cooks for themselves almost every night, shops without a strict grocery list but wants to save money, and spends way more time trying to figure out what to eat than actually eating.

**Capability:** Show recipes you can make right now, using what's already in your kitchen.

**Value:** Control. Dinner gets sorted out without spending on takeout or letting food go to waste.

## 2. The Three Screens

| Screen | Single Job | Why It Earned a Slot | Design Question It Examines |
| --- | --- | --- | --- |
| **1. Landing** | Show the user what the app can do and why it's worth using | It's the only screen every user sees before deciding whether to look further | Does the user understand what this app does and why it matters within the first few seconds? |
| **2. Recipe List** | Turn "I don't know what to make" into an actual dish | It's the proof that the app does what it says, right after the landing screen's promise | Can the user navigate this screen easily enough to actually use it to decide dinner? |
| **3. Recipe Detail** | Let the student follow through and cook | It's where the capability and the value both actually happen, cooking something so nothing goes to waste | Does this make the student feel confident enough to cook instead of giving up? |

## 3. Design Question Plan

| Group | Question | Predicted Answer | What It Rests On |
| --- | --- | --- | --- |
| Need | "Tell me about the last time you were in this situation. What did you end up doing?" | "I was in this situation last night, actually. I just ended up making instant ramen since it's super fast and simple, even though I'd already had it twice this week." | This prediction rests on the landing page, since this is the first question I would ask when someone opens the app. |
| Value | "If this app solved that problem, what value would you see in this app and why?" | "Efficiency. I'd be more efficient with my time instead of wasting it deciding what to make, and more efficient with money since I wouldn't spend it on fast food or on groceries I don't know how to use." | This prediction rests on the recipe list screen, which shows all the recipes along with the number of ingredients needed and the time it takes to make each dish. Those two details signal that the app solves both the time and money problem. |
| Persona | "Do you know anyone else that has this issue?" | "My roommate and other college friends." | This prediction rests on the idea that this is a common issue within the target audience. Most college students are busy with work and school while also trying to save money, and those two factors together are what commonly lead to this problem. |
| Capability | "What would you click first, and what do you expect would happen?" | "I would click the 'See what I can make' button, and I'd expect it to show me what I can make." | This prediction rests on the landing screen, since the orange "See what I can make" button is the only thing that should be clickable on this page. The landing screen should have only one purpose. |

## 4. Design Justification and First Read

*(Opened the live URL fresh, as a first time visitor.)*

| Question | Answer |
| --- | --- |
| Does the landing screen signal the primary capability and fundamental value at first glance, before reading? | Yes. The large headline immediately states what the app does, and the short numbered list underneath reinforces it. |
| Does every element on the landing screen earn its place, or does anything compete with the primary job? | Everything on the landing screen earns its place. Nothing competes with the primary job; each element supports it. |
| What information and actions belong together on each screen, and which Gestalt grouping principle communicates that? | On the recipe list screen, each recipe and its details (time to make and number of ingredients on hand) are grouped together on one card. On the recipe screen, the ingredient list is its own group and the step by step instructions are their own group. All of this is communicated through Gestalt's principles of *similarity* and *proximity*. |
| Do screens 2 and 3 stay on mission, and can you return to the landing screen from everywhere? | Yes. Screens 2 and 3 both stay on mission, and each has a button that returns to the landing page, using the same icon for consistency. |
| What did the AI initially get wrong, skip, or oversimplify, and what did you change? | The AI initially added too much to the landing screen: an extra paragraph explaining the app, and a row of ingredient chips with a "+4 more" pill that looked tappable but did nothing. I asked it to simplify until nothing unnecessary remained. |
| Which design question or grouping/signaling decision motivated each important change? | The question "Does the user understand what this app does and why it matters to them within the first few seconds?" motivated the changes to the landing screen, since I wanted every element to support the app's main purpose instead of competing with it. |

## 5. Before / After

**Landing screen, before (raw AI output, first commit) vs. after (reviewed revision):**

![Before: raw AI-generated landing screen](docs/screenshots/before-landing.png)
![After: revised landing screen](docs/screenshots/after-landing.png)

Before: "Cook what's already in the fridge." implies a meal already exists. The value stat is a small pill lost next to a paragraph. An unlabeled decorative circle does no communicative work.
After: "Turn what's in your kitchen into dinner." signals the shift from ingredients to a finished meal. The "8 recipes ready to make now" stat is a standalone visual anchor. The hero banner uses real ingredient imagery instead of empty shapes.

Full diff: see the `Initial screens generated by Claude Design (AI raw output)` commit vs. the `revise-screens` branch merged via pull request.
