# SillyTavern - WorldInfo Info

**This fork (serina-sketch):** shows which word fired each entry. SillyTavern only logs the key, and a regex key logs as the whole regex, so the extension runs each active entry's keys again on what was scanned (the last messages, by scan depth, then the other active entries' text for recursion). The panel shows a 🔑 line under each entry (`"shock"`, or `"room" in The pink room` when another entry's text pulled it in), the tooltip adds the text around the word, and `/wi-report` shows the word instead of the regex. Upstream: aikohanasaki/SillyTavern-WorldInfoInfo.

Forked from the amazing LenAnderson. Original at https://github.com/LenAnderson/SillyTavern-WorldInfoInfo; this version adds the following features:


Click the book in the lower left corner of the screen to see the list of active entries. 

![list of entries](https://github.com/aikohanasaki/imagehost/blob/main/wii-list.png)

The floating book icon can be dragged to a different location (right-click to enable dragging). To reset its position, use `/wi-position-reset`.
![drag-to-move](https://github.com/aikohanasaki/imagehost/blob/main/wii-dragtomove.png)

🆕 `/wi-report` shows you what keywords triggered which entry during which round of recursion.

![Popup showing /wi-report](https://github.com/aikohanasaki/imagehost/blob/main/worldinfo.png)

Visibility and privacy
- Entries from hidden lorebooks are omitted from /wi-report for non-admin users.
- All counts in the report (summary and per-loop) reflect only visible entries.

![hidden lorebook](https://github.com/aikohanasaki/imagehost/blob/main/wii-listwithhide.png)

![report omits hidden books](https://github.com/aikohanasaki/imagehost/blob/main/wii-hiddenreport.png)

## License

This project is licensed under the GNU Affero General Public License v3.0. See [LICENSE](./LICENSE).