# ImHere - Participant Manager

This is a simple application for managing event participants. It allows you to add and remove participants and displays a message when the list is empty.

## 🚀 Features

- Add participants to a list.
- Remove participants with confirmation.
- Display personalized messages when the list is empty.

## 🖥️ Technologies Used

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- TypeScript

## 📂 Project Structure

```plaintext
imhere/
├── App.tsx
├── package.json
├── src/
│   ├── components/
│   │   └── Participant/
│   │       ├── index.tsx
│   │       └── styles.ts
│   └── screens/
│       └── Home/
│           ├── index.tsx
│           └── styles.ts
```

## 🛠️ How to Run

### Prerequisites

- Node.js
- Expo CLI
- Android/iOS emulator or physical device

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/tiagoh671/imhere.git
   ```

2. Install dependencies:

   ```bash
   cd imhere
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the app on an emulator or physical device:

   - For Android:
     ```bash
     npm run android
     ```
   - For iOS:
     ```bash
     npm run ios
     ```

5. Alternatively, open the app in a web browser:

   ```bash
   npm run web
   ```

## 🖼️ Layout

### Home Screen

- Event name and date.
- Input field to add a participant.
- List of added participants.

### Participant Component

- Displays the participant's name.
- Button to remove the participant.

---

Made with 💙 by [tiagoh671](https://github.com/tiagoh671).