#Rust Userland Drop-in Replacements

This is an editable table of rust userland programs, either in development or actively maintained, 
that aspire to be drop-in replacements for existing popular userland applications, programs, packages, etc, 
with no more and no less functionality.

## Progress key

* I : initial stages
* II : active development
* III : approaching feature parity
* IV: feature parity. Testing, reliability, performance, refactoring.
* V: stable

Org | Project | Toolname | Replacement Name | Project | Org | Status
--- | --- | --- | --- | --- | --- | ---
Gnu | Coreutils | Echo | uutils echo | [uutils coreutils][uutils coreutils]| [uutils][uutils] | II


### Why make drop-in replacements? Why not make new, better designed programs?

Having rust versions of them is a big step to an all-rust userland.

### My program is like ls, but only better because it can do x, y, and z. Why is this program not on the list?

We want people to be confident that if they start testing and dogfooding anything on this list, and start using it with scripts, 
there is no possibility that they will get "locked in" to something that is simply supposed to be a 1:1 replacement.

[uutils]: https://github.com/uutils/coreutils 
[uutils coreutils]: https://github.com/uutils/coreutils
