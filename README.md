# 🌌 Destroyer
### A powerful Discord Selfbot written in Python using [discord.py-self](https://github.com/dolfies/discord.py-self)!

<div align="center">
  <img src="https://media.discordapp.net/attachments/1305195862154149999/1307340531579490414/destroyer.png?ex=6739f33f&is=6738a1bf&hm=9b9c84633f3ae4f5adf2288d8c36ca346a66d7026bae001db32866b260d9ae59&=&format=webp&quality=lossless&width=620&height=620" alt="icon" width="50%" height="50%">

  [![GitHub release (latest by date)](https://img.shields.io/github/v/release/DarkM00n9/Destroyer-SelfBot.svg?style=flat)](https://github.com/DarkM00n9/Destroyer-SelfBot/releases)
  [![GitHub downloads](https://img.shields.io/github/downloads/DarkM00n9/Destroyer-SelfBot/total.svg?style=flat)](https://github.com/DarkM00n9/Destroyer-SelfBot/releases)
  [![GitHub stars](https://img.shields.io/github/stars/DarkM00n9/Destroyer-SelfBot.svg?style=flat)](https://github.com/DarkM00n9/Destroyer-SelfBot/stargazers)
  [![GitHub watchers](https://img.shields.io/github/watchers/DarkM00n9/Destroyer-SelfBot.svg?style=flat)](https://github.com/DarkM00n9/Destroyer-SelfBot/watchers)
  [![CodeFactor](https://www.codefactor.io/repository/github/DarkM00n9/Destroyer-SelfBot/badge?style=flat)](https://www.codefactor.io/repository/github/DarkM00n9/Destroyer-SelfBot)
  [![GitHub issues](https://img.shields.io/github/issues/DarkM00n9/Destroyer-SelfBot.svg?style=flat)](https://github.com/DarkM00n9/Destroyer-SelfBot/issues)
</div>

<div align="center">

  [![Discord Support](https://dcbadge.limes.pink/api/server/https://discord.gg/JuUNzQdaDA)](https://discord.gg/JuUNzQdaDA)
</div>

## 📖 Table of content
1. [💾 Installation](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-installation)
2. [🔧 Config](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-config)
3. [🌟 Features](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-features)
4. [📜 How to get a user token](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-how-to-get-a-user-token)
5. [👀 Preview](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-preview)
6. [☣️ Issues](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#%EF%B8%8F-issues)
7. [🛠️ Developement version](https://github.com/DarkM00n9/Destroyer-SelfBot#%EF%B8%8F-developement-version)
8. [❓ How to contribute](https://github.com/DarkM00n9/Destroyer-SelfBot#-how-to-contribute)
9. [⭐ Contributors](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-contributors)
10. [🫂 Support](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#support)

## 💾 Installation
1. Download the latest version from the [Releases](https://github.com/DarkM00n9/Destroyer-SelfBot/releases) section on GitHub.
2. Make sure to have [Python](https://www.python.org/downloads/ "Install Python here") installed.
3. Open your Terminal and go to Discord-Selfbot with `cd`.
4. Install dependencies: `pip install -r requirements.txt`
5. Run the program: `python main.py`
6. Get started with `&help`!

## 🔧 Config
Open `config_selfbot.py` with any text editor  and enter a [user token](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#-how-to-get-a-user-token).

## 🌟 Features
* Custom RPC templates,
* Build your own RPC,
* Voice commands,
* Raid commands,
* Massive DM (DM All),
* Nitro Sniper,
* Spam and Flood command,
* Snipe command,
* Auto bump,
* And others, check the `Help` command!

## 📜 How to get a user token
1. Go to [Discord Web](https://discord.com/app)
2. Do ``CTRL + MAJ + I`` and go to `Console`
3. Paste this code:
```js
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    if (!req.c) return;
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```
Now your token is in your clipboard. <br><br>
3b. If you can't paste the code, just type `allow pasting` and retry. <br>
<br>
4. Paste your token in `config_selfbot.py`

## 👀 Preview
<div align="center">
  <img src="https://imgur.com/kRgNROK.png" alt="preview" width="" height="">
</div>
<br>
<div align="center">
  <img src="https://imgur.com/VsN9cUd.png" alt="preview_second" width="" height="">
</div>


<br>

## ☣️ Issues
### Library Issues
`discord.py-self` has some issues.
<br>

One of the most common is when an incompatible library is already installed. To solve this problem, you can uninstall them:
```powershell
pip uninstall discord discord.py py-cord pycord nextcord discord.py-self aiohttp
```
And now, you just need to re-install discord.py-self (from Git or from [here](https://github.com/DarkM00n9/Destroyer-SelfBot/releases/latest))

If you still get an error, you can check [discord.py-self's support](https://t.me/dpy_self_discussions)
### Discord's issues
Check [support](https://github.com/DarkM00n9/Destroyer-SelfBot?tab=readme-ov-file#support)!

## 🛠️ Developement version
1. Open your Terminal and go to the wanted folder with `cd`.
2. Clone the repository: `git clone https://github.com/DarkM00n9/Destroyer-SelfBot`
**or**
Just clone it with the green "Code" button above the README.


## ❓ How to contribute

🖤 You can contribute by leaving a star if you love my project! <br>
🧷 You can also translate the selfbot (using `langs.py`)! <br>

## ⭐ Contributors
<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/DarkM00n9">
        <img src="https://avatars.githubusercontent.com/u/151471955?s=400&u=a71a3e31524d26be7f321610f2e120a9b5420813&v=4" alt="DarkM00n9" width="80px" height="80px" style="border-radius: 50%;">
        <br>
        DarkM00n9
      </a>
    </td>
<table>

# Support

- Discord server: [https://discord.gg/JuUNzQdaDA](https://discord.gg/JuUNzQdaDA)

<br>

---

[![](https://visitcount.itsvg.in/api?id=jnm&label=Profile%20Views&color=1&icon=5&pretty=true)](https://visitcount.itsvg.in)

---
Destroyer-SelfBot : [![wakatime](https://wakatime.com/badge/github/DarkM00n9/Destroyer-SelfBot.svg)](https://wakatime.com/badge/github/DarkM00n9/Destroyer-SelfBot)

My total Code Time: [![wakatime](https://wakatime.com/badge/user/b0f7240f-350e-417f-a836-f34a393b7abc.svg)](https://wakatime.com/@b0f7240f-350e-417f-a836-f34a393b7abc)


