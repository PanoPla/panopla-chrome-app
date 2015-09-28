<img src="assets/banner.png" alt="banner" />

# PanoPla

PanoPla is a CMS for creating and sharing virtual reality and virtual tour content. This plugin is an application for the Chrome browser and Chromebooks to help PanoPla users work and play. 

## Usage

Install the plugin using the plugin manager or download from the Chrome Web Store, click the icon and enjoy PanoPla.


## Editing

You can easily edit this project for your own website by chaning the icon.png and altering the manifest file to reflect your application.

```json
{
    "name": "PanoPla",
    "description": "PanoPla is an easy way to build and share virtual tours, google cardboard content, and spherical panos. Explore and create, share, and play.",
    "app": {
        "urls": ["http://www.panopla.com/"],
        "launch": {
            "web_url": "http://www.panopla.com/"
        }
    },
    "manifest_version": 2,
    "update_url": "http://clients2.google.com/service/update2/crx",
    "version": "0.1",
    "icons": {
        "128": "icon.png"
    }
}

```

Change `name` and `description` to reflect your application. Replace `urls` and `web_url` to point to your website or application.

## License 

```
The MIT License (MIT)

Copyright (c) 2015 PanoPla

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
