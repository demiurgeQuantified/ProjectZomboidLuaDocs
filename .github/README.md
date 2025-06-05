## Contributing
You can build the docs locally by running [Doxygen](https://www.doxygen.nl) with the repository as your working directory.

Regular pages are created with `.dox` files at the root of the repository. See Doxygen's documentation for more information on this.

The events/callbacks/hooks pages are generated with [PZEventDoc](https://github.com/demiurgeQuantified/PZEventDoc). Modifications to the formatting of the data should be made there.

To generate the class pages, you'll also need [pz-lua-stubdata](https://github.com/omarkmu/pz-lua-stubdata) and [rosetta_doxygen](https://github.com/demiurgeQuantified/rosetta_doxygen).
However, this increases the build time massively, so if you aren't specifically trying to alter those pages, I recommend leaving them out.

See the [build workflow](https://github.com/demiurgeQuantified/ProjectZomboidLuaDocs/blob/develop/.github/workflows/publish.yml) for a closer look at how the website is built.
