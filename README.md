# Zillow iFrame Integration

## 📖 Introduction

Integrating real estate search functionalities often involves complex APIs or geographic limitations. Zillow, one of the most popular platforms, imposes strict CAPTCHA measures, making it challenging to work with its API. This project provides a simple solution: embedding Zillow search results in an iframe. Users can enter an address, and Zillow's search results dynamically load without the need for API integration.

![Greenshot 2024-12-11 22 06 19](https://github.com/user-attachments/assets/dc819519-4b07-403a-aa0a-03bceede11ef)
![Greenshot 2024-12-11 22 19 54](https://github.com/user-attachments/assets/33e9a204-63ce-4bc7-a3d4-413271a5e654)
![Greenshot 2024-12-11 22 06 56](https://github.com/user-attachments/assets/8d418925-d423-4af8-9867-696f6138cc6a)

---

## ✨ Features

- **Dynamic Address Input**: Users can enter an address to search directly on Zillow.
- **Submit Button**: Loads Zillow search results dynamically into an iframe.
- **Material-UI Styled Close Button**: A polished "X" button to close and clear the iframe.

---

## ⚙️ How It Works

### 🏗️ Structure
1. **Input Field**: Collects the address to be searched.
2. **Submit Button**: Triggers the iframe to load Zillow results for the given address.
3. **iFrame**: Displays the Zillow search page dynamically.
4. **Close Button**: A Material-UI styled button that clears the iframe and hides it.

### 🔄 Workflow
1. **User Input**: The user enters an address in the input field.
2. **Search Trigger**: Clicking "Submit" encodes the address into a Zillow-compatible URL and loads it into the iframe.
3. **Result Display**: The iframe appears with Zillow's search results.
4. **Close Interaction**: Clicking the "X" button hides the iframe and resets its content.

---

## 🚀 Running the Project

1. **Save the Files**: Save the project as `index.html`.
2. **Start a Local Server**: Run the following command in your terminal:
   ```bash
   python -m http.server 8000
   ```
3. **Open in Browser: Go to http://localhost:8000.
4. **Test the App:
	•	Enter an address and click “Submit.”
	•	Zillow search results will load in the iframe.
	•	Use the “X” button to close the iframe.

## Why It Works
	•	No APIs: Embedding Zillow directly avoids API restrictions and complications.
	•	Dynamic and Lightweight: URL generation and iframe embedding are efficient and straightforward.
	•	Polished UI: Material-UI styling ensures a clean, professional look.

## Limitations
	•	Cross-Origin Restrictions: Some iframe interactions may be limited by browser security policies.
	•	Zillow CAPTCHA: Repeated or unusual activity could trigger CAPTCHA.

## Conclusion

This project provides a quick, effective way to integrate Zillow search functionality without the need for API access. It’s simple, efficient, and easy to customize for different use cases.
