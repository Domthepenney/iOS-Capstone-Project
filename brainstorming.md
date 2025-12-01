# App Idea Brainstorming

## New App Ideas - List
1.  **SnapHabit**: A habit tracker where users must verify they completed a task by taking a photo of it (e.g., photo of the gym, photo of a healthy meal).
2.  **PantryPal**: A recipe finder app. Users input the 3 ingredients they have left in their fridge, and the app uses an API to suggest simple recipes.
3.  **FlashCard Flex**: A study aid that allows users to create flashcards and swipe left/right (Tinder style) to mark them as "Known" or "Need to Study."
4.  **HydrateOrDiedrate**: A water intake tracker that sends local push notifications reminding the user to drink water based on their daily goal.
5.  **Bargain Hunter**: An app that uses a free API (like CheapShark) to show a list of video games currently on sale for under $10.
6.  **Mood Journal**: A simple diary app where users select an emoji for their mood and type a short entry. It saves the data locally to track mood trends over time.

## Top 3 Analysis

### Idea #1: SnapHabit (Habit Tracker with Photos)
* **Mobile**: Highly mobile. Uses the **Camera** to verify tasks and **Push Notifications** to remind users. It relies on being with the user throughout the day.
* **Story**: Compelling value. "Pics or it didn't happen" adds a layer of accountability that standard checkbox apps lack.
* **Market**: Large market. Productivity and self-improvement are huge categories.
* **Habit**: Very habit-forming. Users interact with it daily to maintain their "streaks."
* **Scope**: Manageable. The core is a list view and the camera API. No complex backend is required (can use local storage).

### Idea #2: PantryPal (Recipe Finder)
* **Mobile**: Moderate. Useful in the kitchen, but could be a website. We could add a "Shopping List" feature to make it more mobile-friendly.
* **Story**: Clear value. Solves the "what's for dinner?" problem and reduces food waste.
* **Market**: Anyone who cooks or wants to save money on groceries.
* **Habit**: Usage would be episodic (whenever they cook), rather than daily.
* **Scope**: Easy to Medium. Requires working with a Recipe API (like TheMealDB) and parsing JSON data.

### Idea #3: FlashCard Flex (Study App)
* **Mobile**: Good for on-the-go studying on the bus or between classes. Utilizes touch gestures (swiping).
* **Story**: clear value for students, but there are many competitors (Quizlet).
* **Market**: Students and life-long learners.
* **Habit**: High usage during exam seasons, low usage otherwise.
* **Scope**: Easy. Primarily UI work and saving data arrays locally.

## Final Idea
**Winner**: **SnapHabit**
*Rationale: It meets the "Mobile" requirement best by integrating the Camera, and the logic is simple enough to build quickly while still looking impressive for the demo.*
