# Competition_Programming_Environment

```
export PATH="/home/dev/.local/bin:$PATH"

gpp() {
    g++ -std=c++20 $1.cpp
}
gppt() {
    gpp $1
    oj t
}
```

`~/.bashrc` に追記して、`source ~/.bashrc` をたたく