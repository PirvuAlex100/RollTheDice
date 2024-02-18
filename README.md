---

## Web-Dice Framework Documentation

### Overview

Web-Dice is a lightweight JavaScript framework that allows you to easily integrate a dice animation onto your web page. This framework provides functionality for displaying a dice, rolling it with animation, and executing custom actions based on the rolled number.

### Installation

To install Web-Dice, use npm:

```bash
npm install web-dice
```

### Usage

To use Web-Dice in your project, simply call the `createDice` function with optional parameters to customize the dice appearance and behavior. Here's an example:

```javascript
createDice({
  position: { x: 40, y: 30 },
  onRoll: function(num) {
    console.log("The dice rolled:", num);
  },
  color: { background: '#ffffff', border: '#000000', dots: '#000000' },
  speed: 10
});
```

### Parameters

- `position`: Object specifying the position of the dice on the page (default: `{ x: 40, y: 30 }`).
- `onRoll`: Function to be executed after the dice is rolled. It receives the rolled number as a parameter (default: no function).
- `color`: Object specifying the color scheme of the dice (default: `{ background: '#ffffff', border: '#000000', dots: '#000000' }`).
- `speed`: Animation speed of the dice roll, in seconds (default: `10`).

### Compatibility

Web-Dice is compatible with most modern web browsers and can be integrated into various libraries and frameworks.

### Support

For support or to report issues, please visit [Web-Dice GitHub Issues](https://github.com/PirvuAlex100/Web-Dice/issues).

### License

Web-Dice is released under the [MIT License](https://opensource.org/license/mit/).

### Feedback and Contributions

I welcome feedback and suggestions from the community. Feel free to open issues or submit pull requests on GitHub.

---
