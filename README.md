# sublime-erlang-rebar3
Sublime Text 3 build system for Erlang using Rebar3. This provides options to compile, run eunit tests, generate edocs etc right inside Sublime Text.

# How to use
Place the `Rebar3.sublime-build` file in Sublime Text packages folder. In Mac, packages folder is under `$HOME/Library/Application Support/Sublime Text 3/Packages/User`.

You should see `Rebar3` under Tools > Build System. Choose that to set Rebar3 as your buld system. Cmd + B will compile current Erlang project using `Rebar3`. These options are available in the Command Panel too.
