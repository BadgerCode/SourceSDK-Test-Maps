* Garry's Mod soundscapes preview- https://www.youtube.com/watch?v=P7lk3kXX7Go
* HL2 soundscapes preview- https://www.youtube.com/watch?v=nbVvZ8d1W1U

# Info about making your own
* All soundscapes need to be listed in a single "manifest" file in order to be available.
* Maps can get around this by embedding their own soundscape file within the map.
    * The only soundscapes available are the ones in this file
    * If you want to use other soundscapes, copy them into this file
* More info
    * https://web.archive.org/web/20190406193056/https://forum.facepunch.com/dev/rlha/Custom-soundscapes-in-Garry-s-Mod-broken-again/1/
    * https://www.youtube.com/watch?v=ZndfpzpQfvk

# Where to place them
* Place the soundscapes around the entraces to the areas of your map
    * I.e. put the "Outside" soundscapes on the outsides of doors and windows, and the inside soundscapes in the middle of rooms
* Behaviour
    * For a soundscape to play
        * The player must be within the radius
        * The player must be able to see the soundscape entity
        * Of all soundscapes within range, this soundscape must be the closest


# Good
* Inside
    * construct.inside
        * Good for: Generic inside background hum
    * general.concrete_quiet
        * Good for: underground carpark
    * eli_02_scrapyard_1
        * Good for: a cave near the ocean. creepy maps
* Inside/outside
    * construct.garage
        * Good for: inside areas of a map which are open to the outside
* Outside
    * construct.outside
        * Good for: outside maps with birds
        * Good mixture of birds, wind
    * construct.lake
        * Good for: outside maps near water
    * d1_trainstation.TerminalSquare 
        * Good for: Active town/city main square
    * coast.util_windgusts
        * Good for: Open, windy areas outside
    * cabin_outdoor
        * Good for: Maps in remote locations like forests, swamps
        * Constant outdoor wind and birds
        * Might be a bit annoying as it is constant sound
    * canals_canal_water
        * Good for: Maps right next to the ocean


# Meh
* d1_canals.windchimes_and_wind (very windy; some weird animal/bird noises; not sure where to use this)


# Busted
* canals_canal_nowater





# Sounds
* Birds
    * ambient/animal/bird1.wav
        * Medium pitch chatter, distinct
    * ambient/animal/bird2.wav
        * High pitch slow chatter
    * ambient/animal/bird3.wav
        * Short, high pitch two speeds of chatter
    * ambient/animal/bird4.wav
        * Varying speeds of chatter
    * ambient/animal/bird5.wav
        * Distinct medium pitch call
    * ambient/animal/bird6.wav
        * High pitch alarm call
    * ambient/animal/bird7.wav
        * Medium pitch song
    * ambient/animal/bird8.wav
        * High pitch call ending in song
    * ambient/animal/bird9.wav
        * High pitch song
    * ambient/animal/bird10.wav
        * High pitch song, rapid
    * ambient/animal/bird11.wav
        * High pitch chatter
    * ambient/animal/bird12.wav
        * Two delayed tweets
    * ambient/animal/bird13.wav
        * High pitch song, fast
    * ambient/animal/bird14.wav
        * Very distinct rapid chatter
    
