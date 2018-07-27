# glitch.css
glitch.css makes nice cyperpunky glitch effects.

## How To Use
Include the glitch libary inside the `<head>` tag.
```
<head>
  <link rel="stylesheet" href="css/glitch.min.css">
</head>
```
Add the `glitch` and the desired glitch effect class to a `<div>`. Add as many `<h1>` children needed by the specefic glitch effect, (or add 3 `<h1>` children, that will work for every effect.)
```
<div class="glitch hack1">
  <h1>GLITCHED TEXT</h1>
  <h1>GLITCHED TEXT</h1>
  <h1>GLITCHED TEXT</h1>
</div>
```
Replace `hack1` with desired glitch effect class. All available glitch classes can be previewed on [link here].

### Change Color
To change colors the first `<h1>` tag needs to be selected.
```
#someGlitchDiv h1:first-child {
  color: blue;
}
```
Change the color as desired after `color: `. Replace `#someGlitchDiv` with desired glitch div container.

### Change Font, Font Size, Text Alignment
To change properties `<h1>` tags needs to be selected.
```
#someGlitchDiv h1 {
  font-size: 70px;
  text-align: left;
  font-family: "Courier New";
}
```
Change or remove these values as desired. Replace `#someGlitchDiv` with desired glitch div container.

## Glitch Effects
| Class name | Required `<h1>` children |
| --- | --- |
| `hack1` | 3 |

## Contributing
I :heart: pull requests and issues!
