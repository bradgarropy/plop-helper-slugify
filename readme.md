## 💧 plop-helper-slugify

<a href="https://npmjs.com/package/plop-helper-slugify">
    <img alt="npm" src="https://img.shields.io/npm/v/plop-helper-slugify.svg?style=flat-square">
</a>

<a href="https://npmjs.com/package/plop-helper-slugify">
    <img alt="npm" src="https://img.shields.io/npm/dt/plop-helper-slugify?style=flat-square">
</a>

_A [plop][plop] helper that slugifies text._

### 📦 Installation

This package is installable from [npm][npm].

```bash
npm install --save-dev plop-helper-slugify
```

### 🥑 Usage

Before you can use the `plop-pack`, you have to load it into the `plop` object.

```javascript
plop.load("plop-helper-slugify")
```

Once loaded, you now have access the following helpers.

#### `slugify`

Creates a slug for any input text.

**input**

```javascript
{
    title: "This Is An Example Slug"
}
```

**helper**

```handlebars
{{slug title}}
```

**output**

```javascript
"this-is-an-example-slug"
```

### ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]  
🙋🏼‍♂️ use my [ama][ama] or [twitter][twitter] to ask any other questions

[plop]: https://plopjs.com
[npm]: https://npmjs.com
[bradgarropy]: https://bradgarropy.com
[issues]: https://github.com/bradgarropy/plop-helper-slugify/issues
[twitter]: https://twitter.com/bradgarropy
[ama]: https://github.com/bradgarropy/ama
