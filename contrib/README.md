My notes for a sake of my fork so I can save myself some time if anything unexpected happens.
And yeah, forks need to be public, so you can see them.

To run Librespot we have to:
1. do compiling of a dev branch as mentioned here: https://github.com/librespot-org/librespot/blob/dev/COMPILING.md
Note: run release build instead of debug. Move compiled app into usr/bin/librespot to set up a service later on (or change librespot.user.service accordingly).
2. to set up a service do as follows: https://github.com/librespot-org/librespot/wiki/Running-as-a-service
3. librespot.user.service is changed to my liking. I use user service so I can set it up via SSH.