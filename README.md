
# `custom-button` Web Component Documentation
[html file](index.html)
## Description

The `custom-button` component is a customizable button element. It allows for dynamic styling and content adjustments based on user interaction. It is designed following the Web Components standard.

## Usage

The `custom-button` component can be used in HTML as follows:

```html
<custom-button
    type="url"
    href="http://example.com"
    icon="🌟"
    position="left"
    style-config="background-color: red; color: white; padding: 1rem 2rem; border-radius: 100px;"
    class="example-class">
    Click me
</custom-button>
```

## Attributes

- **`type`**: Specifies the type of the button.
  - **Values**: `url`, `submit`
  - **Default**: `submit`
  - **Description**: Determines whether the button acts as a link (`url`) or a form submit button (`submit`).

- **`href`**: Applicable when `type="url"`, specifies the URL the button will link to.
  - **Default**: `#`
  - **Description**: When `type` is set to `url`, it makes the button behave as a clickable link.

- **`icon`**: Defines the icon to be displayed inside the button.
  - **Default**: None
  - **Description**: The Unicode character or emoji to be used as the button's icon.

- **`position`**: Specifies the position of the icon within the button.
  - **Values**: `left`, `right`
  - **Default**: `left`
  - **Description**: Determines whether the icon appears to the left or right of the button's text.

- **`style-config`**: Contains custom styles to be applied to the button.
  - **Default**: None
  - **Description**: A string of CSS styles that are applied to the inner element of the button. This allows for flexible styling of the button.

## Example

Here is an example of a `custom-button` with various attributes:

```html
<custom-button
    type="url"
    href="http://example.com"
    icon="🌟"
    position="left"
    style-config="background-color: red; color: white; padding: 1rem 2rem; border-radius: 100px;"
    class="example-class">
    Click me
</custom-button>
```
