# News Classification using LDA (Latent Dirichlet allocation)

## What this project is for?

There are 5 main goals.
- To understand the theory of [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation).
- To implement LDA with [Gensim](https://radimrehurek.com/gensim/) or [fastText](https://fasttext.cc/).
- To develop a web application for categorizing news.
- To improve my coding and development skills.
- To enrich my mathematical skills.

## Development environment

My development environment is as follows.
### OS
- [Ubuntu 20.04.4 LTS (Focal Fossa)](https://releases.ubuntu.com/20.04/)

### Python3
- version

    - 3.8.10

- package
    
    The following command is to install packages.
    ```bash
    $ pip3 install -r ./config/requirement.txt
    ```
    The following command is to update ```./config/requirement,txt```.
    ```bash
    $ pip3 freeze > ./config/requirement.txt
    ```

### Editor
I use [Visual Studio Code](https://code.visualstudio.com/) and recommend to include some extensions:

- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

## Directory tree

The main composition od directories is as follows.
```
.
├── app
├── config
├── data
├── doc
└── src

```

We can check the directory tree in detail by typing:
```bash
$ sudo apt install tree
$ tree -d .
```
## Documents
The new what I studied is saved as a document in [```./doc```](./doc/README.md).