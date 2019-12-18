# CSS Flexbox snippets for Sublime [![Build Status](https://travis-ci.org/brenopolanski/css-flexbox-sublime-snippets.svg?branch=master)](https://travis-ci.org/brenopolanski/css-flexbox-sublime-snippets)

![image snippets](https://raw.githubusercontent.com/brenopolanski/css-flexbox-sublime-snippets/assets/snippets.gif)

## Install

To install through Package Control, search for [**Flexbox Snippets**](https://sublime.wbond.net/packages/Flexbox%20Snippets). If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation). If you insist to not install it, you can download the package and put it manually inside your Pacakages directory. It should work but will not update automatically.

## Snippets

Works for CSS/LESS/Sass/SCSS/Stylus & Vue Component.

## display

**trigger:** flexbox⇥

```
display: ${1:flex|inline-flex};
```

## flex-direction

**trigger:** flexdir⇥

```
flex-direction: ${1:row|row-reverse|column|column-reverse};
```

## flex-wrap

**trigger:** flexwrap⇥

```
flex-wrap: ${1:nowrap|wrap|wrap-reverse};
```

## flex-flow

**trigger:** flexflow⇥

```
flex-flow: ${1:<'flex-direction' (row|row-reverse|column|column-reverse)> || <'flex-wrap' (nowrap|wrap|wrap-reverse)>};
```

## justify-content

**trigger:** flexjust⇥

```
justify-content: ${1:flex-start|flex-end|center|space-between|space-around};
```

## align-items

**trigger:** flexitems⇥

```
align-items: ${1:flex-start|flex-end|center|baseline|stretch};
```

## align-content

**trigger:** flexcont⇥

```
align-content: ${1:flex-start|flex-end|center|space-between|space-around|stretch};
```

## order

**trigger:** flexorder⇥

```
order: ${1:0};
```

## flex-grow

**trigger:** flexgrow⇥

```
flex-grow: ${1:0};
```

## flex-shrink

**trigger:** flexshr⇥

```
flex-shrink: ${1:1};
```

## flex-basis

**trigger:** flexbasis⇥

```
flex-basis: ${1:auto|<'width' (%|rem|em|px)>};
```

## flex

**trigger:** flex⇥

```
flex: ${1:none|auto|[<'flex-grow' (0)> <'flex-shrink' (1)> || <'flex-basis' auto|<'width' (%|rem|em|px)>>]};
```

## align-self

**trigger:** flexself⇥

```
align-self: ${1:auto|flex-start|flex-end|center|baseline|stretch};
```

## Prefixing Flexbox

Flexbox requires some vendor prefixing to support the most browsers possible. It doesn't just include prepending properties with the vendor prefix, but there are actually entirely different property and value names. This is because the Flexbox spec has changed over time, creating an ["old", "tweener", and "new"](http://css-tricks.com/old-flexbox-and-new-flexbox/) versions.

Perhaps the best way to handle this is to write in the new (and final) syntax and run your CSS through [Autoprefixer](https://github.com/postcss/autoprefixer), which handles the fallbacks very well.

## Contributing

If you want to help, please read the [Contributing](https://github.com/brenopolanski/css-flexbox-sublime-snippets/blob/master/CONTRIBUTING.md) guide.

## History

For detailed changelog, see [Releases](https://github.com/brenopolanski/css-flexbox-sublime-snippets/releases).

## References

- [Flexbox in the CSS specifications](http://www.w3.org/TR/css-flexbox/)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## License

[MIT License](https://brenopolanski.mit-license.org/) © Breno Polanski
