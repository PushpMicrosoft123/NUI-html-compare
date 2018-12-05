
# NUI html compare tool 
is a highly customizable html compare tool. Feature include: 

Comparison of two html fragements and returns the comparison result in html form.

Exhibit the comparison using styling(background color).

Deleted tags/text are shown in red.

Added tags/text are shown in green.

Final html can be appended to other element if target is passed.

Manual

Usage
Manual:  var  _.tool = new NUI.CompareTool({
            oldHtml: inputOldHtml,
            newHtml: inputNewHtml,
            target: targetSelector
        });
       var comparisonResult = _.tool.compare();
       

Requirements

jQuery version 1.6.0 or higher


Browser compatibility

Internet Explorer 8+
Firefox
Chrome
Opera
Safari
iOS
Android
Windows Phone


License

MIT License (MIT)

http://opensource.org/licenses/MIT
