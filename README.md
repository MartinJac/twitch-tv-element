# &lt;twitch-tv&gt;

Web Component wrapper for [Twitch.tv player](http://www.twitch.tv/) using Polymer.

> Maintained by [Rodrigo Silva de Melo](https://github.com/rsmelo).

## Demo

> [Check it live](http://rsmelo.github.io/twitch-tv-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="http://cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/twitch-tv.html">
	```

3. Start using it!

	```html
	<twitch-tv></twitch-tv>
	```

## Options

Attribute  | Options                   | Default          | Description
---        | ---                       | ---              | ---
`channel`         | *string*           | `joindotared`    | your channel in twitch.tv
`allowFullScreen` | *boolean*   	   | true             | fullscreen enable/disable
`height`          | *int*              | 378              | height of the video
`width`           | *int*              | 620              | width of the video
`autoPlay`        | *boolean*          | true             | auto play enable/disable
`startVolume`     | *int*              | 25               | initial volume
`type`            | `live`, `archive`  | `live`           | `live` for live stream, `archive` for channel recorded videos
`archiveId`       | *int*              | undefined        | recorded video id, only used to `archive` type, archiveId composes video url (e.g., http://www.twitch.tv/channel/b/999999)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History
* v0.2.0 August 28, 2013
	* Added Support for recorded videos
* v0.1.1 August 28, 2013
	* Changed "a" element style
	* Using Polymer cdn
* v0.1.0 August 27, 2013
	* First version of twitch-tv element
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)