### Hi there 👋

# Bernardo de Freitas

<h2 align="center">About me</h2>

```python
import this

class Bio:
    def __init__(self, data: list[str]):
        self.data = data

    def format(self) -> str:
        keys = [
            'Name', '⚡ Quick bio', '🔭 i\'m currently studing on',
            '🌱 I’m currently learning', '💬 Ask me about', '✉️ contact'
        ]
        strings = []
        length_spaces = max(map(len, keys))
        for key, value in zip(keys, self.data):
            strings.append(f"{key: <{length_spaces}} {value}")
        return '\n'.join(strings)

data = [
    'Bernardo de Freitas',
    'A kind of full-stack developer, dubstep head, python lover, not gamer, coder, programmer, '
    'depressive :smiling_face_with_tear:, dog lover',
    'Trybe', 'javascript, html, css',
    'python, javascript, html, css, sql, functional paradigm',
    'https://github.com/b166erbot#contact'
]
print('\n' * 3)

print(Bio(data).format())
```

<p>
output:<br>
Name                        Bernardo de Freitas<br>
⚡ Quick bio                A kind of dubstep head, python lover, not gamer, coder, programmer, depressive :smiling_face_with_tear:, dog lover <br>
🔭 i'm currently studing on Trybe<br>
🌱 I’m currently learning   javascript, html, css<br>
💬 Ask me about             python, javascript, html, css, sql, functional paradigm<br>
✉️ contact                  https://github.com/b166erbot#contact
</p>

<h2 id="contact" align="center">You can reach me at :alien:</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/bernardo-de-freitas-teodoro-18a5322a9/" target="_blank">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="b166erbot's LinkedIn Profile" height="30" width="30">
  </a>

  <a href="https://t.me/coquinha_geladinha" target="_blank">
    <img src="https://www.vectorlogo.zone/logos/telegram/telegram-icon.svg" alt="b166erbot's Telegram Profile" height="30" width="30">
  </a>
</p>

<h2 align="center">Github stats :bar_chart:</h2>

<h4 align="center">Visitor's count :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/{b166erbot}/count.svg" alt="b166erbot :: Visitor's Count" /></p>

<h4 align="center">Top langs :tongue:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=b166erbot&langs_count=10&theme=tokyonight&layout=compact" alt="b166erbot :: Top Langs" /></p>

<h4 align="center">Profile stats of public repositories :musical_keyboard:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=b166erbot&show_icons=true&theme=synthwave" alt="b166erbot :: Profile Stats" /></p>

<p align="center"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2FzXmbOaTpbY6mA%2Fgiphy.gif&f=1&nofb=1&ipt=43b362505ca64a2422cc8bb64020e1fc8668123eb1cecb9b3b96e8e3f1ac7bed&ipo=images" alt="Neo seeing behind the matrix" height="150" width="250"></p>

<!--
**b166erbot/b166erbot** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
