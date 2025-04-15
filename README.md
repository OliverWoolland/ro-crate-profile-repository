# RO-Crate Profile Repository

This repository demonstrates the use of the [profile-repository-to-pages](https://github.com/vliz-be-opsci/profile-repository-to-pages) Github Action to generate a static website showing the contents of a profile repository.

## Local testing / development

If you wish to test the website locally, you can use the `docker-compose` file in this repository. This will:
* Generate the static content
* Create a local web server that serves the static website.

To get started, you must clone this repository **with** submodules:

```bash
$ git clone --recurse-submodules git@github.com:OliverWoolland/ro-crate-profile-repository.git
```

Then, you can run the following command to start the local server:

```bash
$ docker-compose up
```

## Roll your own 

If you wish to set up your own profile repository you can follow the approch demonstated by VLIZ [here](https://github.com/vliz-be-opsci/demo-profile-repository), or the approach demonstrated by this repository, forked from the VLIZ example.
