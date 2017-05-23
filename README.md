# MechKeyboard

## How to program your new KB

### Making your layout

Plug in your keyboard and navigate to:

http://123.57.250.164:3000/tada68

Now design your KB and if you have to map the fn key this is what worked for me:

![fn key config](https://cl.ly/2E1K2I1P2U0f/Image%202017-05-23%20at%2010.44.25%20AM.png "fn key config")

https://cl.ly/2E1K2I1P2U0f/Image%202017-05-23%20at%2010.44.25%20AM.png

Select the second option from the dropdown and layer 1. Now down generate and download the .bin file when you are done editing the layout

### Flashing your KB

Flip it over reach and push down the button in the back, the lights should now be flashing. Everything else is going to happen on the terminal sorry.

```
# New volume mounted when you are flashing your KB
cd /Volumes/TADA68\ \ 

# This is your newly generated bin file
cp ~/Documents/FLASH.BIN .

# Delete the mac auto created files :facepalm:
rm -rf .fseventsd ._FLASH.BIN 
```

That's it see @karl.rivest.harnois (slack) @KarlHarnois (gh) for help and support requests.
