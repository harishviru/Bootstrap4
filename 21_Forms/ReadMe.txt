Bootstrap 4 Forms
--------------------------
.All textual <input>, <textarea>, and <select> elements with class .form-control have a width of 100%.

.form-inline
.form-group

.form-control
.form-check
.form-check-label
.form-check-input

.col
.row
.form-row

.was-validated            -before submitting the form
.needs-validation         -after the form has been submitting. 
 novalidate
.valid-feedback
.invalid-feedback

# For .needs-validation  and novalidate.
<script>
// Disable form submissions if there are invalid fields
(function() {
  'use strict';
  window.addEventListener('load', function() {
    // Get the forms we want to add validation styles to
    var forms = document.getElementsByClassName('needs-validation');
    // Loop over them and prevent submission
    var validation = Array.prototype.filter.call(forms, function(form) {
      form.addEventListener('submit', function(event) {
        if (form.checkValidity() === false) {
          event.preventDefault();
          event.stopPropagation();
        }
        form.classList.add('was-validated');
      }, false);
    });
  }, false);
})();
</script>