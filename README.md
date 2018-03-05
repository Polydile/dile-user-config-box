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

### Styling
The following custom properties and mixins are also available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--dile-user-config-box-zindex` | A property that controls the overlay z-index | 999999
`--dile-user-config-box-overlay` | A mixin that is applied to the overlay | `{}`
`--dile-user-config-box-icon-color` | A property that controls de icon color | #999
`--dile-user-config-icon` | A mixin that is applied to the icon | `{}`
