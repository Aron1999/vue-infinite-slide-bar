<p>
<a href="https://npmjs.com/package/vue-infinite-slide-bar"><img src="https://img.shields.io/npm/v/vue-infinite-slide-bar.svg?style=flat" alt="NPM version"></a>
<a href="https://npmjs.com/package/vue-infinite-slide-bar"><img src="https://img.shields.io/npm/dm/vue-infinite-slide-bar.svg?style=flat" alt="NPM downloads"></a>
<a href="https://www.npmjs.com/package/vue-infinite-slide-bar"><img src="https://img.shields.io/npm/l/vue-infinite-slide-bar.svg?style=flat" alt="License"></a>
<a href="https://biigpongsatorn.github.io/#/vue-infinite-slide-bar"><img src="https://travis-ci.org/biigpongsatorn/biigpongsatorn.github.io.svg?branch=dev" alt="Demo Build Status"></a>
</p>

# ∞ Vue Infinite Slide Bar

🎚 Infinite slide bar component.

# 👀 Document & Demo Page

Coming soon...

# 💻 Install

```sh
npm install --save vue-infinite-slide-bar
```
or
```sh
yarn add vue-infinite-slide-bar
```

# 🕹 Usage
```javascript
import Vue from 'vue'
import InfiniteSlideBar from 'vue-infinite-slide-bar'

Vue.component('InfiniteSlideBar', InfiniteSlideBar)
```
or
```javascript
import InfiniteSlideBar from 'vue-infinite-slide-bar'

export default {
  components: {
    InfiniteSlideBar
  }
}
```

# 🔎 Example

```html
<infinite-slide-bar :barStyle="{ background: '#42b883', padding: '5px 0' }">
  <span style="color: #fff;">Helo World, I love Vue Infinite Slide Bar</span>
</infinite-slide-bar>
```

# ⚙️ Props
| Props       | Type          | Default  | Description  |
| ----------- |:--------------| ---------|--------------|
| barStyle       | Object        | -     | Customize style of slide bar |
| duration      | String        | 12s     | Speed of animation |
| direction      | String        | normal     | Direction of animation (`normal`, `reverse`) |
| delay      | String        | 0s     | Delay time before animation start |

# 🤝 Contributing
1. Fork this repository.
2. Create new branch with feature name.
3. Run `npm install` and `npm run dev`.
4. Create your feature.
5. Commit and set commit message with feature name.
6. Push your code to your fork repository.
7. Create pull request. 🙂

# ⭐️ Support

```
If you like this project, You can support me with starring ⭐ this repository.
```

# 📄 License

[MIT](LICENSE)

Developed with ❤️ and ☕️ 
