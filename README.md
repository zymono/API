# How To Add A Report Button To Your Website
Use The Zymono API To Embed A Button Into Any Webpage That Launches Your Zymono Report Page.

## Step 1: Paste This Code
```html
<script type="module" id="zymono-script">
    //THIS CODE WAS MADE FOR THE ZYMONO API AND FOLLOWS OUR API LICENSE. 
    //https://github.com/zymono/API
    
    window.sessionStorage.setItem('gameID', 'Your_ID_HERE')
    
    import { createButton, report } from 'https://api.zymono.com/api.js'

    createButton()
</script>
  ```

## Step 2: Modify For Your Page

Edit the ```Your_ID_Here``` text to be your unique report id. You can find this at: https://zymono.com/dashboard/

## Final Information and Attribution Policy

Do NOT remove the script tag that has ```zymono-script``` as the id, otherwise the system will break!

Do NOT remove the credits inside of the script tag, or else there will be legal consequences.

THE CODE IMPORTED FROM https://api.zymono.com/api.js HAS A SEPARATE LICENSE AGREEMENT TO THE API AGREEMENT WHICH YOU CAN READ AT: https://api.zymono.com/license.md

# How To Setup A Panel On Your Website

## Step 1: Insert This Code Into Your Page
```html 
<iframe src="https://api.zymono.com/panel/" style="position:absolute;top:0;left:0;width:100%;height:100%;border:none;">
<script type="module" id="zymonoPanel">
  import { createPanel } from 'https://api.zymono.com/panel.js'
  createPanel('Your_Panel_Key_Here')
</script>
```

## or:

```html 
<script src="https://api.zymono.com/panel.js"></script>
<iframe src="https://api.zymono.com/panel/" style="position:absolute;top:0;left:0;width:100%;height:100%;border:none;">
<script>
    createPanel('Your_Panel_Key_Here')
</script>
```
    
## Step 2: Modify
    
Edit ```Your_Panel_Key_Here``` to your panel key which you can find at: https://zymono.com/dashboard/
    
## Warning
    
Anybody with access to this page can view the source code where you list your panel key.
    
## Final Information and Attribution Policy

Do NOT remove the script tag that has ```zymonoPanel``` as the id, otherwise the system will break!

Do NOT remove the credits inside of the script tag, or else there will be legal consequences.

THE CODE IMPORTED FROM https://api.zymono.com/panel.js HAS A SEPARATE LICENSE AGREEMENT TO THE API AGREEMENT WHICH YOU CAN READ AT: https://api.zymono.com/license.md

THE WEBSITE REFERENCED IN THE IFRAME IS OWNED AND COPYRIGHTED UNDER ALL RIGHTS RESERVED BY ZYMONO AND WE CAN RESTRICT ACCESS TO IT FOR ANY REASON WE SEE FIT!
    
YOU ARE NOT ALLOWED TO MODIFY ANY CODE ACCEPT: ```Your_Panel_Key_Here```
