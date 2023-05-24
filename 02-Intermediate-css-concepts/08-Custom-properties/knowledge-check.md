# [Custom Properties Knowledge Check](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-custom-properties#knowledge-check)

## How would you declare a custom property with a name of text-color?
`--text-color: blue;`

## How would you access a custom property with a name of background-color?

```
div {
   backround-color: var(--background-color)
}
```
## Where would you declare a custom property to have its scope be global and accessible by all other selectors?
root:

## Where would you declare a custom property so that a user’s theme setting from their OS or browser was taken into account?
```
@media (prefer-color-scheme: dark) {}
```