# &lt;github-repos&gt;

Web Component to list a github user's repos list using Polymer.


## Usage

1. Install [polymer elements](http://www.polymer-project.org/docs/elements/polymer-elements.html) using [bower](http://bower.io/):

    ```shell
    bower install Polymer/polymer-elements
	bower install Polymer/platform
	bower install Polymer/polymer-jsonp
    ```

2. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

3. Import Custom Element:

    ```html
    <link rel="import" href="src/github-repos.html">
    ```

4. Start using it!

    ```html
    <github-repos username="{GITHUB USER NAME}"></github-repos>
    ```

## Options

Attribute  |Options   | Default | Description
---        | ---      | ---     | ---
`username` | None     | None    | GitHub username


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## License

[MIT License](http://opensource.org/licenses/MIT)
