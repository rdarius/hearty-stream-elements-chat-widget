# F2U ~ Heart Shaped Chat Widget ~ for StreamElements

Original code from: https://ko-fi.com/s/76ed4108a5

Check them out and support them for this great widget!

-----

This repository has some changes made in original code, to make it easier to change colors of the widget to make it fit your stream asthetics!

-----

## Changes that were been made

- Renamed files (for text editor's highlighting support):
    - `css.txt` -> `css.css`
    - `js.txt` -> `js.js`
    - `html.txt` -> `html.html`
    - `data.txt` -> `data.json`
    - `fields.txt` -> `fields.json`

- extracted all color settings to variables
    - in `css.css` as `:root{...}` stylesheet variables
    - in `js.js` as `colorSettings` javascript data object

---
---
# Colors mapping


## Message Icons

---

### Streamer

`js.js` > `colorSettings.streamerIconColor`

![streamer](/imgs/streamer.png)

### Mod

`js.js` > `colorSettings.modIconColor`

![mod](/imgs/mod.png)

### VIP

`js.js` > `colorSettings.vipIconColor`

![vip](/imgs/vip.png)

### Sub

`js.js` > `colorSettings.subIconColor`

![sub](/imgs/sub.png)

---

## Streamer's Messages

---

`css.css` > `--rouded-corners-and-heart-next-to-username-color`

![1](/imgs/1.png)

---

`css.css` > `--top-right-heart-and-bottom-left-heart-color`

![2](/imgs/2.png)

---

`css.css` > `--top-and-bottom-border-lines-color`

![3](/imgs/3.png)

---

`js.js` > `colorSettings.streamerRightBorderColor`

![4](/imgs/4.png)

---


## Non-Streamer's Messages

---

`js.js` > `colorSettings.messageMentionedUsernameColor`

![7](/imgs/7.png)

---

`js.js` > `colorSettings.nonStreamerHeartTopLeftColor`

![8](/imgs/8.png)

---

`js.js` > `colorSettings.heartInChatBubbleOnTheRightColor`

![9](/imgs/9.png)

---

`js.js` > `colorSettings.nonStreamerTopRightCornerColor`

![10](/imgs/10.png)

---

`js.js` > `colorSettings.nonStreamerBottomRightCornerColor`

![11](/imgs/11.png)

---

`js.js` > `colorSettings.nonStreamerBottomLeftCornerColor`

![12](/imgs/12.png)

---

`js.js` > `colorSettings.nonStreamerHeartBottomLeftColor`

![13](/imgs/13.png)

---

`css.css` > `--right-border-color`

![14](/imgs/14.png)

---

`css.css` > `--bottom-border-color`

![15](/imgs/15.png)

---

`css.css` > `--top-border-color`

![16](/imgs/16.png)

---

`css.css` > `--top-right-border-piece-color`

![17](/imgs/17.png)

---


## All Messages

---


`js.js` > `colorSettings.cornerPieceUnderBadgeColor`

![5](/imgs/5.png)

---

`js.js` > `colorSettings.messageMentionedUsernameColor`

![6](/imgs/6.png)

---

`css.css` > `--background-gradient-top-color`

![18](/imgs/18.png)

---

`css.css` > `--background-gradient-bottom-color`

![19](/imgs/19.png)

---

`css.css` > `--message-text-color`

![20](/imgs/20.png)

---

`css.css` > `--mod-icon-background-color`

![21](/imgs/21.png)

---

`css.css` > `--username-bubble-background-color`

![22](/imgs/22.png)

---

`css.css` > `--username-bubble-text-color`

![23](/imgs/23.png)

---

## Events

---

`js.js` > `colorSettings.eventBorderTopRightCornerColor`

![24](/imgs/24.png)

---

`js.js` > `colorSettings.eventBorderTopLeftCornerColor`

![25](/imgs/25.png)

---

`js.js` > `colorSettings.eventBorderBottomRightCornerColor`

![26](/imgs/26.png)

---

`js.js` > `colorSettings.eventBorderBottomLeftCornerColor`

![27](/imgs/27.png)

---

`js.js` > `colorSettings.eventTopLeftHeartColor`

![28](/imgs/28.png)

---

`js.js` > `colorSettings.eventTopRightHeartColor`

![29](/imgs/29.png)

---

`js.js` > `colorSettings.eventBottomHeartColor`

![30](/imgs/30.png)

---

`js.js` > `colorSettings.eventLeftHeartColor`

![31](/imgs/31.png)

---

`js.js` > `colorSettings.eventBackgroundLeftEnvelopeInsidesColor`

![32](/imgs/32.png)

---

`js.js` > `colorSettings.eventBackgroundLeftEnvelopeOuterBorderColor`

![33](/imgs/33.png)

---

`js.js` > `colorSettings.eventBackgroundLeftEnvelopeBottomLeftInsideLineColor`

![34](/imgs/34.png)

---

`js.js` > `colorSettings.eventBackgroundLeftEnvelopeBottomRightInsideLineColor`

![35](/imgs/35.png)

---

`js.js` > `colorSettings.eventBackgroundLeftEnvelopeInsideTopLinesColor`

![36](/imgs/36.png)

---

`js.js` > `colorSettings.eventBackgroundRightEnvelopeInsidesColor`

![37](/imgs/37.png)

---

`js.js` > `colorSettings.eventBackgroundRightEnvelopeOuterBorderColor`

![38](/imgs/38.png)

---

`js.js` > `colorSettings.eventBackgroundRightEnvelopeBottomLeftInsideLineColor`

![39](/imgs/39.png)

---

`js.js` > `colorSettings.eventBackgroundRightEnvelopeBottomRightInsideLineColor`

![40](/imgs/40.png)

---

`js.js` > `colorSettings.eventBackgroundRightEnvelopeInsideTopLinesColor`

![41](/imgs/41.png)

---

`js.js` > `colorSettings.eventBackgroundLeftHeartColor`

![42](/imgs/42.png)

---

`js.js` > `colorSettings.eventBackgroundLeftWhiskersColor`

![43](/imgs/43.png)

---

`js.js` > `colorSettings.eventBackgroundRightWhiskersColor`

![44](/imgs/44.png)

---

When subscribed:

`js.js` > `colorSettings.eventBackgroundSubscribeHeartLeftColor`

When re-subscribed:

`js.js` > `colorSettings.eventBackgroundReSubscribeHeartLeftColor`

When gifted more than one sub:

`js.js` > `colorSettings.eventBackgroundGiftManyHeartLeftColor`

When gifted one sub:

`js.js` > `colorSettings.eventBackgroundGiftOneHeartLeftColor`

When giving bits:

`js.js` > `colorSettings.eventBackgroundCheerHeartLeftColor`

When donating:

`js.js` > `colorSettings.eventBackgroundDonationHeartLeftColor`

![45](/imgs/45.png)

---

When subscribed:

`js.js` > `colorSettings.eventBackgroundSubscribeHeartRightColor`

When re-subscribed:

`js.js` > `colorSettings.eventBackgroundReSubscribeHeartRightColor`

When gifted more than one sub:

`js.js` > `colorSettings.eventBackgroundGiftManyHeartRightColor`

When gifted one sub:

`js.js` > `colorSettings.eventBackgroundGiftOneHeartRightColor`

When giving bits:

`js.js` > `colorSettings.eventBackgroundCheerHeartRightColor`

When donating:

`js.js` > `colorSettings.eventBackgroundDonationHeartRightColor`

![46](/imgs/46.png)

---

`css.css` > `--event-background-gradient-top-color`

![47](/imgs/47.png)

---

`css.css` > `--event-background-gradient-bottom-color`

![48](/imgs/48.png)

---

`css.css` > `--event-right-border-color`

![49](/imgs/49.png)

---

`css.css` > `--event-icon-background-color`

![50](/imgs/50.png)

---

`css.css` > `--event-text-color`

![51](/imgs/51.png)

---

`css.css` > `--event-top-center-border-color`

![53](/imgs/53.png)

---

`css.css` > `--event-top-right-border-color`

![54](/imgs/54.png)

---

`css.css` > `--event-bottom-left-border-color`

![55](/imgs/55.png)

---

`css.css` > `--event-bottom-right-border-color`

![56](/imgs/56.png)

---

`css.css` > `--event-left-top-border-color`

![57](/imgs/57.png)

---

`css.css` > `--event-left-bottom-border-color`

![58](/imgs/58.png)

---