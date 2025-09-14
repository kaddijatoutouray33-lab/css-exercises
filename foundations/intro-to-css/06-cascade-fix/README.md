# 06-cascade-fix

This exercise focuses on understanding how the CSS cascade works — specifically how styles are applied when multiple rules target the same element.

## Objective

Fix the styling so that the correct rules apply based on:
- Selector specificity
- Rule order
- Avoiding `!important` unless absolutely necessary

## Instructions

You are given two `<p>` elements:
- One with the class `text`
- One with both `id="special"` and class `text`

Your task is to:
- Style the `.text` paragraph with one rule
- Style the `#special.text` paragraph with a more specific rule
- Ensure the second paragraph overrides the first rule without using `!important`

## Desired Outcome

- The first paragraph should have blue text and a font size of 16px
- The second paragraph should have red text and a font size of 20px

## Self Check

- [x] Did you fix the cascade using selector specificity or order?
- [x] Does the `#special.text` paragraph override the `.text` styles?
- [x] Did you avoid using `!important` unless absolutely necessary?