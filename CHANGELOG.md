## [2.5.0-dev.3.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.5.0-dev.3.fork.2) (2026-11-28)

### ✨ New Features

* **YouTube - Seekbar:** Add "Enable smooth seekbar" setting (#5532) ([b772935cc](https://github.com/0xAnasEzz/morphe-patches/commit/b772935cc))

### 🐛 Bug Fixes

* **YouTube - Hide layout components:** "Hide video labels" does not hide the labels of the videos on 20.26, such as "Auto-dubbed" ([13e64613f](https://github.com/0xAnasEzz/morphe-patches/commit/13e64613f))
* **YouTube:** "Replay slower" swipe gesture interferes with precise seeking (#5492) ([65b4dcf32](https://github.com/0xAnasEzz/morphe-patches/commit/65b4dcf32))
* **Spoof video streams:** Settings screen stays in memory after it is closed (#5518) ([5e2170396](https://github.com/0xAnasEzz/morphe-patches/commit/5e2170396))

## [2.5.0-dev.3.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.5.0-dev.3.fork.1) (2026-11-28)

### ✨ New Features

* **YouTube - Miniplayer:** Add "Continue watching on startup" setting (#5436) ([28c833deb](https://github.com/0xAnasEzz/morphe-patches/commit/28c833deb))
* **YouTube:** Add `Open shared links` patch (#5482) ([aee997385](https://github.com/0xAnasEzz/morphe-patches/commit/aee997385))
* **YouTube:** Add `Restore old Cast behavior` patch (#5441) ([cb4edf2f9](https://github.com/0xAnasEzz/morphe-patches/commit/cb4edf2f9))

### 🐛 Bug Fixes

* **YouTube - Restore old Cast behavior:** Minimize the player when swiped down while casting (#5510) ([2fe8d244e](https://github.com/0xAnasEzz/morphe-patches/commit/2fe8d244e))
* **YouTube - Ambient mode:** Enhanced Ambient mode shows no light around the player with a theme color (#5496) ([f2c047ef7](https://github.com/0xAnasEzz/morphe-patches/commit/f2c047ef7))

## [2.5.0-dev.2.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.5.0-dev.2.fork.2) (2026-11-28)

### ✨ New Features

* **YouTube - Video delay:** Support negative video delay (#5475) ([b17c1cdb4](https://github.com/0xAnasEzz/morphe-patches/commit/b17c1cdb4))
* **YouTube - Download post images:** Download images in the quality they were uploaded in ([f481b3e9b](https://github.com/0xAnasEzz/morphe-patches/commit/f481b3e9b))
* **Reddit:** Add `High-contrast navigation buttons` patch (#5460) ([fd975d475](https://github.com/0xAnasEzz/morphe-patches/commit/fd975d475))
* **Reddit:** Add `Create button in communities` patch (#5457) ([5bc3e6601](https://github.com/0xAnasEzz/morphe-patches/commit/5bc3e6601))

### 🐛 Bug Fixes

* **YouTube - Feed card layout:** "Default" gives the cards of the server the style of the converted cards, without their rounded bottom corners, instead of only removing the blurred avatar background ([2048bd754](https://github.com/0xAnasEzz/morphe-patches/commit/2048bd754))
* **YouTube / YouTube Music - Glass menus:** Rows of choice dialogs that are narrower than half of the dialog keep an opaque background, such as "Double-tap to seek" ([70976c9f6](https://github.com/0xAnasEzz/morphe-patches/commit/70976c9f6))
* **YouTube - Restore old video action bar:** "Classic Two-Rows" still shows one row on 20.26 while the template cache has never had the channel bar ([50519a9fe](https://github.com/0xAnasEzz/morphe-patches/commit/50519a9fe))
* **YouTube - Theme:** The status bar and the navigation bar of the Shorts player stay black or light instead of the dark theme color, such as with the glass navigation bar ([49ee46c05](https://github.com/0xAnasEzz/morphe-patches/commit/49ee46c05))
* **YouTube - Theme:** The ambient mode light below the player ends at a hard black edge with a dark theme color on 21.47 ([c5a3fac62](https://github.com/0xAnasEzz/morphe-patches/commit/c5a3fac62))
* **YouTube - Feed card layout:** Give every card the style of the converted cards, so the cards show no light arcs, and add the card layouts with the avatar glow ([51d3bddc2](https://github.com/0xAnasEzz/morphe-patches/commit/51d3bddc2))
* **YouTube - Theme:** Fade at the end of the collapsed description uses the theme background color instead of being removed ([2c31fe4c8](https://github.com/0xAnasEzz/morphe-patches/commit/2c31fe4c8))
* **YouTube Music - Third-party lyrics:** Prevent lyrics panel from scrolling past the footer (#5476) ([c3d3fd72c](https://github.com/0xAnasEzz/morphe-patches/commit/c3d3fd72c))
* **Reddit - Glass navigation bar:** Keep the selected pill and buttons centred in the glass at any height (#5461) ([9a5b7aa21](https://github.com/0xAnasEzz/morphe-patches/commit/9a5b7aa21))
* **Reddit - Glass navigation bar:** Gap between the top bar buttons and the tab capsule (#5459) ([0b6f5f4c2](https://github.com/0xAnasEzz/morphe-patches/commit/0b6f5f4c2))
* **YouTube Music - Downloads:** Downloaded songs show as videos with a black player background ([59b868887](https://github.com/0xAnasEzz/morphe-patches/commit/59b868887))

## [2.5.0-dev.2.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.5.0-dev.2.fork.1) (2026-11-27)

### ✨ New Features

* **YouTube - Custom branding:** 🍴 Add 'Music dark' app icon ([414f0493f](https://github.com/0xAnasEzz/morphe-patches/commit/414f0493f))
* **YouTube - Custom branding:** 🍴 Add 'Play dark' app icon ([ec23c97f7](https://github.com/0xAnasEzz/morphe-patches/commit/ec23c97f7))
* **YouTube - Hide layout components:** Add "Hide 'Privacy Policy' 'Terms of Service' footer" setting ([d0fc54d45](https://github.com/0xAnasEzz/morphe-patches/commit/d0fc54d45))
* **YouTube - Custom branding:** Add the launcher icons of YouTube 21.47 ([3bcdb5338](https://github.com/0xAnasEzz/morphe-patches/commit/3bcdb5338))
* **YouTube - Shorts autoplay:** Add Autoplay toggle to the Shorts player menu (#5448) ([2bce34cbd](https://github.com/0xAnasEzz/morphe-patches/commit/2bce34cbd))
* **Reddit - Glass navigation bar:** Frosted glass for the top bar buttons and tabs (#5433) ([79bd6b9de](https://github.com/0xAnasEzz/morphe-patches/commit/79bd6b9de))
* **Reddit - Settings:** Show only sub-pages on the root settings page (#5427) ([cafc21bf4](https://github.com/0xAnasEzz/morphe-patches/commit/cafc21bf4))
* **Reddit - Glass navigation bar:** Top bar with tabs is see-through once the feed scrolls (#5429) ([2859f757b](https://github.com/0xAnasEzz/morphe-patches/commit/2859f757b))

### 🐛 Bug Fixes

* **YouTube - Playback speed:** App crashes when tapping the playback speed overlay button with the old speed menu ([3387325cb](https://github.com/0xAnasEzz/morphe-patches/commit/3387325cb))
* **YouTube - Feed card layout:** Remove the blurred avatar background at the bottom of the cards, which shows light arcs at its corners, and the tinted background of the converted cards ([aa6b6cbd1](https://github.com/0xAnasEzz/morphe-patches/commit/aa6b6cbd1))
* **Custom branding:** Show icon gradients on the HyperOS 4 launcher ([ba41adab4](https://github.com/0xAnasEzz/morphe-patches/commit/ba41adab4))
* **YouTube - Snackbar:** The text of a custom snackbar stays dark when it is not colored when created, such as "Comment added" in Shorts on 21.47 ([420a3355a](https://github.com/0xAnasEzz/morphe-patches/commit/420a3355a))
* **YouTube - Open post images in fullscreen:** Fix crash when a feed has a post with images ([9c098c17e](https://github.com/0xAnasEzz/morphe-patches/commit/9c098c17e))
* **Reddit - Glass navigation bar:** Search button is no longer drawn over bottom sheets (#5428) ([5ccb244e0](https://github.com/0xAnasEzz/morphe-patches/commit/5ccb244e0))

## [2.4.0-fork.3](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-fork.3) (2026-11-27)

### ✨ New Features

* **Reddit - Settings:** Split Layout into sub-pages (#5416) ([eb48b027d](https://github.com/0xAnasEzz/morphe-patches/commit/eb48b027d))

### 🐛 Bug Fixes

* **YouTube - Theme:** The fade at the end of the collapsed description shows as a dark band with a custom theme color ([60bef1ad5](https://github.com/0xAnasEzz/morphe-patches/commit/60bef1ad5))
* **YouTube - Feed card layout:** "Default" adds the spacing and the rounded corners of the cards to the cards of a newer A/B test, instead of showing them as YouTube sends them ([57ab1de40](https://github.com/0xAnasEzz/morphe-patches/commit/57ab1de40))
* **YouTube / YouTube Music - Glass menus:** Bottom sheets are not drawn as glass and a "R.id.design_bottom_sheet is null" toast shows when the patch class loads before the app context is set ([fb347595c](https://github.com/0xAnasEzz/morphe-patches/commit/fb347595c))

## [2.4.0-fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-fork.2) (2026-11-27)

### ✨ New Features

* **YouTube - Hide status bar:** Add tabletop-only mode for foldable phones (#5379) ([778532562](https://github.com/0xAnasEzz/morphe-patches/commit/778532562))
* **Reddit - Glass navigation bar:** Add "Tabs in top bar" setting with tab pills (#5411) ([f379c0edc](https://github.com/0xAnasEzz/morphe-patches/commit/f379c0edc))
* **Reddit - Settings:** Add search to the Morphe settings (#5407) ([7b804f7b6](https://github.com/0xAnasEzz/morphe-patches/commit/7b804f7b6))
* **YouTube - Return YouTube Dislike:** Show dislikes in the 'Video details' section of the description (#5404) ([20acb1bb4](https://github.com/0xAnasEzz/morphe-patches/commit/20acb1bb4))
* **YouTube - Hide layout components:** Add "Hide auto-generated chapters" setting (#5400) ([2c91f3bad](https://github.com/0xAnasEzz/morphe-patches/commit/2c91f3bad))
* **YouTube - Captions:** Add "Default" option to "Auto captions visibility" ([05e15e123](https://github.com/0xAnasEzz/morphe-patches/commit/05e15e123))

### 🐛 Bug Fixes

* **YouTube - Restore old video action bar:** "Classic Two-Rows" shows one row after the app starts without the channel bar in its template cache, such as on 20.26 ([2f9750042](https://github.com/0xAnasEzz/morphe-patches/commit/2f9750042))
* **YouTube - Theme:** The header of the Shorts shelf in the home feed keeps a gray background when the feed has no cards ([c69e95b9e](https://github.com/0xAnasEzz/morphe-patches/commit/c69e95b9e))
* **YouTube - Theme:** The watch page is black instead of the dark theme color on 21.47 ([e14a2ab87](https://github.com/0xAnasEzz/morphe-patches/commit/e14a2ab87))
* **YouTube - Glass menus:** A dark panel stays inside the glass of menus shown over a video, such as the dropdown of the Shorts header ([290360620](https://github.com/0xAnasEzz/morphe-patches/commit/290360620))
* **YouTube - Snackbar:** The text of a custom snackbar stays dark when the message has no color of its own, such as "Comment added" in Shorts ([d889f1491](https://github.com/0xAnasEzz/morphe-patches/commit/d889f1491))
* **YouTube - Comment search:** Parts of the shown comments are hidden while searching, such as the like count ([b38a3e233](https://github.com/0xAnasEzz/morphe-patches/commit/b38a3e233))
* **YouTube - Hide Shorts components:** The header of a shelf with only Shorts stays in the modern home feed layout, such as "Breaking news" ([33fb24c41](https://github.com/0xAnasEzz/morphe-patches/commit/33fb24c41))
* **YouTube Music - Sonos Cast:** Stop linking the phone volume to the speaker (#5403) ([c68a7cd31](https://github.com/0xAnasEzz/morphe-patches/commit/c68a7cd31))
* **YouTube Music - Third-party lyrics:** Show why the AI connection test failed and use the latest Gemini model (#5394) ([f727b66ff](https://github.com/0xAnasEzz/morphe-patches/commit/f727b66ff))
* **YouTube - Open post images in fullscreen:** Images of posts open the posts feed in the feed cards (#5384) ([6fa7b4385](https://github.com/0xAnasEzz/morphe-patches/commit/6fa7b4385))

## [2.4.0-fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-fork.1) (2026-11-26)

### ✨ New Features

* **Reddit - AutoModerator comments:** Also hide bot and pinned moderator comments (#5364) ([b03d4cf04](https://github.com/0xAnasEzz/morphe-patches/commit/b03d4cf04))
* **Reddit - Glass navigation bar:** Add "Glass strength" setting (#5363) ([3bf57bf4c](https://github.com/0xAnasEzz/morphe-patches/commit/3bf57bf4c))
* **Reddit - Glass navigation bar:** Add "Search button" setting (#5360) ([17fe42310](https://github.com/0xAnasEzz/morphe-patches/commit/17fe42310))
* **Spoof video streams:** Update yt-dlp-ejs (#5369) ([6e1b8d475](https://github.com/0xAnasEzz/morphe-patches/commit/6e1b8d475))
* **YouTube - Hide ads:** Hide YouTube Premium exclusive videos ([50e48c9ab](https://github.com/0xAnasEzz/morphe-patches/commit/50e48c9ab))

### 🐛 Bug Fixes

* **YouTube - Voice over translation:** Show a message when the video has no captions ([a34a3409e](https://github.com/0xAnasEzz/morphe-patches/commit/a34a3409e))
* **YouTube - SponsorBlock:** New segment is marked at the first frame such as at 00:00.040, instead of the start of the video after a seek to the start, such as with the rewind button (#5355) ([bdb64f945](https://github.com/0xAnasEzz/morphe-patches/commit/bdb64f945))
* **YouTube - Comment search:** Scrolling the comments lags while searching (#5356) ([97a45eb82](https://github.com/0xAnasEzz/morphe-patches/commit/97a45eb82))
* **Reddit - Show flairs in home feed:** Flairs are shown twice for classic text posts in subreddit feeds ([92d8f9e06](https://github.com/0xAnasEzz/morphe-patches/commit/92d8f9e06))
* **YouTube Music - Third-party lyrics:** Stop AI connection test from failing with a valid key ([743bed7ee](https://github.com/0xAnasEzz/morphe-patches/commit/743bed7ee))
* **YouTube - Feed card layout:** "Default" removes the spacing between the videos of the lists without the cards of a newer A/B test, such as the Subscriptions feed (#5353) ([abe377f45](https://github.com/0xAnasEzz/morphe-patches/commit/abe377f45))
* **YouTube Music - Android Auto:** Home loads with missing sections or wrong layout (#5325) ([f834703c0](https://github.com/0xAnasEzz/morphe-patches/commit/f834703c0))
* **YouTube Music - Downloads:** Fix seeking and duration of downloaded songs (#5352) ([c7c81b899](https://github.com/0xAnasEzz/morphe-patches/commit/c7c81b899))
* **YouTube - Keyword content filter:** Check the channel when filtering “Latest from” Shorts in search (#5248) ([59bdab655](https://github.com/0xAnasEzz/morphe-patches/commit/59bdab655))
* **YouTube - Return YouTube Username:** Handles are not replaced in the feed cards ([e5c256863](https://github.com/0xAnasEzz/morphe-patches/commit/e5c256863))
* **YouTube - Hide layout components:** "Hide 'Members only' chip" leaves an empty space in the channel filter bar and does not select the 'Public' chip ([63578d123](https://github.com/0xAnasEzz/morphe-patches/commit/63578d123))

### 🚀 Updated App Support

* **Reddit:** Add experimental support for `2026.48.0` (#5358) ([d0b92b1c9](https://github.com/0xAnasEzz/morphe-patches/commit/d0b92b1c9))

## [2.4.0-dev.14.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.14.fork.2) (2026-11-26)

### 🐛 Bug Fixes

* **YouTube - Spoof video streams:** Truncated base64 response and reset warm-up page address ([db5649bec](https://github.com/0xAnasEzz/morphe-patches/commit/db5649bec))

## [2.4.0-dev.14.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.14.fork.1) (2026-11-25)

### ✨ New Features

* **Reddit - Glass navigation bar:** Add "Bar position" and "Show labels" settings (#5339) ([aa46fca7a](https://github.com/0xAnasEzz/morphe-patches/commit/aa46fca7a))
* **Reddit:** Add `Settings in sidebar` patch (#5334) ([ff1b9d9cd](https://github.com/0xAnasEzz/morphe-patches/commit/ff1b9d9cd))
* **YouTube - Navigation bar:** Support "Account switcher shortcut" on versions before 21.30 ([0d3e6d650](https://github.com/0xAnasEzz/morphe-patches/commit/0d3e6d650))
* **YouTube - Hide status bar:** Add "Keep player below display cutout" (#5328) ([eb4cafcba](https://github.com/0xAnasEzz/morphe-patches/commit/eb4cafcba))
* **YouTube - Fullscreen video scale:** Add "Fullscreen video alignment" setting (#5307) ([4873b5a2c](https://github.com/0xAnasEzz/morphe-patches/commit/4873b5a2c))

### 🐛 Bug Fixes

* **YouTube - Glass menus:** Menus shown as a dropdown, such as the dropdown of the Shorts header, are not drawn as glass ([d8fe33490](https://github.com/0xAnasEzz/morphe-patches/commit/d8fe33490))
* **YouTube - Navigation bar:** Subscriptions button is missing when YouTube moves it to a tab of Home and sends the navigation buttons without labels (#5346) ([e3c8b4c7a](https://github.com/0xAnasEzz/morphe-patches/commit/e3c8b4c7a))
* **YouTube - Feed card layout:** Save button of the cards with action buttons is not filled for the videos saved before the app is opened, and does not follow the Watch later button of the thumbnails (#5347) ([a76caaadc](https://github.com/0xAnasEzz/morphe-patches/commit/a76caaadc))
* **YouTube - Restore original titles:** Link cards of a description that is not translated, such as of a playlist, are replaced by the plain link (#5348) ([98aa63045](https://github.com/0xAnasEzz/morphe-patches/commit/98aa63045))
* **YouTube - Video quality:** Shorts play at a lower quality with the clients other than TV, Web and Mobile Web on devices whose video decoder lists a landscape size (#5349) ([09fae2248](https://github.com/0xAnasEzz/morphe-patches/commit/09fae2248))
* **YouTube - Hide layout components:** "Hide mix playlists" does not hide mixes of the new feed card layout, and "Hide video labels" hides "Members only" badges and no longer hides labels in search results ([369fde4fa](https://github.com/0xAnasEzz/morphe-patches/commit/369fde4fa))
* **YouTube - Hide layout components:** Change "Hide horizontal shelves" to default off ([3cabaa11c](https://github.com/0xAnasEzz/morphe-patches/commit/3cabaa11c))
* **YouTube Music - Downloads:** Download podcast fails (#5342) ([271fbe15b](https://github.com/0xAnasEzz/morphe-patches/commit/271fbe15b))
* **YouTube / YouTube Music - Glass menus:** Blur behind menus while the battery saver is on, glass from the first frame and on the "Please wait" dialog of downloads (#5324) ([e73d6d310](https://github.com/0xAnasEzz/morphe-patches/commit/e73d6d310))
* **YouTube:** App keeps using the CPU until it's closed, also in the background, when Litho layouts are calculated again in a loop (#5331) ([7b9d1018e](https://github.com/0xAnasEzz/morphe-patches/commit/7b9d1018e))
* **YouTube / YouTube Music - Video effects:** HDR videos are too dark when an effect is used, and effects do not apply to a video opened again with the effect off ([557cfb0b6](https://github.com/0xAnasEzz/morphe-patches/commit/557cfb0b6))

## [2.4.0-dev.12.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.12.fork.1) (2026-11-25)

### ✨ New Features

* **YouTube Music - Third-party lyrics:** Add fullscreen lyrics mode (#5076) ([8822fdf13](https://github.com/0xAnasEzz/morphe-patches/commit/8822fdf13))
* **Reddit:** Add `See-through status bar` patch (#5280) ([e09ea081d](https://github.com/0xAnasEzz/morphe-patches/commit/e09ea081d))
* **Reddit:** Add `Video playback speed` patch (#5308) ([df23e08e1](https://github.com/0xAnasEzz/morphe-patches/commit/df23e08e1))
* **Reddit:** Add `Hide community menu badge` patch (#5303) ([b637a41d7](https://github.com/0xAnasEzz/morphe-patches/commit/b637a41d7))
* **Reddit:** Add `Hide comment flairs and badges` patch (#5298) ([e8002283f](https://github.com/0xAnasEzz/morphe-patches/commit/e8002283f))
* **Reddit:** Add `Hide community highlights` patch (#5297) ([5719bd041](https://github.com/0xAnasEzz/morphe-patches/commit/5719bd041))
* **Reddit:** Add `Hide Answers preview` patch (#5296) ([e0b97a346](https://github.com/0xAnasEzz/morphe-patches/commit/e0b97a346))
* **Reddit:** Add `Disable post detail swipe` patch (#5295) ([70ea4acc2](https://github.com/0xAnasEzz/morphe-patches/commit/70ea4acc2))
* **Reddit - Customize post layout:** Add option to hide the view count (#5286) ([4ea330d8d](https://github.com/0xAnasEzz/morphe-patches/commit/4ea330d8d))
* **Reddit - Hide post buttons:** Add `Hide vote count` and `Hide Share count` options (#5285) ([44b6ba690](https://github.com/0xAnasEzz/morphe-patches/commit/44b6ba690))
* **Reddit - Home feed tabs:** Add `Disable home feed swipe` option (#5284) ([04deda5a8](https://github.com/0xAnasEzz/morphe-patches/commit/04deda5a8))
* **YouTube - Hide layout components:** Add `Duration filter` (#5277) ([e52445701](https://github.com/0xAnasEzz/morphe-patches/commit/e52445701))

### 🐛 Bug Fixes

* **Reddit - Show flairs in home feed:** Flairs are shown twice for classic posts in subreddit feeds (#5299) ([a32154dde](https://github.com/0xAnasEzz/morphe-patches/commit/a32154dde))
* **YouTube Music - Third-party lyrics:** Lyrics button is disabled for tracks without official lyrics (#5293) ([d13862182](https://github.com/0xAnasEzz/morphe-patches/commit/d13862182))
* **YouTube - Navigation bar:** Account switcher shortcut closes right away on `21.30` ([b99460790](https://github.com/0xAnasEzz/morphe-patches/commit/b99460790))
* **Reddit - Keep media viewer in subreddit:** Media viewer gets stuck on a loading screen when the subreddit has no more media (#5312) ([2439f9073](https://github.com/0xAnasEzz/morphe-patches/commit/2439f9073))
* **Reddit - Glass navigation bar:** Frosted glass blur slides with the bar when it hides (#5309) ([f4f56881f](https://github.com/0xAnasEzz/morphe-patches/commit/f4f56881f))
* **YouTube - Hide Shorts components:** Search results show empty cells after Shorts are opened from them, when Shorts are hidden in the home feed ([f18a2e3fa](https://github.com/0xAnasEzz/morphe-patches/commit/f18a2e3fa))
* **YouTube - Restore original titles:** Miniplayer title stays loading after a Short is opened while a video is in the miniplayer ([bec3acc8f](https://github.com/0xAnasEzz/morphe-patches/commit/bec3acc8f))
* **YouTube - Video quality:** Videos do not play with a default quality whose formats are all larger than the video decoder of the device supports, and the next Shorts use the qualities of the Short playing ([cd64c6fd8](https://github.com/0xAnasEzz/morphe-patches/commit/cd64c6fd8))

## [2.4.0-dev.11.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.11.fork.2) (2026-11-25)

### ✨ New Features

* **YouTube Music - Navigation bar:** Add "Hide Samples button" setting for the toolbar ([798292807](https://github.com/0xAnasEzz/morphe-patches/commit/798292807))
* **Reddit - Glass navigation bar:** Add Frosted glass style (#5282) ([fcd4fa5d3](https://github.com/0xAnasEzz/morphe-patches/commit/fcd4fa5d3))
* **YouTube - Change form factor:** Hide the navigation bar on a car display (#4933) ([bc14cd68d](https://github.com/0xAnasEzz/morphe-patches/commit/bc14cd68d))

### 🐛 Bug Fixes

* **YouTube - Video quality:** Shorts still do not play with the TV, Web and Mobile Web clients and a default quality, when the quality has no format of the codec playing or the Short does not fill the player ([65dbef68d](https://github.com/0xAnasEzz/morphe-patches/commit/65dbef68d))
* **YouTube:** Video description shows an older like and view count (#5301) ([a9f29f998](https://github.com/0xAnasEzz/morphe-patches/commit/a9f29f998))
* **YouTube - Spoof video streams:** Web and Mobile Web clients keep failing after a stream failed, until the network is turned off and on ([a42820724](https://github.com/0xAnasEzz/morphe-patches/commit/a42820724))
* **YouTube - Restore old video action bar:** "Classic Two-Rows" shows the channel and the buttons in one row on 20.26 ([c5d1d130b](https://github.com/0xAnasEzz/morphe-patches/commit/c5d1d130b))
* **YouTube - Ghost mode:** Player shows the Ghost mode button with the legacy player buttons, such as on 20.26, while Ghost mode is off ([032cdaab8](https://github.com/0xAnasEzz/morphe-patches/commit/032cdaab8))
* **YouTube Music - Downloads:** Player background is black instead of the album artwork color for downloaded songs ([1ced5f32a](https://github.com/0xAnasEzz/morphe-patches/commit/1ced5f32a))
* **YouTube Music - Jam queue sharing:** Nothing happens after connecting Jam Layer ([e9fb3d346](https://github.com/0xAnasEzz/morphe-patches/commit/e9fb3d346))

## [2.4.0-dev.11.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.11.fork.1) (2026-11-24)

### ✨ New Features

* **YouTube - Automotive layout on car displays:** Use the automotive layout on a car display (#4932) ([120c4f00d](https://github.com/0xAnasEzz/morphe-patches/commit/120c4f00d))
* **YouTube Music:** Add `Android Auto third-party apps` patch (#4931) ([4b9683df4](https://github.com/0xAnasEzz/morphe-patches/commit/4b9683df4))
* **Reddit:** Add `Glass navigation bar` patch (#5272) ([6b4d7e1a5](https://github.com/0xAnasEzz/morphe-patches/commit/6b4d7e1a5))
* **YouTube - Captions:** Add "Copy transcript" setting (#5226) ([7719fcee4](https://github.com/0xAnasEzz/morphe-patches/commit/7719fcee4))
* **YouTube - Spoof video streams:** Show "Signed in" in stats for nerds for every client that fetched the video signed in, such as TV and the web clients ([96f4cf158](https://github.com/0xAnasEzz/morphe-patches/commit/96f4cf158))
* **YouTube - Hide Shorts components:** Hide standalone Shorts cards in modern home feed layout ([decc56b77](https://github.com/0xAnasEzz/morphe-patches/commit/decc56b77))
* **YouTube:** Add `Ghost mode` patch (#5197) ([9c625c6f4](https://github.com/0xAnasEzz/morphe-patches/commit/9c625c6f4))
* **YouTube - Keyword filtering:** Add "Hide posts by keywords" setting (#5264) ([7b03c9832](https://github.com/0xAnasEzz/morphe-patches/commit/7b03c9832))

### 🐛 Bug Fixes

* **YouTube - Hide Shorts components:** Shorts are not hidden in the modern home feed layout ([827989e26](https://github.com/0xAnasEzz/morphe-patches/commit/827989e26))
* **YouTube - Glass menus:** Rows of some menus, such as the notifications menu of a channel, are not drawn as glass ([5007bbc63](https://github.com/0xAnasEzz/morphe-patches/commit/5007bbc63))
* **YouTube - Miniplayer:** Glass minimal miniplayer shows a black band beside the video while the player is dragged ([dd9c52131](https://github.com/0xAnasEzz/morphe-patches/commit/dd9c52131))
* **YouTube:** Player buttons cover the mute button of YouTube, and "Mute button" shows a second mute button ([a2d407e8c](https://github.com/0xAnasEzz/morphe-patches/commit/a2d407e8c))
* **YouTube - Playback in feeds:** Videos that play in feeds show an empty round button above the seek forward button ([8749f180b](https://github.com/0xAnasEzz/morphe-patches/commit/8749f180b))
* **YouTube - Spoof video streams:** Shorts in the regular player restart again and again with the TV, Web and Mobile Web clients ([4b6171c44](https://github.com/0xAnasEzz/morphe-patches/commit/4b6171c44))
* **YouTube - Theme:** Do not theme feed video card title background (#5276) ([7bb751c58](https://github.com/0xAnasEzz/morphe-patches/commit/7bb751c58))
* **Reddit:** Add `2026.37.0` target, update `2026.40.0` and later min Android target to Android 12L ([f415eb37d](https://github.com/0xAnasEzz/morphe-patches/commit/f415eb37d))
* **YouTube:** Player menu items show in the download quality menu ([eb62e6ac1](https://github.com/0xAnasEzz/morphe-patches/commit/eb62e6ac1))
* **YouTube:** App crashes when scrolling the player menu if menu items are hidden ([ca8077e35](https://github.com/0xAnasEzz/morphe-patches/commit/ca8077e35))
* **YouTube - Keyword filtering:** Keywords may not hide videos with card layout ([93ff52128](https://github.com/0xAnasEzz/morphe-patches/commit/93ff52128))
* **YouTube - Hide layout components:** "Hide video labels" does not hide 'Earns commission' thumbnail badge ([8c6e1ebb4](https://github.com/0xAnasEzz/morphe-patches/commit/8c6e1ebb4))
* **YouTube - Ghost mode:** Toolbar button overlaps the wide search bar and voice search button ([934fc0d29](https://github.com/0xAnasEzz/morphe-patches/commit/934fc0d29))
* **YouTube - Hide layout components:** Keyword filter does not hide collaboration videos ([05b6dfe7b](https://github.com/0xAnasEzz/morphe-patches/commit/05b6dfe7b))
* **YouTube - Theme:** Do not override video card background color ([9a2dc5031](https://github.com/0xAnasEzz/morphe-patches/commit/9a2dc5031))
* **YouTube - Video effects:** Effects are not applied to videos that A/B tests or server configs draw on a dual, GL or secure surface view (#5257) ([fac1a261f](https://github.com/0xAnasEzz/morphe-patches/commit/fac1a261f))

### 🚀 Updated App Support

* **YouTube Music:** Add experimental support for `9.47.51` ([b8e393f09](https://github.com/0xAnasEzz/morphe-patches/commit/b8e393f09))

## [2.4.0-dev.9.fork.4](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.9.fork.4) (2026-11-24)

### 🐛 Bug Fixes

* **YouTube Music - Third-party lyrics:** Fix Indic cluster wrapping, ruby elevation, glow halo, and text resize layout refresh (#5213) ([702056033](https://github.com/0xAnasEzz/morphe-patches/commit/702056033))

## [2.4.0-dev.9.fork.3](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.9.fork.3) (2026-11-23)

### ✨ New Features

* **Reddit:** Add `Disable refresh on back to exit` patch (#5245) ([e66700885](https://github.com/0xAnasEzz/morphe-patches/commit/e66700885))
* **Reddit:** Add `Disable home feed auto-refresh` patch (#5244) ([208ab88da](https://github.com/0xAnasEzz/morphe-patches/commit/208ab88da))
* **Reddit:** Add `Always show Hide` patch (#5243) ([6d2c5aedf](https://github.com/0xAnasEzz/morphe-patches/commit/6d2c5aedf))
* **Reddit:** Add `Disable bottom bar auto-hide` patch (#5242) ([48f05e82b](https://github.com/0xAnasEzz/morphe-patches/commit/48f05e82b))
* **Reddit:** Add `Colorize comment indent lines` patch (#5241) ([cc034df55](https://github.com/0xAnasEzz/morphe-patches/commit/cc034df55))
* **YouTube - Navigation bar:** Add "Account switcher shortcut" setting (#5255) ([a80f177f9](https://github.com/0xAnasEzz/morphe-patches/commit/a80f177f9))
* **YouTube - Playback in feeds:** Add "Show seek buttons in feeds" setting ([f865d982d](https://github.com/0xAnasEzz/morphe-patches/commit/f865d982d))
* **YouTube Music - Navigation bar:** Add "Show Settings button" setting to the navigation bar and toolbar (#5254) ([909fcb95c](https://github.com/0xAnasEzz/morphe-patches/commit/909fcb95c))
* **Spoof video streams:** Add "Use QuackJS" setting (#5170) ([d840eb905](https://github.com/0xAnasEzz/morphe-patches/commit/d840eb905))
* **YouTube - Spoof video streams:** Add "Web" client (#5208) ([67f409e5c](https://github.com/0xAnasEzz/morphe-patches/commit/67f409e5c))
* **Reddit - Copy text:** Make post titles selectable and keep collapsing comments (#5237) ([453757b4d](https://github.com/0xAnasEzz/morphe-patches/commit/453757b4d))
* **YouTube - Wide search bar:** Show the search bar in You tab (#5228) ([d7c5aecfa](https://github.com/0xAnasEzz/morphe-patches/commit/d7c5aecfa))

### 🐛 Bug Fixes

* **YouTube - Settings:** Morphe settings entry is not translated ([2c43304d1](https://github.com/0xAnasEzz/morphe-patches/commit/2c43304d1))
* **YouTube - FlyoutUtils:** Injected menu items scroll separately from the app items in landscape ([6e77014f2](https://github.com/0xAnasEzz/morphe-patches/commit/6e77014f2))
* **YouTube - FlyoutUtils:** Injected items of the player menu in fullscreen can be cut to less than one item, hiding the items after the first ([99dc255a6](https://github.com/0xAnasEzz/morphe-patches/commit/99dc255a6))
* **YouTube - Hide layout components:** 'Visit the Community' section of the comments is shown again with "Hide community posts" ([624295fcc](https://github.com/0xAnasEzz/morphe-patches/commit/624295fcc))
* **YouTube - Downloads:** Saved videos have no seekbar thumbnails if the streams are saved from a client without storyboards ([46dfb0280](https://github.com/0xAnasEzz/morphe-patches/commit/46dfb0280))
* **Reddit - Search hidden profiles:** Make the profile search find the posts of hidden profiles (#5246) ([5bca869d6](https://github.com/0xAnasEzz/morphe-patches/commit/5bca869d6))
* **Reddit - Download all from gallery:** Dialog is not shown after leaving the media viewer (#5249) ([f9d64660e](https://github.com/0xAnasEzz/morphe-patches/commit/f9d64660e))
* **Reddit:** Fix fingerprints that match more than one method ([9c3948c0d](https://github.com/0xAnasEzz/morphe-patches/commit/9c3948c0d))
* **YouTube - Snackbar:** Fix ambiguous snackbar display fingerprint ([efc2110d2](https://github.com/0xAnasEzz/morphe-patches/commit/efc2110d2))

### 🚀 Updated App Support

* **YouTube:** Add experimental support for `21.47.483` ([4dd89a357](https://github.com/0xAnasEzz/morphe-patches/commit/4dd89a357))

## [2.4.0-dev.9.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.9.fork.2) (2026-11-23)

### ✨ New Features

* **YouTube - Search comments:** Rename patch to `Comment search` ([03678e7d9](https://github.com/0xAnasEzz/morphe-patches/commit/03678e7d9))
* **YouTube - Hide layout components:** Add `View count filter` (#5227) ([3da0c214d](https://github.com/0xAnasEzz/morphe-patches/commit/3da0c214d))

### 🐛 Bug Fixes

* **Reddit - Collapse all comments:** App crash on clicking collpase button (#5233) ([60ca47084](https://github.com/0xAnasEzz/morphe-patches/commit/60ca47084))

## [2.4.0-dev.9.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.9.fork.1) (2026-11-23)

### ✨ New Features

* **YouTube - Hide layout components:** Add "Hide 'Visit the Community' section" setting for comments ([8e6863898](https://github.com/0xAnasEzz/morphe-patches/commit/8e6863898))
* **Reddit:** Add `Hide People also search for section` patch (#5225) ([c713ce4ae](https://github.com/0xAnasEzz/morphe-patches/commit/c713ce4ae))
* **Reddit:** Add `Collapse all comments` patch (#5217) ([986025cdc](https://github.com/0xAnasEzz/morphe-patches/commit/986025cdc))
* **Reddit:** Add `Enable debugging` patch (#5201) ([9b0bf3e34](https://github.com/0xAnasEzz/morphe-patches/commit/9b0bf3e34))
* **YouTube:** Add `Playlist search` patch (#5200) ([2969e39cb](https://github.com/0xAnasEzz/morphe-patches/commit/2969e39cb))
* **YouTube:** Add replay slower button and swipe (#5006) ([0e240efb2](https://github.com/0xAnasEzz/morphe-patches/commit/0e240efb2))
* **YouTube - Hold gesture:** Add a launcher that opens with a drag up (#5134) ([a1bc93ae0](https://github.com/0xAnasEzz/morphe-patches/commit/a1bc93ae0))

### 🔧 Improvements

* **YouTube - Ambient mode:** Draw the light of Enhanced Ambient mode with OpenGL ES (#5222) ([b37f7b29b](https://github.com/0xAnasEzz/morphe-patches/commit/b37f7b29b))
* **YouTube - Ambient mode:** Draw the light of Enhanced Ambient mode on one surface (#5221) ([3d3462d42](https://github.com/0xAnasEzz/morphe-patches/commit/3d3462d42))

### 🐛 Bug Fixes

* **YouTube Music - Downloads:** Save songs with Opus audio by default (#5224) ([c9c572b94](https://github.com/0xAnasEzz/morphe-patches/commit/c9c572b94))
* **YouTube Music - Hide ads:** Hide Premium promotion under menu Download button (#5207) ([2c46ef81a](https://github.com/0xAnasEzz/morphe-patches/commit/2c46ef81a))
* **YouTube Music - Android Auto:** Home screen shows "No items" on startup (#5159) ([bd4c6040d](https://github.com/0xAnasEzz/morphe-patches/commit/bd4c6040d))
* **YouTube Music - Spoof video streams:** Android Auto shows "Could not load your selection" when Music is closed (#5198) ([2ff116408](https://github.com/0xAnasEzz/morphe-patches/commit/2ff116408))
* **YouTube - Ambient mode:** Enhanced Ambient mode leaves the comment box black and flashes black when a panel closes on wide screens (#5219) ([b395b0cc3](https://github.com/0xAnasEzz/morphe-patches/commit/b395b0cc3))
* **YouTube - Navigation bar:** Empty bar shows behind the navigation bar while it auto-hides on scroll ([7652268e2](https://github.com/0xAnasEzz/morphe-patches/commit/7652268e2))

## [2.4.0-dev.8.fork.3](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.8.fork.3) (2026-11-23)

### ✨ New Features

* **Reddit:** Add `Download all from gallery` patch (#5193) ([f317c6d12](https://github.com/0xAnasEzz/morphe-patches/commit/f317c6d12))
* **Reddit:** Add `Full-screen reply` patch (#5191) ([1425fe60a](https://github.com/0xAnasEzz/morphe-patches/commit/1425fe60a))
* **Reddit:** Add `Swipe up for comments` patch (#5190) ([55242e30a](https://github.com/0xAnasEzz/morphe-patches/commit/55242e30a))
* **Reddit:** Add `Private browsing mode` patch (#5161) ([6d007728d](https://github.com/0xAnasEzz/morphe-patches/commit/6d007728d))
* **Reddit:** Add `Home feed tabs` patch (#5192) ([e949b860a](https://github.com/0xAnasEzz/morphe-patches/commit/e949b860a))
* **Reddit:** Add `AutoModerator comments` patch (#5156) ([8e8de8b09](https://github.com/0xAnasEzz/morphe-patches/commit/8e8de8b09))
* **Reddit:** Add `Keep media viewer in subreddit` patch (#5155) ([85c153e5f](https://github.com/0xAnasEzz/morphe-patches/commit/85c153e5f))
* **Reddit - Post side panel:** Drag the edge of the panel to resize it (#5152) ([7507f1c33](https://github.com/0xAnasEzz/morphe-patches/commit/7507f1c33))

### 🐛 Bug Fixes

* **Youtube Music - Android Auto:** Fix crash when opening Settings (#5153) ([968c0da6e](https://github.com/0xAnasEzz/morphe-patches/commit/968c0da6e))
* **YouTube / YouTube Music - Video effects:** Show a clear error when pasted effect code is cut off ([7070ba719](https://github.com/0xAnasEzz/morphe-patches/commit/7070ba719))

## [2.4.0-dev.8.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.8.fork.2) (2026-11-22)

### ✨ New Features

* **YouTube - Ambient mode:** Show the light of Enhanced Ambient mode behind the comments panel of fullscreen (#5194) ([954f974fe](https://github.com/0xAnasEzz/morphe-patches/commit/954f974fe))
* **YouTube:** Add `Return YouTube Username` patch (#5173) ([f05bb2048](https://github.com/0xAnasEzz/morphe-patches/commit/f05bb2048))
* **Reddit:** Add `Search hidden profiles` patch (#5189) ([03b54000d](https://github.com/0xAnasEzz/morphe-patches/commit/03b54000d))
* **YouTube / YouTube Music - Video effects:** Edit an effect by long pressing in the effect list dialog ([af5475dca](https://github.com/0xAnasEzz/morphe-patches/commit/af5475dca))
* **Reddit:** Add `Hide Related Posts section` patch (#5181) ([6bbd8812c](https://github.com/0xAnasEzz/morphe-patches/commit/6bbd8812c))
* **YouTube:** Add `Reverse playlist autoplay` patch and "Reverse order" setting for "Play all" patch (#5171) ([0d7a76d8f](https://github.com/0xAnasEzz/morphe-patches/commit/0d7a76d8f))
* **GmsCore support:** Universal GNP / Chime push notification registration support (#5145) ([65f742fa5](https://github.com/0xAnasEzz/morphe-patches/commit/65f742fa5))

### 🐛 Bug Fixes

* **YouTube - Ambient mode:** Compute the light of Enhanced Ambient mode with less work (#5186) ([91dd6e6db](https://github.com/0xAnasEzz/morphe-patches/commit/91dd6e6db))
* **Youtube Music - Android Auto:** Fix empty For You card (#5175) ([eb7f123de](https://github.com/0xAnasEzz/morphe-patches/commit/eb7f123de))

## [2.4.0-dev.8.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.8.fork.1) (2026-11-22)

### ✨ New Features

* **YouTube / YouTube Music:** Add `Video effects` patch (#5137) ([f9dbc7796](https://github.com/0xAnasEzz/morphe-patches/commit/f9dbc7796))
* **Disable DRC audio:** Disable the DRC version of the audio, and add "Disable loudness normalization" setting (#5131) ([7f7bbdf84](https://github.com/0xAnasEzz/morphe-patches/commit/7f7bbdf84))
* **YouTube Music - Third-party lyrics:** Add offline Kuromoji romanizer, custom font upload, inline share editor, separate cache clearing, and romaji/CJK sweep fixes (#5072) ([58074f6c7](https://github.com/0xAnasEzz/morphe-patches/commit/58074f6c7))
* **YouTube Music:** Add `Glass menus` patch (#5123) ([f691df66b](https://github.com/0xAnasEzz/morphe-patches/commit/f691df66b))
* **YouTube:** Add `Glass menus` patch (#5107) ([ed52a0dda](https://github.com/0xAnasEzz/morphe-patches/commit/ed52a0dda))
* **YouTube  Music:** Add `Apple Music animated artwork` patch (#5082) ([a48adbee3](https://github.com/0xAnasEzz/morphe-patches/commit/a48adbee3))
* **YouTube:** Add `Hold gesture` patch (#5099) ([0e899ed49](https://github.com/0xAnasEzz/morphe-patches/commit/0e899ed49))
* **YouTube - Hide layout components:** Add "Hide Topics" setting (#5097) ([e0fb5e3e5](https://github.com/0xAnasEzz/morphe-patches/commit/e0fb5e3e5))
* **YouTube - Hide layout components:** Add "Hide Badges", "Hide 'Liked videos'" and "Hide 'Watch later'" settings for the You tab ([a67178893](https://github.com/0xAnasEzz/morphe-patches/commit/a67178893))
* **Reddit - Hide post buttons:** "Hide Award button" also hides the Award button of comments ([c02951aa3](https://github.com/0xAnasEzz/morphe-patches/commit/c02951aa3))
* **YouTube Music:** Add `Sonos Cast` patch (#4891) ([b7605075b](https://github.com/0xAnasEzz/morphe-patches/commit/b7605075b))

### 🐛 Bug Fixes

* **YouTube Music - Enable audio/video switch:** Use the album of a music video to find its exact song ([c0b083f87](https://github.com/0xAnasEzz/morphe-patches/commit/c0b083f87))
* **YouTube Music - Play album songs:** Replace album music videos with their songs in the queue (#5141) ([dd4c2f00d](https://github.com/0xAnasEzz/morphe-patches/commit/dd4c2f00d))
* **YouTube - Glass menus:** Draw the glass only on the panel of a bottom sheet (#5128) ([ece07e2c9](https://github.com/0xAnasEzz/morphe-patches/commit/ece07e2c9))
* **YouTube - DeArrow:** Elements are mounted again entirely when a still image or DeArrow thumbnail is not available, instead of loading only the thumbnail again (#4966) ([e2b96b55b](https://github.com/0xAnasEzz/morphe-patches/commit/e2b96b55b))
* **YouTube - DeArrow:** Thumbnail keeps the previous branding after tapping the DeArrow icon, as the element is mounted again before it's laid out again ([4aaadacd0](https://github.com/0xAnasEzz/morphe-patches/commit/4aaadacd0))
* **YouTube:** Feed stutters when the titles loaded meanwhile are laid out again, as their layout is calculated on the main thread (#4966) ([3f02ea1cd](https://github.com/0xAnasEzz/morphe-patches/commit/3f02ea1cd))
* **YouTube:** Feed stutters while scrolling fast, as the titles loaded meanwhile are laid out again during the fling and all in the same frame (#4966) ([f5ee3968b](https://github.com/0xAnasEzz/morphe-patches/commit/f5ee3968b))
* **YouTube Music - Theme:** Playlist header ends in a hard black edge with a non-black background ([9ab4dcbc5](https://github.com/0xAnasEzz/morphe-patches/commit/9ab4dcbc5))
* **YouTube - Download post images:** Download button and menu item are missing on posts with a short text or without text (#4066) ([6b8be0f63](https://github.com/0xAnasEzz/morphe-patches/commit/6b8be0f63))
* **YouTube - Navigation bar:** Live chat scroll to bottom button stays half visible with the glass or translucent navigation bar (#5100) ([1f47abdbb](https://github.com/0xAnasEzz/morphe-patches/commit/1f47abdbb))
* **YouTube - Navigation bar:** Navigation bar does not auto-hide while scrolling when the miniplayer is shown (#4432) ([db91dbeba](https://github.com/0xAnasEzz/morphe-patches/commit/db91dbeba))
* **YouTube & YouTube Music - Glass menus:** Hide new Litho fills before they are drawn (#5130) ([1ea74d705](https://github.com/0xAnasEzz/morphe-patches/commit/1ea74d705))
* **Reddit - Feed auto-scroll:** Patching fails with Reddit 2026.24.0 and older ([41650c4b3](https://github.com/0xAnasEzz/morphe-patches/commit/41650c4b3))
* **YouTube Music - Navigation bar:** "Hide 'Ask Music' button" does not hide the button in the player, miniplayer and fullscreen (#5120) ([9ae8dd69a](https://github.com/0xAnasEzz/morphe-patches/commit/9ae8dd69a))
* **YouTube Music - Glass miniplayer:** Miniplayer missing album artwork (#5117) ([6af6775c7](https://github.com/0xAnasEzz/morphe-patches/commit/6af6775c7))
* **YouTube Music - Remember video quality:** Default quality is used about 10 seconds after a track starts (#5109) ([7531b56ae](https://github.com/0xAnasEzz/morphe-patches/commit/7531b56ae))
* **YouTube Music - Remember video quality:** Videos with only low quality VP9 play at 360p with no quality menu (#5108) ([ac829a2fe](https://github.com/0xAnasEzz/morphe-patches/commit/ac829a2fe))
* **YouTube - Hide layout components:** Keyword filter does not hide videos with fancy text titles ([5f5609b87](https://github.com/0xAnasEzz/morphe-patches/commit/5f5609b87))
* **YouTube - Add to queue:** Handle Play next in queue on playlist pages for native queue (#5088) ([033d4b56d](https://github.com/0xAnasEzz/morphe-patches/commit/033d4b56d))
* **YouTube - Navigation bar:** Navigation bar does not auto-hide while scrolling on accounts whose app controllers never hide it (#4432) ([e1a024896](https://github.com/0xAnasEzz/morphe-patches/commit/e1a024896))
* **YouTube - Restore original titles:** Titles stay loading or are not restored after the app is opened again from the background ([3863119f6](https://github.com/0xAnasEzz/morphe-patches/commit/3863119f6))
* **YouTube - DeArrow:** Thumbnails that failed to load are not loaded again when the connection comes back while the app is in the background ([b9a8094fb](https://github.com/0xAnasEzz/morphe-patches/commit/b9a8094fb))
* **YouTube - Restore original titles:** Title of the previous video is shown when the next video of a playlist plays before its video ID is known ([a1a2dc821](https://github.com/0xAnasEzz/morphe-patches/commit/a1a2dc821))
* **YouTube:** Video ID is not updated when the next video of a playlist plays in the background ([c35d12c4e](https://github.com/0xAnasEzz/morphe-patches/commit/c35d12c4e))
* **YouTube - Navigation bar:** Navigation bar does not auto-hide while scrolling on accounts whose feed pages do not enable it (#4432) ([dfb784e4d](https://github.com/0xAnasEzz/morphe-patches/commit/dfb784e4d))
* **YouTube - Player controls:** Old player buttons show over the overlay buttons on 21.47 ([040df4397](https://github.com/0xAnasEzz/morphe-patches/commit/040df4397))
* **YouTube - Litho filter:** Elements that the element hooks hide, such as the YouTube Premium promotions, leave empty cells in the tablet feed (#5012) ([358afd0ac](https://github.com/0xAnasEzz/morphe-patches/commit/358afd0ac))
* **YouTube - Hide layout components:** Hide new type of community posts ([7ce7538b8](https://github.com/0xAnasEzz/morphe-patches/commit/7ce7538b8))
* **YouTube:** Feed stutters while scrolling, as the element hooks run twice for each loaded element (#5096) ([6db505e22](https://github.com/0xAnasEzz/morphe-patches/commit/6db505e22))
* **YouTube:** Feed stutters while scrolling, as the titles and thumbnails loaded meanwhile lay out and mount again all the shown elements ([2283c7afe](https://github.com/0xAnasEzz/morphe-patches/commit/2283c7afe))
* **YouTube:** Update tab selected fingerprint to match more app versions ([4c7f60178](https://github.com/0xAnasEzz/morphe-patches/commit/4c7f60178))
* **YouTube:** Feed thumbnail badges take a text below the thumbnail for the duration badge, and are missing on the rows of a list, on screens with a high display density ([5617a08b0](https://github.com/0xAnasEzz/morphe-patches/commit/5617a08b0))
* **YouTube Music - Change start page:** Subscriptions start page is sometimes blank on `9.26+` ([0c5353a00](https://github.com/0xAnasEzz/morphe-patches/commit/0c5353a00))
* **YouTube - Return YouTube Dislike:** Feed thumbnail like count of a grid of Shorts is shown below the thumbnail, and twice on the left Short, when a Short at the right has a channel name in capital letters (#5070) ([6896cbe49](https://github.com/0xAnasEzz/morphe-patches/commit/6896cbe49))
* **YouTube - Restore old video action bar:** "Classic One-Row" shows two rows and comments do not load GIFs on 20.26 (#5068) ([5007b0a24](https://github.com/0xAnasEzz/morphe-patches/commit/5007b0a24))
* **YouTube:** Location setting changes back to the country of the device after leaving YouTube settings (#5071) (#5080) ([efff3b32c](https://github.com/0xAnasEzz/morphe-patches/commit/efff3b32c))
* **YouTube:** Subscriptions settings are not used with the layout that shows Subscriptions as a tab at the top of Home ([045c3e521](https://github.com/0xAnasEzz/morphe-patches/commit/045c3e521))

## [2.4.0-dev.5.fork.5](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.5.fork.5) (2026-11-22)

### ✨ New Features

* **Reddit:** Add `Hide 'Videos for you' shelf` patch (#5074) ([125173a31](https://github.com/0xAnasEzz/morphe-patches/commit/125173a31))

### 🐛 Bug Fixes

* **Clone app:** Fix invalid package names instead of rejecting them ([12b43baaf](https://github.com/0xAnasEzz/morphe-patches/commit/12b43baaf))
* **Spoof video streams:** Playback freezes if the server redirects a stream range with a SABR error (#5073) ([29f57c477](https://github.com/0xAnasEzz/morphe-patches/commit/29f57c477))

### 🚀 Updated App Support

* **Reddit:** Add experimental support for `2026.47.0` (#5075) ([681d03e75](https://github.com/0xAnasEzz/morphe-patches/commit/681d03e75))

## [2.4.0-dev.5.fork.4](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.5.fork.4) (2026-11-22)

### ✨ New Features

* **YouTube Music - Downloads:** Export albums and playlists to their own folders ([0164aac36](https://github.com/0xAnasEzz/morphe-patches/commit/0164aac36))
* **YouTube Music - Downloads:** Include album artwork in exported music (#5048) ([e21d57b19](https://github.com/0xAnasEzz/morphe-patches/commit/e21d57b19))
* **YouTube - Navigation bar:** Restore the toolbar Cast button hidden by YouTube, and add "Hide Cast button" and "Hide Companion button" toolbar settings (#5034) ([b88a6c195](https://github.com/0xAnasEzz/morphe-patches/commit/b88a6c195))
* **Reddit:** Add `Hide post buttons` patch (#5022) ([9f79c5797](https://github.com/0xAnasEzz/morphe-patches/commit/9f79c5797))
* **Reddit:** Add `Hide home tabs` patch and support 2026.40.0+ in `Disable modern home` (#5044) ([1ee6efe55](https://github.com/0xAnasEzz/morphe-patches/commit/1ee6efe55))

### 🐛 Bug Fixes

* **YouTube - Ambient mode:** Enhanced Ambient mode shows the chat through the poll of a live chat (#5063) ([7754b92c4](https://github.com/0xAnasEzz/morphe-patches/commit/7754b92c4))
* **YouTube:** Settings applied only after a restart do not show the restart dialog when changed, such as the order of the navigation buttons, sliders, colors and the settings of the same groups ([7c4b58148](https://github.com/0xAnasEzz/morphe-patches/commit/7c4b58148))
* **YouTube:** DeArrow titles and Return YouTube Dislike feed counts stay missing or loading for minutes after the connection comes back (#5061) (#5062) ([c2ab61662](https://github.com/0xAnasEzz/morphe-patches/commit/c2ab61662))
* **YouTube - Video quality:** Selected quality plays only after the buffered video on 21.17 - 21.24 (#5053) ([131c4b991](https://github.com/0xAnasEzz/morphe-patches/commit/131c4b991))
* **YouTube - Translate live chat:** Translations of a busy chat arrive many seconds late (#4553) ([ebb5248a9](https://github.com/0xAnasEzz/morphe-patches/commit/ebb5248a9))
* **YouTube - Ambient mode:** Enhanced Ambient mode shows static next to the camera cutout on the way from fullscreen to the miniplayer (#5058) ([5c60c244b](https://github.com/0xAnasEzz/morphe-patches/commit/5c60c244b))
* **YouTube - Miniplayer:** Glass miniplayer adds another scroll listener every time its glass is made again ([f90c925b2](https://github.com/0xAnasEzz/morphe-patches/commit/f90c925b2))
* **YouTube - Hide layout components:** "Hide video labels" hides the rows of the player menu and of the "Save to" sheet that have a badge, as it was not limited to the labels of the videos (#4761) ([a2eba3673](https://github.com/0xAnasEzz/morphe-patches/commit/a2eba3673))
* **YouTube - Hide Shorts components:** The feed stutters while scrolling fast, as the buffer of every nested component of a video is searched for Shorts thumbnails (#4966) ([fb3076096](https://github.com/0xAnasEzz/morphe-patches/commit/fb3076096))
* **YouTube - Hide layout components:** AI channel filter misses listed channels on Home, when the tag after the channel path in the element is a letter or a digit (#5010) ([e4bd5aa0e](https://github.com/0xAnasEzz/morphe-patches/commit/e4bd5aa0e))
* **YouTube Music - Third-party lyrics:** Reject unrelated local lyric files (#4947) ([b811b5d84](https://github.com/0xAnasEzz/morphe-patches/commit/b811b5d84))
* **YouTube Music - Downloads:** In-app export menu item is not always shown for albums (#5043) ([a939eb0d5](https://github.com/0xAnasEzz/morphe-patches/commit/a939eb0d5))
* **YouTube - Return YouTube Dislike:** Feed thumbnail like count blinks as loading on every card while the API limits the requests (#5021) ([11b0668c2](https://github.com/0xAnasEzz/morphe-patches/commit/11b0668c2))
* **YouTube:** App crashes on 21.28 - 21.31 when a delayed ping is sent, such as when opening a Short (#5032) ([06f4c8f4e](https://github.com/0xAnasEzz/morphe-patches/commit/06f4c8f4e))
* **YouTube - Save to Watch later:** Item shows in the menus of feed videos, also if their save item is hidden by Hide feed flyout menu (#5031) ([72dc3eaae](https://github.com/0xAnasEzz/morphe-patches/commit/72dc3eaae))

## [2.4.0-dev.5.fork.3](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.5.fork.3) (2026-11-22)

### ✨ New Features

* **YouTube - Custom branding:** 🍴 Add 'Music dark' app icon ([414f0493f](https://github.com/0xAnasEzz/morphe-patches/commit/414f0493f))

## [2.4.0-dev.5.fork.2](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.5.fork.2) (2026-11-22)

### ✨ New Features

* 🍴 Show as Anas Patches with the GitHub profile picture in Morphe Manager ([59983eb3d](https://github.com/0xAnasEzz/morphe-patches/commit/59983eb3d))

## [2.4.0-dev.5.fork.1](https://github.com/0xAnasEzz/morphe-patches/releases/tag/v2.4.0-dev.5.fork.1) (2026-11-19)

### ✨ New Features

* **YouTube - Custom branding:** 🍴 Add 'Play dark' app icon ([ec23c97f7](https://github.com/0xAnasEzz/morphe-patches/commit/ec23c97f7))
* **YouTube - Navigation bar:** Long press the Settings button to open the other settings ([b43b6568c](https://github.com/0xAnasEzz/morphe-patches/commit/b43b6568c))
* List contributors for all time, 6 months, 3 months ([9335e4927](https://github.com/0xAnasEzz/morphe-patches/commit/9335e4927))
* **Reddit:** Add `Open system share sheet` patch (#5004) ([5deaef1e9](https://github.com/0xAnasEzz/morphe-patches/commit/5deaef1e9))
* **Reddit:** Add `Hide interactive posts` patch (#4990) ([cd42ad763](https://github.com/0xAnasEzz/morphe-patches/commit/cd42ad763))
* **YouTube Music:** Add `Disable swipe to change track` patch (#4982) ([551b7980a](https://github.com/0xAnasEzz/morphe-patches/commit/551b7980a))
* **YouTube Music - Hide buttons:** Add "Hide 'Ask Music' button" setting and Toolbar screen (#4981) ([4fc323f54](https://github.com/0xAnasEzz/morphe-patches/commit/4fc323f54))
* **Reddit:** Add `Post side panel` patch (#4978) ([2e5599d1a](https://github.com/0xAnasEzz/morphe-patches/commit/2e5599d1a))
* **Reddit:** Add `Feed auto-scroll` patch (#4958) ([7014677db](https://github.com/0xAnasEzz/morphe-patches/commit/7014677db))
* **YouTube Music:** Add `Queue likes filter` patch (#4929) ([93a93cfc8](https://github.com/0xAnasEzz/morphe-patches/commit/93a93cfc8))
* **Reddit:** Add `Tablet grid feed` patch (#4923) ([c25d4ef52](https://github.com/0xAnasEzz/morphe-patches/commit/c25d4ef52))
* **Reddit:** Add `Share post content` patch (#4916) ([306165b83](https://github.com/0xAnasEzz/morphe-patches/commit/306165b83))
* **YouTube:** Add `Android Auto parked app mode` patch (#4930) ([2ed659c62](https://github.com/0xAnasEzz/morphe-patches/commit/2ed659c62))
* **YouTube Music - Third-party lyrics:** Add smooth word sweep, inactive blur, relaxed scroll, duet alignment, section pill redesign, and fix sync and toggle lag (#4866) ([0900b8896](https://github.com/0xAnasEzz/morphe-patches/commit/0900b8896))
* **YouTube - DeArrow:** Add "Clean up titles" setting (#4959) ([36466e1b0](https://github.com/0xAnasEzz/morphe-patches/commit/36466e1b0))
* **YouTube - Navigation bar:** Add glass navigation bar edge and bottom margin settings (#4975) ([96b7181d8](https://github.com/0xAnasEzz/morphe-patches/commit/96b7181d8))
* **YouTube - Feed video actions:** Keep the thumbnail badges and buttons over the inline preview (#4973) ([068e9d40e](https://github.com/0xAnasEzz/morphe-patches/commit/068e9d40e))
* **Reddit:** Add `Flair filters` patch (#4868) ([a0808b73c](https://github.com/0xAnasEzz/morphe-patches/commit/a0808b73c))
* **YouTube:** Add `Ungroup notifications` patch (#4896) ([659cba454](https://github.com/0xAnasEzz/morphe-patches/commit/659cba454))

### 🐛 Bug Fixes

* **Disable Play Store updates:** Show original version code in Morphe crash logs ([d05979964](https://github.com/0xAnasEzz/morphe-patches/commit/d05979964))
* **Disable Play Store updates:** Keep original version code for Morphe extension code ([6dc03f37c](https://github.com/0xAnasEzz/morphe-patches/commit/6dc03f37c))
* **YouTube - Navigation bar:** Update availability of Create and Notifications button settings when swapped ([c4089c28b](https://github.com/0xAnasEzz/morphe-patches/commit/c4089c28b))
* **YouTube Music - Crossfade:** Disable the settings if the spoof client does not support crossfade, and show which client to use ([2e5bada2f](https://github.com/0xAnasEzz/morphe-patches/commit/2e5bada2f))
* **YouTube - Feed view count:** Badge shown on a Home card that already shows the view count as a text of its own, after the video is loaded in another list ([56ec044aa](https://github.com/0xAnasEzz/morphe-patches/commit/56ec044aa))
* **Reddit - Feed auto-scroll:** Button shows over the search screen (#4995) ([538b2c93e](https://github.com/0xAnasEzz/morphe-patches/commit/538b2c93e))
* **YouTube - Return YouTube Dislike:** Feed thumbnail like count of a card that shows the view count as a text of its own waits until the card is almost fully shown ([e7e31230e](https://github.com/0xAnasEzz/morphe-patches/commit/e7e31230e))
* **YouTube:** The feed stutters while a new page loads, as the elements of the videos are analyzed on the main thread (#4966) ([2afb249d8](https://github.com/0xAnasEzz/morphe-patches/commit/2afb249d8))
* **YouTube:** The feed stutters while scrolling fast with the patches that change the feed cards (#4966) ([4dd04d914](https://github.com/0xAnasEzz/morphe-patches/commit/4dd04d914))
* **YouTube - Litho filter:** Filtered cards leave empty cells in the tablet feed and draw the next card or shelf at the wrong width (#5012) ([6ec006a40](https://github.com/0xAnasEzz/morphe-patches/commit/6ec006a40))
* **YouTube - Restore old video action bar:** Like and dislike buttons have no icon on tablets, and buttons without an icon get one with every layout ([81922fe53](https://github.com/0xAnasEzz/morphe-patches/commit/81922fe53))
* **YouTube - Playback speed:** Music videos played from the downloads keep the default speed ([8efb54c09](https://github.com/0xAnasEzz/morphe-patches/commit/8efb54c09))
* **YouTube - Hide layout components:** AI channel filter misses listed channels whose handle differs in case or has non-ASCII characters ([2263cbe9a](https://github.com/0xAnasEzz/morphe-patches/commit/2263cbe9a))
* **YouTube - Translate posts:** Translate item shows in the menus of some videos ([1a243091b](https://github.com/0xAnasEzz/morphe-patches/commit/1a243091b))
* **YouTube Music - Change miniplayer color:** Do not color the miniplayer gray on a cold start ([799c7cdcb](https://github.com/0xAnasEzz/morphe-patches/commit/799c7cdcb))
* **YouTube - DeArrow:** Make the title icon easier to tap ([615077d03](https://github.com/0xAnasEzz/morphe-patches/commit/615077d03))
* **YouTube Music - Third-party lyrics:** Add local TTML song search and display, fix agent name tag alignment (#4989) ([c1485256e](https://github.com/0xAnasEzz/morphe-patches/commit/c1485256e))
* **Reddit - Settings:** Match the About page to the app background ([efd5f757f](https://github.com/0xAnasEzz/morphe-patches/commit/efd5f757f))
* **YouTube Music - Hide ads:** Hide ad overlay while casting ([14eccbf95](https://github.com/0xAnasEzz/morphe-patches/commit/14eccbf95))
* **YouTube - Navigation bar:** Glass navigation bar is taller with the bottom margin and system navigation buttons or gesture handle (#4991) ([abf73cd43](https://github.com/0xAnasEzz/morphe-patches/commit/abf73cd43))
* **YouTube - Hide layout components:** Hide a new type of survey ([f8987445c](https://github.com/0xAnasEzz/morphe-patches/commit/f8987445c))
* **YouTube - Force original audio:** Shorts keep playing the dubbed audio track ([6c1c47527](https://github.com/0xAnasEzz/morphe-patches/commit/6c1c47527))
* **YouTube Music - Change miniplayer color:** Miniplayer keeps the album color after dismissing the queue ([f60b4d112](https://github.com/0xAnasEzz/morphe-patches/commit/f60b4d112))
* **YouTube - Restore old video action bar:** Save button in the More menu of the action bar has no icon ([e1608cd60](https://github.com/0xAnasEzz/morphe-patches/commit/e1608cd60))
* **YouTube - Autoplay control:** Old player button does not respond to taps, which hide the player controls instead ([99103440e](https://github.com/0xAnasEzz/morphe-patches/commit/99103440e))
* **YouTube - Open system share sheet:** In-app share sheet opens for videos made for kids ([f44dac3ab](https://github.com/0xAnasEzz/morphe-patches/commit/f44dac3ab))
* **YouTube - Translate posts:** Translated text is smaller than the original text (#4972) ([82c50c30f](https://github.com/0xAnasEzz/morphe-patches/commit/82c50c30f))
* **YouTube - Navigation bar:** Glass navigation bar buttons are pushed out of the capsule in incognito mode (#4971) ([73fbfde66](https://github.com/0xAnasEzz/morphe-patches/commit/73fbfde66))
* **YouTube - Spoof video streams:** Mobile Web client waits up to 24 seconds before playing videos with ads ([f0014c44e](https://github.com/0xAnasEzz/morphe-patches/commit/f0014c44e))
* **YouTube - Spoof video streams:** Playback starts slower and reports a playback error for each video with replaced SABR streams ([4aedb185a](https://github.com/0xAnasEzz/morphe-patches/commit/4aedb185a))
* **YouTube - Spoof video streams:** Mobile Web client shows overlapping frames when a live stream starts and fails the playback after seeking back ([ef1a5ff0c](https://github.com/0xAnasEzz/morphe-patches/commit/ef1a5ff0c))
* **YouTube - Spoof video streams:** Mobile Web client plays the previous live stream after switching to another live stream or video ([46b7b622b](https://github.com/0xAnasEzz/morphe-patches/commit/46b7b622b))
* **YouTube - Ambient mode:** Enhanced Ambient mode shows the video through a panel that is dragged up over the player ([343e2c0f3](https://github.com/0xAnasEzz/morphe-patches/commit/343e2c0f3))
* **YouTube - Spoof video streams:** SABR clients buffer far more media ahead than the app player config allows, which can run the app out of memory on long videos ([e1eaba5d9](https://github.com/0xAnasEzz/morphe-patches/commit/e1eaba5d9))
