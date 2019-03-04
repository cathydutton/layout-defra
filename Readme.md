# Defra flood warning layout

Defra page template for showing flood warnings in the Gov.uk Prototype kit

## How to install

Download this repo and run NPM install in the protoype kit copying this folder as the path

## How to include

Set the class name and banner text values at the top of the page.

```
{% set floodWarningClass = "alert" %}
{% set floodWarningTitle = "Flooding is possible - be prepared" %}
```

```
{% set floodWarningClass = "warning" %}
{% set floodWarningTitle = "Flooding expected - Take action" %}`
```

```
{% set floodWarningClass = "severe" %}
{% set floodWarningTitle = "Danger to life" %}`
```

Replace this line 

`{% extends "layout.html" %}`

With...

`{% extends 'layout-defra-flood-warning.html' %}`


## License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").