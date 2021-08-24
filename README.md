<p align="center">
  <a href="https://github.com/JardelBrandon/Twitter_Api_Client/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/JardelBrandon/Twitter_Api_Client"></a>
  <a href="https://github.com/JardelBrandon/Twitter_Api_Client/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/JardelBrandon/Twitter_Api_Client"></a>
  <a href="https://github.com/JardelBrandon/Twitter_Api_Client/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/JardelBrandon/Twitter_Api_Client"></a>
  <a href="https://github.com/JardelBrandon/Twitter_Api_Client/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/JardelBrandon/Twitter_Api_Client"></a>
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/JardelBrandon/Twitter_Api_Client">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/JardelBrandon/Twitter_Api_Client">
  <a href="https://github.com/JardelBrandon/Twitter_Api_Client/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/JardelBrandon/Twitter_Api_Client">
  </a>
</p>

<h1 align="center">
    <img alt="Twitter API Client" title="#Twitter API Client" src="./assets/twitter_api_client_banner.jpeg" width="600px"/>
</h1>

<h4 align="center"> 
	🚧  Twitter API Client 🐦 Under construction ⚠️ 🚧
</h4>

<p align="center">
 <a href="#-about-the-project">About</a> •
 <a href="#-functionalities">Functionalities</a> • 
 <a href="#-developer">Developer</a> • 
 <a href="#-how-to-contribute-to-the-project">Contribute</a> • 
 <a href="#-license">License</a>
</p>

## 💻 About the project

🐦 Twitter API Client - Development of an android application using kotlin to perform twitter API queries for developers, in order to perform searches for specific words in a twitter and return users who used them, also allowing access to the profile by link to twitter.

---

## ⚙️ Functionalities

The goal is to create a basic Twitter client in Kotlin. The main features will be: search for tweets with a specific text, and show a user's tweets. In more detail:
  
- [ ] The app's home screen should contain a search screen, with a search bar at the top. When typing a text and confirming, the search must be performed through the endpoint `search/tweets.json` (https://developer.twitter.com/en/docs/tweets/search/api-reference/get-search-tweets .html)
- [ ] During the quest, a spinner must be shown on the screen. After the result, the tweets should be shown in the order they are returned by the API
- [ ] When tapping a tweet, the page of the user who posted it should open, showing its timeline, through the endpoint `statuses/user_timeline.json` (https://developer.twitter.com/en/docs/tweets/timelines /api-reference/get-statuses-user_timeline.html).
- [ ] As far as possible, try to simulate the Twitter app interface. More specifically, ensure that the profile image will be shown along with the tweet text.

---

## 👨‍💻 Developer

<table>
  <tr>
    <td align="center"><a href="https://github.com/JardelBrandon"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/25730081?v=4" width="100px;" alt=""/><br /><sub><b>Jardel Brandon</b></sub></a><br /><a href="https://github.com/JardelBrandon" title="Jardel">👨‍🚀</a></td>
</table>

## 💪 How to contribute to the project

1. Fork** the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save the changes and create a commit message telling you what you've done: `git commit -m "feature: My new feature"`
4. Submit your changes: `git push origin my-feature`

---

## 📝 License

This project is under the license [MIT](./LICENSE).

---
