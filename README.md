# GitHub User Finder 🔍
 
A simple, responsive web app that lets you search for any GitHub username and view their profile details and latest repositories — built with vanilla HTML, CSS, and JavaScript using the GitHub REST API.
 
## 🌟 Features
 
- 🔎 Search any GitHub username
- 🧑‍💻 View profile info: avatar, name, bio, location, and join date
- 📊 See stats: followers, following, and public repo count
- 🏢 Additional details: company, blog/website, and Twitter handle (when available)
- 📁 Displays the user's 6 most recently updated repositories with:
  - Description
  - Primary language
  - Stars and forks count
  - Last updated date
- ⚠️ Error handling for invalid or non-existent usernames
- 📱 Fully responsive design for mobile devices
## 🛠️ Built With
 
- **HTML5** – structure and markup
- **CSS3** – styling, flexbox/grid layout, and responsive design
- **JavaScript (Vanilla)** – DOM manipulation and API calls
- **[GitHub REST API](https://docs.github.com/en/rest)** – fetching user and repository data
- **[Font Awesome](https://fontawesome.com/)** – icons

## 🚀 Demo
[Live Demo](https://itssalman095.github.io/Github-Profime-Finder/)

 

 
## ⚙️ How It Works
 
1. Enter a GitHub username in the search box (or press Enter).
2. The app fetches the user's public profile data from `https://api.github.com/users/{username}`.
3. Once the profile loads, it fetches the user's repositories from the `repos_url` returned in the profile response (limited to 6 per page).
4. Profile info and repository cards are rendered dynamically on the page.
5. If the username doesn't exist, an error message is shown instead.
## 📂 Project Structure
 
```
github-user-finder/
├── index.html      # Markup and structure
├── style.css       # Styling and responsive layout
└── script.js       # GitHub API logic and DOM rendering
```
 
## 🖥️ Getting Started
 
No build tools or dependencies required — it's a static site.
 
1. Clone the repository
```bash
   git clone https://github.com/Itssalman095/github-profile-finder.git
```
2. Open `index.html` in your browser
That's it — no npm install, no build step.
 
## 🔮 Possible Improvements
 
- Add a loading spinner while the profile is being fetched
- Handle GitHub API rate limiting (unauthenticated requests are limited to 60/hour)
- Add pagination or "load more" for repositories
- Add a dark/light theme toggle
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
## 🙋‍♂️ Author
 
**Salman**
- GitHub: [@Itssalman095](https://github.com/Itssalman095)
---
 
⭐ If you like this project, consider giving it a star on GitHub!
 
