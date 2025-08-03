# 🎮 Command Pattern - Unity Mini Project

This project demonstrates the **Command Design Pattern** implemented in Unity through a simple, interactive game. The core focus is to encapsulate user actions (like undo and replay) as commands, allowing greater flexibility and control over player input history.

---

## 🚀 Features

- **Command Pattern Implementation**: Actions like player movement and undo/replay are wrapped in command classes.
- **Input Abstraction**: User inputs are decoupled from action logic using invoker classes.
- **Undo/Replay System**: Stores a history of commands to allow reversing or reapplying actions.
- **Visual Feedback**: Player moves in response to arrow keys; undo/redo updates are reflected in real-time.

---

## 🧠 Design Patterns Used

| Pattern    | Usage                                  |
|------------|-----------------------------------------|
| Command    | Encapsulates player actions as objects  |
| Invoker    | Triggers commands from input            |
| Receiver   | Player movement logic                   |
| Singleton  | Input Manager (optional global access)  |

---

## 🎓 Learning Outcomes

- Better understanding of the **Command Design Pattern** in Unity
- Implementing **Undo/Replay functionality** using command history
- Writing **modular, decoupled code** for input and actions

---

## 📎 Gameplay Video

![Gameplay](https://github.com/Chintan-Patel-Games/Cosmic_Curation/assets/example1.gif)
