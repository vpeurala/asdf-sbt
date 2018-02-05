# asdf-sbt

Plugin for asdf version manager (https://github.com/asdf-vm/asdf/), for installing sbt (https://www.scala-sbt.org/).

Forked from https://github.com/lerencao/asdf-sbt.

## Usage

``` shell
asdf plugin-add sbt https://github.com/vpeurala/asdf-sbt
asdf list-all sbt
asdf install sbt 0.13.16
```
To run SBT, you need to have a working Java JDK installed (either Oracle's or OpenJDK).

## Limitations

**Currently this repository can install ONLY sbt 0.13.16, no other versions!**

**IF YOU NEED SOME OTHER VERSION THAN 0.13.16, USE https://github.com/lerencao/asdf-sbt (which, on the other hand, CANNOT install 0.13.16).**

The problem is that 0.13.16 must be downloaded from a different place than all the other versions.

Right now this repository contains a lot of semi-hardcoded stuff, because this exists only for the installation on sbt 0.13.16.

Hopefully someday someone has the time and energy to write an asdf plugin for sbt which supports all versions.

