# Buzzword Bingo in Elm

## Project Structure

All of the Elm code lives in `Bingo.elm` and `BingoUtils.elm`.

This project is designed for version 0.16 of the Elm Platform and relies on the [elm-html](http://package.elm-lang.org/packages/evancz/elm-html/4.0.2/) and [start-app](http://package.elm-lang.org/packages/evancz/start-app/2.0.2/) packages.

The `index.html` file embeds the program as a fullscreen app and includes
the necessary JavaScript (`bingo.js`) and CSS stylesheet (`style.css`).

## Build Instructions

Run the following command from the root of this project:

```
elm make Bingo.elm --output bingo.js
```

Then open `index.html` in your browser!

## Copyright

This software is Copyright (c) 2015 The Pragmatic Studio
(pragmaticstudio.com), unless otherwise marked. Software from
other projects are subject to the license(s) appropriate to those
projects. You are responsible for complying with licenses for
software you use.

## Warranty

This Software is provided for educational purposes only, and comes
with absolutely no warranty. We make no guarantees that this code
is fit for any purpose.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
