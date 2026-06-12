# AI SEO Content Production Research

Created: 2026-06-12

This workspace is a practical research and operating kit for producing SEO content with AI assistance. It is built around one principle: AI can accelerate research, structure, and drafting, but ranking-resilient content still needs original value, human judgment, clear evidence, and editorial accountability.

This repository also studies how experienced SEO operators use AI across research, content production, optimization, distribution, and AI-search visibility.

## Why this topic

AI content production is easy to demonstrate badly: generate more pages, faster. The useful question is harder: how do teams combine automation with original information, editorial judgment, technical SEO, measurement, and distribution? This collection focuses on practitioners who operate products, agencies, publications, or in-house content programs and regularly show their work.

## Files

### Operating kit

- [research-brief.md](research-brief.md): Current findings, recommendations, risks, and source links.
- [content-production-workflow.md](content-production-workflow.md): A repeatable workflow from topic selection to refresh.
- [templates/content-brief-template.md](templates/content-brief-template.md): Fill-in template for each article, landing page, or guide.
- [templates/editorial-review-checklist.md](templates/editorial-review-checklist.md): Quality-control checklist before publishing.

### Research collection

- [`research/sources.md`](research/sources.md): Expert directory, source links, dates, annotations, and collection status.
- [`research/linkedin-posts/`](research/linkedin-posts/): Author-organized LinkedIn collection logs and public themes.
- [`research/youtube-transcripts/`](research/youtube-transcripts/): Caption-derived notes, short excerpts, and video metadata.
- [`research/other/`](research/other/): First-party articles, frameworks, and synthesis notes.
- [`scripts/`](scripts/): Reproducible YouTube discovery and transcript utilities.

## Expert set

1. Kevin Indig — Growth Memo; growth and AI-search research.
2. Ryan Law — Ahrefs; AI-search and content strategy backed by Ahrefs data.
3. Bernard Huang — Clearscope; content relevance, AEO, and query fan-out.
4. Ethan Smith — Graphite; programmatic SEO, AEO, and scaled content systems.
5. Mike King — iPullRank; relevance engineering and the AI Search Manual.
6. Aleyda Solis — Orainti and SEOFOMO; technical SEO and AI-search analysis.
7. Lily Ray — Amsive; SEO research, quality systems, and AI-search visibility.
8. Ross Simmonds — Foundation; B2B content distribution and AI-era workflows.
9. Nate Matherson — Positional; content operations, SEO tooling, and interviews.
10. Jake Ward — Byword; AI-assisted content production and programmatic SEO.

Selection favored operating experience, first-party research, repeatable frameworks, and evidence of publishing or teaching from current practice.

## How to Use This Folder

1. Start with the research brief to understand the strategy.
2. Use the workflow for each production cycle.
3. Duplicate the content brief template for every new page.
4. Run the editorial checklist before publishing or updating content.
5. Review [`research/sources.md`](research/sources.md) and expert collection files for practitioner evidence.

## Collection method

Public websites and YouTube search pages were checked on 2026-06-12. YouTube captions can be fetched with `youtube-transcript-api`. Files in the transcript folder contain research notes and limited excerpts, not republished full transcripts. LinkedIn blocks logged-out activity pages behind an auth wall, so those files document profile/activity URLs, access status, and themes verified through each expert's public site, publication, or videos.

Run a transcript capture:

```bash
python3 -m pip install youtube-transcript-api
python3 scripts/fetch_youtube_transcript.py VIDEO_ID output.json
```

## Initial findings

- AI works best as a production layer around a differentiated content strategy, not as the strategy itself.
- Winning workflows separate discovery, briefing, drafting, fact checking, expert input, optimization, distribution, and refreshes.
- Original information gain and brand authority are recurring defenses against commodity output.
- Search visibility now includes citations and recommendations in answer engines, but classic crawlability, relevance, links, and brand demand remain.
- Measurement is moving from rankings alone toward qualified traffic, conversions, assisted discovery, citations, and prompt-level visibility.

## Working Position

AI-assisted content is acceptable when it helps create useful content for people. It becomes risky when it is used to produce large volumes of low-originality pages, keyword-variation pages, unsupported claims, or articles that exist mainly to manipulate search visibility.

The safest production system combines:

- Audience and search-intent research.
- First-hand experience, expert review, original examples, data, or analysis.
- Human editing for accuracy, usefulness, and voice.
- Transparent sourcing and clear ownership.
- Basic technical SEO, internal linking, crawlability, and measurement.

## Limitations

LinkedIn post bodies were not scraped around the platform's authentication wall. Some YouTube captions are auto-generated and may contain errors. Dates marked "accessed" are collection dates when a stable publication date was not available from the public page.
