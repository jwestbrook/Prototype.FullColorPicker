Prototype.FullColorPicker
=========================

PrototypeJS based color picker with fill HSB and RGB options of Adobe Photoshop’s picker


This is a lot more involved then the document load observer like below check out the test.html to see demo implementation


```javascript
	document.observe('dom:loaded',function(){
		cp1 = new FullColorPicker.ColorPicker('cp1', {startHex: 'ffcc00', startMode:'s'});
	});
```