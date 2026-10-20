# admin

A service of the fictorg example, for [orca](https://github.com/adamkirk/orca), that's disabled by default.

`orca ws init` still clones it, and runs its `clone.post` hook, but `orca up` skips it, along with its `up` hooks. Enable it with `orca ws enable admin`, or start it on its own with `orca up -p admin`.
