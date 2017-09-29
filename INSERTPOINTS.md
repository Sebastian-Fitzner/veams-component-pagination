## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: pagination, @tag: component-partial }}
{{#with pagination-bp.simple}}
	{{> c-pagination}}
{{/with}}
{{! @INSERT :: END }}
```