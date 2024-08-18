# Here's how I improved your website!

## Improvement 1:

### Before:
![before](https://github.com/hex248/Radiant-AI/blob/master/improvements/Use%20Cases%20(before).png?raw=true)

('Use Cases' is misaligned vertically with the other nav links)

### After:
![after](https://github.com/hex248/Radiant-AI/blob/master/improvements/Use%20Cases%20(after).png?raw=true)

### Solution:

The 'Use Cases' `<a>` tag was in the same `<div>` as 'Solutions', so I separated them in the same way that the other navlinks are.


## Improvement 2:

### Before:
![before](https://github.com/hex248/Radiant-AI/blob/master/improvements/Say%20hello%20to%20more%20clients%20(before).png?raw=true)

(The background box doesn't fill out the space of the elements in the foreground and distracts from the information presented)

### After:
![after](https://github.com/hex248/Radiant-AI/blob/master/improvements/Say%20hello%20to%20more%20clients%20(after).png?raw=true)


### Solution:

Change `scale3d(0.8, 1, 1)` to `scale3d(1.6, 1, 1)`. Background element now fills out the area of the foreground elements.


## Improvement 3:

### Before:
![before](https://github.com/hex248/Radiant-AI/blob/master/improvements/Hover%20(before).png?raw=true)

(When hovering over text, it is very hard to see due to the darker background)

### After:
![after](https://github.com/hex248/Radiant-AI/blob/master/improvements/Hover%20(after).png?raw=true)

### Solution:

Change `color: rgba(26, 27, 31, .75);` to `color: var(--light-slate-grey);`


## Improvment 4:

### Before:
![before](https://github.com/hex248/Radiant-AI/blob/master/improvements/Supply%20chain%20(before).png?raw=true)

(Unnecessary spacing on one of the boxes)

### After:
![after](https://github.com/hex248/Radiant-AI/blob/master/improvements/Supply%20chain%20(after).png?raw=true)

### Solution:

Removed unnecessary `<br />`
