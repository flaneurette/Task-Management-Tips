# Example for programming a project

Same technique, applied to software development.

#### 0. Requirements

- A repo with a file called "Dev log - daily notes"
- A file called "Architecture Outline"
- A file called "Backlog / Alternative ideas" as a doubt log
- 15–30 minutes a day to write or refactor at least one small piece.

#### 1. Project Sentence

Summarize the entire project in one sentence.

> *"A web app that lets users track daily habits and visualizes their progress over time."*

#### 2. Outline Modules

List the major modules/components:

```
1. User Authentication
2. Habit Data Model & Storage
3. Habit Tracking UI
4. Progress Visualization
5. Notifications / Reminders
6. Deployment & Testing
```

#### 3. Module Sentences

Summarize each module in **one sentence**.

```
1. Authentication: Users can sign up, log in, and securely manage their session.
2. Data Model: Habits and their completion logs are stored and retrievable per user.
3. Tracking UI: Users can mark habits done/not done for the day quickly.
4. Visualization: Users see streaks and trends via charts.
5. Notifications: Users get reminded if they haven't logged a habit.
6. Deployment: The app runs reliably in production with basic test coverage.
```

#### 4. Key Points per Module

Break each module into 5–10 concrete tasks ("beats") before coding line by line.

Beats for Module 1 (Authentication):
```
1. Authentication
  1.1. Set up sign-up form and validation
  1.2. Set up login form and session handling
  1.3. Hash and store passwords securely
  1.4. Add "forgot password" flow
  1.5. Add logout functionality
  1.6. Write basic tests for auth flows
```

#### 5. Start Coding Toward the Beat

Pick the first beat (e.g., sign-up form) and just build that - don't jump ahead to password hashing or login yet.

#### 6. Daily Coding

Write/commit **a small working piece per day** - one function, one component, one test. Consistency over volume: a tiny working commit beats a stalled ambitious one.

#### 7. Doubt Log / Backlog

If you think of a feature or refactor that doesn't belong to the current module (e.g., "what if we add social sharing?"), log it in the backlog file instead of chasing it mid-task. Keeps focus on the beat at hand.

#### 8. Building Toward Module Completion

Chain the beats together until the module works end-to-end (e.g., full auth flow functions and passes tests).

#### 9. Building Toward Project Completion

Do the same at the macro level - complete modules one at a time until they integrate into the full working app.

#### 10. Code Review / Editing

At the end (or per module), do a slow pass: refactor, clean up naming, remove dead code, check edge cases - same as a writer editing chapter by chapter.

---

##### **Core Principle:** Step by step, not too much at once - one function, one beat, one commit at a time.

---

This mapping shows the pattern holds regardless of domain: **big idea -> components -> one-liners -> small concrete tasks -> daily consistent execution -> doubt-parking -> incremental assembly -> final review.** 
