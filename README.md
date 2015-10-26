# &lt;made-with-love&gt;

## Demo

[Check it live!](http://koddsson.github.io/made-with-love)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install made-with-love --save
```

Or [download as ZIP](https://github.com/koddsson/made-with-love/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/made-with-love/my-element.html">
    ```

3. Start using it!

    ```html
    <my-element></my-element>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/made-with-love/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/koddsson/made-with-love/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
