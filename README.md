# AI Image Generator

A simple web application that uses an image-generation API to turn your text prompts into stunning visuals.

## 🚀 How to Run

1. Clone this repository.
2. Create a `config.js` file in the root directory of your project.

### 🔐 Setup Your API Key

To keep your API key private and out of GitHub, do not hardcode it in `script.js`.  
Instead, create a file called `config.js` and add the following:

```js
// config.js
const CONFIG = {
  API_KEY: 'your-api-key-here'
};
