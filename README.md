# Loki The Painter 🎨

A simple in-browser text editor where you can type freely and restyle your text live: change the background color, text color, and font family with one click.

Built with plain **HTML, CSS and JavaScript** (no frameworks).

## Features

- Editable text box ("Type your text here...")
- Background color picker (circle buttons)
- Text color picker (circle buttons)
- Font family switcher: Cursive, Monospace, Serif, Fantasy (each button previews its own font)

## Tech Used

| Part | Technology |
|------|------------|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox, hover effects, text-shadow) |
| Logic | JavaScript (DOM manipulation with `onclick` handlers) |

## How It Works

Each button calls a small JavaScript function that updates the style of the text box:

```js
function BgColor(color){
    document.getElementById("box").style.backgroundColor = color
}
function textColor(color){
    document.getElementById("box").style.color = color
}
function changeFontFamily(font){
    document.getElementById("box").style.fontFamily = font
}
```

## Planned Improvements

- [ ] Working **Download** button to save the text as a `.txt` file
- [ ] Font size and bold/italic controls
- [ ] Generate color buttons from a JavaScript array
- [ ] Save text with `localStorage` so it survives a refresh

## Author

**Ravdeep** — B.Tech CSE student, GLA University, Mathura
GitHub: [@ravdeep1211](https://github.com/ravdeep1211)
