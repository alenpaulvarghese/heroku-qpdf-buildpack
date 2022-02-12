# Heroku Buildpack QPDF

This is a Heroku buildpack for using `qpdf-10.6.1` in your project.

The binaries for this pack are fetched from qpdf github [release](https://github.com/qpdf/qpdf/releases) page.

This project is a up-to-date clone of jamesdphillips [heroku-buildpack-qpdf](https://github.com/jamesdphillips/heroku-buildpack-qpdf.git)

## Usage

Add the buildpack to your application.

```bash
heroku buildpacks:add https://github.com/alenpaul2001/heroku-qpdf-buildpack -a `app-name`
```

You can verify installation by running the following.

```bash
heroku run "qpdf --help" -a `app-name`
```
