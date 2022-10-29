# Website

The parent repository of the GabriewF website.

## Repository structure

This repository contains all bStats repositories as submodules. These are

- `work/website-backend` - The backend of website.
- `work/website-frontend` - The frontend of website.

This repository also provides the development environment for bStats.

## Clone repository

When cloning the repository, it is recommended to use the `--recursive`
flag to clone the repository with all submodules.

```bash
git clone --recursive https://github.com/GabriewF/Website.git
```

Alternatively, you can also clone the submodules after cloning this parent
repository by running

```bash
git submodule init && git submodule update
```

## License

This project is licensed under the [MIT License](/LICENSE.md).

[website]: https://gabriewf.tk
