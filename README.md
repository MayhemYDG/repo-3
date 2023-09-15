# `<youtube-video>`

[![Version](https://img.shields.io/npm/v/youtube-video-element?style=flat-square)](https://www.npmjs.com/package/youtube-video-element) 
[![Badge size](https://img.badgesize.io/https://cdn.jsdelivr.net/npm/youtube-video-element/+esm?compression=gzip&label=gzip&style=flat-square)](https://cdn.jsdelivr.net/npm/youtube-video-element/+esm)

A [custom element](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
for the YouTube player with an API that matches the 
[`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) API.

- 🏄‍♂️ Compatible [`HTMLMediaElement`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement) API
- 🕺 Seamlessly integrates with [Media Chrome](https://github.com/muxinc/media-chrome)

## Example

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/youtube-video-element@1"></script>
<youtube-video controls src="https://www.youtube.com/watch?v=rubNgGj3pYo"></youtube-video>
```

## Installing

`<youtube-video>` is packaged as a javascript module (es6) only, which is supported by all evergreen browsers and Node v12+.

### Loading into your HTML using `<script>`

Note the `type="module"`, that's important.

> Modules are always loaded asynchronously by the browser, so it's ok to load them in the head :thumbsup:, and best for registering web components quickly.

```html
<head>
  <script type="module" src="https://cdn.jsdelivr.net/npm/youtube-video-element@1"></script>
</head>
```

### Adding to your app via `npm`

```bash
npm install youtube-video-element --save
```
Or yarn
```bash
yarn add youtube-video-element
```

Include in your app javascript (e.g. src/App.js)
```js
import 'youtube-video-element';
```
This will register the custom elements with the browser so they can be used as HTML.


## Related

- [Media Chrome](https://github.com/muxinc/media-chrome) Your media player's dancing suit. 🕺
- [`<mux-video>`](https://github.com/muxinc/elements/tree/main/packages/mux-video) A Mux-flavored HTML5 video element w/ hls.js and Mux data builtin.
- [`<mux-player>`](https://github.com/muxinc/elements/tree/main/packages/mux-player) The official Mux-flavored video player web component.
- [`<vimeo-video>`](https://github.com/luwes/vimeo-video-element) A web component for the Vimeo player.
- [`<videojs-video>`](https://github.com/luwes/videojs-video-element) A web component for Video.js.
- [`<wistia-video>`](https://github.com/luwes/wistia-video-element) A web component for the Wistia player.
- [`<jwplayer-video>`](https://github.com/luwes/jwplayer-video-element) A web component for the JW player.
- [`<hls-video>`](https://github.com/muxinc/hls-video-element) A web component for playing HTTP Live Streaming (HLS) videos.
- [`castable-video`](https://github.com/muxinc/castable-video) Cast your video element to the big screen with ease!
