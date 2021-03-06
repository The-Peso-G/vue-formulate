<p align="center"><a href="https://vueformulate.com" target="_blank" rel="noopener noreferrer"><img width="100" src="https://assets.wearebraid.com/vue-formulate/logo.png" alt="VueFormulate"></a></p>

<p align="center">
  <a href="https://travis-ci.org/wearebraid/vue-formulate"><img src="https://travis-ci.org/wearebraid/vue-formulate.svg?branch=master"></a>
  <a href="https://www.npmjs.com/package/@braid/vue-formulate"><img alt="npm" src="https://img.shields.io/npm/v/@braid/vue-formulate"></a>
  <a href="https://github.com/wearebraid/vue-formulate"><img alt="GitHub" src="https://img.shields.io/github/license/wearebraid/vue-formulate"></a>
  <a href=""><img src="https://img.badgesize.io/wearebraid/vue-formulate/master/dist/formulate.esm.js.svg?compression=gzip&label=gzip"></a>
</p>

<p align="center">
  <a href="https://vueformulate.com">Documentation Website</a>
</p>

### What is Vue Formulate?

Vue Formulate is the easiest way to build forms using Vue. Key features include
form and field validation, file uploads, form generation, single-element inputs that support labels, help text, error messages, placeholders and more, and [comprehensive documentation](https://vueformulate.com) for use within your own projects.

### Vue Formulate lets you:
✓ Create any input element with a single component<br>
✓ Use `v-model` [binding](https://vueformulate.com/guide/#model-binding) on fields and entire forms<br>
✓ [Re-populate an entire form](https://vueformulate.com/guide/forms/#setting-initial-values) from a single object<br>
✓ [Generate a form](https://vueformulate.com/guide/forms/#generating-forms) using json<br>
✓ Easily add field labels<br>
✓ Easily add help text<br>
✓ Easily add [form validation](https://vueformulate.com/guide/validation)<br>
✓ Easily add [custom validation](https://vueformulate.com/guide/validation/#custom-validation-rules) rules<br>
✓ Easily create custom [validation messages](https://vueformulate.com/guide/validation/#customize-validation-messages)<br>
✓ Easily create [custom inputs](https://vueformulate.com/guide/custom-inputs)

There's a lot more available to read at the comprehensive [documentation website](https://vueformulate.com).

v-model an entire form    |  Well-considered file uploads
:-------------------------:|:------------------------------:
![v-model an entire form](https://assets.wearebraid.com/vue-formulate/formulate-form.gif) | ![well-considered file uploads](https://assets.wearebraid.com/vue-formulate/formulate-uploads.gif)

### How is Vue Formulate used?

The syntax is what developers would expect. To create an input you use the `FormulateInput` element and provide it with a few props:

```vue
<FormulateInput
  v-model="value"
  type="email"
  name="email"
  label="What is your email address"
  help="Where should we contact you?"
  validation="required|email"
/>
```

Collecting multiple `FormulateInput` elements within a single `FormulateForm` element (even deeply nested) allows you to `v-model` your entire form.

### Comprehensive Documentation

There's a lot more available to read at the comprehensive [documentation website](https://vueformulate.com).

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/wearebraid/vue-formulate/graphs/contributors"><img src="https://opencollective.com/vue-formulate/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/vue-formulate/contribute)]

#### Individuals

<a href="https://opencollective.com/vue-formulate"><img src="https://opencollective.com/vue-formulate/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/vue-formulate/contribute)]

<a href="https://opencollective.com/vue-formulate/organization/0/website"><img src="https://opencollective.com/vue-formulate/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/1/website"><img src="https://opencollective.com/vue-formulate/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/2/website"><img src="https://opencollective.com/vue-formulate/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/3/website"><img src="https://opencollective.com/vue-formulate/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/4/website"><img src="https://opencollective.com/vue-formulate/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/5/website"><img src="https://opencollective.com/vue-formulate/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/6/website"><img src="https://opencollective.com/vue-formulate/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/7/website"><img src="https://opencollective.com/vue-formulate/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/8/website"><img src="https://opencollective.com/vue-formulate/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/vue-formulate/organization/9/website"><img src="https://opencollective.com/vue-formulate/organization/9/avatar.svg"></a>
