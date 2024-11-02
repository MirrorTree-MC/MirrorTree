<a title="MirrorTree Wiki" href="wiki.mirror.bearcabbage.top/"><img align="right" alt="MirrorTree logo" width="120" height="120" src="/source/images/logo.svg"></a>

# MirrorTree Wiki

> Once upon a time, there was a Mirror Tree.

## About This Repository

> [!WARNING]
> Contributors ought to look through this section throughly before editing the website.

### Local Deployment

You may follow the steps below to deploy the website locally. [Node.js](https://nodejs.org/zh-cn) is required for the deployment.

```bash
# clone the repository and install the dependencies
git clone https://github.com/MirrorTree-MC/MirrorTree.git
cd MirrorTree
npm install

# start the local server
hexo g -d
hexo s
```

### Core File Structure

```bash
.
├── source
│   ├── _posts # common posts
│   ├── docs   # documentation
│   │   ├── server        # culture of the server
│   │   ├── introduction  # introduction for freshers
│   │   ├── advanced-info # advanced information
│   │   └── issue.md      # problem solving
│   └── news   # mirror news
├── .gitignore
├── _config.next.yml # configuration of NexT theme
├── _config.yml      # configuration of Hexo
└──  README.md       # guidelines for contributors
```

> [!NOTE]
> Given that [Hexo](https://hexo.io/) has its own specific file structure when deploying a website, you may refer to the `pbulic` folder in the root directory as a reference while using internal links, which is the actual root directory of the internal links.

### Documentation Norm

The documentation should be clear and concise in order that problem dealing can be more efficient. You may follow the github markdown syntax when writing a document. Note that we use `###` as the top level heading in markdown posts, and that to insert a space between Chinese and English words is strongly recommended.

> [!TIP]
> Trick-playing is recommended when writing a document, which means your expressions needn't be that *wikism*.

### Git Norm

A commit message should be clear and concise in order that problem dealing can be more efficient. It ought to be in the following format:

```git
<type>(<scoop>): <subject>
// <BLANK LINE>
<body>
// <BLANK LINE>
<footer>
```

- `<type>`: The type of the commit, such as `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, etc.
- `<scoop>` (optional) : The scope of the commit, such as `algorithm`, `communication`, `archive`, etc.
- `<subject>`: A brief summary of the commit. It should be in the imperative mood without `dot (.)` at the end of a line.
- `<body>` (optional) : A detailed description of the commit.
- `<footer>` (optional) : A footer for the commit, such as `BREAKING CHANGE`, `ISSUES CLOSED`, etc.

> [!NOTE]
> Although pull requests are different from commits, you may follow the same format when writing a pull request.

## License

[![CC BY-NC-SA 4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

```plaintext
Copyright (c) 2024 MirrorTree
Current version is Type M Edition 0.10
2024.11.2
```
