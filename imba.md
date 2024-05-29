# imba
- https://imba.io the friendly fullstack language
- 2nd study = 18 April 2024 , 1st study is 2021 from [this hacker news](https://news.ycombinator.com/item?id=28207662)

## from change log 
- `global.L = console.log` for shorter log command
- [use svg](https://imba.io/changelog#200alpha189) `import * as icons from 'imba-codicons' <svg src=icons.volume-up>`
- `for member,index,len in list` to get index and length
- [functional component](https://imba.io/changelog#200alpha194) `< tag() >`
- `<div[size:value]>` [size of div](https://imba.io/docs/css/properties/size)
- `let res = try await some-function catch` to catch and [return error](https://imba.io/changelog#200alpha224)

## from api page
- [Router](https://imba.io/docs/router) `def routed` to load data. o@suspended0.4 set opacity during load. see demo for genre.fetch(params.id)
- [Element](https://imba.io/api/Element) route scrollTo()
- [Event](https://imba.io/api/Event) @input @click emit debounce 
- [local storage](https://imba.io/api/imba/locals) `imba.locals.prop = 'value'`
- [re-render](https://imba.io/api/imba/commit) outside dom event and promise event
- [touch event](https://imba.io/api/imba/Touch) sync() x y
- [Date](https://imba.io/api/Date) toLocaleDateString()
