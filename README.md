# svelte-3-wc-debug

Reproduction repository of issue with Svelte <-> Custom Elements Events

## svelte3-raw

Example using just Svelte syntax. Inner component dispatch a custom event 'message'. App component listen to it using on:message

It works !

## svelte3-wc

Example using just Svelte syntax and exporting component to Web Components. Inner component dispatch a custom event 'message'. App component listen to it using on:message

Same syntax doesn't work.

Vanilla JS works fine in public/index.html
