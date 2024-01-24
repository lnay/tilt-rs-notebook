# Try Out `pseudo_tilt` Rust Crate in a notebook

This is a repository to try out my rust crate [pseudo_tilt](https://gitlab.com/pseudowalls/tilt.rs), a library for computing pseudowalls
for a given Chern character (currently only when there are finitely many) on a Picard rank 1 surface.

If you are already familiar with rust and or have the toolchain installed, it may be better to follow the link to the create directly and use that instead.
If you are unfamiliar with rust, but are working with a variety where the self intersection of $\ell$, the chosen generator of the Neron-Severi group, is 1 or 2;
then it may be better to check out the Python wrapper instead [here](https://github.com/lnay/pseudo_tilt_py).

However, if unfamiliar with rust, and want to try out the functionality that is not available in the [Python wrapper](https://github.com/lnay/pseudo_tilt_py);
then this repository exists to enable the use of the rust library directly in a notebook with minimal software setup (i.e. none if using codespaces).

## Instructions

### Codespaces

Note that free Github accounts are allowed to use up to 60hrs of codespaces compute time. This project allows you to make use of some of this time to avoid installing software on your own computer.

On the Github page,
- click on the green "code" button
- choose the "codespaces" tab
- then create a codespace on main

This will open a tab preparing your codespaces, this will take a few minutes. Then you fill be able to open the jupyter notebook [notebook.ipynb], see examples computing pseudowalls for given Chern characters.
The documentation for the library is also available [here](https://pseudowalls.gitlab.io/tilt.rs/pseudo_tilt)

### VSCode + devcontainers

Alternatively, instead of running in the cloud, you can have a similar experience in VSCode with Docker (or podman) installed along with the "remote development" extension for VSCode.
You can find instructions elsewhere about devcontainers with VSCode.
