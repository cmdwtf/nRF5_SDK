# Nordic nRF5 SDK v17.0.0

This is a mirror of the Nordic nRF5 SDK, version 17.0.0 (9d13099)

Please refer to Nordic's [official documentation](https://www.nordicsemi.com/Software-and-tools/Software/nRF5-SDK) for any questions.

The following files have been omitted due to size. Please see the official Nordic release if you need these files.

* ./external/fatfs/doc/res/*

# Licensing

This is **not** an official repository, but provided as a mirror for projects (mostly my own) that prefer to have git dependencies.

Please refer to [Nordics Licensing Documentation](./documentation/licenses.txt). All copyright notices have been maintained in their entirety within this repository.

# Modifications

Currently, this repository has two modifications to the nrfx_nfct code. All of the changes have been submitted as PRs to the NordicSemiconductor/nrfx repository, but I'm not sure if they'll merge them, nor when a release would follow. I will attempt to document all the changes here as long as they're out of sync.

* [nrfx_nfct: Add callback for RXFRAMESTART](https://github.com/NordicSemiconductor/nrfx/pull/78)
* [nrfx_ncft: Add function to tx specific bit amount](https://github.com/NordicSemiconductor/nrfx/pull/79)
