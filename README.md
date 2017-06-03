# wkhtmltox Buildpack

This is a [Heroku buildpack][0] for bundling compatible [wkhtmltopdf][1] and [wkhtmltoimage][1] binaries with your environment.

## Versions

* Buildpack:   `0.1`
* wkhtmltopdf: `0.12.4`

## Usage

This buildpack only installs wkhtmltopdf and wkhtmltoimage, it isn't very useful by itself. 

```bash
$ echo 'https://github.com/Bizcuit/wkhtmltox-buildpack.git' >> .buildpacks
$ git add .buildpacks
$ git commit -m 'Add wkhtmltox-buildpack'
```

[0]: http://devcenter.heroku.com/articles/buildpacks
[1]: http://wkhtmltopdf.org/
