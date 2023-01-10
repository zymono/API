# How To Use The API
Use The Zymono API To Embed A Button Into Any Webpage That Launches Your Zymono Report Page.

## Step 1: Paste This Code
```  <script type="module" id="zymono-script">
    window.sessionStorage.setItem('gameID', 'lava')
    
    import { createButton, report } from 'https://zymono-api.zymono.repl.co/api.js'

    createButton()
  </script>```
