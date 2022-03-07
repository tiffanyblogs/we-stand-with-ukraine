## We stand with Ukraine

A simple website badge to show your support for Ukraine.

### Installation
```
<script src="https://cdn.jsdelivr.net/gh/virae/we-stand-with-ukraine@v1.0.1/badge.js" async></script>
```

### Remove from mobile
```

<script>
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
    //Do something for mobile
    display: none;
}else{
    var script = document.createElement('script');
    script.src = "https://cdn.jsdelivr.net/gh/virae/we-stand-with-ukraine@v1.0.1/badge.js";
    document.write(script.outerHTML);
}
</script>
```

### Preview
![](https://github.com/virae/we-stand-with-ukraine/raw/master/preview.png)
