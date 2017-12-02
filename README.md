<div align="center">
	<img height="400px" src="art/kuzmich-toolkit.png">
</div>

Kuzmich tookit - it is a group of components for running Android instrumentation tests.

This toolkit consists of:
1. [Kuzmich runner](http://github.com/kuzmich-toolkit/kuzmich-runner) - tool for grouping devices and running instrumentation tests on parallel mode. This tool may run tests in two modes:
	
	a) **Normal mode** - this mode uses default instrumentation tests mechanism for running tests.

    b) **Isolation mode** - in this mode kuzmich runs test in separate instrumentation and clear package data before every test.
    
2. [Kuzmich http report](http://github.com/kuzmich-toolkit/kuzmich-http-report) - tool for generating http report from [Kuzmich runner](http://github.com/kuzmich-toolkit/kuzmich-runner) artifacts.
3. [Kuzmich junit report](http://github.com/kuzmich-toolkit/kuzmich-junit-report) - tool for generating junit report from [Kuzmich runner](http://github.com/kuzmich-toolkit/kuzmich-runner) artifacts.
4. Kuzmich dex parser - tool for getting tests from apk for further running [Kuzmich runner](http://github.com/kuzmich-toolkit/kuzmich-runner) in isolation mode.

WIP

## Artifacts

WIP