# typst-quic-style

![](thumbnails/typst-quic-style-design.png)

This is a typst template for creating papers in the Taniii style. Forked from https://github.com/JamesxX/graceful-genetics; Thanks for the original work.

## 日本語対応

- 段落の字下げ (見出しの直下も字下げする)
- 行間
- 日本語フォント (Zen Kaku Gothic New, Zen Old Mincho)
- 表の上にキャプション

など...

## Media

<p align="center">
  <img alt="paper" src="./thumbnails/paper.jpg" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="progress report" src="./thumbnails/progress_report.jpg" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
</p>

<p align="center">
  <img alt="note" src="./thumbnails/note.jpg" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="log" src="./thumbnails/log.jpg" width="45%">
</p>

## Getting Started

To use this template, simply import it as shown below:

```typ
#import "@local/typst-quic-style:0.0.1"

#show: typst-quic-style.template.with(
  title: [タイトル],
  authors: (
    (
      name: "name",
      department: "department",
      institution: "institution",
      city: "city",
      country: "country",
      mail: "mail@example.com",
    ),
  ),
  date: (
    year: 2025,
    month: "May",
    day: 7,
  ),
  keywords: (
    "Space",
    "Mail",
    "Astromail",
    "Faster-than-Light",
    "Mars",
  ),
  doi: "",
  abstract: [
    Recent advances in space-based document processing have enabled faster mail delivery between different planets of a solar system. Given the time it takes for a message to be transmitted from one planet to the next, its estimated that even a one-way trip to a distant destination could take up to one year. During these periods of interplanetary mail delivery there is a slight possibility of mail being lost in transit. This issue is considered so serious that space management employs P.I. agents to track down and retrieve lost mail. We propose A-Mail, a new anti-matter based approach that can ensure that mail loss occurring during interplanetary transit is unobservable and therefore potentially undetectable. Going even further, we extend A-Mail to predict problems and apply existing and new best practices to ensure the mail is delivered without any issues. We call this extension AI-Mail.
  ]
)

// セクション
= 1.
```
