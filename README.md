# Data for the Evaluation of IT Systems regarding Longterm Preservation of Research Data

This repository contains a collection of several IT systems in order to evaluate their usability for the longterm preservation of research data.
It consists of several git submodules that have to be initiated after cloning the repository by:

```
git submodule update --init
```

# Repository Structure

For each IT system a separate folder has been created in the root level of this repository, e.g. `archivematica`.
Each of these directories contains a submodule integrating the particular source code used for the evaluation.

The local test instances that have been used were created according to the following how-tos:

* archivematica: has not been evaluated locally, instead the [public demo](https://sandbox.archivematica.org/administration/accounts/login/) has been used for the evaluation
* [DSpace](https://wiki.lyrasis.org/display/DSPACE/Try+out+DSpace+7#TryoutDSpace7-InstallviaDocker)
* [MyCoRe MIR](mycore/mir/README.md)