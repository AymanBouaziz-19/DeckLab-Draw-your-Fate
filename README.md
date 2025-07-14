# 🧑‍💻🃏 DeckLab – Draw Your Fate

An interactive Python tool that connects with a **card-drawing API** to generate randomized playing cards.  
Built to strengthen skills in **HTTP requests**, **JSON parsing**, **API logic**, and **interactive terminal outputs**, DeckLab is a fusion of fun, fate, and functionality.

---

## 🎯 Project Objective

- Learn API integration with `requests`
- Practice parsing and extracting data from JSON
- Build modular, readable logic with functions and control flow
- Create dynamic console output showing card details and status

---

## ⚙️ Features

| Feature               | Description                                                |
|------------------------|------------------------------------------------------------|
| 🃎 Random Card Draw     | Connects to https://deckofcardsapi.com to draw cards       |
| ♻️ Multiple Draw Logic  | Single or multiple card draw options                       |
| 📦 JSON Parsing         | Extracts suit, value, image link, and code from API data   |
| 🖥️ CLI Output           | Simple yet clear terminal interface                        |
| 📡 Offline Mode (opt)   | Optional fallback with local mock data                     |
| 🎮 User Interaction     | Select number of cards or play simple minigames (planned)  |

---

## 📁 Project Structure
```
DeckLab-DrawYourFate/ ├── src/ │   ├── main.py         # Main interactive interface │   ├── api_handler.py  # Handles connection and fetching from deck API │   ├── parser.py       # Parses JSON and extracts card data │   └── utils.py        # Helper functions (e.g., card display formatting) ├── assets/             # Sample outputs, logs, or images (optional) ├── README.md └── requirements.txt
```
---

## 🧪 Example Usage

```bash
> python main.py
🎲 Welcome to DeckLab – Draw Your Fate!

How many cards would you like to draw? (1–5): 2

🃏 Card 1: Queen of Hearts ♥️
🃏 Card 2: 7 of Spades ♠️
```
---

## 🌐 Live API Reference

DeckLab uses the free public API:
🔗 https://deckofcardsapi.com/

Sample Response:

{
  "cards": [
    {
      "value": "QUEEN",
      "suit": "HEARTS",
      "code": "QH",
      "image": "https://deckofcardsapi.com/static/img/QH.png"
    }
  ]
}
```

---

## 🧠 Extensions & Ideas

Idea	Description

🎨 Card Art Display	Render images of drawn cards (via PIL or Tkinter)

🧩 Simple Card Game	Mini blackjack / war game logic

💾 Save Draw History	Save cards drawn per session (CSV/JSON log)

🎴 Tarot Mode (Fantasy)	Use custom deck logic or alternate decks

🌍 Web Version (Streamlit)	Optional web UI to interact with deck



---

## 🔧 Technologies Used

🐍 Python 3

🔗 requests for HTTP API access

📦 JSON parsing

(Optional) colorama for CLI color styling

(Optional) tkinter or PIL for card image rendering



---

## 👨‍💻 Author

Ayman Bouaziz
🎓 AI & Software Engineering Student – Faculty of Science and Technology Al Hoceima
📍 Morocco | 🧠 Python • AI • API Integration

🔗 LinkedIn: https://www.linkedin.com/in/ayman-bouaziz-7ab181349

✉️ projects.aymanbouaziz@gmail.com


---

## 📜 License

MIT License — Educational and personal use permitted
© 2025 Ayman Bouaziz


---

## ✨ Final Thought

> "Your fate is in the deck... or maybe in your code. DeckLab brings randomness, logic, and magic into one interactive experiment."