Module: Information Security Management (ism)
===============================================================================

This is a learning module for Information Security Management.  Its aim is to 
introduce the students to Information Security Management Systems, e.g. the ISO 
27000 framework.  They will also reflect on the fact that all risks cannot be 
technically mitigated, and that some threats don't constitute any risks.  ISM 
is about structurally handle risks.

The module is part of the [Open Security Education][OpenSecEd] project and the 
maintainer is [Daniel Bosk][dbosk].  The latest release can be found under 
[releases][Releases].  You can safely link directly to the PDFs found there.

[OpenSecEd]: https://github.com/OpenSecEd/
[dbosk]: https://github.com/dbosk/
[Releases]: https://github.com/OpenSecEd/ism/releases


File Structure and Building
-------------------------------------------------------------------------------

*To build* the PDFs, after cloning the repository you must clone its required 
submodules:

```shell
$ git submodule update --recursive --init
```
Then you can go into the directory of the desired document and run `make`.
The source files are structured as follows:

- `ismsmemo` contains a memo assignment on ISMS.
- `risksem` contains a seminar assignment on risk management.

In each directory the files are structured as follows:

- `<name>.tex` contains the main instruction.
- `aims.tex` is an itemized list of the intended learning outcomes, as such it 
  can be included in another document summarizing the list of intended learning 
  outcomes.
- `literature.tex` covers the required reading instructions, thus you can 
  include these in a study guide containing all reading instructions for the 
  course.
- `<name>.bib` contains the bibliography entries, thus this file can be 
  included along with the reading instructions.

*To contribute*, please [fork the repository][ForkARepo], make your changes, 
commit them and then create a [pull request][PullRequest] in the original 
repository.

[ForkARepo]: https://help.github.com/articles/fork-a-repo/
[PullRequest]: https://help.github.com/articles/using-pull-requests/
