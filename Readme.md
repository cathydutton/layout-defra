# Defra layout

Defra page template for internal services

## How to install

`npm install cathydutton/layout-defra`

## How to include

Replace this line 

`{% extends "layout.html" %}`

With...

`{% extends 'layout-defra.html' %}`

Just above the layout include set the service name... 

`{% set DefraServiceName = "My service name" %}`


## License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
