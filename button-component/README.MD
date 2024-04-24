# Button Component

[![NPM Version](https://img.shields.io/npm/v/button-component.svg)](https://www.npmjs.com/package/button-component)
[![License](https://img.shields.io/npm/l/button-component.svg)](https://github.com/Dj1236/button-component/blob/main/LICENSE)

A customizable and reusable button component for React applications.

## Installation

You can install the Button Component package via npm or yarn:

```bash
# Using npm
npm install button-component

# Using yarn
yarn add button-component
 
# usage
import React from 'react';
import Button from 'button-component';

const MyComponent = () => {
  return (
    <div>
      <Button onClick={() => console.log('Button clicked')}>
        Click me
      </Button>
    </div>
  );
};

export default MyComponent;

#Props
The Button component accepts the following props:

onClick: Function to be called when the button is clicked.
type: The type of button (e.g., "button", "submit", "reset").
disabled: Boolean indicating whether the button is disabled.
className: Additional CSS class(es) to apply to the button.

# example
<Button onClick={() => console.log('Button clicked')} type="button" disabled={false} className="custom-button">
  Click me
</Button>


#license
This project is licensed under the MIT License - see the LICENSE file for details.
Feel free to customize the README file according to the specific features, usage instructions, and customization options of your button component. Additionally, you can add more sections like "Contributing", "Changelog", or "Credits" as needed.
