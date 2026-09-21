Create a clean, responsive single-page Web App for "Self-Aversion Hypnosis & Daily Habit Conditioning" designed to help users build a strong, unconscious disgust response toward specific trigger foods (e.g., white flour, sugar, deep-fried foods). 

Build this using HTML, Tailwind CSS, and Vanilla JavaScript inside a single-file interactive component (or React component).

### Key Features & Requirements:

1. **Dashboard & Habit Tracker:**
   - **Target Food Setup:** Allow the user to define their personal target food/ingredient (e.g., "White Flour / Pastries") and upload or select a representative visual image.
   - **Daily Conditioning Streak:** Interactive counter showing consecutive days completed (Target: 21-Day Rewiring Phase).
   - **Daily Session Log:** A quick-check button ("Complete Today's Session") that logs the timestamp and increments the streak.

2. **Guided Audio/Visual Hypnosis Module (Interactive Session):**
   - A 5-minute guided step-by-step interactive timer with dynamic visual prompts and ambient cues:
     - **Phase 1 (0:00 - 1:00):** Deep Induction & Relaxation (Calming visuals / breathing guide).
     - **Phase 2 (1:00 - 2:30):** Vivid Food Visualization & Sensory Amplification (High-contrast, sharp imagery of target food).
     - **Phase 3 (2:30 - 4:00):** Repulsion Superimposition (Darkening visuals, vivid descriptive text prompts linking target food to visceral disgust, rot, and toxins).
     - **Phase 4 (4:00 - 5:00):** Anchor Installation & Clean Refresh (Installing the throat-tightening/gag cue + reset with fresh water visualization).
   - Includes full audio-guided text or text-to-speech triggers (using the Web Speech API `speechSynthesis` if available, with a toggle switch).

3. **Scheduled Time-to-Time Alerts & Notifications:**
   - **Browser Push Notifications:** Request browser notification permissions so alerts fire even when the tab is in the background.
   - **Custom Alarm Schedules:** Allow users to set 2 to 3 daily reminder times (e.g., Morning 08:00 AM, Evening 09:00 PM) for their conditioning sessions.
   - **Trigger Reminders:** A "Pre-Meal Flash Alert" timer that users can manually tap 5 minutes before eating to trigger a rapid 30-second aversion reminder.
   - Use `localStorage` so user schedules, streaks, and target food choices persist across browser refreshes.

4. **UI & Aesthetic Requirements:**
   - Modern, sleek dark-mode UI with high-contrast accent colors (e.g., deep emerald green for fresh state, warning crimson/purple for aversion phase).
   - Clean card-based layout, fully mobile-responsive.

Generate the full, complete code with no missing functions or placeholder comments.
# food-ai-