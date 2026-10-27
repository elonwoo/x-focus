# x-focus

A UserCSS for [Stylus](https://github.com/openstyles/stylus) that reworks the layout of x.com / twitter.com.

## What it does

**Wide screens (≥ 1280px)**

- Left sidebar at 256px, keeping X's native icon + text navigation
- Timeline widened to 860px, centered as a whole
- Navigation sits directly under the search box

**Narrow screens (≤ 1279px)**

- Left sidebar hidden entirely, timeline only
- Timeline stays 860px and centers, shrinking gracefully on smaller windows with no horizontal scroll

**At any width**

- Right column removed entirely (Premium, livestreams, trends, NBA)
- Hidden nav entries: X logo, Chat, Calls, Grok, Premium, Creator Studio, the post button, the account block
- Hidden Grok "explain this post" button and the compose box avatar
- Hidden the floating dock, the "posted" toast, and the mobile bottom tab bar
- Hidden the header logo bar and the "Live on X" card

## Install

1. Install the [Stylus](https://github.com/openstyles/stylus) extension
2. Open [`x-focus.user.css`](https://raw.githubusercontent.com/elonwoo/x-focus/main/x-focus.user.css)
3. Click **Install** on the Stylus install page

## License

MIT
