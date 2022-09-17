# Cue banner
Edit controls (ENTRY, TEXT, COMBO, SPIN) can be extended to have a 'cue banner'  (that greyed-out placeholder or explanatory text often seen in text fields).
![Cue banner](https://github.com/mikeduglas/Cue-Banner/blob/master/cuebanner_demo.png?raw=true)  

**Cue banner supports Unicode.**

### Usage in hand-coded project.
- Include cuebanner.inc file:
```
  INCLUDE('cuebanner.inc'), ONCE
```
- Declare an instance of TCueBannerMgr class:
```
cueMgr TCueBannerMgr
```
- After OPEN(Window) add edit control to cue manager, passing control label and cue banner text:
```
  cueMgr.AddControl(?ENTRY1, 'Enter your name.')
```

That's all.    

### Usage in an application.
- Register cuebanner.tpl.
- Add global extension 'Activate Cue banner'.
- Add procedure extension 'Activate Cue banner' in WINDOW procedure and fill in cue banner text for every edit control.
![Cue banner](https://github.com/mikeduglas/Cue-Banner/blob/master/cuebanner_procext1.png?raw=true)  

That's all.  

### Demo program
The demo can be downloaded [here](https://www.dropbox.com/s/tzc13zxhle0qxzc/CueBannerDemo.zip?dl=0).

### Requirements
- CW6 and newer.
- ABC and Clarion template chain.
- Windows Vista and newer (I haven't tested it yet on XP or Win2000).
- No extra libraries.

### Contacts
mikeduglas@yandex.ru  
mikeduglas66@gmail.com  



[But now](https://www.clarionshop.com/checkout.cfm?pid=1656&q=1&)
