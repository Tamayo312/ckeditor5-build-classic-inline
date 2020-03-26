CKEditor 5 classic and inline editor build
========================================

Based on the [Using different editors](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/advanced-setup.html#scenario-3-using-two-different-editors) guide from [CKEditor 5](https://ckeditor.com/docs/ckeditor5/latest/index.html)

Includes [Mention Plugin](https://ckeditor.com/docs/ckeditor5/latest/features/mentions.html)
## Documentation

See:

* [Installation](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/installation.html) for how to install this package and what it contains.
* [Basic API](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/basic-api.html) for how to create an editor and interact with it.
* [Configuration](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/configuration.html) for how to configure the editor.
* [Creating custom builds](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/development/custom-builds.html) for how to customize the build (configure and rebuild the editor bundle).

## Usage

1. Run `npm install`
2. Run `npm run build`
3. Copy the contents of *build* in your project's public *js* folder
4. To use editors in your project add ```<script src="[ckeditor-build-path]/ckeditor.js"></script>``` to your app's head.

