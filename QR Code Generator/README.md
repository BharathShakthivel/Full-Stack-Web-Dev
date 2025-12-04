# QR Code Generator (Node.js)

A simple command-line QR Code Generator built with **Node.js**.
It allows you to enter any URL using the `inquirer` prompt, generates a QR code image using the `qr-image` package, and stores the original URL inside a text file using Node's native `fs` module.

---

## 🚀 Features

* Prompts the user for any URL using **Inquirer.js**
* Converts the URL into a QR code PNG using **qr-image**
* Saves the user-entered URL into a `URL.txt` file
* Automatically generates a `qr-img.png` file in the project directory

---

## 📦 Technologies Used

* **Node.js**
* **inquirer** — for interactive CLI input
* **qr-image** — for generating QR code images
* **fs** — Node.js file system module for writing files

---

## 🛠 Installation

1. Clone this repository:

   ```sh
   git clone <your-repo-url>
   ```

2. Navigate into the project folder:

   ```sh
   cd your-project-folder
   ```

3. Install the required dependencies:

   ```sh
   npm install inquirer qr-image
   ```

---

## ▶️ Usage

Run the project using:

```sh
node index.js
```

You will be prompted to enter a URL.
The app will then:

* Generate a QR code image named **`qr-img.png`**
* Save the entered URL in a text file named **`URL.txt`**
* Display a confirmation message when the file is saved

---

## 📁 Output Files

* **qr-img.png** — generated QR code image
* **URL.txt** — contains the user-entered URL

---

## 🧩 Example

```
? Type in your URL: https://example.com
The file has been saved!
```

This produces:

* `qr-img.png` — QR code for *[https://example.com](https://example.com)*
* `URL.txt` — contains the text: *[https://example.com](https://example.com)*

---

## 📜 License

This project is open-source and free to use.

---

## 💡 Future Improvements

* Allow custom file names
* Support different QR code formats (SVG, EPS)
* Add validation for URLs

Feel free to contribute or suggest improvements!

