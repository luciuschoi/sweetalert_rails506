# SweetAlert for Rails 5.0.x

This post was tested on the following environment:

- ruby 2.4.2
- rails 4.2.10, 5.0.6


I wish this tutorial works in all Rails 4.x and 5.0.x versions.

**Gemfile**

```ruby
gem 'sweetalert-rails'
gem 'sweet-alert-confirm', github: 'humancopy/sweet-alert-rails-confirm'
```

**application.js**

```js
//= require jquery
//= require jquery_ujs
//= require sweetalert
//= require sweet-alert-confirm
//= require turbolinks
//= require_tree .
```

**application.css**

```css
*= require_self
*= require sweetalert
*= require_tree .
```

or **application.scss**

```scss
@import sweetalert;
```

I hope it helps you.