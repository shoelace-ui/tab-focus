
# tab-focus

  Webkit-style focus

## Usage

```stylus
@require 'tab-focus'

.btn
  tab-focus()
```

  yields:

```css
.btn:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
```

## Installation

```bash
$ npm install shoelace-ui/tab-focus
```

## License

  MIT
