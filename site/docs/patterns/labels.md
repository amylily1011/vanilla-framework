---
wrapper_template: '_layouts/default.html'
context:
  title: Labels | Components
---

## Labels

<hr>

Labels are static elements which you can apply to signify status, tags or any other information you find useful.

<div class="p-notification--information">
  <p class="p-notification__response">
    <span class="p-notification__status">Note:</span>These labels are used to inform <a href="/docs/component-status" class="p-notification__action">status</a> of components in Vanilla.
  </p>
</div>

### New

Label to be used on newly released components, utilities or settings that are safe to use in projects.

<a href="/docs/examples/patterns/labels/new/" class="js-example">
View example of the new label pattern
</a>

### Deprecated

Label to be used on components, utilities or settings are in the process of being removed and should no longer be used in projects.

<a href="/docs/examples/patterns/labels/deprecated/" class="js-example">
View example of the deprecated label pattern
</a>

### In progress

Label to be used when a design spec and code implementation are not yet finished.

<a href="/docs/examples/patterns/labels/in-progress/" class="js-example">
View example of the in progress label pattern
</a>

### Updated

Label to be used on existing components, utilities or settings that have been updated either through design or code.

<a href="/docs/examples/patterns/labels/updated/" class="js-example">
View example of the updated label pattern
</a>

### Validated

Label to be used on a proposal approved in our bi-weekly meeting. A design spec is created and development starts ready for code review.

<a href="/docs/examples/patterns/labels/validated/" class="js-example">
View example of the validated label pattern
</a>

### Import

To import just this component into your project, copy the snippet below and include it in your main Sass file.

```scss
@import 'patterns_label';
@include vf-p-label;
```

For more information see [Customising Vanilla](/docs/customising-vanilla/) in your projects, which includes overrides and importing instructions.

### Design

For more information view the [labels design spec](https://github.com/ubuntudesign/vanilla-design/tree/master/Labels) which includes the specification in markdown format and a PNG image.