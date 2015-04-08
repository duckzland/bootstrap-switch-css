# Bootstrap Switch Element

A simple switch element for checkbox made with pure CSS only.

Browser must support :checked syntax in order for this css to work.

Originaly from http://www.bootstrap-switch.org

# How To use

1. Include the css

```html
<link href="bootstrap.css" rel="stylesheet">
<link href="bootstrap-switch.css" rel="stylesheet">
```

2. Use this markup structure
```html
<div class="checkbox form-group bootstrap-switch-mode">
  <label class="bootstrap-switch-label">
    <div class="bootstrap-switch bootstrap-switch-mini">
      <div class="bootstrap-switch-container">
        <input type="checkbox" value="1" name="my-checbox">
          <span class="bootstrap-switch-handle-off bootstrap-switch-danger">OFF</span>
          <span class="bootstrap-switch-handle-on bootstrap-switch-primary">ON</span>
      </div>
    </div>
    Some Label Text
  </label>
</div>
```
