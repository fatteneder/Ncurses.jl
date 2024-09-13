# Ncurses.jl

This wraps the [ncurses](https://invisible-island.net/ncurses/)
library. The Julia bindings are generated automatically via
[Clang.jl](https://github.com/JuliaInterop/Clang.jl).

* [![GitHub
  CI](https://github.com/eschnett/Ncurses.jl/workflows/CI/badge.svg)](https://github.com/eschnett/Ncurses.jl/actions)
* [![codecov](https://codecov.io/gh/eschnett/Ncurses.jl/graph/badge.svg?token=VGMG5U8M41)](https://codecov.io/gh/eschnett/Ncurses.jl)

Note to myself: Use this command to regenerate the bindings:
```sh
# Clang v0.18.3
cd gen && julia --project=@. --threads=auto generator.jl
```
