# Eonweld

### Shape a world. Watch its people make history.

Eonweld is a playable god game about land, intelligent life, and consequences across centuries. Draw a mountain range, open an ocean, bring a new people into the world, and watch cultures migrate, trade, fight, remember, and forget.

**Created with AI, directed and play-tested by Nick Mokashi.** This repository is a showcase of the local game, not a source-code or downloadable game release.

## Actual gameplay

These are unaltered screenshots captured while playing a separate test world. No concept art or simulated interface images. At year 1,049, this world held 145,766 people in 93 towns, including humans and dwarves. It had already experienced regional terrain changes, permanent flooding and disease.

<table>
<tr>
<td width="50%"><img src="assets/living-world.png" alt="Eonweld's living world at year 1049, with coastlines, towns, routes and permanent water" width="440"></td>
<td width="50%"><img src="assets/people-closeup.png" alt="A close view of population groups around Mirelanlia and neighbouring towns" width="440"></td>
</tr>
<tr><td><strong>A world with a past.</strong> Towns and routes grow across the land you shape.</td><td><strong>People on the map.</strong> In this close view, one figure represents up to 200 people. Green figures mark sickness. The in-game key changes with zoom and density.</td></tr>
</table>

## What you can do

- **Mold whole regions.** Raise, lower or flatten land and water using broad strokes or rectangular selections. Draw mountain ranges and carve oceans, with an area and power preview before applying.
- **Release lasting floods.** Pick their scope and depth, see the price, and leave permanent water behind. Raise the basin again to reclaim it.
- **Create intelligent peoples.** Name and place humans, elves, dwarves, orcs and giants. These five species differ in visible proportions, food needs, growth, disease resistance and combat. A suggested-site marker makes placement easier.
- **Design named diseases.** Choose breath, water or close-contact spread, mortality, contagiousness and duration. Disease follows inhabited land, migration and trade. Each outbreak has its own direct-death total and a recorded ending.
- **Watch migration and conquest.** Population groups and marching trails represent real transfers. Battle formations show opposing forces and the winner; conquered towns change ownership.
- **See societies change their land.** Crowding, extraction and war strip vegetation and exhaust soil. Stewardship and abandonment allow recovery. Long-damaged slopes erode into lowlands, changing height and drainage. Vegetation is visible on the ordinary map, with significant changes recorded in the chronicle.

<table>
<tr>
<td width="50%"><img src="assets/disease-controls.png" alt="Choosing a disease name, transmission route, annual mortality, spread and infectious duration" width="440"></td>
<td width="50%"><img src="assets/voice-settings.png" alt="Optional ElevenLabs key and cloned voice ID fields, three-minute announcement spacing, and a 1000-character spending cap" width="440"></td>
</tr>
<tr><td><strong>Your disease, your settings.</strong> Outcomes depend on the people and connections it reaches.</td><td><strong>Your voice, optional.</strong> Announcements start off. The game works without either API service.</td></tr>
</table>

## History you can inspect

The chronicle stores observed events and their causes. What actually happened stays distinct from what a culture remembers. Within a rules version, the same seed and actions replay the same history. Saved worlds continue across updates from a preserved rules boundary.

Landscape priorities are a game abstraction based on institutions, inequality, population pressure and recent war. They are not an AI judgment of a species or culture. Figures aggregate people; battle formations illustrate recorded outcomes rather than individually simulated soldiers.

## Optional AI and voice

- **Anthropic:** add your own API key in Settings & keys → Narrator key for optional tellings. Ordinary play needs no model calls.
- **ElevenLabs:** enter your own API key and existing cloned voice ID under Voice announcements. There is also a device voice option that uses no ElevenLabs credits.
- Announcements use short templates of actual world events, with no extra AI writing request. Defaults are major events at most once every three minutes, at most 320 characters per update, and a hard 1,000-character allowance shared across the server run.
- Replay uses cached audio. Failed requests are counted conservatively and do not automatically retry. Actual credit charges depend on the provider plan and voice.
- Keys and cached speech stay in server memory; they are not written into world saves. Re-enter keys after closing the game server.

## Release status

Local playable build, rules **12.1**, September 23, 2026. This showcase is prepared for review; source-code publication and a public game download are separate future decisions. No API credentials, player save files, or private development records are included here.

Provider connections were verified with local test doubles to avoid paid calls. Live cloned-voice quality has not been tested with a real key.
