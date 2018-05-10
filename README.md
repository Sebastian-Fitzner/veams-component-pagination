<p align="right">
<a href="https://badge.fury.io/js/%40veams%2Fcomponent-pagination"><img src="https://badge.fury.io/js/%40veams%2Fcomponent-pagination.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Pagination

## Description

Simple pagination component.

-----------

## Requirements

- [@veams/core](https://github.com/Veams/core) - Veams Core Framework.

-----------

## Installation

### Installation with Veams

``` bash
veams install component pagination
```
``` bash
veams -i c pagination
```

-----------

## Fields

### `pagination.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- |:---:|:---: |:--- |
| settings.pagContextClass | String | `default` | Context class of component. |
| settings.pagClasses | String | | Modifier classes for component. |

#### Content

| Parameter | Type | Description |
|:--- |:---:|:--- |
| content.pagButtons | Object | Object with multiple elements. |
| content.pagButtons.pagDescription | String | Description for buttons. |
| content.pagButtons.previous | String | Description for previous button. |
| content.pagButtons.next | String | Description for next button. |
| content.pagCurrent | String | Description for current element. |
| content.pagMax | Number | Last number in pagination. |
