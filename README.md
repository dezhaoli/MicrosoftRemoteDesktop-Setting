# MicrosoftRemoteDesktop-Setting
MacOS shortcut binding for `Microsoft Remote Desktop Client`

Already remap:
```shell
1.
command + qwertyuiop[]\                    ctrl +  qwertyuiop[]\
          asdfghjkl;'                ->            asdfghjkl;'
          zxcvbnm,./                               zxcvbnm,./

2.
command + shift + qwertyuiop[]\            ctrl + shift +  qwertyuiop[]\
                  asdfghjkl;'        ->                    asdfghjkl;'
                  zxcvbnm,./                               zxcvbnm,./
3.
command + Delete                     ->    Delete
```

Install
-------


1. copy ClipboardActionTransformations.xml to "/Applications/Microsoft Remote Desktop.app/Contents/Resources/Keyboard/ClipboardActionTransformations.xml"

2. 
<img width="644" alt="setting" src="https://user-images.githubusercontent.com/23163073/177980597-ae64dcc4-2482-42b5-ba71-af3255889ecf.png">



Note
-------
Generally speaking, command + w is reserved by the operating system and cannot be passed to MicrosoftRemoteDesktop, but according to the method given by ALEUT, it can be configured in this way:

<img width="644" alt="image" src="https://github.com/dezhaoli/MicrosoftRemoteDesktop-Setting/assets/23163073/9dd16997-ac50-4b8e-ac7b-7d5ddabf3dfb">

In system settings, add a Close action with a new combination to MicrosoftRemoteDesktop app. After that, Cmd + W will work fine.
