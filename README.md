# [Slyer](http://darsa.in/sly)

JavaScript library for one-directional scrolling with item based navigation support.
This is a fork, which tries to implement original Sly from darsain with es6.

install with jspm:
```
jspm i github:capaj/slyer
```

or with npm:
```
npm i slyer
```

Sly supports navigation with:

- mouse wheel scrolling
- scrollbar (dragging the handle or clicking on scrollbar)
- pages bar
- various navigation buttons
- content dragging with mouse or touch
- automated cycling by items or pages
- lots of super useful methods

... and has a powerful & developer friendly API!

That's all build around a custom [highly optimized animation rendering](http://i.imgur.com/nszjJBZ.png) with
requestAnimationFrame, and GPU accelerated positioning with fallbacks for browsers that don't support it.

#### Compatibility

Works everywhere where jQuery 2.2 runs.

## Usage

Constructor:

```js
var options = {
	horizontal: 1,
	itemNav: 'basic',
	speed: 300,
	mouseDragging: 1,
	touchDragging: 1
}
var frame = new Sly('#frame', options).init()
```

## Documentation

Can be found in the [docs](https://github.com/darsain/sly/tree/master/docs) directory.

## Contributing

Please, read the [Contributing Guidelines](CONTRIBUTING.md) for this project.

## License

MIT
