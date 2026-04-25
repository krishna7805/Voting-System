# Secure Election Portal (Token-Based Voting System)

A web-based voting application featuring token-based authentication and an administrative dashboard, powered by a Google Apps Script backend.

## Features

* **Token-Based Voting**: Users must enter a unique token to cast their vote, ensuring secure and single-use voting.
* **Admin Dashboard**: A control panel to manage candidates, refresh/send tokens, and reset votes.
* **Live Results**: Real-time visualization of election results using Chart.js.

## Project Structure

* `index.html`: The main voter-facing portal where users enter their tokens and select a candidate.
* `Admin.html`: The administrator control panel for managing the election and viewing results.
* `Notes.md`: Scratchpad for backend Google Apps Script URLs and debugging notes.

## Setup

To connect the frontend to your backend:
1. Deploy your Google Apps Script as a Web App.
2. Update the `SCRIPT_URL` variable in both `index.html` and `Admin.html` with your deployed endpoint url.