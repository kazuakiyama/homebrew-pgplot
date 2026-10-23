# homebrew-pgplot: moved to homebrew-vlbi

The PGPLOT Homebrew formula is now maintained in
[kazuakiyama/homebrew-vlbi](https://github.com/kazuakiyama/homebrew-vlbi),
together with PGPLOT, SCHED, and DIFMAP.

## New installations

```sh
brew install kazuakiyama/vlbi/pgplot
```

## Existing installations

```sh
brew tap kazuakiyama/vlbi
brew update
```

This repository provides a `tap_migrations.json` entry so Homebrew can migrate
installed `pgplot` formulae to `kazuakiyama/vlbi`. Follow any trust prompts
displayed by your Homebrew version, then use `brew upgrade` normally.
After migration, you can remove this old tap with `brew untap kazuakiyama/pgplot`.
If Homebrew reports that an installed formula still belongs here, leave the tap
in place and report the migration problem in the new repository.

See the [new README](https://github.com/kazuakiyama/homebrew-vlbi#readme) for
environment settings, validation coverage, and migration details.
Please file new packaging issues in
[homebrew-vlbi](https://github.com/kazuakiyama/homebrew-vlbi/issues).

This repository remains available for migration and historical reference.
