# Wheel of Names

This is an app inspired by the TV show Wheel of Fortune. In the TV show, contestants try to figure out a short phrase by guessing letters. If they guess correctly, the letter will be revealed. They spin the wheel to determine how much money each correct letter is worth.

Wheel of Names is similar, but allows us to create a virtual wheel, putting our own names on it. We can then virtually spin it to determine a "winner".

<hr />

## Tech stack

- Bun / Vite
- React / Typescript
- SASS / styled-components
- canvas / canvas-confetti

## Application features:

### I. Question

1. This is where users can submit a question or phrase that will determine the focus of the spins.
2. Any changes made in the input field are saved when the user clicks outside of it (on focus out).

### II. Wheel

1. The wheel component spins with an easing animation and determines the winner.
2. The spin direction can be adjusted using the buttons, for either clockwise or counterclockwise rotation.
3. Each adjacent sector is uniquely colored, and their sizes are calculated proportionally to the number of participants.

### III. Add Participants

1. The participant entry area includes an input field for entering a participant's name and an 'ADD' button to add it to the participants list.
2. To add participants more quickly, the user can press the ENTER key on the keyboard.

### IV. Participants List

1. This section displays all the participants' names.
2. The list offers options to sort the names alphabetically or shuffle them randomly, with both actions dynamically updating the wheel component.

### Running the app locally

To run the app, follow these steps.

1. Ensure that [NodeJS](http://nodejs.org/) is installed.
2. Install [bun](https://bun.sh/docs/installation).
3. From the project folder, execute the following commands:

To install dependencies:

```shell
  bun install
```

To run the app:

```shell
  bun run dev
```