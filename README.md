# Example test for Internet 6

This repository tests a feature in Internet 6 - the ping fails.

It also demonstrates that there's some problem with accessing zero page for some reason.

## Contents

* `bin` - the tools directory from the release
* `internet` - the InetDBase equivalent, mapped through `OBSD$Path`. Contains a pre-populated random seed file as this takes stupidly long to generate normally.
* `resfs` - extracted resources from the modules, mapped through `Resources$Path`.
* `rm` - unmodsqz'd modules from the release.
* `modules` - additional modules that are needed to test things.

