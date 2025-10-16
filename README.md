# 📝 Redux Todo App (React Native)

This is a **React Native To-Do List** project built using **Redux Toolkit** for state management.  
It allows you to add, toggle, delete, and filter todos (All, Active, Completed) — all with a clean UI and persistent Redux state.

---

## ⚙️ Getting Started

> **Note:** Before proceeding, ensure you have completed the official React Native setup guide:  
> 🔗 [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment)

---

### Step 1: Clone the Repository

```sh
git clone https://github.com/OwenImudia-Humber/ReduxTodoAppLab6.git
cd redux-todo-app
```

---

### Step 2: Install Dependencies

```sh
# Using npm
npm install

# OR using Yarn
yarn install
```

---

### Step 3: Start Metro Bundler

Metro is the JavaScript bundler for React Native.

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

---

### Step 4: Run the App

#### Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

#### iOS (Mac Only)

Make sure you have CocoaPods installed before running:

```sh
bundle install
bundle exec pod install
```

Then:

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

---

## 🧠 Project Structure

```
src/
 ├── screens/
 │    └── TodoListScreen.js      # Main connected component
 ├── store/
 │    ├── index.js               # Redux store configuration
 │    └── todosSlice.js          # Slice containing state, actions, reducers
App.js                           # Root component with Provider wrapper
```

---

## 🧩 Features

✅ Add new todos  
✅ Toggle completion status  
✅ Delete todos  
✅ Filter by All / Active / Completed  
✅ Redux Toolkit for simplified state management  
✅ React Hooks (`useSelector`, `useDispatch`)  
✅ Clean Material Icons UI  

---

## 🧪 Testing Redux Implementation

```sh
# Run app
npx react-native run-android
# OR
npx react-native run-ios

---

## 🧑‍💻 Author

**Owen Imudia**  
📧 [Imudiaowen@gmail.com](mailto:Imudiaowen@gmail.com) 