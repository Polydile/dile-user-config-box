# \<dile-user-config-box\>

A Polymer web component to display an image with an asociated overlay. The image colud be an user avatar or an icon (by default). When the user clicks on the avatar, the overlay opens with an animation.

You can use any content in the overlay via an slot named "overlay-content".

```html
<dile-user-config-box>
  <span slot="overlay-content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi natus temporibus delectus saepe reprehenderit labore ab nemo est vitae. Ipsum deserunt cupiditate animi sit nihil soluta est sapiente tempora facere.</p>
    </span>
</dile-user-config-box>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
