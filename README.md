# scripts

-- allowCopy.js -- 

enableContextMenu(false);

```
javascript:(function () { 
    var script =  document.createElement('script');
    script.src="//cdn.jsdelivr.net/gh/msobkyy/scripts/allowCopy.js"; 
    document.body.appendChild(script);
    script.onload = function () { 
        enableContextMenu(false);
    } 
})();
```

----------------
