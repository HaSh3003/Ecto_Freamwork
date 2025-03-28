# Ecto JS Library

This is a custom JavaScript library designed for dynamic variable handling and conditional rendering in HTML using `<x-var>` and `<x-loop>` components.

## 🚀 Features
- **Dynamic Variables:** Define and use global variables with `<x-var>`.
- **Conditional Rendering:** Use `if="{{variable}} == 'value'"` to control element visibility.
- **Looping Elements:** Iterate over lists using `<x-loop>`.
- **CDN Ready:** Hosted on jsDelivr for easy usage.

## 📦 Installation
You can include this library in your project using jsDelivr CDN:
```html
<script src="https://cdn.jsdelivr.net/gh/YOUR_USERNAME/YOUR_REPO@latest/index.min.js"></script>
```

## 📖 Usage
### 1️⃣ Define Variables
```html
<x-var name="userName" value="Hesham"></x-var>
<x-var name="userRole" value="admin"></x-var>
```
### 2️⃣ Conditional Rendering
```html
<div if="{{userRole}} == 'admin'">Welcome, Admin!</div>
```
### 3️⃣ Looping Through Data
```html
<x-var name="users" value='[{"name": "Ahmed"}, {"name": "Sarah"}]'></x-var>
<x-loop name="users">
  <p>{{item.name}}</p>
</x-loop>
```

## 🛠 Development
To contribute or modify the library, clone this repository:
```sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
```

## 📜 License
This project is licensed under the MIT License.

