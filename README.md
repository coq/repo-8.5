# Coq Repository
The repository for stable Coq 8.5 packages. Powered by [OPAM](http://opam.ocamlpro.com/).

## Usage
Enable this repository:

    opam repo add coq-stable https://github.com/coq/repo-8.5.git

To install Coq 8.5 beta 1:

   opam install coq.8.5beta1

To install a package:

    opam search coq:that-package
    opam install coq:that-package

## Publish
If you want to add your package, please do a pull-request to this repository. Note that only stable versions for Coq 8.5 will be accepted. For development versions, you can use the [testing](https://github.com/coq/repo-testing) or [unstable](https://github.com/coq/repo-unstable) repositories.
