# Road Creator Pro Max

A flexible road creation package for Unity based on MCrafterzz/MarcusElg's now-undeveloped [Road Creator Pro](https://github.com/MarcusElg/Road-Creator-Pro).

## Help Needed!
I am not good at Unity's tool development, so I need some help with this.

## Current Goals
- [ ] Fix some UI/UX pet peeves
  - [x] Right-clicking resets the tool, and tool buttons aren't toggles
  - [ ] First time I started this project, icons didn't appear on buttons and I had to rely on tooltips
  - [ ] Adding points to existing roads is unintutitive, you have to select the point you want to add points to. While later it's become clear why it's done like that (to make it easier to add intersections), it's not communicated properly
  - [ ] Intersections don't work the way they're advertised in the promo video on itch.io in 2.x, and it's really cumbersome
- [ ] Fix bugs
  - [ ] Curved roads behave weirdly compared to alternative tools like [EasyRoads3D](https://assetstore.unity.com/packages/tools/terrain/easyroads3d-pro-v3-469) and [Road Architect](https://github.com/FritzsHero/RoadArchitect), getting all wobbly when adding points in a straight line
  - [ ] Intersections glitch out when first connected (fixes itself as more points as added)
  - [ ] Manually-created intersections get mismatched sometimes
- [ ] Move away from Resources ([which aren't recommended by Unity anymore](https://docs.unity3d.com/2022.2/Documentation/Manual/BestPracticeUnderstandingPerformanceInUnity6.html)) as much as possible (maybe only use them for a master asset that contains all the links to Resources assets?)
- [ ] Make this installable with Unity's Package Manager
- [ ] Refactor the code to make it more readable