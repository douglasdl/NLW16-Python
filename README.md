# NLW16 - Journey

Trilha Python

<p align="center">
    <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-ide">IDE</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-license">License</a>
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=49AA26&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>
<p align="center">
    <a href="https://douglasdl.github.io/NLW16-Python/index.html">
        <img alt="NLW Journey" src="https://douglasdl.github.io/images/NLW16-Python.png" width="100%">
    </a>
</p>

## 🚀 Technologies

This project was developed using the following technologies:

<p alight="center">
    <a href="https://www.python.org/"><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.sqlite.org/index.html"><img height="40" src="https://douglasdl.github.io/images/SQLite3.png"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

📚 Libraries

- [virtualenv](https://pypi.org/project/virtualenv/)
- [Flask](https://pypi.org/project/Flask/)

🛠 Utilities

- Databases

  - [DBeaver](hhttps://dbeaver.io/)

- DevOps

  - [Git](https://git-scm.com/)

- API
  - [Postman](https://www.postman.com/)

## 📐 Project

This was the project from the Next Level Week 16th Edition that was presented from JUL/08/2024 ~ JUL/11/2024.
This project is a web travel plan application to help people to efficiently plan the next trip, invite friends and organize the activities.
Check the project online [here](https://douglasdl.github.io/NLW16-Python/index.html).

Install the packages:

```sh
pip3 install virtualenv
pip3 install Flask
```

Create the Virtual Environment:

```sh
python3 -m venv venv
```

Activate the Virtual Environment to use:

```sh
. venv/bin/activate
```

Run the server:

```sh
python3 run.py
```

## 🔖 Layout

The basic layout project can be accessed in [this link](https://www.figma.com/design/sY04E2s0FLhZU4wsdCBE3w/NLW-Journey-%E2%80%A2-Roteiro-de-Viagem?node-id=0-1&t=ZrUmpZJmqO76cS9O-0) in your [Figma](https://figma.com) account.

## 💻 IDE

This project was done using [Visual Studio Code](https://code.visualstudio.com/) IDE.

### 🧩 VS Code Extensions

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Omni Theme](https://marketplace.visualstudio.com/items?itemName=rocketseat.theme-omni)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode#:~:text=Prettier%20is%20an%20opinionated%20code,account%2C%20wrapping%20code%20when%20necessary.)

### ⚙ VS Code Configuration

- CRTL + SHIFT + P
  - settings.json

```json
{
  "editor.fontSize": 16,
  "terminal.integrated.fontSize": 16,
  "workbench.colorTheme": "Omni",
  "workbench.iconTheme": "material-icon-theme",
  "editor.bracketPairColorization.enabled": true,
  "editor.minimap.enabled": false,
  "editor.wordWrap": "on",
  "workbench.editor.tabSizing": "shrink",
  "explorer.compactFolders": false,

  // formatter
  "prettier.tabWidth": 2,
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "none",
  "prettier.arrowParens": "avoid",
  "prettier.endOfLine": "auto",
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true
}
```

## 📝 License

This project is under the MIT license. See the file [LICENSE](https://github.com/douglasdl/NLW16-Python/blob/main/LICENSE) for more details.

---

Done with ♥ by [Douglas Dias Leal](mailto:douglasdiasleal87@gmail.com)
