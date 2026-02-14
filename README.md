# Postiz CLI (postiz-agent)

**Social media automation CLI for AI agents** - Schedule posts across 28+ platforms programmatically.

[![npm version](https://img.shields.io/npm/v/postiz.svg)](https://www.npmjs.com/package/postiz)
[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://opensource.org/licenses/AGPL-3.0)

The Postiz CLI provides a command-line interface to the [Postiz](https://postiz.com) API, enabling developers and AI agents to automate social media posting, manage content, and handle media uploads across platforms like Twitter/X, LinkedIn, Reddit, YouTube, TikTok, Instagram, Facebook, and more.

---

## 🚀 Quick Start

### Installation

\`\`\`bash
npm install -g postiz
# or
pnpm install -g postiz
\`\`\`

### Setup

\`\`\`bash
export POSTIZ_API_KEY=your_api_key_here
\`\`\`

Get your API key from [postiz.com/settings/api](https://postiz.com/settings/api)

### First Post

\`\`\`bash
# List your integrations
postiz integrations:list

# Schedule a post
postiz posts:create \\
  -c "Hello from Postiz CLI! 🚀" \\
  -s "2024-12-31T12:00:00Z" \\
  -i "your-integration-id"
\`\`\`

---

## ✨ Features

- ✅ **28+ platforms** - Twitter/X, LinkedIn, Reddit, YouTube, TikTok, Instagram, Facebook, and more
- ✅ **Scheduled posting** - Required date with schedule/draft modes
- ✅ **Threaded posts** - Main post + comments, each with own media
- ✅ **Platform-specific settings** - Auto-detection from integration ID
- ✅ **Integration tools** - Fetch dynamic data (Reddit flairs, YouTube playlists, LinkedIn companies)
- ✅ **Media upload** - Images, videos, audio, documents
- ✅ **Multi-platform** - Post to multiple platforms at once
- ✅ **JSON mode** - Complex posts via files
- ✅ **AI agent ready** - Full automation support

For complete documentation, see the files in this repository.

---

## 📄 License

AGPL-3.0 - See [LICENSE](./LICENSE) file for details.

---

## 🔗 Links

- **Website:** [postiz.com](https://postiz.com)
- **GitHub:** [github.com/gitroomhq/postiz-agent](https://github.com/gitroomhq/postiz-agent)
- **Main Project:** [github.com/gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)

---

**Ready to automate your social media? Get started with \`npm install -g postiz\`! 🚀**
