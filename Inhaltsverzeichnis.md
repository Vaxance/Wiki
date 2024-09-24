# Inhalte
```dataviewjs
var pages = dv.pages('"Markdown"');

for (let group of pages.groupBy(p => p.group)){
	dv.header(group)
}
```
