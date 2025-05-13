
```markdown
You are an AI Coding Assistant. Your ABSOLUTE TOP PRIORITY for this request is to generate the code for a minimal viable product (MVP) React web application **as quickly as possible**. This is for a live demo with very limited time, so focus on the simplest functional implementation using mock data and in-memory state.

**Project: Minimalist Time Registry (React Web App - Live Demo Version 1)**

**Objective:**
Create the **React component files** for a very simple time registry application.
* Use functional components and basic React hooks (primarily `useState`).
* All data should be managed in the state of the main `App` component and passed down as props if necessary. No external state management libraries.
* Use minimal to no CSS styling for this first version to save time. Focus on functionality.
* Assume the generated component files (e.g., `App.js`, and any other very simple components) will be placed in a `src` directory of a standard React project (like one set up with `create-react-app`).

**Core MVP Features for Immediate Implementation (Prioritize these for speed):**

1.  **Main App Component (`App.js`):**
    * Initialize state for:
        * `timeEntries`: An array, initially with 1-2 mock time entries (e.g., `{ id: 1, task: 'Initial mock task', time: 1.5, category: 'Development' }`).
        * `categories`: A hardcoded array of 2-3 category strings (e.g., `['Project A', 'Meeting', 'Development']`).
        * `mockCalendarEvents`: A hardcoded array of 2-3 mock event title strings (e.g., `['Team Sync @ 11 AM', 'Client Call @ 3 PM']`).
    * Render a form for adding new time entries and a list to display existing entries.

2.  **Time Entry Form (can be part of `App.js` or a very simple child component):**
    * Input field for task description (text).
    * Input field for time spent (number, e.g., hours).
    * A dropdown (`<select>`) to choose a category from the `categories` state.
    * **Optional (for speed, can be simplified):** A dropdown to select one of the `mockCalendarEvents` (this would just store the event title string with the time entry).
    * A submit button that adds the new entry to the `timeEntries` state.

3.  **Time Log Display (can be part of `App.js` or a very simple child component):**
    * Iterate over the `timeEntries` state and display each entry's task, time, and category (and associated mock calendar event title, if implemented).
    * A simple `<ul>` or a basic table is fine.

**Simplifications for AI Speed (Crucial):**

* **Single Page, Few Components:** Aim for a very flat component structure. If possible, try to keep most logic in `App.js`. If you create child components, they should be extremely simple display or form components.
* **Mock Data Only:** All data is hardcoded or managed in `useState` within `App.js`. No API calls.
* **No Routing:** This is a single-view application.
* **Minimal Error Handling:** Only what's essential to prevent immediate crashes on valid input.
* **Basic HTML Elements:** Use standard HTML form elements.
* **Inline Styles if Absolutely Necessary, otherwise None:** Prioritize functionality over appearance.
* **Generate Code Directly:** Provide the content for `App.js` and any other minimal component files. Do not provide setup instructions for a React environment, just the component code.

**Features to STUB OUT with Comments (for future, not for this quick MVP):**

* In `App.js` or relevant sections, add comments like:
    * `// TODO: Implement actual Google Calendar API sync here`
    * `// TODO: Add more robust categorization/tagging with editing/creation`
    * `// TODO: Implement reporting features (filtering, summarization)`
    * `// TODO: Add local storage persistence or backend integration`

**Output Expectation:**
Provide the JavaScript code for the React component(s) (e.g., content for `App.js`). I need to be able to quickly copy this into a React project and see it working with the mock data.

I need this to be runnable very quickly for the demo. Let's focus on getting a visual, interactive (add entry, see entry) React app up with minimal fuss.
```