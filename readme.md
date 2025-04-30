# Frontend Technical Task – Vanilla JavaScript Dashboard

## Overview
Your task is to create a small, responsive dashboard using only vanilla JavaScript, HTML, and CSS. The focus is on clean code and structure. No AI, frameworks or libraries are allowed.

## Requirements

### Layout
- A layout with a sidebar and main content area.

### Sidebar
- The sidebar should contain 3 static navigation links, with one of them having 2 nested submenu items (all non-functional is fine). Submenu should be closed by default.

### User List (Main Content)
- Fetch and display a list of users from this API:
  https://jsonplaceholder.typicode.com/users
- Show each user's name and email.
- Add a text input to filter users by name (live filtering, no submit button).

### User Details
- When a user is clicked, fetch their posts from:
  https://jsonplaceholder.typicode.com/posts?userId=<id>
- Show the post titles in a modal or side panel.
- Display a loading indicator while fetching.
- Gracefully handle and display errors if any occur.

## Technical Notes
- Use only vanilla JavaScript — no libraries or frameworks.
- Organize your code cleanly across multiple files if needed.
- Use comments to explain your logic if needed.
- Make the UI responsive for different screen sizes.
- AI usage is not allowed.

## Time Estimate
This task should take approximately 3–4 hours. Please don’t overengineer — focus on clarity and functionality.

## Due Date
The due date for this task is 2 calendar days starting from the day it is sent to you.

## What to Submit
A GitHub repository containing your project.
