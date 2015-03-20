# polymer-tile

A tile component using [Polymer](http://www.polymer-project.org/).

## Demo

[Check it live!](http://teaegg.github.io/polymer-tile)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install git://github.com/teaegg/polymer-tile.git --save
```

Or [download as ZIP](https://github.com/teaegg/polymer-tile/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/polymer-tile/polymer-tile.html">
    ```

3. Start using it!

    ```html
    <polymer-tile fit>
      <tile>
        <tile style="background: yellow;"></tile>
        <tile style="background: red;"></tile>
      </tile>
      <tile style="background: orange;"></tile>
      <tile double style="background: purple;"></tile>
      <tile style="background: orange;"></tile>
    </polymer-tile>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`tileSize` | *string*                  | `120px`             | Default size of a "&lt;tile&gt;&lt;/tile&gt;"
`gutter`   | *string*                  | `4px`               | The `gutter` attribute sets the margin between each tile
`orient`   | *string*                  | `h`                 | Orientation of the scroller to be observed (`v` for vertical, `h` for horizontal)
`tiles`    | *array*                   | `null`              | `tiles` is a property that contains all tile nodes

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](https://github.com/teaegg/polymer-tile/blob/master/LICENSE)
