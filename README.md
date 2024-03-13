
# jsTab

## Description

This project is a simple tab component implemented in JavaScript. It allows users to switch between different tabs to view content.

## Features

- Tab switching functionality.
- Customizable tab styles.
- Easy to integrate into existing projects.

## Installation

To use the jsTab component in your project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/prasiddha007/jsTab.git
   ```
2. Include the necessary files in your project:

   - `jsTab.js`
   - `styles.css`

3. Add the HTML structure for the tabs in your project:

   ```html
   <div class="tabs">
     <div class="tab">
       <button class="tablinks" onclick="openTab(event, 'Tab1')">Tab 1</button>
     </div>
     <div class="tab">
       <button class="tablinks" onclick="openTab(event, 'Tab2')">Tab 2</button>
     </div>
   </div>

   <div id="Tab1" class="tabcontent">
     <h3>Tab 1 Content</h3>
     <p>This is the content of tab 1.</p>
   </div>

   <div id="Tab2" class="tabcontent">
     <h3>Tab 2 Content</h3>
     <p>This is the content of tab 2.</p>
   </div>
   ```

4. Initialize the jsTab component in your JavaScript file:

   ```javascript
   const tabComponent = new TabComponent('.tabs');
   tabComponent.init();
   ```

## Usage

To use the jsTab component, follow these steps:

1. Include the necessary files in your project.
2. Add the HTML structure for the tabs.
3. Initialize the jsTab component in your JavaScript file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
