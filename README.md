# LinkedIn Ads MCP Server by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/linkedin-ads)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Connect LinkedIn Ads to AI assistants for B2B advertising analytics and campaign optimization.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — The LinkedIn Ads MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to analyze your LinkedIn advertising campaigns. Optimize B2B marketing, track lead generation, and get AI-powered recommendations.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![LinkedIn Ads MCP Server](https://insightfulpipe.com/images/linkedin-app-icon.svg)

## MCP Server URL

```
https://linkedin-ads.insightfulmcp.com/
```

## What is LinkedIn Ads MCP?

LinkedIn Ads MCP is a **remote Model Context Protocol server** that connects your LinkedIn Campaign Manager to AI assistants. This B2B-focused integration allows you to:

- Query LinkedIn ad performance using natural language
- Analyze audience targeting effectiveness
- Track lead generation and conversion metrics
- Get AI recommendations for campaign optimization
- Access demographic and creative analytics

## Installation

### Claude

1. Copy the MCP Server URL: `https://linkedin-ads.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://linkedin-ads.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add linkedin-ads https://linkedin-ads.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://linkedin-ads.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

| Action | Description |
|--------|-------------|
| `get_accounts` | List all ad accounts accessible to the authenticated user |
| `get_campaigns` | List campaigns for an ad account |
| `get_campaign` | Fetch details for a single campaign |
| `get_campaign_groups` | List campaign groups for an ad account |
| `get_campaign_group` | Fetch details for a single campaign group |
| `get_creatives` | List creatives for an ad account |
| `get_creative` | Fetch details for a single creative |
| `get_conversions` | List conversion tracking rules for an ad account |
| `get_lead_forms` | List lead generation forms for an ad account |
| `get_budget_pricing` | Get bid pricing insights based on targeting criteria |
| `get_tracking_params` | Get UTM tracking parameters for a campaign |
| `get_analytics` | Retrieve analytics/performance data for campaigns or creatives |
| `get_campaign_analytics` | Retrieve analytics grouped by campaign |
| `get_account_analytics` | Retrieve analytics for the entire ad account |
| `get_campaign_group_analytics` | Retrieve analytics grouped by campaign group |
| `get_creative_analytics` | Retrieve analytics grouped by creative |
| `get_demographic_analytics` | Retrieve analytics grouped by member demographics |

## Usage Examples

### Campaign Performance

```
"How are my LinkedIn ad campaigns performing this quarter?"
```

### Audience Analysis

```
"Which industries have the lowest cost per lead?"
```

### Lead Generation

```
"Show me lead form performance for my latest campaigns"
```

### Demographic Insights

```
"What job titles are converting best on my LinkedIn ads?"
```

### Budget Optimization

```
"Which campaigns should I allocate more budget to?"
```

## Supported Metrics

| Metric | Description |
|--------|-------------|
| Impressions | Total ad views |
| Clicks | Total ad clicks |
| CTR | Click-through rate |
| CPC | Cost per click |
| CPL | Cost per lead |
| Lead Form Opens | Users who opened lead forms |
| Lead Form Submissions | Completed lead forms |
| Social Actions | Likes, comments, shares |

## Why LinkedIn Ads MCP?

### For B2B Marketers
- **Professional targeting** - Analyze job-based targeting
- **Lead quality insights** - Beyond just volume
- **ABM support** - Account-level analytics

### For Demand Generation
- **Funnel tracking** - Lead to MQL analysis
- **Cost optimization** - Reduce CPL efficiently
- **Channel comparison** - LinkedIn vs other channels

### For Agencies
- **Multi-account management** - Handle B2B clients
- **Reporting automation** - Generate client reports
- **Performance benchmarking** - Industry comparisons

## Security & Privacy

- **LinkedIn Marketing Partner** - Official integration
- **OAuth 2.0** - Secure LinkedIn authentication
- **Read-only access** - Safe analytics queries
- **Enterprise security** - SOC 2 compliant

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### Advertising MCP Servers
- [Google Ads MCP](https://insightfulpipe.com/mcp-servers/google-ads) - Search advertising
- [Facebook Ads MCP](https://insightfulpipe.com/mcp-servers/facebook-ads) - Social advertising
- [Microsoft Ads MCP](https://insightfulpipe.com/mcp-servers/microsoft-ads) - Bing advertising

### B2B Tools
- [Enrichment MCP](https://insightfulpipe.com/mcp-servers/enrichment) - Lead enrichment
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Website analytics

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/linkedin-ads)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
