# Bootstrap Multi Email   
   
Bootstrap Multi Email is a jQuery plugin providing a Twitter Bootstrap user interface adding multiple email addresses to a field (like Gmail's compose). It extends the functionality of Bootstrap Tags Input (https://github.com/TimSchlechter/bootstrap-tagsinput) to accomplish this.   
   
## Installation   
   
### Bower   
   
Not added to the Bower Package Repository, yet. Use:   
   
`{
   "bootstrap-multiEmail":"git@github.com:ThinkBigPartners/bootstrap-multiEmail.git"
}`
   
## Usage   
   
### Include JS and CSS   
   
`<link href="/bower_components/bootstrap-tagsinput/dist/bootstrap-tagsinput.css">`   
`<link href="/bower_components/bootstrap-multiEmail/src/bootstrap-multiEmail.css">`
   
`<script src="/bower_components/jquery-validation/jquery.validate.js"> //Optional`
`<script src="/bower_components/bootstrap-tagsinput/dist/bootstrap-tagsinput.min.js">`
`<script src="/bower_components/bootstrap-multiEmail/src/bootstrap-multiEmail.css">`   
   
   
### HTML5 Data Instantiation   

Just add `data-role="multiemail"` to your input, select, or textarea element to automatically change it to a multi email input field.   
   
   
### Manual Instantiation   
   
`$('input').multiEmail()`   
   

## License   

This project is licensed under [MIT](https://raw.github.com/TimSchlechter/bootstrap-tagsinput/master/LICENSE "Read more about the MIT license").


