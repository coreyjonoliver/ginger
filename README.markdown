ginger
================================================================
Corey Oliver, 2011

A Computer Algebra System written in OCaml.

Requirements
------------
  * OCaml
  * [OCaml with Batteries][1]

Usage
-----

The Ginger project includes one command line tool: `gingeri`, the
Ginger interpreter. `gingeri` uses standard input for the Ginger input
and standard output for the program output. For example, to interpret
the Ginger script `foo.ginger` and write the output of `gingeri` to
the file `bar.out` you would use the following command:

    ./gingeri < foo.ginger > bar.out

Language Tutorial
-----------

A brief tutorial for getting started using Ginger is provided in
`tutorial/`.

Language Manual
---------------

A manual for the input language of Ginger is available in
`manual/language-input.txt`.

Architecture
------------

A brief document describing the architecture of Ginger is given in
`manual/architecture.txt`.

License
-------

Copyright (c) 2011, Corey Oliver, corey.jon.oliver@gmail.com

Permission to use, copy, modify, and/or distribute this software for
any purpose with or without fee is hereby granted, provided that the
above copyright notice and this permission notice appear in all
copies.

THE SOFTWARE IS PROVIDED “AS IS” AND THE AUTHOR DISCLAIMS ALL
WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE
AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL
DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR
PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER
TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.

[1]: http://batteries.forge.ocamlcore.org/