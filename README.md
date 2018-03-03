# Ti.ImmersiveMode

This module realize [Immersive Full-Screen Mode](https://developer.android.com/training/system-ui/immersive.html)
<img src="https://developer.android.com/images/training/imm-states.png" />    
  
## Usage

```javascript
var Imm = require("ti.ímmersivmode");
win.addEventListener("open",function(){
	Imm.setSticky(true);
	Imm.hideSystemUI();
	Imm.showSystemUI();
	Imm.resetSystemUI();
	Imm.setStatusBarColor("#ff0000");
	Imm.setNavigationBarColor("#88ff0000");
	
});
```