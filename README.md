# DTZ-Schreiben-Practice

A simple web-based tool to help you practice writing tasks for the **Deutsch-Test für Zuwanderer (DTZ)** exam. Write your responses, save them as `.txt` files, and share them with your teacher or ChatGPT for corrections.

---

## Features

- **Task Selection**: Choose from a list of DTZ-style writing tasks.
- **Random Task Picker**: Get a random task to practice.
- **Save Responses**: Save your response as a `.txt` file, formatted with the task details.
- **Clean Interface**: Easy-to-use design for focused writing practice.

---

## How to Use

### Prerequisites
- **Node.js** installed on your machine.
- **Express.js** ```npm install express```

### Steps
1. Clone this repository or download the files.
2. Open a terminal in the project folder.
3. Run `npm install` to install dependencies (Express.js).
4. Run `node server.js` to start the server.
5. Open your browser and go to `http://localhost:3000`.
6. Select a task or click "Pick Random Task."
7. Write your response in the text area.
8. Click "Save as .txt" to download your response with the task details.
9. Share the file with your teacher or ChatGPT for feedback.

---

## Example Output

Saved `.txt` files include the task details and your response:

```
Task: Falsche Hose geliefert
Details:
- Welche Hose genau haben Sie bestellt (Farbe, Modell, Größe …)
- Warum haben Sie bei dieser Firma die Hose gekauft?
- Was haben Sie bekommen?
- Was möchten Sie jetzt?

-----------------------------------

Sehr geehrte Damen und Herren,

ich habe am 15. Oktober eine blaue Jeans, Modell "Slim Fit", Größe 32 bestellt. Leider habe ich stattdessen eine schwarze Hose erhalten.
Ich habe bei Ihnen gekauft, weil ich Ihre Qualität schätze. Bitte senden Sie mir die richtige Hose zu oder erstatten Sie den Betrag.

Mit freundlichen Grüßen
[Your Name]
```

---

## Repository Structure

- **`index.html`**: Main interface for the tool.
- **`tasks.json`**: Contains the list of writing tasks.
- **`server.js`**: Express server to serve files locally.

---

## Missing:
- **More Tasks**: Expand `tasks.json` with new writing tasks.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Perfect for DTZ exam prep! 🚀
