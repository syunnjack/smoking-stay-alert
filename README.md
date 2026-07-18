# Smoking Stay Alert

喫煙可ホテル・バストイレ付き宿通知

## Repository

Recommended repository name: `smoking-stay-alert`

## Domain candidates

Confirmed domain: `smokingstay.jp`

Other candidates:

- `smokingstay.jp`
- `kitsuenstay.jp`
- `smokehotel.jp`
- `btstay.jp`

## Concept

喫煙可、バストイレ付き、深夜チェックインなど条件特化の空室通知で宿泊予約へ送客するサービス。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 宿泊予約
- 条件検索プレミアム
- ホテル掲載
- クーポン送客
- 法人出張導線

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
