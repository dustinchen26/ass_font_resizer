# ass_font_resizer
online tool: https://dustinchen26.github.io/ass_font_resizer

## Example
上傳ass字幕，可以中文字幕變大26，英文字幕變小17，雙語字幕
```
// 原本ass
[Events]
Format: Layer, Start, End, Style, Name, MarginL, MarginR, MarginV, Effect, Text
Dialogue: 0,0:00:31.02,0:00:34.22,Default,NTP,0000,0000,0000,,蜜雪兒 我們實現了 祝我們順利畢業\NWell, Michelle, we did it. Happy graduation.
Dialogue: 0,0:00:40.03,0:00:43.26,Default,NTP,0000,0000,0000,,你知道 住在我父母的家\NYou know, Iiving at my parents' house,

// 後來ass
[Events]
Format: Layer, Start, End, Style, Name, MarginL, MarginR, MarginV, Effect, Text
Dialogue: 0,0:00:31.02,0:00:34.22,Default,NTP,0000,0000,0000,,{\fs26}蜜雪兒 我們實現了 祝我們順利畢業\N{\fs17}Well, Michelle, we did it. Happy graduation.
Dialogue: 0,0:00:40.03,0:00:43.26,Default,NTP,0000,0000,0000,,{\fs26}你知道 住在我父母的家\N{\fs17}You know, Iiving at my parents' house,

```
