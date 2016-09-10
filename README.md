# jQuery-GIF-loader

# jQuery plugin to create a video player that swap between static images and heavy gif files.

# Add data-gif to the image you'd like to swap with a path to the desire gif file.
<img src="img.jpg" alt="GIF Loader" data-gif="img.gif" class="gif">

# loop through all the gif elelments and set them up 
$('.gif').each(function() {
  $(this).gif();
});
