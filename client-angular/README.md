# Angular Template (NgxMarkdown)

## Web App ([repo](https://github.com/david-rachwalik/Templates-Angular15-NgxMarkdown))

Template Angular v15 web application with ngx-markdown

### Project Commands Used

Generate a new Angular application ([tutorial](https://angular.io/tutorial/toh-pt5), [layouts](https://indepth.dev/posts/1235/how-to-reuse-common-layouts-in-angular-using-router-2), [RxJS](https://www.learnrxjs.io))

```bash
ng new <app-name>
```

Install [ngx-markdown](https://github.com/jfcere/ngx-markdown) and [gray-matter](https://github.com/jonschlinkert/gray-matter)

- based on features of [Jekyll](https://github.com/jekyll/jekyll) ([docs](https://jekyllrb.com/docs), [resources](https://jekyllrb.com/resources), [showcase](https://jekyllrb.com/showcase))

```bash
npm i ngx-markdown marked gray-matter
npm i -D @types/marked
npm i prismjs clipboard
```

---

[Default Angular component css display block](https://stackoverflow.com/questions/51032328/angular-component-default-style-css-display-block) (generated components will contain css `:host { display: block; }`)

```json
...
// Set default value in angular.json (Angular v9.1+)
"projectType": "application",
"schematics": {
  "@schematics/angular:component": {
    "displayBlock": true
  }
}
...
```

### Angular Generate Commands Used

Generate a new Angular component

```bash
ng g c <component-name>
```

Generate a new Angular module

```bash
ng g m <module-name>
```
