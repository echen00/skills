# Story to Hand-drawn Video

This directory contains the installable skill package copied from
[gnipbao/story-to-handdrawn-video](https://github.com/gnipbao/story-to-handdrawn-video).

- Upstream source: `skill-package/story-to-handdrawn-video/`
- Upstream commit: `198aefa9b298af3a20d3bd757c93433623d38ccd`
- License: MIT, copyright 2026 gnipbao; see [LICENSE](LICENSE).
- The five upstream skill files are unchanged.

## Runtime requirement

This is the skill package, not the complete video renderer. To render videos,
clone the upstream project, install its dependencies following its README, and
run the skill from that project or set `STORY_VIDEO_PROJECT` to its absolute path.
The wrapper in `scripts/run_story_video.py` delegates to that project's renderer.

Install this skill from:
https://github.com/echen00/skills/tree/main/story-to-handdrawn-video

See [SKILL.md](SKILL.md) for the workflow and usage examples.
