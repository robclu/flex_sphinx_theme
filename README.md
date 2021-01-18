# Flex Sphinx Theme

This is designed to be a flexible sphinx theme, which can be realatively easily customized to
create good looking documentation. It is based off the pytorch sphinx theme.

## Installation

Run python setup:

```
python setup.py install
```

and install the dependencies using `pip install -r docs/requirements.txt`

# Local Development

In the root directory install the `package.json`:

```
# node version 8.4.0
yarn install

```

If you have `npm` installed then run:

```
npm install
```

If you want to see generated documentation for `docs/demo` then create
`.env.json` file and make it empty json file. Means `.env.json file` will
contain

```
{}
```

Run grunt to build the html site and enable live reloading of the demo app at `localhost:1919`:

```
grunt
```

The resulting site is a demo.

