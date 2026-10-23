# hearthtube-reports

Community reports about YouTube videos and channels, collected from HearthTube users: AI generated content,
content that isn't appropriate for some ages, and sponsored content.

This is a plain list for people and tools to read. HearthTube never changes what anyone watches because of a report,
and nothing is sent from the app by itself.

## What a report looks like

One line per report. In HearthTube, open **Settings > General > Reports** and use Share, or copy the text shown.

```
target | id | kind | detail | under-age | date | channel | title
video | dQw4w9WgXcQ | ai_generated | music |  | 2026-10-23 | Some Channel | Some Title
channel | UCxxxxxxxxxxxxxxxxxxxxxx | age |  | 13 | 2026-10-23 | Some Channel | Some Channel
```

- **target**: `video` or `channel`; **id**: the YouTube video id, or the channel id (starts with `UC`).
- **kind**: `ai_generated`, `age` (not appropriate for some ages), `sponsored`, `other`.
- **detail** (optional): for AI generated: `video`, `music`, `voiceover`, `images`, `script`. For sponsored:
  `paid-promotion`, `self-promotion`.
- **under-age**: for `AGE`, the report says "not for under N"; blank when not said.

Reports hold only public facts about the video or channel. No names, accounts or devices.

## How to send reports

Open an issue here and paste the lines. One issue can hold many reports. Please don't include anything personal.

## Where this goes

The aim is better community data. Where an existing project accepts a kind of report (for example
SponsorBlock for sponsored segments, or AiSList for AI channels), the reports here can be passed on to it.
