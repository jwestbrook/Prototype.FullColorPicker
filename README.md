Prototype.FullColorPicker
=========================

PrototypeJS based color picker with fill HSB and RGB options of Adobe Photoshop’s picker

Mirrored from http://johndyer.name/photoshop-like-javascript-color-picker/


This is a lot more involved then the document load observer like below check out the test.html to see demo implementation


```javascript
	document.observe('dom:loaded',function(){
		cp1 = new FullColorPicker.ColorPicker('cp1', {startHex: 'ffcc00', startMode:'s'});
	});
```

__NOTICE__ If you use this color picker with Twitter BootStrap make sure you use the included CSS file. The CSS in Twitter BootStrap has some resets for DIV and IMG tags that changes how all the layers for this picker work. The CSS styles apply only to the elements that are created by the picker and unset those resets so that the picker works.