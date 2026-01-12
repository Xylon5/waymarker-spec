# Type Convention

All events use a hierarchical type identifier:

<layer>.<namespace>.<name>[.vN]

Where:
- layer ∈ {fact, interp, narr}
- namespace groups related concepts
- vN is used only for breaking semantic changes

Examples:
- fact.drive.segment.highway
- interp.drive.style.aggressive
- narr.chapter.drive_segment
