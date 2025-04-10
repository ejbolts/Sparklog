# Sparklog

A private personal journaling app for daily reflection (Log) and capturing ideas (Spark).

Inspired by Bullet Journaling principles, Sparklog helps you track your days and cultivate your insights.

## Key Features

*   **Calendar View:** Visualize your month at a glance.
*   **Daily Logging:** Capture key information for each day in dedicated squares:
    *   **Mood Tracking:** Simple visual dots to represent emotional states.
    *   **Activity Outline:** Briefly list significant activities.
    *   **Notes:** Jot down thoughts or events.
    *   **Day Rating:** Assign an overall rating reflected by a colored border.
*   **Spark Capture:** A dedicated system for managing ideas, quotes, and insights:
    *   Capture sparks initially within daily notes.
    *   Review and promote relevant sparks during a weekly review process.
    *   Organize captured sparks with mandatory tags and categories.
    *   Track sources and add detailed elaborations.

## Technology Stack

C#, .NET, AWS

## Roadmap

This roadmap outlines the planned development phases for Sparklog (subject to change).

**Phase 1: Core Logging & MVP (v0.1)**

*   [X] Basic Calendar View implementation (monthly).
*   [ ] Daily Square UI structure.
*   [ ] Basic Mood Dot input (e.g., select color).
*   [ ] Plain text input for Activity Outline.
*   [ ] Plain text input for Notes section.
*   [ ] Basic Day Rating input (select color for border).
*   [ ] Data persistence for daily entries.
*   [ ] Basic "Captured Ideas" tab structure (manual entry only).
*   [ ] Ability to add new ideas directly to the "Captured Ideas" tab with Title/Elaboration.

**Phase 2: Spark Integration & Organisation (v0.2)**

*   [ ] Implement mechanism to "promote" a note from Daily Log to Captured Ideas.
*   [ ] Add mandatory Tagging system to Captured Ideas.
*   [ ] Add a Categorisation system to Captured Ideas.
*   [ ] Add an index page to categories.
*   [ ] Add optional "Source" field to Captured Ideas.
*   [ ] Basic search/filter functionality within the Captured Ideas tab (by tag/category/keyword).
*   [ ] Refine Mood Dots (allow defining labels/meanings).

**Phase 3: Enhanced Tracking & Review (v0.3)**

*   [ ] Add optional Habit Tracking checkboxes to Daily Square.
*   [ ] Add optional dedicated Gratitude field to Daily Square.
*   [ ] Implement basic Trends/Statistics view (e.g., mood graph over time).
*   [ ] Develop Weekly/Monthly Review summary generation (pulling key data).
*   [ ] Implement "Promoted Tags" / "Reference Category" logic based on tag usage threshold.

**Phase 4: User Experience & Polish (v0.4)**

*   [ ] User customization: Allow toggling visibility of modules (Habits, Gratitude) on Daily Square.
*   [ ] Implement Themes (e.g., Dark Mode).
*   [ ] Add customisable Reminders for daily logging/weekly review.
*   [ ] Implement Data Export functionality (e.g., CSV, JSON).
*   [ ] Refine Day Rating (allow defining scale/meaning).

**Future Ideas (Post v0.4 / Wishlist)**

*   [ ] Energy Level tracking.
*   [ ] Sleep Quality tracking.
*   [ ] Advanced statistics and correlations.
*   [ ] Photo attachment to daily notes/sparks or ideas.
*   [ ] Voice note recording.
*   [ ] More advanced search/filtering options.
*   [ ] Cloud sync/backup options.

## Getting Started

