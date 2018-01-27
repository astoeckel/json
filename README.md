# Release-tracking repository for nlohmann/json

This repository automatically tracks releases of https://github.com/nlohmann/json.
It downloads the released `json.hpp` and `json_fwd.hpp` files, stores them
in the `src` directory, and adds a Git tag. Correspondingly, this repository
can be used as a lightweight Git submodule, without having to download
megabytes of data for a JSON library.

See [#732](https://github.com/nlohmann/json/issues/732), [#620](https://github.com/nlohmann/json/issues/620), [#556](https://github.com/nlohmann/json/issues/556), [#482](https://github.com/nlohmann/json/issues/482), [#96](https://github.com/nlohmann/json/issues/96)

#### Update 2017/02/04
Force-pushed new version of the repository. The new update script automatically
downloads the newly released `json_fwd.hpp` header.
