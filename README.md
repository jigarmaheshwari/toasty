# Toasty

Alloy Widget for enhanced cross-platform Toast notifications.

![demo](https://raw.github.com/manumaticx/toastyDemo/master/demo.gif)

## Install

### Download

#### as Archive
* [download](https://github.com/manumaticx/toasty/releases) latest version as zip
* unzip under `app/widgets/toasty`
	
#### as Git Submodule

`$ git submodule add https://github.com/manumaticx/toasty.git app/widgets/toasty`

### update config.json

```javascript
"dependencies": {
    "toasty":"1.3"
}
```

## Features
* different types (backgroundColor): default, confirm, alert, info
* multiple animations: fade, slide from top, slide from left, zoom in/out
* queues up messages
* very customizable: dimension, position, custom content view, etc.

## Usage

Create an instance of the widget ( global reference is recommeded: `Alloy.Globals.toasty` )
```javascript
var toasty = Alloy.createWidget("toasty");
```

Show a simple toast message
```javascript
toasty.show("Hello World");
```

## More
* [Documentation](https://github.com/manumaticx/toasty/wiki)
* [Demo](https://github.com/manumaticx/toastyDemo)
* [Changelog](https://github.com/manumaticx/toasty/wiki/Changelog)

## License

<pre>
Copyright 2013 Manuel Lehner

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
