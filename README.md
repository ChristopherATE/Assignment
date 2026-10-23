index.html:	First page with the big Portfolio button
menu.html:	Second page with About Me and Achievements buttons
about.html: About Me page with text and photo
style.css:	All the looks

I decided to use JavaScript to make simpler

For HTML:
<link rel="stylesheet" href="style.css"> loads the CSS file. Without it, the page looks plain.
<img class="logo" ...> shows the logo.
<button class="btn"> makes a clickable button.
<script> holds the code that runs when you click. --> Learnt from High school

For CSS:
.logo, .btn, .back and so on are classes. A class matches any HTML element with the same name, like class="btn".
font-size: clamp means “scale with the screen.
.btn:hover is the style when the mouse is over the button.
@media (max-width: 800px) is for phones. The About page stacks into one column.
