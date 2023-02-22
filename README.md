# Road Creator Pro Max

A flexible road creation package for Unity based on MCrafterzz/MarcusElg's now-undeveloped [Road Creator Pro](https://github.com/MarcusElg/Road-Creator-Pro).

## Help Needed!
I am not good at Unity's tool development, so I need some help with this.

## Current Goals
- [ ] Fix some UI/UX pet peeves
  - [x] Right-clicking (used to move the camera) resets the tool, and tool buttons aren't toggles
  - [ ] First time I started this project, icons didn't appear on buttons and I had to rely on tooltips
  - [ ] Adding points to existing roads is unintutitive, you have to select the point you want to add points to. While later it's become clear why it's done like that (to make it easier to add intersections), it's not communicated properly
  - [ ] Improve UX by combining the best things from other tools:
    - [ ] Road Creator Pro v1.x's drag to create intersection
    - [ ] [EasyRoads3D Pro v3](https://assetstore.unity.com/packages/tools/terrain/easyroads3d-pro-v3-469)'s custom intersections and drag from empty connection to create new roads
    - [ ] [Road Architect](https://github.com/FritzsHero/RoadArchitect)'s preset select
  - [ ] Redo icons so they don't look as ugly
  - [x] Click to select points instead of hover
    - [ ] Make this toggleable in settings
- [ ] Fix bugs
  - [ ] Tangents behave weirdly compared to other tools like [EasyRoads3D](https://assetstore.unity.com/packages/tools/terrain/easyroads3d-pro-v3-469) and [Road Architect](https://github.com/FritzsHero/RoadArchitect), getting all wobbly when adding points in a straight line after a turn when curved roads are on
  - [ ] Intersections glitch out when first connected (fixes itself as more points as added)
  - [ ] Manually-created intersections get mismatched sometimes
- [ ] Move away from Resources ([which aren't recommended by Unity anymore](https://docs.unity3d.com/2022.2/Documentation/Manual/BestPracticeUnderstandingPerformanceInUnity6.html)) as much as possible (maybe only use them for a master asset that contains all the links to Resources assets?)
- [x] Make this installable with Unity's Package Manager
- [ ] Refactor the code to make it more readable
- [ ] Add back proper URP/HDRP support