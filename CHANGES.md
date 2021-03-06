# Change Log

## v1.2.0

_Release Date_: 2016-10-06

- Target expansion
- Retire example _drone_

## v1.1.1

_Release Date_: 2016-09-20

- Wrapper mode
- Upgrade dependency [clix.go](https://github.com/codingbrain/clix.go)

## v1.1.0

_Release Date_: 2016-08-31

- Patching `/etc/passwd` with valid username for certain apps (like `git`) to work;
- Extract `~` as `$HOME` in host path of volume mapping;
- Direct `docker commit` support in target, via `commit` property;
- Unify implementation logic with/without `docker-machine`;
- Properties and values in target are also calculated in target digest;
- `cmd` and `script` are calculated in target digest;
- Target name validation;
- Options `-s` and `-v` are default;
- In-container execution support (`-x` and `-X` options);
- Direct `docker push` support in target, via `push` property;

## v1.0.0

_Release Date_: 2016-06-26

Initial stable release
