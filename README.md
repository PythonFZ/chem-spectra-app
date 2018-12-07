# Chem_spectra

This web service provides automatically peaks-picking for jcamp files.

### Funding

This project has been funded by the  ![DFG](http://www.dfg.de/includes/images/dfg_logo.gif)


### License

see [LICENSE][LICENSE]


### Install

see [INSTALL.md][INSTALL]


### Run Production

```
$ waitress-serve --port=2412 --call 'chem_spectra:create_app'
```


### Run test

```
$ pytest --disable-pytest-warnings
```




[LICENSE]: LICENSE
[INSTALL]: INSTALL.md
