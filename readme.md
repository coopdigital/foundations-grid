# Component/Module Template
This repository serves as a template for creating new components and modules for Co-op Frontend Toolkit. To get started, refer to this repo's [Wiki](https://github.com/coopdigital/component-template/wiki).

---

# `component-[name]` or `module-[name]`
Your brief description of your component or module.

## Installation
Install via `npm` or Yarn:
```bash
$ npm install @coopdigital/component-[name] --save
# OR
$ yarn add @coopdigital/component-[name]
```

## Usage
You can include `component-[name]` in your project by referencing it from your existing CSS via `@import` statement, i.e.:
```css
@import "node_modules/@coopdigital/component-[name]/dist/[name].css";
```

If you use PostCSS in your build pipeline, you can reference the sources directly like so:
```css
@import "node_modules/@coopdigital/component-[name]/src/[name].pcss";
```

If you use a `postcss-import` plugin, it gets even easier:
```css
@import "@coopdigital/component-[name]";
```

## Examples
Here's a bunch of examples, showing how you can integrate this CSS module in your project, based on most popular stacks of project. You can either use a post-processed and pre-built CSS form the `dist` directory, ot use PostCSS sources from the `src` dir.

The latter have certain dependencies, which should be consumed by your frontend toolkit to postprocess the CSS correctly.

### Vue.js
TBD

### React.js
TBD

## Development
TBD
