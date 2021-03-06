# Silverstripe Sitemap(2)

Better, simpler sitemap module for SilverStripe

This module creates a simple sitemap page which lists the entire site tree.

By default all searchable pages are visible on the page, but can be opted out by selecting
"Hide on Sitemap" under page Settings.

Visibility of pages can optionally be customised by code.

## Credits and Authors

 * Damian Mooyman - <https://github.com/tractorcow/silverstripe-sitemap2>

## Requirements

 * SilverStripe 3.1

## Installation Instructions

 * Either extract the module into the `sitemap2` folder, or install using composer

```bash
composer require "tractorcow/silverstripe-sitemap2" "3.1.*@dev"
```

 * Do a dev/build to generate the required tables
 * Create a page of type "SitemapPage" in your sitetree

## License

Revised BSD License

Copyright (c) 2013, Damian Mooyman
All rights reserved.

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * The name of Damian Mooyman may not be used to endorse or promote products
   derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
