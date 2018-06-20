# sqlmap

Dockerized version of [sqlmap](https://github.com/sqlmapproject/sqlmap/releases).

## How to use?

Add this alias to .zshrc or .bashrc

```bash
alias sqlmap='docker run --rm -it -v /tmp/sqlmap:/root/.sqlmap/ evenh/sqlmap'
```
