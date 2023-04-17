# AGSchemas

AGSchemas will contain the source code which runs: https://agschemas.org


## Building

The site is using [11ty](https://www.11ty.dev/) static site generator and requires [Node.js](https://nodejs.org/en). Once Node is installed, the site can be run locally as:

```
npm run build
```

If you want to watch the changes pages while you edit it, you can also run:

```
npm run serve
```

and the pages can be seen at: http://localhost:8080

The site is automatically deployed after a push using [github Actions](https://github.com/agschemas/agschemas.github.io/actions/workflows/build.yml).


