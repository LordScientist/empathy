---
title: "The Grandparent and the Smartphone"
subtitle: "Task 2 — UX Research Assignment"
author: "Roland Quarshie KNUST"
date: "25th September 2026"
---

# The Grandparent and the Smartphone

**Researcher:** Roland Quarshie
**Location:** Kumasi, Ghana (Asawase and Ayigya)
**Method:** Direct observation, interviews, and a swap-seats exercise

## Contents

1. Field Notes
2. Empathy Map
3. Persona
4. Journey Map
5. "How Might We…?" Question
6. System Proposal
7. Artifact — Website Demo
8. Check-Back Notes
9. Reflection

---

## 01. Field Notes

### Who I spent time with

| Pseudonym | Age | Role | Context |
|---|---|---|---|
| Maa Efua | 70 | Older adult (edge case) | Widow, retired seamstress, lives alone in a compound house in Asawase, Kumasi. JHS education. Reads Twi comfortably, not English. Weak eyesight (no reading glasses on hand most days). Primary phone: an entry-level Android, given to her by her daughter. |
| Papa Kojo | 58 | Older adult | Retired trader/driver, lives with his son's family in Ayigya, Kumasi. JHS + some SHS. Reads simple English slowly. Steadier hands and eyesight than Maa Efua, but similarly avoids anything that looks "technical." |
| Kwabena | 19 | Younger helper | Maa Efua's grandson (visits twice a week) and Papa Kojo's neighbour. First-year SHS graduate, waiting to enter university. The one who "fixes the phone" for both of them. |

**Consent:** Before each session I explained, in Twi and English, that I was a student studying how people use their phones, that there were no right or wrong answers, that I would not touch or look at any private messages, PINs, or balances, and that they could stop at any time without needing a reason. Maa Efua initially said "wo bɛ gyi me" ("you will laugh at me") before agreeing; I told her the opposite was true — I was there to learn from her, not test her.

### Observed (30-minute session, Maa Efua)

I watched Maa Efua try to send a WhatsApp voice note to her daughter Abena, who lives in Accra, with Kwabena present but asked to only help "when she calls him."

- **0:00–0:04** — She unlocked the phone on the third attempt (fingerprint sensor didn't register the first two times because her thumb was dry).
- **0:04–0:09** — She opened the phone's app drawer and scrolled past WhatsApp twice, saying "menhu no" ("I don't see it") before Kwabena silently tapped the correct icon for her without being asked.
- **0:09–0:14** — Inside WhatsApp, she found Abena's chat correctly on the first try (this is a well-worn path — she does it almost daily).
- **0:14–0:19** — She tapped the camera icon instead of the microphone icon, which are close together at the bottom right of the WhatsApp keyboard bar. This opened the camera and briefly showed her own face. She flinched and said "Ei! Me de!" ("Ei! It's me!") and handed the phone toward Kwabena.
- **0:19–0:24** — I asked Kwabena to wait 10 seconds before taking it. In that pause, Maa Efua pressed the back arrow herself, found the correct microphone icon, and successfully recorded and sent a 12-second voice note. She smiled and said, "Me nam so!" ("I did it myself!").
- **0:24–0:30** — Kwabena then took the phone anyway "to check it sent well," scrolled through the chat without asking, and handed it back already on the home screen. Maa Efua did not object, but her shoulders dropped slightly.

### Observed (Papa Kojo, shorter session)

Papa Kojo dialled `*170#` to check his MoMo balance while I watched from across the room (I did not look at the PIN entry). He read each on-screen menu option aloud slowly before choosing a number, and got the balance correctly in about 90 seconds without help. He mentioned this was "one of the only things" he can do alone with confidence.

### Interpretation

*(Kept separate from Observed above, as required.)*

- Maa Efua's difficulty is concentrated at the exact moment a screen changes state unexpectedly (camera opening instead of recording starting) — the panic response (handing the phone away) seems automatic, almost a reflex, rather than a considered choice.
- The 10-second pause mattered: when Kwabena was asked to wait, she recovered and self-corrected. This suggests some of her "dependency" is habit built by helpers acting too quickly, not only a skill gap.
- Papa Kojo's confidence with `*170#` versus WhatsApp icons suggests numeric, sequential menus (which resemble the old feature-phone menus he grew up with) feel safer to him than icon-based, visual interfaces.
- Kwabena's unprompted phone-check at the end (0:24–0:30) — taking the phone back "to check it sent well" — is a small, well-meaning act that nonetheless removes her sense of completion. This is a recurring pattern worth designing around.

### Quote bank

| # | Quote | Speaker | Context |
|---|---|---|---|
| 1 | "Ei! Me de!" ("Ei! It's me!") | Maa Efua | Observed — after accidentally opening the camera instead of the microphone |
| 2 | "Me nam so!" ("I did it myself!") | Maa Efua | Observed — right after sending the voice note without help |
| 3 | "Menhu no yiye. Biribiara sua sua." ("I can't see it well. Everything is small small.") | Maa Efua | Interview — explaining why icons are hard to find |
| 4 | "Sɛ ɛyɛ yiye a, ɛyɛ me anigye — me te sɛ me ho onipa bio." ("When it works, I feel like myself again.") | Maa Efua | Interview — describing a rare proud moment from last month |
| 5 | "Me pa wo kyɛw, gyae, ma menyɛ bio." ("Please, stop, let me try again.") | Maa Efua | Observed — resisting Kwabena taking the phone |
| 6 | "I don't read the English writing well, so I just press and see what happens." | Maa Efua | Interview — describing her main workaround strategy |
| 7 | "Ɛyɛ den paa. I don't want to disturb the children every time, but I don't get option." | Papa Kojo | Interview — on needing help repeatedly |
| 8 | "Last week I checked my own balance for the first time in three months without calling anybody." | Papa Kojo | Interview — proud moment |
| 9 | "The bank people changed the app and now everything is different. Nobody tell me." | Papa Kojo | Interview — frustration with sudden interface changes |
| 10 | "Auntie, no, no, let me do it, you go and sit." | Kwabena | Observed — taking the phone from Maa Efua mid-task |
| 11 | "Sometimes I just do it for them because explaining takes long and I have my own work too." | Kwabena | Interview — admitting helper fatigue |
| 12 | "If I show her once and she forgets, I get small vex, but I don't shout." | Kwabena | Interview |

### Swap-seats exercise

I set my own Android phone's system language to French — a language I read slowly and unreliably — and, without changing it back, tried to (a) send a WhatsApp voice note to a friend and (b) join a scheduled video call, both from memory of where the buttons "usually" sit.

- I found WhatsApp by icon shape and colour, not by reading its name, which was now in French. This matched something Maa Efua told me: she also navigates by icon shape and position, never by reading labels.
- Inside a chat, I hesitated for several seconds over two icons I could not confidently tell apart at a glance — one for attaching a file, one for recording audio — because the tap targets are close together and the icon shapes are subtle at normal size. This is the same mistake Maa Efua made with the camera/microphone icons, and it took me longer than I expected to feel confident, even though I already knew the app well.
- For the video call, I relied entirely on remembered position (top-right of a chat header) rather than reading any label, and it worked — which told me that muscle memory and spatial consistency matter more than text literacy once a person has done a task before. The problem is the *first* time, and any time the layout changes.
- What helped me guess correctly was exactly the "action → visible result" pattern the assignment describes: tapping something and immediately seeing whether the result matched what I expected, then backing out if not. I never once tried to read instructions — I tried, watched, and adjusted. This directly shaped the design of the artifact in Section 07.

---

## 02. Empathy Map

Composite of the older adult I met most (built strictly from the field notes above; guesses are marked with `?`).

| Quadrant | Notes |
|---|---|
| **SAYS** | "Ɛyɛ den paa" (it's very difficult) · "Please just show me" · "I did it myself!" · "Everything is small small" |
| **DOES** | Taps the same icon several times when unsure · waits for a helper before touching the phone at all · hands the phone away quickly after any unexpected screen change · quietly retries alone once the helper has left the room |
| **THINKS** | "If I press wrong, will I spoil it?" `?` · "Am I too old to learn this?" `?` · "I don't want to look foolish in front of the grandchildren" `?` |
| **FEELS** | Embarrassed asking the same person repeatedly · anxious right before pressing an unfamiliar icon · genuinely proud on the rare occasion something works without help · quietly excluded when a helper finishes a task for her rather than with her |

---

## 03. Persona

**Maa Adjoa Boateng, 68**
*"When it works, I feel like myself again."*

| Field | Detail |
|---|---|
| Location | A suburb of Kumasi, Ghana |
| Background | Retired trader, JHS education, lives with extended family, speaks and reads Twi comfortably, reads little English |
| Phone | Entry-level Android smartphone, given to her by a younger relative |
| Goal | To send voice notes and check her own MoMo balance without waiting for a grandchild to be free |
| Frustrations | Small icons that look alike; English-only menus; fear that pressing the wrong thing will "spoil" the phone; helpers who finish tasks *for* her instead of *with* her; app layouts that change without warning |
| Evidence line | Composite of two older adults (aged 58 and 70) and one younger helper (aged 19), observed and interviewed in Kumasi, Ghana, in September 2026. |

---

## 04. Journey Map

**Journey: getting a new smartphone task done, from need to outcome**

| # | Stage | What happens | Feeling |
|---|---|---|---|
| 1 | Need arises | A family member is waiting for a message; she wants to reach them herself | Hopeful, a little nervous |
| 2 | Finds the app | Scrolls the home screen looking for the right icon by shape and colour, not by reading | Confused |
| 3 | Starts the task | Gets into the right chat or menu, usually the well-worn part of the path | Cautiously determined |
| 4 | **Something unexpected happens** | Taps the wrong icon; the screen changes to something she didn't expect | **Embarrassed — LOW POINT** |
| 5 | Asks for help | Calls out to whoever is nearby | Reluctant, a little ashamed |
| 6 | Helper takes over | The helper finishes the whole task, often faster than explaining it | Relieved, but sidelined |
| 7 | Afterward | Occasionally retries alone later, quietly, without telling anyone | Proud on success, discouraged on failure |

**Text-based map (low point circled):**

```
[Need] --> [Finds app] --> [Starts task] --> ((LOW POINT: wrong icon,
                                               screen changes,
                                               embarrassment))
                                                       |
                                                       v
                                              [Asks for help]
                                                       |
                                                       v
                                          [Helper finishes it for her]
                                                       |
                                                       v
                                     [Quiet solo retry later: pride or discouragement]
```

**Hand-drawn sketch, described:** a single horizontal line of stick-figure panels, left to right. Panel 4 (the low point) is the only one drawn with a jagged, uneven circle around it and a small exclamation mark, to visually separate it from the calmer rounded panels on either side. A dotted arrow loops from the last panel back to panel 1, showing that the whole cycle repeats the next time a task is needed.

The low point is directly supported by the field notes: Maa Efua's camera/microphone mix-up (0:14–0:19) and my own confusion between similar-looking icons during the swap-seats exercise both happened at the exact same kind of moment — an unexpected screen change with no easy way back.

---

## 05. "How Might We…?" Question

**How might we help older adults in Ghana recover on their own when a smartphone screen changes unexpectedly, so a small mistake doesn't have to end with someone else finishing the task for them?**

---

## 06. System Proposal

The low point is not "she doesn't know how to use a phone." It is: *the moment something unexpected happens, she has no low-pressure way to check what's going on or undo it herself, so the fastest fix becomes handing the phone to someone else — which quietly reinforces dependency.*

**The system: "Show Me, Don't Take It."** A small set of habits and materials around the phone itself, not a single app:

| Who | What they do |
|---|---|
| **Family (Kwabena, Abena)** | Practice a "show me" habit: point at the icon or narrate the step instead of grabbing the phone; record one short Twi voice note per task and pin it to the top of WhatsApp so she can replay it herself, any time, without asking |
| **Phone shop attendant** | At the point of sale or first setup, hands over a small printed card (icon pictures, no long text) for the 3–4 tasks the buyer says they care about most |
| **Peer buddy (same-age friend)** | A same-age friend who already manages one task confidently (e.g. Papa Kojo with MoMo) is paired to teach that one task to someone still learning it — advice from a peer carries less shame than advice from a grandchild |
| **Church / community group** | A short monthly "phone corner" after service — 15 minutes, volunteer-run, practising one task at a time on people's own phones |
| **The phone itself** | Larger default text size and simplified home screen turned on once, by a helper, during setup — a one-time accessibility fix rather than a recurring favour |

**System map (box and arrow):**

```
 [Phone shop attendant] --gives printed picture-card at purchase--> [Older adult]
                                                                          |
                                                             (sets larger text once)
                                                                          |
                                                                          v
      [Family] --records short Twi voice-guide, pinned in WhatsApp--> [Older adult] <--peer teaching-- [Peer buddy, same age]
                                                                          |
                                                            (practices between sessions)
                                                                          |
                                                                          v
                                                        [Monthly church "phone corner"]
```

**How this answers the low point:** none of these pieces require the older adult to read fluently or remember a long explanation. Each gives her a way to check "what do I do from here?" *by herself*, in the moment of confusion, instead of the only option being to hand the phone over. The pinned voice guide and the printed card exist specifically for the recovery moment — the low point — not for the parts of the task she already manages fine.

---

## 07. Artifact — Website Demo

**What it is:** the first thing an older adult touches — a home screen offering exactly the four tasks that came up in the field notes, followed by one instruction at a time, a "Show me" option instead of someone taking the phone, and a low-pressure "I'm stuck" button that offers help without judgement.

**Design hypothesis:** reducing the first screen to a handful of familiar, named actions (rather than a general app grid) removes the "menhu no" (I don't see it) moment. Revealing only the next step, one at a time, mirrors how Maa Efua and I both actually learned in the swap-seats exercise — by doing one thing and checking the result, not by reading ahead.

**Visual style:** built on a reference "phone help" prototype I reviewed while designing this — a dark, glass-panelled, neumorphic layout with a phone-shaped preview, a task rail down the side, and a guide panel that reveals one step at a time. I kept that visual language deliberately (the glass cards, the phone mockup, the accent colour, the layout), because it does something useful beyond looking polished: the phone-shaped frame keeps the demo honest about what it is standing in for, and the glass panels give each step its own clearly bounded space. I only adjusted what was actually working against the brief's own requirements, not the style itself: labels, hints, and buttons that were sized for a general audience (9–13px text, small tap targets) are sized up for large text and big touch targets, and the external Google Font import was removed in favour of the device's own system font, since the demo has to run fully offline with no external dependencies.

**Screens:**

| Screen | Purpose |
|---|---|
| Hero | Brand, one-line pitch, and a phone-shaped preview showing what the home screen looks like |
| Task rail | Four tasks always visible on the side: Make a Call, Send Voice Note, Check MoMo Balance, Join Video Call |
| Guide panel | A progress bar and step count, one plain-language instruction with a big step number, and a simplified tappable phone screen for that step |
| Helper (modal) | Opens from "I'm stuck": "Show me the exact place" (keeps her doing it herself) or "Let my helper take over" (accepted without judgement) |

**Interaction principle:** action → visible result → next action. Each step shows a simplified mock of that moment on the phone (e.g. the home screen, a chat list, a dial pad) with the correct option among a couple of distractors. Tapping the right one advances the task with a highlight and a toast message; tapping the wrong one is a gentle, recoverable nudge, never a dead end — which is exactly the recovery the low point in the journey map was missing. The one private moment (entering a MoMo PIN) is shown as a plain notice instead of anything tappable or recorded, in line with the privacy rule from Section 01.

**Helper modal:** mirrors the tension in the field notes between Kwabena "showing" Maa Efua a step and Kwabena quietly "taking over." Tapping "I'm stuck" offers both, by name, as equally acceptable choices, with a footer line making clear that asking for help is not treated as a failure.

**The file:** `show-me-phone-helper.html`, submitted alongside this document. It is a single, self-contained HTML file with no external files, fonts, or network calls, so it opens and runs the same with or without an internet connection — save it anywhere and open it in a browser.

---

## 08. Check-Back Notes

Each person opened the demo without any explanation from me first.

| Tester | What they did, unprompted | What they said |
|---|---|---|
| Maa Efua | Tapped "Send Voice Note" immediately, followed steps 1–2 without hesitation, paused at step 3 and tapped "Show me" before acting | "Ah, so it will show me small small before I try." |
| Papa Kojo | Went straight to "Check MoMo Balance," read each step aloud, tapped "I'm stuck" once out of curiosity rather than need | "This one doesn't talk plenty. Good." |
| Sister Akosua (new tester, church member, never briefed) | Tapped "Join Video Call" out of curiosity, completed it, then tried to exit using the small "Back" button and missed it twice | "Eh, the back one is too small — I nearly pressed the wrong side of the screen." |

**Question asked after:** "Does this help with what you told me about?" Maa Efua and Papa Kojo both said yes, specifically pointing to being able to try a step before "the phone leaves my hand."

**Single most important change made because of this reaction:** Sister Akosua's difficulty finding the small "Back" button was the same category of problem as the original low point — a small, easy-to-miss control at the exact moment someone wants to recover or step back. I widened the Back button's touch target and gave it a visible border so it reads clearly at a glance, rather than only enlarging it after the fact for aesthetics.

---

## 09. Reflection

*(~150 words)*

Going in, I expected the low point to be "she doesn't understand icons," which would have pointed me toward more labels and text. Watching the actual 30 minutes corrected that: Maa Efua understood the *task* fine and only lost her footing at the one moment a screen changed in a way she didn't expect. My own swap-seats attempt, in a language I don't read well, produced the exact same stumble at the exact same kind of moment — which told me this isn't really about age or literacy, it's about recovery. I caught myself, early on, wanting to design "an app that teaches her step by step," which quietly assumed she needed a full course rather than a shorter safety net for the moments she already handles well. The tension between what I expected (a learning problem) and what I actually saw (a recovery problem) is what shaped the final "Show me, don't take it" system, rather than a bigger, more explanatory app.
