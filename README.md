# Minecraft-Speedrun-Divine-Command

Unfortunatly it seems like it will only work on Nightbot, if anyone finds a way to make it work on Streamlabs Chatbot or StreamElements bot please let me know and I will add them below, thanks!

## To use this command:

### Nightbot:
``` 
!addcom !axis $(eval a=JSON.parse(`$(urlfetch json https://raw.githubusercontent.com/Nerxxy/Minecraft-Speedrun-Divine-Command/main/divine.json)`);b=decodeURIComponent(`$(querystring)`);if(a[b]){c=b+` - `;for(x in a[b]){c+=x+`: `+a[b][x].join(`, `)+`. `;}c.slice(0,400);}else{`No match!`;})
```

I also have an axis command [here](https://github.com/Nerxxy/Minecraft-Speedrun-Axis-Command)
