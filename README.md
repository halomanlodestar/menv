# menv

This software in my current understanding serves a simpler purpose that is configuration management , odly specific huh ??

There's a lot in a system config - what window manager to use , what display server this runs on , what compositors to use (X11 side only) , and specific combination of all this can have multiple configs too like hyprland with/without ags , the list is endless , long story short all this is super painfull to manage combine this with icon themes , gtk themes , color palletes , and most importantly the dependency of all these which creates a dependency hell 

The goal is simple a easy to use , smart dependency manager this purpose requiring least user effort , the point at which the software exposes its underlying complexity to the user , the game is over - that'll be our philosophy 

    This should allow effortless session management , hot swapping , startup scripts , env vars 

There should be no global source of truth for the software , our software would be smart enough to determine it , no global pollution , we only writing specific sym links to respect integrity of the system , and this should be removed gracefully as well on a "config swap"

a really great thing is to have super high compatbility with Version control systems to allow rollbacks 

FEAT: Non config specfic multiple monitor management 

FEAT: Abstraction over background services (status bars , notifications , system tray) and more 

FEAT: Sessions should be hot swappable

This can be the ultimate systemd for desktop management , in the plethora of endless choices , the painfull config changes restrict this vast ecosystem of unix , essentially systemd for desktop environments
