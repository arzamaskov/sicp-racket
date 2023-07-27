# Tasks from the SICP textbook

This repository is the copy of [Hexlet repository](https://github.com/hexlet-boilerplates/sicp-racket)

## Requirements

- [Racket](https://racket-lang.org/)
- Rackunit (raco pkg install rackunit)
- SICP Support for DrRacket (raco pkg install sicp)
- Racket-review surface-level linter (raco pkg install review)
- Make

## install

1. Install Racket from [PPA](https://launchpad.net/~plt/+archive/ubuntu/racket)

```shell
sudo add-apt-repository ppa:plt/racket
sudo apt update
sudo apt install racket
```

2. Install Rackunit

```shell
raco pkg install rackunit
```

3. Install SICP support and Racket-review

```shell
make install
```

## Using

- Write code (look sicp/chapter1/02.rkt)

- Run tests

```shell
make test
```
- Run linter

```shell
make lint
```
