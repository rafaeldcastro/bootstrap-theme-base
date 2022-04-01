# Bootstrap Custom Theme (boilerplate)
Boilerplate to create a custom Bootstrap theme

### How to Use
- First, don't forget to install bootstrap using:

```npm install bootstrap```



- Using **VSCode IDE** install a SASS compiler extension

![live_sass_compiler](https://user-images.githubusercontent.com/5839269/161335736-60373a21-b252-4b31-9a5e-d4b5c181d34f.png)

- Re-start/Re-load **VSCode** to the extension work

- On **VSCode** go to:

```File > Preferences > Settings```

Or just press ```CTRL + , ```

- On the ```Search settings``` bar type: ```live sass format```

- Click on ```Edit in settings.json```

- Under ```liveSassCompile.settings.formats``` change to the following: 
```
{
    "format": "compressed",
    "extensionName": ".min.css",
    "savePath": "/css"
}
```

- This will set the compiler to compressed the final ```.css``` file and add it to a folder at ```/css```

- To start work in your project, open the ```main.scss``` file and using the **VSCode Status Bar** click to ```Watch  Sass```

![watch_sass](https://user-images.githubusercontent.com/5839269/161337107-eb12dbb2-42b4-40ce-a4f2-b292ee3e67f3.png)

- This will watch for every change saved on ```main.scss``` file and re-compiled it

### Optional

- Install ```live server``` extension to apply live reload over index.html file.
