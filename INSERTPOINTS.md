## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: pagination, @tag: component-partial }}
{{#with pagination.variations.simple}}
	{{> pagination}}
{{/with}}
{{! @INSERT :: END }}
```
