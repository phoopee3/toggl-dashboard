# toggl dashboard

## Installation

Clone the repo

If running locally, serve the html using a local server like npm's `serve` or php's `php -S localhost:8000` or whatever solution you prefer.

If you are hosting it somewhere you can copy the index.html file to your server.

## Setup

The first time you visit the site, you will have to enter your toggl api key. You can get that from your [toggl profile page](https://track.toggl.com/profile), scroll down to the bottom and click the 'click to reveal' text to show the api key. Paste that key in the modal and press 'OK'. This key is stored in your browsers local storage.

## Usage

After entering your API key, a list of your projects should show up on the page. Clicking the 15/30/60 minute buttons in a project will pop up a modal where you can enter what task you were working on. It defaults to meetings because I have a lot of meetings. Clicking 'OK' will send that task to your toggl workspace.
