# WebPeek Chrome Extension
![Screenshot 2024-02-28 010105](https://github.com/user-attachments/assets/60225475-c66e-4f97-a850-e06ff1704662)

WebPeek is a Chrome extension designed to simplify and enhance your browsing experience by providing tailored summaries of web pages. Using the Cohere Summarisation API, WebPeek generates concise summaries, saving users time and effort. With additional customisation options, WebPeek ensures the summaries meet your specific needs.

---

## Table of Contents

- [Features](#features)
- [Installation Guide](#installation-guide)
- [Setting Up Your Cohere Summarisation API Key](#setting-up-your-cohere-summarisation-api-key)
- [Customisation Options](#customisation-options)
  - [Summary Customisation](#summary-customisation)
  - [Personalisation Settings](#personalisation-settings)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

---

## Features

- **Web Page Summaries**  
  Generate concise summaries of web pages directly in your browser.

- **Open Graph Tag Integration**  
  Preview page summaries by hovering over links before opening them.

- **Customisation Options**  
  Personalise the summary length, format, and display style with over five presets.

- **Multi-Language Support**  
  Choose your preferred language for summaries.

---

## Installation Guide

Follow these steps to install WebPeek locally:

1. **Access Chrome Extensions Dashboard**  
   - Open your browser settings.  
   - Navigate to the extensions section and select "Manage Extensions."

2. **Enable Developer Mode**  
   - Switch on the **Developer Mode** option in the top-right corner of the extensions page.

3. **Load the Extension**  
   - Click on the **Load unpacked** button in the top-left corner.  
   - Select the folder containing the WebPeek extension files, including the `manifest.json` file.  

4. **Complete the Installation**  
   - The extension will now appear in your browser's extensions list, ready to use.

---

## Setting Up Your Cohere Summarisation API Key

To unlock WebPeek's full potential, follow these steps:

1. **Obtain an API Key**  
   - Visit [Cohere Summarise API](https://cohere.com/summarize).  
   - Create an account (if you don’t already have one) and retrieve your API key.

2. **Add Your API Key to WebPeek**  
   - Go to the extensions dashboard and click on **Details** under the WebPeek extension.  
   - Scroll to **Extension Options** and open the settings menu.  
   - Paste your API key in the field labeled **API Key**.  
   - Click **Save** to apply the changes.

---

## Customisation Options

### Summary Customisation

- **Length**  
  Choose the approximate length of the summary or set it to **Auto** for an ideal length.

- **Format**  
  Opt for **Paragraph** or **Bullets** based on your preference.

- **Model**  
  Select from multiple models, balancing speed and quality.

- **Extractiveness**  
  Adjust how closely the summary mirrors the original text.  
  - **High**: Uses sentences directly from the text.  
  - **Low**: Generates more paraphrased content.

- **Temperature**  
  Control the creativity of the summaries.  
  - Range: **0** (predictable) to **5** (creative).  
  - Recommended: **0-1** for best results.

### Personalisation Settings

- **Themes**  
  Select from pre-built themes to customise the summary box's appearance.

- **Language Preferences**  
  Choose your preferred language for summaries to enhance accessibility.

---

## Technologies Used

- **Languages**: JavaScript  
- **API**: Cohere Summarisation API  
- **Browser Integration**: Chrome Extensions  
- **Additional Features**: Open Graph Tag integration for hover-based previews

---
