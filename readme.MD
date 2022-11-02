# PLEASE NOTE THAT THIS PROJECT WAS DONE WITH 1280 SET AS THE WIDTH

# Learning Outcomes

- Learned to understand when and how to differentiate the usage of padding vs margin.
  - Margin between elements.
  - Padding between sections.
- Flexbox will only work on direct parent to child relationships

## vertical-align

- used vertical-align on header image to align inline and inline-block text in navigation to the bottom of the bean image.

## ::selection

- used a pseudocode to change the selection colour and the text font colour to match the design of style guide.

```
::selection {
    background-color: #5bacc3;
    color: #fff;
}
```

## :is()

- selectors that are in the () will account for the highest specificity and apply it to all the selectors.
- if one of the selectors are invalid, it will be ignored while the other selectors will still have the style applied for the other selectors in the ().
- Will help make lists easier to read
  - can nest different level selectors

## scroll-behavior

- Used scroll-behavior to have a smooth scrolling experience when user clicks on sub nav in the menu page.

---

# Coffee Shop - Sprint Two

- Added `<address>` schematic tag to the address company-info portion in footer
- Refactored code to use Flexbox for all elements that were previously using

```
div {
    display: inline;
}

div {
    display: inline-block;
}
```

Refactored to:

```
div {
    display: flex;
}
```

- properties were different based on the need of the design and mock up delivered to us.
- Refactored all code with recommendations given on Feedback.

## :not()

- Pseudo class that chooses every element that is not targeting the one in brackets. Used to target all elements in the .discount\_\_content container since alignment was off with the image.
