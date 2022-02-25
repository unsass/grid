# Grid

[![Version](https://flat.badgen.net/npm/v/@unsass/grid)](https://www.npmjs.com/package/@unsass/grid)
[![Downloads](https://flat.badgen.net/npm/dt/@unsass/grid)](https://www.npmjs.com/package/@unsass/grid)
[![License](https://flat.badgen.net/npm/license/@unsass/grid)](https://www.npmjs.com/package/@unsass/grid)

## Introduction

Sass grid classes generator.

## Installing

```shell
npm install @unsass/grid
```

## Usage

### Styles

```scss
@use "@unsass/grid/styles";
```

> This will generate the default grid classes.

### Configuration

```scss
@use "@unsass/grid" with (
    $columns: 10
);
```

### Options

| Name          | Default | Description              |
|---------------|---------|--------------------------|
| `$columns`    | `12`    | Sets numbers of columns. |
| `$column-gap` | `12px`  | Sets the column gap.     |
| `$rows`       | `6`     | Sets  numbers of rows.   |
| `$rows-gap`   | `12px`  | Sets the row gap.        |

## API

_Coming soon..._
