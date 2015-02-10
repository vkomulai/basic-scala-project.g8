This is a [giter8](https://github.com/n8han/giter8) template for generating a new scala project. It comes bundled with:

* `main` and `test` source directories
* [ScalaTest](http://www.scalatest.org/)
* [Scalacheck](http://www.scalacheck.org/)
* SBT configuration for `0.13.0`, `Scala 2.11.1`, and `ScalaTest 2.11` dependencies
* project `name`, `organization` and `version` customizable as variables

## Usage

    # create project and open using idea.
    g8 vkomulai/basic-scala-project.g8
    cd {your-project}
    sbt gen-idea
    # https://gist.github.com/vkomulai/8fb059238de8183673ce
    idea

## Changelog

### 0.1.3 (vkomulai fork)
* Included good stuff from https://github.com/fractal/skeleton/blob/master/build.sbt
* Scala 2.11.1
* Scalatest 2.11 - 2.2.2

### 0.1.2
* Scala 2.10.3

### 0.1.1
* Scalatest 1.9.2 for testing
* Sbt 0.13.0

### 0.1.0 (Initial release!)
* Scalatest 1.9.1 for testing
* Sbt 0.12.4
* Scala 2.10.2
