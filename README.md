
- **index.html** — main HTML file  
- **style.css** — CSS styles  
- **script.js** — JavaScript logic for password generation  
- **assets/** — images or icons used in UI (if any)  

## 🧠 How It Works

1. The user sets desired password length and selects which character types (uppercase, lowercase, numbers, symbols) to include.  
2. When the “Generate Password” button is clicked, the JavaScript script picks one character from each selected character set to ensure all types are included.  
3. Then it fills the rest of the password by randomly picking from the combined allowed characters until it reaches the desired length.  
4. The generated password is displayed on the page, with an option to click and copy it to the clipboard.  

## 🛠 Usage

1. Clone or download this repository.  
2. Open `index.html` in your browser.  
3. Select your desired options (length, types).  
4. Click **Generate Password**.  
5. Optionally click to copy the password.  
6. Repeat as needed.

## 📦 How to Run Locally

You don’t need a server — the app is static HTML/JS/CSS:

```bash
git clone https://github.com/mim515/Random-Password-Generator.git
cd Random-Password-Generator
open index.html


