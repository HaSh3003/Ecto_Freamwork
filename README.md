# Ecto Library 🚀

Ecto is a lightweight JavaScript library that provides dynamic variable binding and condition-based rendering without requiring users to write JavaScript! 🎯

## 📌 Features
- **Dynamic Variables**: Use `<x-var>` to declare global variables.
- **Looping**: Use `<x-loop>` to iterate over arrays.
- **Conditional Rendering**: Use `if="{{variable}} == 'value'"` to show/hide elements.
- **Component System**: Load external HTML components easily.

## 📥 Installation
You can include Ecto in your project using jsDelivr CDN:
```html
<script src="https://cdn.jsdelivr.net/gh/HaSh3003/Ecto_Library/ecto.min.js"></script>
```

## 🚀 Usage
### 1️⃣ Define a Variable
```html
<x-var name="userName" value="John Doe"></x-var>
```

### 2️⃣ Use Loops
```html
<x-loop repeat="10">
  <!-- ========== Start flex ========== -->
  <x-click action="alert('hmed')">btn</x-click>
  <!-- ========== End flex ========== -->
</x-loop>
```

### 3️⃣ Conditional Rendering
```html
<x-var name="role" value="admin"></x-var>
<div if="{{role}} == 'admin'">Welcome, Admin! 👑</div>
```

### 4️⃣ Using Components
```html
<x-component src="header.html"></x-component>
```

## 💡 Contributing
Want to improve **Ecto Library**? Feel free to fork, submit issues, or contribute! 🎉

## 📜 License
This project is open-source and available under the MIT License.

---

⭐ **Star the repo if you like it!** ⭐

