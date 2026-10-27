# X — Wide Timeline

A [Stylus](https://github.com/openstyles/stylus) UserCSS theme that rewrites the layout of x.com / twitter.com.

## What it does

**Wide screens (≥ 1280px)**

- Left sidebar keeps X's native icon + text navigation, at 275px
- Timeline widens to 860px
- The whole block is centered

**Narrow screens (≤ 1279px)**

- Left sidebar is hidden entirely — just the timeline
- Timeline stays at 860px and centered, shrinking gracefully on smaller windows (no horizontal scroll)

**Always, at any width**

- Right column removed entirely — no Premium upsell, livestreams, trends, or NBA schedules
- Navigation entries hidden: X logo, Chat, Calls, Grok, Premium, Creator Studio
- Grok "explain this post" button on every post hidden
- The avatar next to the compose box hidden

## Install

1. Install the [Stylus](https://github.com/openstyles/stylus) extension
2. Open [`x-focus.user.css`](https://raw.githubusercontent.com/elonwoo/x-focus/main/x-focus.user.css)
3. Click **Install** on the Stylus install page

Or create a new style in Stylus and paste the file contents in.

## License

MIT
