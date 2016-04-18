
$(function(){
  $(window).resize(function(){
    if($(this).width() > 767){
	// add the following lines 
	// http://stackoverflow.com/questions/14004318/show-random-image-from-array-in-javascript
	    $imgArr = ["2.JPG", "3.JPG"];
	    $basePath = "https://raw.githubusercontent.com/Spatial-R/spatial-r.github.io/master/assets/images/";
	    $rand = $imgArr[Math.floor(Math.random() * $imgArr.length)];
	    $imag = $basePath + $rand;
      $.backstretch($imag, {speed: 150}); 
      //$.backstretch("assets/images/6.jpg", {speed: 150}); 
      $('#backstretch').show();
    } else {
      $('#backstretch').hide();
      }
  })
  .resize();//trigger resize on page load
});

