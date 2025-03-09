# pp-log

[![CI Status](https://github.com/mbarbin/pp-log/workflows/ci/badge.svg)](https://github.com/mbarbin/pp-log/actions/workflows/ci.yml)

⚠️ This project is still active, but it has moved [there](https://github.com/mbarbin/pplumbing). This repository will be archived and made read-only.

----

In this project I explore designs to build pretty printed documents to log and raise user messages with `pp`.

I intend to produce something compatible with [logs](https://github.com/dbuenzli/logs), [pp](https://github.com/ocaml-dune/pp) and design choices made by `dune` for [user_message](https://github.com/ocaml/dune/blob/main/otherlibs/stdune/src/user_message.mli).

This is very experimental and a work in progress.

## Acknowledgements

- We would like to thank the Dune developers for the user-facing error handling of Dune (`Stdune.User_message`), on which we based the error handling scheme used in (`Err`). By adopting a similar approach, we aim to provide a consistent and unified user experience for OCaml users across different tools and libraries.
