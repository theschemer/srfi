# srfi

SRFIs for Chez Scheme

repackage by theschemer / Raven support team from https://github.com/ovenpasta/thunderchez

There is an existing R6RS srfi project at:

https://code.launchpad.net/~scheme-libraries-team/scheme-libraries/srfi

In that project, the library names use the colon character. E.g.:

    (srfi :1 lists)

Filenames with a colon are not portable across UNIX and Windows. Some
Scheme implementations support an encoding whereby ':1' is
mapped to '%3a1'. Chez Scheme does not perform the conversion.

The surfage libraries are a port of the R6RS srfi libraries to have
names such as:

    (surfage s1 lists)

