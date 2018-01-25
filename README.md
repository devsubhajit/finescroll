# fineScroll bar
Easy jquery scrollBar plugin, easy to use.
* This plugin is dependent on two libraries
1. jquery (obviously)
2. jquery ui : https://code.jquery.com/ui/1.12.1/jquery-ui.js

# Use
    $(".scrollContainer").finescroll({
        alignment:'right',
        value:'4px',
        bgColor:'#7878dc',
        width:'8px'
    });

  Or 
  $(".scrollContainer").finescroll();

# Options 

* alignment : string, right/left
* value: string, value of position, example: '4px'
* width: string, value of position, example: '10px'
* bgColor: background color of scrollbar, string, example: '#ababab'
* fgColor: color of scrollbar, string, example: 'red'

# In the js folder, you will find touchSupport.js , this is to enable touch for jquery UI (drag)

Thanks for using.
