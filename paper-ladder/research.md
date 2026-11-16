# Paper Ladder's web page: research

Dani, 16 November 2026, for `media-page-research-web-page`. Drawn from: `media/web/copy.md` as delivered by Paige (commit `faae9a43`), the name **Paper Ladder** (`identity`, chosen 18 Oct), direction **B, Proof Sheet** (`design/tokens.json`, `docs/design-system/index.md`), the five store screenshots in `fastlane/screenshots/en-GB/`, and Vinod's answer on videos: the page shows the app's videos.

## The app, met as a stranger

- A calm daily word ladder: one puzzle a day, the same for everyone, and nothing to sign up for. The store subtitle is "A calm daily word ladder"; the promotional text ends "then put the phone down".
- Its look is its strongest asset and unlike any rival: no tiles, big Gloock capitals on ruled lines, proof paper with a grain, near-black ink and one proof red used only for pencil marks (rings, a strike, the ON PAR stamp). Every radius is 0. No people, mascots, scenery, photos or gradients (`design/tokens.json`, `imagery`).
- What exists to show: five real screens (Ladder, Home, Result, Practice, Your record), the app icon, the Play feature graphic, the paper grain, the pencil marks, the bundled fonts. No video is published yet (the launch video is being scripted, due 4 Dec), and the office's recording `launch-daily` has not been cut for the page.

## Pages looked at

Read in the studio's browser on 16 Nov. The browser pane returned no screenshots this run, so each page was read as text and its layout measured from the page itself (its height, and where the images, video and store links sit). Four more pages were tried and did not load here (SpellTower, TypeShift, Puzzmo, NYT Games) and were skipped.

| Page | What it does well | What I take for Paper Ladder |
|---|---|---|
| [Knotwords](https://playknotwords.com/) (word puzzle, Zach Gage and Jack Schlesinger) | Almost nothing on the page: a logo, a trailer, three store badges. The trailer is the whole pitch. One flat brand colour. | A game this simple to explain can let a video carry the top of the page (direction 3). Its weakness is one to avoid: the store links sit about 2,000 px down, below the first screen. |
| [Good Sudoku](https://www.playgoodsudoku.com/) (puzzle, same makers) | Seven rows, one idea each, every row a heading that starts the same way ("A Sudoku that…") beside one picture. It reads like a list of reasons. | The row-per-idea rhythm for "The three moments" (direction 3). Avoid its length (8,300 px) and its single store link at the very bottom. |
| [Weaver Games](https://wordwormdormdork.com/) (the best-known word ladder) | Opens as a dated front: the day's date, a greeting, today's puzzles with their start and target words set in letters. The page is today's edition. | The closest rival frames the day the way Paper Ladder does. Showing a real ladder, start word to target, in the first screen explains the game faster than a sentence (direction 1). |
| [Monument Valley](https://www.monumentvalleygame.com/) (ustwo games) | Picture-led: a full-width trailer first, a carousel of scenes, very few words, privacy links in the footer. | Lead with the product moving, keep the words short, legal links quiet at the foot. |
| [I Love Hue](https://i-love-hue.com/) (calm puzzle, Zut Games) | The same calm, adult tone as Paper Ladder. A one-line promise, a short paragraph, both store badges inside the first screen (about 640 px down), then four one-word reasons and an FAQ link. Short: 1,500 px. | Badges in the first screen; a page a stranger finishes in one scroll; a quiet voice. All three directions do this. |
| [Squaredle](https://squaredle.app/) (daily word game) | The page is the game: a tiny playable puzzle teaches the rule in five seconds. | Paper Ladder is app-only, so the nearest honest thing is a worked ladder in the page's own type (direction 1) or the recording playing in the phone (direction 2, in the build). |
| [Elevate](https://themindcompany.com/apps/elevate) (brain training, an Apple App of the Year) | The standard app page done cleanly: promise, call to action, "How it works" in three short blocks, then questions written as the headings people search for ("Is the … app free?"). | The three-step block and question-shaped FAQ headings, which Paige's copy already has. |

## What is standard and current for an app's page

- A first screen that shows the real product, with the store badges in it. A recording beats a still, and a still beats a mock.
- A strip of real screens; how it works in three steps; four to six short questions; privacy, terms and support links in the footer.
- Share images (Open Graph, 1200 x 630) so a pasted link shows the app. Each direction carries one made from the feature graphic.
- Fast and readable on a phone: one column, text at 16 px or more, 48 px targets, fonts and pictures served from the page itself. The directions use the app's own bundled Gloock and Instrument Sans files.

## What this means for Paper Ladder

1. **The look is the pitch.** No rival page looks like a printed puzzle column. All three directions are paper, ink, rules and the one red, with radius 0, and none adds a picture the app's imagery rule forbids.
2. **Show a ladder at once.** Cold to Warm in four steps is the app's own example (No. 13, the Result screenshot) and explains the game without words.
3. **Keep it short.** The calm games' pages are the short ones.
4. **A place for the video.** Each direction gives the launch video a place. Until it is published the place shows the feature graphic with a line saying so; the build will not ship that line.

## Tools considered

- Phone frames: Apple's bezel (`bin/bezels`, iPhone 17 Pro Max, silver, unaltered) over the store screenshots, which are its screen size. Chosen over a drawn frame, as the rules require.
- Screens: the store screenshots only. No screen is drawn or mocked. The worked ladder in direction 1 is page typography in the app's type, captioned as an example, not a picture of a screen.
- FLUX, Wan and stock were considered and not used: the app's imagery rule allows no people, scenery or photos, and the page needs none.
- Icons: none needed beyond a play mark.

## Open points for the build

- **The second moment has no picture of its own.** Paige's words describe a refused step and a hint; the five store screenshots show neither, so the directions use the Ladder screen there. The build should take stills (or a clip) from the office's recording scenes `rejected-step` and `hint`.
- **A word in the copy differs from the app.** `copy.md` says "Result and streak" and "your streak"; the app says "run", never "streak" (`media/capture/scenes.json`). The directions keep Paige's words as written; this is hers to settle before the build.
- **A moving hero.** In direction 2 the phone can play the `launch-daily` recording, muted and looping, in place of the still, once it is fetched and cut.
- The closing line "Today's ladder is waiting." (directions 2 and 3), "Free on iPhone and Android. No account." under it (direction 2), the video heading "One ladder, start to finish." (direction 1) and the strip's captions (direction 2) are mine, not Paige's, and are hers to keep or replace.
- The page is drawn in the light theme only, like the store screenshots.

## Sources

- https://playknotwords.com/
- https://www.playgoodsudoku.com/
- https://wordwormdormdork.com/
- https://www.monumentvalleygame.com/
- https://i-love-hue.com/
- https://squaredle.app/
- https://themindcompany.com/apps/elevate
