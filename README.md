# extend-vue-scrollactive

This components is extended from vue-scrollactive, the usage and introduction can be read at [vue-scrollactive](https://github.com/eddiemf/vue-scrollactive).

Based on vue-scrollactive, I make it can be used when the scrollbar isn't belong to window, and the wrap-element can be any element you wanted.The new config value is :

```js

/**
 * The wrap-element which the scrollbar is belong to.
 *
 * @default undefined
 * @type {String}
 */
wrapEle: {
  type: String,
  default: undefined
}

```

## Attention

I just modify the 'src/scrollactive' file, haven't package it now. So, you'd best refer it rather than install it.

