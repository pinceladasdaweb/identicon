# Identicon

Generate [Identicons](https://github.blog/2013-08-14-identicons/) with Elixir (for educacional purposes).

## Installation

After cloning this repository, run the following commands to setup the project:

```sh
mix deps.get
mix deps.compile
```

After installing the dependencies and compiling the project, run the following command to access Elixir’s Interactive Shell:

```sh
iex -S mix
```

And finally generate your Identicon with the following command:

```sh
Identicon.main("your_string_here")
```

With this a new Identicon is generated at the root of the project.