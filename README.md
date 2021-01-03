## Hi, I'm Alex! <img src="https://emojis.slackmojis.com/emojis/images/1570211625/6611/wave-animated.gif?1570211625" width="25px">

<p>
  <em>
    Fan of <a href="https://graphql.org/">GraphQL</a>, <a href="https://reactjs.org/">React</a>, & <a href="https://aws.amazon.com/dynamodb/">DynamoDB</a> | Incoming Software Engineer at <a href="https://aws.amazon.com/"> AWS</a> 
  </em>
</p>

<!-- ![visitors](https://visitor-badge.glitch.me/badge?page_id=leskaa.leskaa) -->
![Repos Badge](https://badges.pufler.dev/repos/leskaa)

```graphql
query GitHubUserAndStack($username: Username, $isProfileReadme: Boolean!) {
  user(username: $username) {
    name
    location
    position
    company
    favoriteLanguages @include(if: $isProfileReadme) {
      language
    }
  }
}
```

```json
{
  "username": "leskaa",
  "isProfileReadme": true
}
```

```json
{
  "data": {
    "user": {
      "name": "Alex Leska",
      "location": "Minneapolis",
      "position": "Software Dev Engineer",
      "company": "Amazon Web Services",
      "favoriteLanguages": [
        {
          "language": "Typescript"
        },
        {
          "language": "Rust"
        },
        {
          "language": "Golang"
        }
      ]
    }
  }
}
```

<a href="https://github.com/leskaa/leskaa">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=leskaa&layout=compact&theme=tokyonight&hide=HTML,CSS,Processing,SCSS&langs_count=10" />
</a>
&nbsp;
<a href="https://github.com/leskaa/leskaa">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=leskaa&show_icons=false&theme=tokyonight&count_private=true&hide=stars&show_icons=true&line_height=24&hide_rank=true" alt="Alex's GitHub Stats" />
</a>
&nbsp;
<img align="center"  alt="GIF" src="https://media3.giphy.com/media/mCmc21BKYUuC2A6p8H/giphy.gif" height="165px" />

---

<p>
  <em><b>
    What projects am I working on right now?
  </em></b>
</p>
<img align="left"  alt="GIF" src="https://media3.giphy.com/media/jsI8nBXJl6s7r7iuJ5/giphy.gif" height="105px" />
&nbsp;&nbsp;
<a href="https://github.com/leskaa/matchup-ranker-api">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=leskaa&repo=matchup-ranker-api&theme=tokyonight" alt="matchup-ranker-api" height="105px" />
</a>
&nbsp;
<a href="https://github.com/leskaa/rallee-api">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=leskaa&repo=rallee-api&theme=tokyonight" alt="matchup-ranker-api" height="105px" />
</a>

<!--
**leskaa/leskaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
