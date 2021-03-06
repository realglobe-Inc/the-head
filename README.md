the-head
==========

<!---
This file is generated by ape-tmpl. Do not update manually.
--->

<!-- Badge Start -->
<a name="badges"></a>

[![Build Status][bd_travis_shield_url]][bd_travis_url]
[![npm Version][bd_npm_shield_url]][bd_npm_url]
[![JS Standard][bd_standard_shield_url]][bd_standard_url]

[bd_repo_url]: https://github.com/the-labo/the-head
[bd_travis_url]: http://travis-ci.org/the-labo/the-head
[bd_travis_shield_url]: http://img.shields.io/travis/the-labo/the-head.svg?style=flat
[bd_travis_com_url]: http://travis-ci.com/the-labo/the-head
[bd_travis_com_shield_url]: https://api.travis-ci.com/the-labo/the-head.svg?token=
[bd_license_url]: https://github.com/the-labo/the-head/blob/master/LICENSE
[bd_codeclimate_url]: http://codeclimate.com/github/the-labo/the-head
[bd_codeclimate_shield_url]: http://img.shields.io/codeclimate/github/the-labo/the-head.svg?style=flat
[bd_codeclimate_coverage_shield_url]: http://img.shields.io/codeclimate/coverage/github/the-labo/the-head.svg?style=flat
[bd_gemnasium_url]: https://gemnasium.com/the-labo/the-head
[bd_gemnasium_shield_url]: https://gemnasium.com/the-labo/the-head.svg
[bd_npm_url]: http://www.npmjs.org/package/the-head
[bd_npm_shield_url]: http://img.shields.io/npm/v/the-head.svg?style=flat
[bd_standard_url]: http://standardjs.com/
[bd_standard_shield_url]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg

<!-- Badge End -->


<!-- Description Start -->
<a name="description"></a>

Head of the-components

<!-- Description End -->


<!-- Overview Start -->
<a name="overview"></a>



<!-- Overview End -->


<!-- Sections Start -->
<a name="sections"></a>

<!-- Section from "docs/guides/01.Installation.md.hbs" Start -->

<a name="section-docs-guides-01-installation-md"></a>

Installation
-----

```bash
$ npm install the-head --save
```


<!-- Section from "docs/guides/01.Installation.md.hbs" End -->

<!-- Section from "docs/guides/02.Usage.md.hbs" Start -->

<a name="section-docs-guides-02-usage-md"></a>

Usage
---------

```javascript
'use strict'

import React from 'react'
import TheHtml from 'the-html'
import TheHead from 'the-head'

class ExampleComponent extends React.PureComponent {
  render () {
    return (
      <TheHtml>
        <TheHead id='my-component'
        />
      </TheHtml>
    )
  }
}

export default ExampleComponent

```


<!-- Section from "docs/guides/02.Usage.md.hbs" End -->

<!-- Section from "docs/guides/03.Components.md.hbs" Start -->

<a name="section-docs-guides-03-components-md"></a>

Components
-----------

### TheHead

Head of the-components

**Props**

| Name | Type | Description | Default |
| --- | --- | ---- | ---- |
| `base` | string  | Base url | `null` |
| `baseTarget` | string  | Target of base url. '_blank', '_parent', '_self', '_top' or frame name | `undefined` |
| `cdn` | string  | CDN URL | `null` |
| `charSet` | string  | Char set | `'utf-8'` |
| `className` | string  |  | `null` |
| `color` | string  | Theme color | `null` |
| `fallbackUnless` | string  | Global property for fall back | `null` |
| `globals` | object  | Global variables | `{}` |
| `icon` | string  | Favicon url | `null` |
| `id` | string  | DOM Id | `null` |
| `itemProps` | object  | Item props | `{}` |
| `manifest` | string  | Path of manifest.json | `null` |
| `metaContents` | object  | Met contents | `{}` |
| `metaProperties` | object  | Met properties | `{}` |
| `title` | string  | Document title | `null` |
| `version` | string  | Version string | `'unknown'` |
| `versionKey` | string  | Key for version query | `'v'` |
| `viewPort` | object  | View port settings | `{initialScale: '1.0', width: 'device-width'}` |


<!-- Section from "docs/guides/03.Components.md.hbs" End -->


<!-- Sections Start -->


<!-- LICENSE Start -->
<a name="license"></a>

License
-------
This software is released under the [MIT License](https://github.com/the-labo/the-head/blob/master/LICENSE).

<!-- LICENSE End -->


<!-- Links Start -->
<a name="links"></a>

Links
------

+ [THE Labo][t_h_e_labo_url]

[t_h_e_labo_url]: https://github.com/the-labo

<!-- Links End -->
