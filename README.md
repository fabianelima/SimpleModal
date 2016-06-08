#SimpleModal

A simple modal made with jQuery + CSS. To use it, just paste the following code inside your html...:

	<div class="modal-box">
		<div class="modal-close" onclick="modalClose()">&times;</div>
		<div class="modal-content">
			<!--Put your content here!-->
		</div>
	</div>
	<div class="modal-fade" onclick="modalClose()"></div>

...and put ''onclick="modalOpen()'' on the HTML element to trigger the modal opening. The following functions will make the modal open and close:

	function modalOpen() {
		$('.modal-fade,.modal-box').fadeIn();
	}

	function modalClose() {
		$('.modal-fade,.modal-box').fadeOut();
	}

Now you just have to edit the some classes on the CSS, and that's it! :)