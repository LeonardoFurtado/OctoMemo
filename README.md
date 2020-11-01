<h1 align="center">:octocat: OctoMemo :memo:</h1>

<p align="center" style="margin-bottom: 5px; margin-top: 5px;">
  <a href="https://travis-ci.org/LeonardoFurtado/OctoMemo">
        <img src="https://img.shields.io/travis/LeonardoFurtado/OctoMemo/master?logo=travis&style=for-the-badge" alt="Build Status"></a>
  <a href="https://coveralls.io/github/LeonardoFurtado/OctoMemo">
        <img src="https://img.shields.io/coveralls/github/LeonardoFurtado/OctoMemo/master?logo=coveralls&style=for-the-badge" alt="Code Coverage"></a>
  <a href="https://github.com/LeonardoFurtado/OctoMemo/blob/master/LICENSE"><img src="https://img.shields.io/github/license/LeonardoFurtado/OctoMemo?logo=git&logoColor=orange&style=for-the-badge"/></a>
   <a href="https://github.com/LeonardoFurtado/OctoMemo/stargazers"><img src="https://img.shields.io/github/stars/LeonardoFurtado/OctoMemo.svg?color=informational&style=for-the-badge&logo=github&label=Stars&logoColor=informational"/></a>
  <a href="https://github.com/psf/black"><img src="https://img.shields.io/badge/code%20style-black-black?style=for-the-badge"/></a>


</p>

### Work in progress, use at your own risk!!!

So, currently I no longer like using note-taking apps like Ever...(You know who :elephant:), so I've been using Github to save some notes on my CS classes. However, I don't like the idea of having to log into Github to add a simple note. Therefore, I created this CLI to accomplish this task.

* Note: I intend to stop using PyGithub in this project because I would like to learn GraphQL and will probably use it here.


### :book: Contents
- [Instalation](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#gear-instalation)
- [QuickStart](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#rocket-quickstart)
- [Usage](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#computer-usage)
- [Contributing](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#handshake-contributing)
- [Project layout](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#tanabata_tree-project-layout)
- [Maintainers](https://github.com/LeonardoFurtado/OctoMemo/blob/master/README.md#building_construction-maintainers)

### :gear: Instalation

1) Fetch from repo:
  ```
  git clone https://github.com/LeonardoFurtado/OctoMemo.git
  ```
2) Change to OctoMemo directory
  ```
  cd OctoMemo
  ```
2) Create virtualenv based on your own system:
  ```
  python3 -m venv venv
  ```
3) Activate virtual environment:
  ```
  source venv/bin/activate
  ```
4) Pipe requirements to venv folder:
  ```
  pip install -r requirements.txt
  ```

### :rocket: QuickStart

[This will be updated soon]

Download thist repo, use `cd OctoMemo` and try `python3 scripts/app-cli.py [OPTIONS] COMMAND [ARGS]`

### :computer: Usage

```
Usage: app-cli.py [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  create
  delete
  edit
  list
```
### :handshake: Contributing

### :test_tube: Testing

### :tanabata_tree: Project layout
```
OctoMemo
├── scripts
│   ├── app-cli.py
│   ├── file_management.py
│   ├── __init__.py
│   ├── note.py
│   └── user.py
├── tests
│   ├── __init__.py
│   └── test_user.py
├── LICENSE
├── readings.md
├── README.md
├── requirements-dev.txt
├── requirements.txt
└── setup.py
```

### :building_construction: Maintainers

| [![Leonardo Furtado](https://github.com/LeonardoFurtado.png?size=100)](http://leonardofurtado.me) |
| :-----------------------------------------------------------------------------------------------: |
|          [Leonardo Furtado](https://github.com/LeonardoFurtado)                                           |
