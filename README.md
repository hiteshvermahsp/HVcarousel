# HVcarousel
Easy to implement, Fully responsive, Bootstrap based plugin, accessible with arrow keys and navigations, thumbnails option, popup of slides option, Autoplay

Simple Implementation

            $(function() {
                $('#MyCarousel').hVCarousel();
            });
            
Implementation with keys and their values

            $(function() {
                $('#MyCarousel').hVCarousel({
                    setting-key: setting-value,
                });
            });
        
Setting
autoplay - Boolean - true Enables autoplay slides

fade - Boolean - false - If true then enables fade animation otherwise enable slide animation

dots - Boolean - false - Enable dots

arrow - Boolean - false - Enable arrows

Interval - Integer - 3000 - Set Interval for slides if autoplay enabled

thumbnailPlace - String	left - Set thumbnail around the slider by values: left, right, top, bottom

largeImage - Boolean - false - To side large slide in popup.

