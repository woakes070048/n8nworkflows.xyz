# n8nworkflows.xyz

Standalone and versionable archive of n8n workflows from the official [n8n.io/workflows](https://n8n.io/workflows) website. This repository allows you to preserve, version, and reuse workflow templates in minimal format, ready to be imported offline.

[n8nworkflows.xyz](https://n8nworkflows.xyz)

---

## 📋 Table of Contents

- [Repository Structure](#-repository-structure)
- [Archived Workflow Format](#-archived-workflow-format)
- [Usage](#-usage)
- [Workflows Summary](#-workflows-summary)
- [License](#-license)

---

## 📁 Repository Structure

```
n8nworkflows.xyz/
├── archive/
│   └── workflows/
│       ├── workflow-name-id-1/
│       │   ├── readme.md
│       │   ├── workflow.json
│       │   ├── metadata.json
│       │   └── workflow-name-id-1.webp
│       ├── workflow-name-id-2/
│       │   └── ...
│       └── ...
└── README.md
```

Each workflow is isolated in its own folder to facilitate navigation, versioning, and individual import.

---

## 📄 Archived Workflow Format

Each workflow folder contains **exactly 4 files**:

| File | Description |
|:---|:---|
| **`readme.md`** | Complete workflow description in Markdown (original template's `readme` field) |
| **`workflow.json`** | Raw workflow export in JSON format, ready to be imported into n8n |
| **`metadata.json`** | Metadata: author (`user_*`), tags, creation date, public link to `https://n8n.io/workflows/<workflowId>` |
| **`<slug-and-id>.webp`** | Workflow screenshot (hero image from Supabase `worklowscreenshot` bucket) |

---



## 📚 Workflows Summary (69 workflows)

- [Activate and deactivate workflows on schedule using native n8n API-3229](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Activate%20and%20deactivate%20workflows%20on%20schedule%20using%20native%20n8n%20API-3229)
- [AI Agent for realtime insights on meetings-2651](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI%20Agent%20for%20realtime%20insights%20on%20meetings-2651)
- [AI-Powered n8n Release Notes Summary Notifications via Gmail with GPT-5-Mini-10236](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI-Powered%20n8n%20Release%20Notes%20Summary%20Notifications%20via%20Gmail%20with%20GPT-5-Mini-10236)
- [Auto-Edit Images from Google Drive with Nano Banana and Send via Gmail-8577](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Auto-Edit%20Images%20from%20Google%20Drive%20with%20Nano%20Banana%20and%20Send%20via%20Gmail-8577)
- [Auto-Respond to Slack Messages as Yourself using GPT and Google Docs RAG-7426](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Auto-Respond%20to%20Slack%20Messages%20as%20Yourself%20using%20GPT%20and%20Google%20Docs%20RAG-7426)
- [Automate Assignment Grading with GPT-4-Turbo and Multi-Format Reports-10316](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20Assignment%20Grading%20with%20GPT-4-Turbo%20and%20Multi-Format%20Reports-10316)
- [Automate Audio-Video Transcription in Any Language with the New ElevenLabs Model-3105](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20Audio-Video%20Transcription%20in%20Any%20Language%20with%20the%20New%20ElevenLabs%20Model-3105)
- [Automate CV screening and applicant scoring from Gmail to Airtable with AI-6418](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20CV%20screening%20and%20applicant%20scoring%20from%20Gmail%20to%20Airtable%20with%20AI-6418)
- [Automate Financial Operations with O3 CFO & GPT-4.1-mini Finance Team-6906](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20Financial%20Operations%20with%20O3%20CFO%20&%20GPT-4.1-mini%20Finance%20Team-6906)
- [Automate QuickBooks Customers & Sales Receipts Generation from a Google Sheet-6770](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20QuickBooks%20Customers%20&%20Sales%20Receipts%20Generation%20from%20a%20Google%20Sheet-6770)
- [Automate Twitter Posting with GPT-4 Content Generation & Google Sheets Tracking-8010](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20Twitter%20Posting%20with%20GPT-4%20Content%20Generation%20&%20Google%20Sheets%20Tracking-8010)
- [Automate Your LinkedIn Engagement with AI-Powered Comments! 💬✨-4357](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automate%20Your%20LinkedIn%20Engagement%20with%20AI-Powered%20Comments!%20%F0%9F%92%AC%E2%9C%A8-4357)
- [Automated Lead Response Template using Google Forms, Sheets, and Gmail-6711](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automated%20Lead%20Response%20Template%20using%20Google%20Forms,%20Sheets,%20and%20Gmail-6711)
- [Automated News Monitoring with Claude 4 AI Analysis for Discord & Google News-8452](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automated%20News%20Monitoring%20with%20Claude%204%20AI%20Analysis%20for%20Discord%20&%20Google%20News-8452)
- [Automated Post-Purchase Product Delivery & Upsell with Jotform,  GDrive, Gemini-9582](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automated%20Post-Purchase%20Product%20Delivery%20&%20Upsell%20with%20Jotform,%20%20GDrive,%20Gemini-9582)
- [Automated Sales Follow-Up System Using HighLevel, Gmail, Slack & Google Sheets-10152](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automated%20Sales%20Follow-Up%20System%20Using%20HighLevel,%20Gmail,%20Slack%20&%20Google%20Sheets-10152)
- [Automated Video Download from Sample.cat using Airtop Browser Automation-4522](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automated%20Video%20Download%20from%20Sample.cat%20using%20Airtop%20Browser%20Automation-4522)
- [Automatically Search Facebook Ad Products on Amazon using Apify Scrapers-6888](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Automatically%20Search%20Facebook%20Ad%20Products%20on%20Amazon%20using%20Apify%20Scrapers-6888)
- [Bulk SEO Content Generation with GPT, Gemini Images, and Webflow Draft Creation-9191](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Bulk%20SEO%20Content%20Generation%20with%20GPT,%20Gemini%20Images,%20and%20Webflow%20Draft%20Creation-9191)
- [Business Intelligence Assistant for Slack using Explorium MCP & Claude AI-9935](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Business%20Intelligence%20Assistant%20for%20Slack%20using%20Explorium%20MCP%20&%20Claude%20AI-9935)
- [CallForge - 06 - Automate Sales Insights with Gong.io, Notion & AI-3036](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/CallForge%20-%2006%20-%20Automate%20Sales%20Insights%20with%20Gong.io,%20Notion%20&%20AI-3036)
- [Connect AI Agents to Canada Holidays API with 6 Province and Holiday Operations-5549](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Connect%20AI%20Agents%20to%20Canada%20Holidays%20API%20with%206%20Province%20and%20Holiday%20Operations-5549)
- [Create .SRT Subtitles & .LRC Lyrics from Audio with Whisper AI and GPT-5-nano-9589](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20.SRT%20Subtitles%20&%20.LRC%20Lyrics%20from%20Audio%20with%20Whisper%20AI%20and%20GPT-5-nano-9589)
- [Create a channel, add a member, and post a message to the channel on Mattermost-832](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20a%20channel,%20add%20a%20member,%20and%20post%20a%20message%20to%20the%20channel%20on%20Mattermost-832)
- [Create a Secure MongoDB Data Retrieval API with Input Validation and HTTP Responses-7674](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20a%20Secure%20MongoDB%20Data%20Retrieval%20API%20with%20Input%20Validation%20and%20HTTP%20Responses-7674)
- [Create Linear tickets from Notion content-2138](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20Linear%20tickets%20from%20Notion%20content-2138)
- [Create Stylized Product Photography with Airtable & Gemini Nano Banana-10250](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20Stylized%20Product%20Photography%20with%20Airtable%20&%20Gemini%20Nano%20Banana-10250)
- [Create Viral Multimedia Ads with AI: NanoBanana, Seedance & Suno for Social Media-8428](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Create%20Viral%20Multimedia%20Ads%20with%20AI:%20NanoBanana,%20Seedance%20&%20Suno%20for%20Social%20Media-8428)
- [Customer Support Ticket System for SMEs with Google Sheets and Auto-Emails-8376](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Customer%20Support%20Ticket%20System%20for%20SMEs%20with%20Google%20Sheets%20and%20Auto-Emails-8376)
- [Daily Meeting Summaries with Google Calendar & Gemini for Slack-Discord-WhatsApp-6934](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Daily%20Meeting%20Summaries%20with%20Google%20Calendar%20&%20Gemini%20for%20Slack-Discord-WhatsApp-6934)
- [Dynamic Media Library with On-demand Downloads for Radarr-Sonarr and Plex-6980](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Dynamic%20Media%20Library%20with%20On-demand%20Downloads%20for%20Radarr-Sonarr%20and%20Plex-6980)
- [Enrich Linkedin profile URLs stored in a Google Sheet-2107](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Enrich%20Linkedin%20profile%20URLs%20stored%20in%20a%20Google%20Sheet-2107)
- [EPA Clean Water Act Data Access & Compliance Monitoring API Integration-5623](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/EPA%20Clean%20Water%20Act%20Data%20Access%20&%20Compliance%20Monitoring%20API%20Integration-5623)
- [Extract Information from a Logo Sheet using forms, AI, Google Sheet and Airtable-2650](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Extract%20Information%20from%20a%20Logo%20Sheet%20using%20forms,%20AI,%20Google%20Sheet%20and%20Airtable-2650)
- [Financial News Digest with Google Gemini AI to Outlook Email-4074](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Financial%20News%20Digest%20with%20Google%20Gemini%20AI%20to%20Outlook%20Email-4074)
- [Fix & Resend Guest Order Emails in Magento 2 via REST API-6707](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Fix%20&%20Resend%20Guest%20Order%20Emails%20in%20Magento%202%20via%20REST%20API-6707)
- [Generate Content Ideas with Gemini Pro and Store in Google Sheets-4432](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Content%20Ideas%20with%20Gemini%20Pro%20and%20Store%20in%20Google%20Sheets-4432)
- [Generate Conversational Twitter-X Threads with GPT-4o AI-3441](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Conversational%20Twitter-X%20Threads%20with%20GPT-4o%20AI-3441)
- [Generate Event Badges with QR Codes, HTMLCSStoImage, Gmail & Google Sheets-10130](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Event%20Badges%20with%20QR%20Codes,%20HTMLCSStoImage,%20Gmail%20&%20Google%20Sheets-10130)
- [Generate Multi-Platform Content from Forms using Tavily Research and OpenAI-8649](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Multi-Platform%20Content%20from%20Forms%20using%20Tavily%20Research%20and%20OpenAI-8649)
- [Generate Multi-Platform Social Media Posts with GPT-4.1 and PostPulse-9195](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Multi-Platform%20Social%20Media%20Posts%20with%20GPT-4.1%20and%20PostPulse-9195)
- [Generate Personalized Sales Emails with LinkedIn Data & Claude 3.7 via OpenRouter-5691](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Generate%20Personalized%20Sales%20Emails%20with%20LinkedIn%20Data%20&%20Claude%203.7%20via%20OpenRouter-5691)
- [Get Real-time Stock Analysis and Rankings with Danelfin's AI Analytics API-6541](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Get%20Real-time%20Stock%20Analysis%20and%20Rankings%20with%20Danelfin's%20AI%20Analytics%20API-6541)
- [Gmail Email Auto-Organizer with Google Sheets Rules-8333](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Gmail%20Email%20Auto-Organizer%20with%20Google%20Sheets%20Rules-8333)
- [Health Monitoring System with Grok-3 AI Analysis and Family-Doctor Email Alerts-10525](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Health%20Monitoring%20System%20with%20Grok-3%20AI%20Analysis%20and%20Family-Doctor%20Email%20Alerts-10525)
- [Hostinger Form Lead Capture & Qualification with OpenAI, Beehiiv & Google Sheets-4575](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Hostinger%20Form%20Lead%20Capture%20&%20Qualification%20with%20OpenAI,%20Beehiiv%20&%20Google%20Sheets-4575)
- [Hyper-Personalize Email Outreach with AI, Gmail & Google Sheets-7163](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Hyper-Personalize%20Email%20Outreach%20with%20AI,%20Gmail%20&%20Google%20Sheets-7163)
- [Learn Workflow Logic with Merge, IF & Switch Operations-5996](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Learn%20Workflow%20Logic%20with%20Merge,%20IF%20&%20Switch%20Operations-5996)
- [Monitor Software Compliance with Jamf Patch Summaries in Slack-5529](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Monitor%20Software%20Compliance%20with%20Jamf%20Patch%20Summaries%20in%20Slack-5529)
- [Multi-platform Video Publishing from Google Sheets to 9 Social Networks via Blotato API-4227](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Multi-platform%20Video%20Publishing%20from%20Google%20Sheets%20to%209%20Social%20Networks%20via%20Blotato%20API-4227)
- [N8N for Beginners: Looping over Items-2896](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/N8N%20for%20Beginners:%20Looping%20over%20Items-2896)
- [Notify on Slack when new product is added in WooCommerce-1458](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Notify%20on%20Slack%20when%20new%20product%20is%20added%20in%20WooCommerce-1458)
- [Predict Housing Prices with a Simple Neural Network-9089](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Predict%20Housing%20Prices%20with%20a%20Simple%20Neural%20Network-9089)
- [Predictive Health Monitoring & Alert System with GPT-4o-mini-10457](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Predictive%20Health%20Monitoring%20&%20Alert%20System%20with%20GPT-4o-mini-10457)
- [readme.md](https://github.com/nusquama/n8nworkflows.xyz/blob/main/workflows/readme.md)
- [Retweet Cleanup with Scheduling for X-Twitter-9766](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Retweet%20Cleanup%20with%20Scheduling%20for%20X-Twitter-9766)
- [Save and Log Clipboard Content from macOS to Google Sheets using Shortcuts App-4063](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Save%20and%20Log%20Clipboard%20Content%20from%20macOS%20to%20Google%20Sheets%20using%20Shortcuts%20App-4063)
- [Send Daily 4K Bluray Preorder Updates from Blu-ray.com to Discord-6830](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Send%20Daily%204K%20Bluray%20Preorder%20Updates%20from%20Blu-ray.com%20to%20Discord-6830)
- [Send Daily Real Estate Construction Updates via Gmail & WhatsApp with Google Sheets-6694](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Send%20Daily%20Real%20Estate%20Construction%20Updates%20via%20Gmail%20&%20WhatsApp%20with%20Google%20Sheets-6694)
- [Simple Eval for Legal Benchmarking-4712](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Simple%20Eval%20for%20Legal%20Benchmarking-4712)
- [Simple Google indexing Workflow in N8N-2123](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Simple%20Google%20indexing%20Workflow%20in%20N8N-2123)
- [Tax Deadline Management & Compliance Alerts with GPT-4, Google Sheets & Slack-10108](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Tax%20Deadline%20Management%20&%20Compliance%20Alerts%20with%20GPT-4,%20Google%20Sheets%20&%20Slack-10108)
- [Tesla Financial Market Data Analyst Tool (Multi-Timeframe Technical AI Agent)-4094](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Tesla%20Financial%20Market%20Data%20Analyst%20Tool%20(Multi-Timeframe%20Technical%20AI%20Agent)-4094)
- [Upload Google Drive Files to an InfraNodus Graph-4486](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Upload%20Google%20Drive%20Files%20to%20an%20InfraNodus%20Graph-4486)
- [Validate email of new contacts in Mautic-1462](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Validate%20email%20of%20new%20contacts%20in%20Mautic-1462)
- [YouTube Comment Sentiment Analysis with Google Gemini AI and Google Sheets-3936](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/YouTube%20Comment%20Sentiment%20Analysis%20with%20Google%20Gemini%20AI%20and%20Google%20Sheets-3936)
- [Zendesk Pending Ticket Follow-up System with Gmail, Google Sheets & ClickUp-8743](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Zendesk%20Pending%20Ticket%20Follow-up%20System%20with%20Gmail,%20Google%20Sheets%20&%20ClickUp-8743)
- [✨🤖Automate Multi-Platform Social Media Content Creation with AI-3066](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/%E2%9C%A8%F0%9F%A4%96Automate%20Multi-Platform%20Social%20Media%20Content%20Creation%20with%20AI-3066)
- [🚛🗺️ Geocoding for Logistics with Open Route API and Google Sheets-4593](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/%F0%9F%9A%9B%F0%9F%97%BA%EF%B8%8F%20Geocoding%20for%20Logistics%20with%20Open%20Route%20API%20and%20Google%20Sheets-4593)

---

## 🔗 Useful Links

- 🌐 [n8nworkflows.xyz website](https://n8nworkflows.xyz)
- 📖 [Official n8n Documentation](https://docs.n8n.io)
- 💬 [n8n Community](https://community.n8n.io)
- 🐙 [n8n on GitHub](https://github.com/n8n-io/n8n)

---

## 📝 License

This repository archives public workflows from [n8n.io/workflows](https://n8n.io/workflows). Each workflow retains its original license. Refer to individual metadata for more information.

The archiving code and repository structure are licensed under [MIT](LICENSE).

---

## ⚠️ Disclaimer

This project is **independent** and not officially affiliated with n8n. It is a personal initiative aimed at facilitating access to and preservation of public n8n workflows.

---

**Made with ❤️ for the n8n community**

