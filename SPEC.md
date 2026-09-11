# TARGET: today's build

- **Thing:** A one-page calisthenics workout planner where beginners choose a workout and add it to a built-in weekly calendar.
- **Audience:** A beginner calisthenics club planning enjoyable workouts together and wanting a simple shared-style routine planner.
- **Requirements:** One working primary interaction: select a workout, briefly reveal its exercise movement/cue, then add it to a chosen calendar day. Calendar choices persist in the current browser and honor the approved standing rule.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Beginner-friendly, energetic, and fun; use clear workout cards, a visible weekly calendar, and a short movement reveal when a workout is selected.
- **Test:** I can select a workout, see its movement cue, add it to a day, refresh and find it still planned, remove it, and point to the standing rule's effect in the preview. After I approve and merge, the same registered Pages URL works.
