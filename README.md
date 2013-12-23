TiNavItems
==========

Multiple `rightNavItems` for your windows! (iOS only)

Usage
-----

```js
var button1 = Ti.UI.createButton({
	title: 'Flic'
});

var button2 = Ti.UI.createButton({
	title: 'Floc'
});

var window = Ti.UI.createWindow({
	rightNavItems: [ button1, button2 ]
});
```

Caveats
-------

Currently only `rightNavItems` on `Ti.UI.Window`s is supported.

Credits
-------

Humbly made the spry ladies and gents at SMC.

License
-------

This library, *TiNavItems*, is free software ("Licensed Software"); you can
redistribute it and/or modify it under the terms of the [GNU Lesser General
Public License](http://www.gnu.org/licenses/lgpl-2.1.html) as published by the
Free Software Foundation; either version 2.1 of the License, or (at your
option) any later version.

This library is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; including but not limited to, the implied warranty of MERCHANTABILITY,
NONINFRINGEMENT, or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General
Public License for more details.

You should have received a copy of the [GNU Lesser General Public
License](http://www.gnu.org/licenses/lgpl-2.1.html) along with this library; if
not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth
Floor, Boston, MA 02110-1301 USA