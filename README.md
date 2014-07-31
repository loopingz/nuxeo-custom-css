nuxeo-custom-css
================

Allow to define custom CSS per workspace

The interface will be using this CSS for every document inside the workspacem, you can define this CSS in the local configuration tab.

You'll then be able to change the logo, change the basic color by overriding some style.

![image](https://raw.githubusercontent.com/loopingz/nuxeo-custom-css/master/doc/screenshot_1.png)

For exemple if you add this CSS :

```CSS
.nxHeader {
  background-color: #ff0000 !important;
}

body {
  background-color: #000000; 
  color: #ffffff !important;
}

.tabsBar {
  background-color: #000000 !important; 
  border-color: #000000 !important;
}

.tabsBar li.selected a {
  color: #ff0000 !important;
}

h1 {
  color: #ffffff !important;
}

.siteLogo {
  visibility: hidden;
}
```

You'll see this :

![image](https://raw.githubusercontent.com/loopingz/nuxeo-custom-css/master/doc/screenshot_2.png)