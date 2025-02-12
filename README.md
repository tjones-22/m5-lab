# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessability
- Color Scheme:
I adjusted the color scheme to a darker green to create a forrest theme. With the darker green on the white I think it will be easy to read. I also used that color for backgrounds in the table body and the comment section background.

- Keyboard only
It wouldn't access all the interactive elements before completing this lab. The show hide button was in a div so tab wouldn't navigate to it. The js provided allowed functionality of the buttons for non accessible users. 

- Label
I used a hide class to hide the label before the search input.

- Ideas
One idea that comes to mind is making the div at the bottom an aside to match html semantics and for screen readers.
Another way it would be more accessible is to ad alt tags to the images for the screen readers and if the link ever breaks.