# rosegard, 1.18 version

an experimental modpack in the mostly sorta prototype stage.  there are no quests, & that's intentional; the only documentation is this readme file.

_n.b.: **i'm putting this together for me first and foremost** and i'm making it public in case anyone with similar likes happens to enjoy the files here.  it's provided in the hope that you might find something here useful **but without any support** and also with no warranty, etc., etc._

design goals:

- gardening
- vibrant world
- player fulfilment
- non-frustration
- gameplay that's slow but is gentle (making things grow) rather than grindy
- things to tinker with, but not frustratingly puzzle-gated progression
- a nether that's foreboding due to its sheer overgrown density above all else
- it would be nice to rid ourselves of the end dimension entirely but i think that's relatively hard to implement without breaking eg., M&A progression

design non-goals, things i don't care about:

- "good balance" by multiplayer-server standards, or by vanilla purist standards, or by "expert mode pack" standards
- only one mod for one function!!1!
- realism

gotchas, alterations, tips & tricks:

- the nether coordinate scaling you may be used to from vanilla isn't a thing here.  implied: nether transportation is no faster than the same transportation in the overworld.
- portable storage items can be stored "underneath" the surprisingly substantial satchel, but can't be stored in each other (and you can't put satchels in other portable storage items)
    - if you find an exception that's probably a bug
- occultism is the intended route for "searchable remote storage" in this pack *(we'll see how that works out for us...)*

## development/configuration references and notes

- if we encounter issues with occultism rituals that require animals to be sacrificed not working with genetic animals animals, see: https://github.com/klikli-dev/occultism/issues/486 and just datapack in the relevant tags
- future milestones could include porting the dyntrees compat mods for atmospheric and upgrade aquatic to 1.18 / replicating the work done for those mods on 1.18
- future milestones could include improving certain textures
    - pam's
    - vibrant journeys
- should try to see if adding starlight would speed up worldgen/chunk loading without causing issues
- difficult future milestones could include trying to fix Mana and Artifice's village system (tho unless they port to 1.19 instead of releasing 2.0 on 1.18, itll presumably be officially fixed later)
- difficult, high-effort future milestones could include backporting some features from 1.19+ hex casting