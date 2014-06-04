Demo-Kaldi-Word-Verification
============================

A demo on automatic speech word selection and verification using Kaldi, with frontends.

Dependencies
-----
 * A basic POSIX environment(cygwin ok), wget, zsh, sed and xz
 * Kaldi : http://kaldi.sourceforge.net/

Install
-----
 1. Install all dependencies. Note that we need a full source tree of Kaldi, not only its binaries and libraries. You can find an example script of installing Kaldi under cygwin [here](https://github.com/cybeliak/KaldiFace/blob/master/doc/compile_cygwin.sh).
 2. copy local.zsh.template to local.zsh, and point variables in local.zsh to the actual path in your environment.
 3. Run 10.prepare/download\_lexicon.zsh to get the CMU dictionary.

Caveats and Known Bugs
-----
 * We directly use the Makefile from Kaldi. If there are bugs, things in this project will also be affected.

Author and Acknowledgements
-----
Yu-chen Kao (cybeliak) : cybeliak [the mysterious symbol] mail asteraceae org

License
-----
This project is licensed under the Academic Free License, Version 3.0.
See LICENSE for details.
