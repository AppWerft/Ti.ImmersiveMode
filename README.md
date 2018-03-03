# Ti.Systembars

This module realize [Immersive Full-Screen Mode](https://developer.android.com/training/system-ui/immersive.html)
<img src="https://developer.android.com/images/training/imm-states.png" />    
  
## Usage

```javascript
var SysBars = require("ti.systembars");
win.addEventListener("open",function(){
	SysBars.hideSystembars();
	SysBars.setStatusBarColor("#ff0000");
	SysBars.setNavigationBarColor("#88ff0000");
	
});
```