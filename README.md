# TACHYONS-LETTER-SPACING

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-letter-spacing
```
or download the css on github and include in your project.

## The Code
```

/*

   LETTER SPACING

*/

.tracked       { letter-spacing:  .16em; }
.tracked-tight { letter-spacing: -.1em; }
.mega-tracked  { letter-spacing:  .3em; }

@include break(not-small) {
  .tracked-ns       { letter-spacing:  .16em; }
  .tracked-tight-ns { letter-spacing: -.1em; }
  .mega-tracked-ns  { letter-spacing:  .3em; }
}

@include break(medium) {
  .tracked-m       { letter-spacing:  .16em; }
  .tracked-tight-m { letter-spacing: -.1em; }
  .mega-tracked-m  { letter-spacing:  .3em; }
}

@include break(large) {
  .tracked-l       { letter-spacing:  .16em; }
  .tracked-tight-l { letter-spacing: -.1em; }
  .mega-tracked-l  { letter-spacing:  .3em; }
}
```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

