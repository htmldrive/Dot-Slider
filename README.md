Dot Slider - simple easy-to-use images slideshow jquery plugins
=======================

[![Dot Slider - simple easy-to-use images slideshow jquery plugins](http://www.htmldrive.net/media/2010/6/11/1276245112.jpg "Dot Slider - simple easy-to-use images slideshow jquery plugins")](http://www.htmldrive.net/items/demo/37/Dot-Slider-simple-easy-to-use-images-slideshow-jquery-plugins "Dot Slider - simple easy-to-use images slideshow jquery plugins")

[**Demo**](http://www.htmldrive.net/items/demo/37/Dot-Slider-simple-easy-to-use-images-slideshow-jquery-plugins "Dot Slider - simple easy-to-use images slideshow jquery plugins")

##Usage
**Include js and css files.**

    <script type="text/javascript" src="js/jquery.js"></script>
    <link href="css/webwidget_slideshow_dot.css" rel="stylesheet" type="text/css">
    <script type="text/javascript" src="js/webwidget_slideshow_dot.js"></script>
  
**Add html.**

    <div id="demo1" class="webwidget_slideshow_dot">
        <ul>
            <li><a href="link1" title="Sky"><img src="images/slideshow_large_1.jpg" width="407" height="301" alt="slideshow_large"/></a></li>
            <li><a href="link2" title="Sea"><img src="images/slideshow_large_2.jpg" width="407" height="301" alt="slideshow_large"/></a></li>
            <li><a href="link3" title="Flower"><img src="images/slideshow_large_3.jpg" width="407" height="301" alt="slideshow_large"/></a></li>
            <li><a href="link4" title="Treelink4"><img src="images/slideshow_large_4.jpg" width="407" height="301" alt="slideshow_large"/></a></li>
        </ul>
        <div style="clear: both"></div>
    </div>
        
**Add startup script.**

    <script language="javascript" type="text/javascript">
    $(function() {
        $("#demo1").webwidget_slideshow_dot({
            slideshow_time_interval: '5000',
            slideshow_window_width: '200',
            slideshow_window_height: '200',
            slideshow_title_color: '#17CCCC',
            soldeshow_foreColor: '#000',
            directory: 'images/' //Icon image directory
        });
    });
    </script>