# Udon Basic Mirror Prefab

This is a Unity Package that contains a Basic Mirror and Mirror Button script that is made using the Udon Graph. This script does not require the knowledge of Udon and allows you to add as many mirrors as you'd like and auto-hide other mirrors once a mirror is enabled.

The very basics is that this object will set 1 object to active, and disable all the others (or disable them all if you set the button to do so)

## How to use

1. Create a Game Object (You should use this to store all of the Mirror Objects)
2. Attach an Udon Behavor and select the Mirror Script as the Program Source.
3. Create your Mirror Objects
4. In the Mirror Udon Behavor, Click on the triangle next to "Mirrors", it should be under "Public Variables"
5. set the size (the amount of mirrors)
6. drag and drop your Mirror Game Objects into the spaces "size"
7. MAKE NOTE OF THE NUMBERS
8. create some game objects (these will be our buttons)
9. Attach an Udon Behavor and select the "Mirror_Button" script
10. For an "Off" button, under "Public Variables", tick the check box next to "disableMirrors"
11. For a mirror button, set the number to the number you made note of (this number coresponds to the mirror next to that number)

This Mirror Script will automatically hide every other mirror. No need to worry.

***BE CAREFUL***
The more mirrors you have in a single Mirror Script, the slower it becomes to toggle these mirrors.
