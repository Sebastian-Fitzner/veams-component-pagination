### Include: Page

``` hbs
{{! @INSERT :: START @id: pagination, @tag: component-partial }}
{{#with pagination-bp.simple}}
	{{> c-pagination}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @tag: scss-self-contained-import //
@import "../components/pagination/scss/_c-pagination";
// @INSERT :: END //
```