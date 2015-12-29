# jquery-notify


$('<p>Hello World!</p>').notify();
$('<p>Hello World!</p>').notify('error');
$('<p>Hello World!</p>').notify({sticky: true});


<p class="notify" data-notify-type="error">Error!</p>
<p class="notify" data-notify-type="success sticky">Sticky Info</p>
$('.notify').notify();
