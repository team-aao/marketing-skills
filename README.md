# AAO Marketing Skills

Marketing skills for Claude Code, used by [Aus Asia Online](https://ausasiaonline.com.au). Forty-four skills covering CRO, copywriting, SEO, AI SEO, paid ads, ad creative, growth, and more. Each one is `aao-` prefixed so it sits cleanly alongside the built-in Anthropic skills without name clashes.

Based on [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT), renamed for the AAO workspace.

## Install

### As a plugin (works in CLI and the browser-based Claude Code)

```
/plugin marketplace add ausasiaonline/aao-marketing-skills
/plugin install aao-marketing-skills
```

(Replace `ausasiaonline` with your GitHub account if you forked it elsewhere.)

### As personal skills (local CLI only)

Copy the folders into your personal skills directory:

```
cp -r skills/aao-* ~/.claude/skills/
```

Then restart Claude Code so the loader picks them up.

## Usage

Invoke any skill by its name, for example:

- `/aao-marketing-plan`
- `/aao-cro`
- `/aao-seo-audit`
- `/aao-prospecting`

## The skills

`aao-ab-testing`, `aao-ad-creative`, `aao-ads`, `aao-ai-seo`, `aao-analytics`,
`aao-aso`, `aao-churn-prevention`, `aao-co-marketing`, `aao-cold-email`,
`aao-community-marketing`, `aao-competitor-profiling`, `aao-competitors`,
`aao-content-strategy`, `aao-copy-editing`, `aao-copywriting`, `aao-cro`,
`aao-customer-research`, `aao-directory-submissions`, `aao-emails`,
`aao-free-tools`, `aao-image`, `aao-launch`, `aao-lead-magnets`,
`aao-marketing-ideas`, `aao-marketing-plan`, `aao-marketing-psychology`,
`aao-onboarding`, `aao-paywalls`, `aao-popups`, `aao-pricing`,
`aao-product-marketing`, `aao-programmatic-seo`, `aao-prospecting`,
`aao-public-relations`, `aao-referrals`, `aao-revops`, `aao-sales-enablement`,
`aao-schema`, `aao-seo-audit`, `aao-signup`, `aao-site-architecture`,
`aao-sms`, `aao-social`, `aao-video`

## Licence

MIT. See [LICENSE](LICENSE). Original work © Corey Haines; AAO modifications © Aus Asia Online.
