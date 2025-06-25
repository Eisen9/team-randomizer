# Team Randomizer

A lightweight, browser-based tool to randomly assign players into teams. Built with HTML, Bootstrap 5, and vanilla JavaScript, this app makes team creation quick and intuitive—perfect for classrooms, meetups, or casual games.

## Demo

View it live via GitHub Pages: [Eisen9.github.io/team-randomizer](https://eisen9.github.io/team-randomizer/)

## Features

* **Dynamic Player Input**: Specify any number of players and teams.
* **Validation**: Ensures you enter valid counts and names.
* **Fisher–Yates Shuffle**: Fair, unbiased randomization.
* **Even Distribution**: Automatically balances team sizes.
* **Bootstrap Styling**: Responsive design out of the box.

## Getting Started

### Prerequisites

* Modern web browser (Chrome, Firefox, Safari, Edge).
* (Optional) Local HTTP server for testing (e.g., VS Code Live Server, Python `http.server`).

### Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/YourUsername/team-randomizer.git
   cd team-randomizer
   ```
2. **Open `index.html`**

   * Double-click `index.html` or serve via a local server:

     ```bash
     # Python 3
     python -m http.server 8000
     ```
   * Navigate to `http://localhost:8000` in your browser.

## Usage

1. Enter the total number of players and desired number of teams.
2. Click **Set Players** to generate name fields.
3. Fill in each player’s name.
4. Click **Randomize Teams** to view balanced team assignments.

## Deployment on GitHub Pages

1. Push your code to a GitHub repository named `team-randomizer`.
2. In the repo settings, under **Pages**, set the source to the `main` branch and `/ (root)` folder.
3. Save—your site will be published at `https://YourUsername.github.io/team-randomizer`.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m "Add YourFeature"`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a Pull Request.


