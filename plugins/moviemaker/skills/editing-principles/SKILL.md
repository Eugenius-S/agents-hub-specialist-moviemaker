---
name: editing-principles
description: Principles of editing and motion graphics for short ad and product videos (15-35 s, 16:9 and 9:16) with numbers: rhythm and cuts, the hook, interface demo (cursor, typing, scale), animation curves and durations, subtitles and safe zones, sound, the ending, formats. Use when you edit, revise or review such a video.
---

# Principles of editing and motion graphics for ad videos

Videos of 15-35 s, 16:9 and 9:16, 30 fps: UGC and product demos (a plugin, a site, an app). Where they differ, the owner's corrections win: his words outrank the set.

Source labels:
- [G] Google ABCD (5000+ TrueView videos, Brand Lift, correlation);
- [YT] YouTube Shorts ads help;
- [T] TikTok Ads, Creative best practices;
- [M] Meta, Safe Zone for Stories and Reels;
- [MD] Material Design motion;
- [NF] Netflix Timed Text Style Guide;
- [C] frame-by-frame analysis of a smoothness reference, a Microsoft Copilot video (https://youtu.be/ACiJFw5Rr6k);
- [R] client corrections on real videos (checked in practice);
- [P] general motion design practice. There is no single study under it: it is a guide, not a law.

## 1. Rhythm and cuts

1. In the first 5 s use more than two shots, that is at least 2 cuts or changes of scale [G].
2. After that change the shot, scale or on-screen action every 2-4 s. One scene carries one idea; after an element lands, hold a pause of 0.3-0.5 s [C].
3. There must be no silence or empty stretches: cut scrolling without speech. Content sets the length; do not stretch to 30 s [R].
4. Cut on action: place the cut in the middle of a gesture, click or scroll, not after it ends [P].
5. Bring the sound in 4-8 frames before the picture (J-cut). Then the cut does not chop the speech and is not heard [P].
6. Cut breath pauses out of speech. Under speech keep a continuous room tone taken from the pauses of the same clip: digital silence between lines is heard as a "dropout" [R].

## 2. The first 1-3 seconds (the hook)

7. Show the main message or the product in the first 3 s. According to TikTok, more than 63% of the videos with the highest CTR are made this way [T].
8. The brand or product must appear in the first 5 s and stay in the frame to the end [G].
9. In a demo the product opens at once. Clicking the icon and launching it belong only to the ending [R].
10. If the video has a person, start with them in a close-up. The heroine is in the frame only in the hook, after that her voice runs as voice-over [G][R].
11. The first frame must be bright and contrasty, with no logo splash and no fade from black [G][P].

## 3. Interface demo

12. Take every screen as it is in Figma, one to one. Do not draw a screen that is not in Figma. Take numbers and names from the site or the catalog, including those baked into a PNG [R].
13. The camera follows the words: move to a block at the moment it is spoken about. Enter full screen at once, without zooming out. Scroll the final site briskly and only down [R].
14. Cursor: a 14-18 px dot or an arrow. A curved path takes 0.5-0.7 s. On click the cursor shrinks, the button fills in about 0.2 s, the transition goes after about 0.3 s [C].
15. Typing text: 30-40 characters per second, with a soft edge. Do not speak the query aloud: it is visible in the search field [C][R].
16. Hover: highlight in 100-150 ms. Press: scale 0.96-0.97 for 2-3 frames, then back [MD][P].
17. Scale: the element being spoken about takes at least a third of the frame width. In 9:16 crop it separately and do not shrink the whole desktop [P].
18. Show a side feature after the main action, on the word "by the way". The insertion point sits opposite the plugin window, the item flies from the window to the target, the window does not cover the target [R].
19. Change content through a "rack focus": the old one blurs to about 12 px and fades in 0.3 s, the new one comes out of the blur [C].
20. Put only the shadows that are in the layout. Do not add your own shadows under a dragged item or under the site [R].

## 4. Motion graphics

21. Move the interface with ease-out and no spring. Containers: cubic-bezier(0.16, 1, 0.3, 1) over 0.5-0.7 s. Small objects: cubic-bezier(0.2, 0, 0, 1) over 0.15-0.3 s. Linear only for constant drift [C].
22. Durations on mobile: enter 225 ms, exit 195 ms, full-screen transition 375 ms. Anything over 400 ms looks slow. Make the exit shorter than the entrance [MD].
23. A fade is always shorter than the movement: 80-150 ms for a movement of 200-600 ms [C].
24. Group stagger: 2-4 frames between elements (about 70-130 ms at 30 fps). The one nearest the source or the largest lands first [C].
25. Overshoot only on "pop-ups" such as subtitles and badges: 3-9% and back in 0.1-0.2 s. Example: a subtitle pop-in, Scale 88→103→100 at 0 / 0.067 / 0.133 s. Interface windows and cards have no overshoot [R][C].
26. Turn on motion blur for fast fly-ins and cuts: shutter angle 180°, 2-4 frames of smear. Slow drift does not need it [C][P].
27. Build depth without 3D from three layers: sharp; blur 3-4 px with 70% contrast; blur 8-12 px with 40% contrast. Parallax on a pan 1 : 0.6 : 0.3 [C].
28. Open a plugin window like this: scale 0.96→1, blur 6→0, then the shadow. Order of appearance: the container, then the text, then the icon [C].

## 5. On-screen text and subtitles

29. Subtitles are required: people watch without sound. Text supports the speech and does not argue with the picture, one message at a time [G][M].
30. Subtitles are word by word, 1-3 words per chunk. Speed no higher than 20 characters per second, a line up to 42 characters, no more than 2 lines, a chunk holds at least 0.83 s (5/6 s) [NF][R].
31. Font Inter SemiBold: 60 px in 9:16, 64 px in 16:9. Set the word timing by the energy onset; whisper puts it before the sound. After any cut edit, check the text against the speech [R].
32. In 9:16 keep text and CTA inside the frame x 120-900, y 270-1250 on a 1080×1920 canvas. This is the intersection of the Meta safe zones (top 14%, bottom 35%, sides 6%) and TikTok (top 240, bottom 660, sides 120 px, a column of buttons on the right) [M][T].

## 6. Sound and voice-over

33. Sound is always needed: in Shorts music or voice gives more than 20% on conversions [YT][T].
34. One voice for the whole video. If you regenerated the voice, regenerate the inserts made with it too, for example a separate clip with the brand name [R].
35. Duck the music under speech by 10-15 dB. Final loudness -14 LUFS, true peak no higher than -1 dBTP [P].
36. The on-screen action matches the word: the color changes on the word "color", the camera goes to the photo on "Photos". Put the click and whoosh SFX on the event frame, with no lead [R][P].

## 7. Ending and CTA

37. Repeat the call to action through the video, more directly toward the end. Put the ask after the context is shown [G].
38. The closing card comes right after the last line, with no pause: the icon together with the name, the first badge after about 0.47 s, the second after about 0.62 s. Hold it 2-3 s to the end of the video [R].
39. In Shorts the CTA headline is up to 40 characters, the description up to 90 [YT].

## 8. Formats 16:9 and 9:16

40. Build 9:16 as a separate comp, not a crop of 16:9: a crop leaves 32% of the width. The flow is the same in both formats: in 9:16 the site is on the left, the plugin on the right over it, and the site stays a desktop layout [R][P].
41. If you hand over only 16:9, Shorts shows it with blurred bars at the top and bottom, and vertical videos work better. For Reels, TikTok and Shorts you need a native 9:16, resolution from 720p, better 1080×1920 [YT][T].

## 9. What holds the viewer (performance)

42. Watch three metrics: the share who watch to 3 s (the hook), the share who watch to 15 s or to the end (retention), and CTR. Fix a weak hook with the first 3 s, weak retention with the middle [P].
43. Every 5-7 s give a new reason to keep watching: a new screen, a result, "by the way". Show the "before and after" result before explaining how it was got [P].
44. The video looks like native content of the platform, not like a TV ad. Benefit first, then the brand large [YT][G].

Not verified: durations and curves marked [C] were taken frame by frame with an accuracy of ±1 frame (42 ms at 24 fps). Numbers marked [P] are practitioners' guides. The Google and TikTok data are correlational; they do not prove the cause.
