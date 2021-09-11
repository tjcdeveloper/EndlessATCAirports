# Munich Airport "Franz Josef Strauß" in the south of Germany.

Second hub of Lufthansa, offering many international and intercontinental routes. Munich has two runways, equally used for takeoffs and landings.

![Image of EDDM airport in EndlessAtc](images/eddm1.png)

## Some tips on how it can be played

- The approaches are meant to help coordination during high traffic. During low traffic, controllers usually skip the transitions completely and vector to final, sometimes giving directs to waypoints.
- Departures are cleared to FL70, meaning that they might have to pass below approaching traffic following the transitions. This is one reason why vectoring arriving planes can be handy, as you can keep more space between arrivals and departures.
- Maximum Skill Cap 16 works fine so that some planes can still depart between the arrivals.

## Already working:
- most SIDs exist
- various transitions and approach waypoints
- real airspaces
- pre-covid airlines

## TODOs, help wanted!
- general aviation traffic missing, maybe government traffic
- special cargo traffic missing, for example antonovs
- airline traffic frequency balance probably not ideal
- check if airspace height restrictions make sense
- check if some SIDs can be removed because they are barely used in real life
- check if arrival entry directions make sense, same for descent altitude

## Changelog

### v1.4

- reduce ceiling to make departure diversions less likely
- add radar name for arriving traffic, added handover frequencies for departures and arrivals (tower)
- remove obaxa 6s departure route that is not used for jet aircraft

### v1.3

- fix wrong heading on BETOS arrival

### v1.2

- added rwy configs
- use new feature of v4.4.0: stars now end on heading like in real life. No more automatic approaches

### v1.1

- Planes now arrive with clearance to ROKIL, LANDU, BETOS or NAPSA, more like in real life where MIQ/OTT are pretty much never used
- Moved transition altitude to 6000ft, to make transition more realistic for arriving traffic. This is not 100% realistic, but the game does not offer a transition level
- Added new Commercial jets and cargo airlines, also added some airlines I forgot
- Added some explanations on how to play to readme
- Overwriting default speed restriction set by the game, so that planes don't slow down automatically anymore
- Removed OBI VOR because it was next to a waypoint, so it was more annoying than helpful
- Removed unused default sids

### v1.0

Initial version

**Feedback or improvements? Create an issue or contribute directly: https://github.com/AdamJCavanaugh/EndlessATCAirports#contributing**. This airport uses no source file to generate stuff, so the [EDDM.txt](EDDM.txt) file can be edited as is.