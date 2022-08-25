```
<script>

window.addEventListener( 'load', function( event ) {

let jquery_load_check_interval = setInterval( function() {

if ( window.jQuery ) {

console.log( 'Username As Variable: jQuery v.' + $.fn.jquery + ' loaded' );

console.log( 'Username As Variable: v.2.3' );

makeFirstname();

clearInterval( jquery_load_check_interval );

} else {

console.log( 'Username As Variable: new try to load jquery...' );

}

}, 150);

function makeFirstname() {

var fname = $('span.usertext.mr-1').text().split(/\s+/)[1]; /*IF THE LASTNAME WILL BE DISPLAYED TRY [0} INSTEAD OF [1] IN THIS LINE */

console.log('Username As Variable: firstname is ' + fname);

$(".fname").text(fname);

console.log('Username As Variable: firstname added to all positions');

}

}, false );

</script>
"
```

Fügt Namen überall bei ```<span class="fname"></span>``` ein.

https://github.com/TRMSC/moodle-editor-inline-codes/blob/main/username-as-variable.html
