# Tic-Tac-Toe (Хрестики-Нолики)

Проєкт "Хрестики-Нолики" — класична гра в React + TypeScript без роутінгу, з двома режимами гри: **проти AI** та **проти друга**.

## 🚀 Можливості

* **Режим гри**

  * Грати проти AI (мінімакс або випадковий вибір ходу).
  * Грати удвох на одному пристрої.
* **Екрани**
  * Головний екран (Home): вибір режиму гри.
  * Ігровий екран (Game): поле 3×3, відображення ходу.
  * Екран результату (Results): відображає переможця чи нічию.
* **Структура**: залежності розділені за фічами та UI (feature-based architecture).

## 📁 Структура проекту

```
src/
├── assets/               # зображення та іконки
├── components/           # UI-компоненти
│   ├── home/
│   ├── game/
│   └── results/
├── features/
│   ├── navigation/       # хук useNavigation
├── App.tsx               # точка входу React-компонентів
├── main.tsx              # точка входу застосунку
├── index.css             # глобальні стилі
└── tsconfig.json         # конфігурація TypeScript
```

## 💻 Встановлення та запуск

1. Клонувати репозиторій

   ```bash
   git clone https://github.com/<your-username>/tic-tac-toe-react-ts.git
   cd tic-tac-toe-react-ts
   ```
2. Встановити залежності

   ```bash
   npm install
   # або
   yarn install
   ```
3. Запустити дев-сервер

   ```bash
   npm start
   # або
   yarn start
   ```
4. Відкрити у браузері `http://localhost:3000`

## ⚙️ Скрипти

* `npm run dev` — запуск у режимі розробки.
* `npm run build` — збірка для продакшну у папку `dist`.

## 🛠 Використані технології

* **React** + **TypeScript**
* **Vite**
* **CSS Modules**

## 📚 Додаткові матеріали

* React Docs: [https://reactjs.org/](https://reactjs.org/)
* TypeScript Docs: [https://www.typescriptlang.org/](https://www.typescriptlang.org/)

---

*Дякую за перегляд! Насолоджуйтесь грою та доповнюйте свій код!*
