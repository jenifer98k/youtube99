Bootstrap Cards & Modals

components > cards , model 

<div class="card" style="width: 18rem;">
  <img src="https://via.placeholder.com/150" class="card-img-top" alt="Image">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This is some sample text inside the card.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>


card: Main card container

card-img-top: Image at the top

card-body: Holds the content inside the card

card-title, card-text: Content styling

btn btn-primary: Button with blue background


# A Modal is a popup box that appears on top of the page. Used for:

Login forms

Confirmations

Alerts

Displaying extra info


<div class="modal" tabindex="-1">
Creates the modal box.

tabindex="-1" allows keyboard focus when active.

🔹 <div class="modal-dialog">
Centers the modal on the screen.

🔹 <div class="modal-content">
The white popup area containing all modal parts.

🔹 <div class="modal-header">
Top section with title and close (X) button.

🔹 <h5 class="modal-title">
Displays the modal’s title.

🔹 <button class="btn-close" data-bs-dismiss="modal">
Closes the modal when clicked.

🔹 <div class="modal-body">
Middle area for your text or form.

🔹 <div class="modal-footer">
Bottom area with buttons like “Close” or “Save”.

🔹 data-bs-dismiss="modal"
Automatically closes the modal on button click.


