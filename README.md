# GitHub User Search App

A stylish GitHub user search application built using HTML, CSS, and JavaScript.  
Users can search any GitHub profile and view details instantly using the GitHub API.

---

## Features

- Search GitHub users
- Fetch real-time data from GitHub API
- Display:
  - Profile picture
  - Name
  - Bio
  - Followers
  - Following
  - Public repositories
- Responsive modern UI
- Error handling for invalid usernames

---

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub REST API

---

## How It Works

1. Enter a GitHub username
2. Click the **Search** button
3. The app fetches user data using:

```javascript
fetch("https://api.github.com/users/username")
```

4. Profile details are displayed on the screen

---

## API Used

GitHub Users API:

```text
https://api.github.com/users/{username}
```

---

## Project Structure

```text
project-folder/
│
├── index.html
└── README.md
```

---

## Future Improvements

- Dark/Light mode
- Search history
- Display repositories
- Show location and company info
- Add loading animation

---

## Author

Created as a JavaScript API practice project.
