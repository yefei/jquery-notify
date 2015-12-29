# jquery-notify

## Setup
```javascript
$.notifySetup({sound: '/static/audio/notify.wav'});
```

## Use
```javascript
$('<p>Hello World!</p>').notify();
$('<p>Hello World!</p>').notify('error');
$('<p>Hello World!</p>').notify({sticky: true});
```

```html
<p class="notify" data-notify-type="error">Error!</p>
<p class="notify" data-notify-type="success sticky">Sticky Info</p>
<script>
$('.notify').notify();
</script>
```
