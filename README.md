# Free Domain Resources

更新日期：2026-04-27  

## 1. 可独立使用的免费域名 / 子域名

| 平台 | 免费域名形式 | 免费额度 / 形式 | 访问网址 | 限制说明 |
|---|---|---:|---|---|
| EU.org | `yourname.eu.org` 及各地区后缀 | 免费注册 | https://nic.eu.org/ | 人工审核；需提前准备可用 NS；审批时间不固定。 |
| PP.UA | `yourname.pp.ua` | 免费注册 | https://pp.ua/ | 通过认证注册商注册；通常需要激活验证；适合作为独立免费域名使用。 |
| is-a.dev | `yourname.is-a.dev` | 免费子域名 | https://is-a.dev/ | 面向开发者；通过 GitHub PR 提交 DNS 记录；公开审核。 |
| JS.ORG | `project.js.org` | 免费子域名 | https://js.org/ | 面向 JavaScript 项目；通常用于 GitHub Pages；项目内容需与 JavaScript 有关联。 |
| FreeDNS / afraid.org | 共享域名下的子域名 | 免费账户最多 5 个子域名 | https://freedns.afraid.org/ | 可指向任意 IP/主机；支持静态 DNS 和动态 DNS；共享域名质量不一。 |
| deSEC / dedyn.io | `yourname.dedyn.io` | 免费 dynDNS 域名 | https://desec.io/ | 免费 DNS 服务；dedyn.io 动态域名适合家庭服务器、VPS、DDNS。 |
| DuckDNS | `yourname.duckdns.org` | 通常最多 5 个域名 / 账号 | https://www.duckdns.org/ | 免费 DDNS；适合家庭网络、NAS、临时服务；TXT 记录能力有限。 |
| Dynu | `yourname.dynu.com` 等 | 免费账户 4 个 hostnames | https://www.dynu.com/ | 免费账户长期可用；支持 DDNS、A/AAAA/CNAME、MX 等；高级功能需会员。 |
| No-IP | 多个 No-IP 自有域名下的 hostname | 免费账户 1 个 hostname | https://www.noip.com/remote-access | 每 30 天需确认一次；不含 SSL 证书；适合远程访问。 |
| ClouDNS | `yourname.cloudns.org` 等 | 免费 DNS：1 个 DNS zone、50 条记录、1 个 DDNS hostname、50 万 DNS 查询/月 | https://www.cloudns.net/ | 提供免费 DNS 与动态 DNS；免费套餐适合小型项目。 |
| ChangeIP | 预选域名下的 DDNS hostname | 免费 Dynamic DNS Hosting | https://www.changeip.com/dns/ | 适合动态 IP 远程访问；具体可选域名以控制台为准。 |
| YDNS | YDNS 提供的免费域名 / 自有域名 DNS | 免费 DNS Hosting + Dynamic DNS | https://ydns.io/ | 支持动态 DNS 和自有域名 DNS 托管；适合自托管服务。 |
| MyDNS.JP | MyDNS.JP 免费子域名 | 免费 DDNS | https://www.mydns.jp/ | 日本免费 DDNS；支持 IPv4/IPv6、通配符、邮件转发等。 |
| dynv6 | `yourname.dynv6.net`、`dns.army`、`v6.rocks` 等 | 免费动态 DNS | https://dynv6.com/ | 重点支持 IPv6，也支持 IPv4；适合家庭宽带、IPv6 服务。 |
| DDNS Now | `yourname.f5.si` | 永久免费 DDNS | https://ddns.kuku.lu/ | 日本服务；无需定期续期；主域名较短。 |

## 2. 部署平台自带免费访问域名

| 平台 | 免费域名形式 | 免费额度 / 形式 | 访问网址 | 限制说明 |
|---|---|---:|---|---|
| GitHub Pages | `username.github.io`、`username.github.io/repo` | GitHub Free 可用 | https://pages.github.com/ | 静态站点；`github.io` 默认 HTTPS；可绑定自有域名。 |
| GitLab Pages | `namespace.gitlab.io` | GitLab Free 可用 | https://docs.gitlab.com/user/project/pages/ | 静态站点；默认 `gitlab.io` 支持 HTTPS。 |
| Cloudflare Pages | `project.pages.dev` | 免费计划可用 | https://pages.cloudflare.com/ | 每个 Pages 项目自动获得 `pages.dev` 子域名；软限制约 100 个项目。 |
| Vercel | `project.vercel.app` | Hobby 免费计划可用 | https://vercel.com/ | 每个部署自动分配 `vercel.app` 域名；名称先到先得。 |
| Netlify | `project.netlify.app` | Free plan 可用 | https://www.netlify.com/ | 默认 Netlify 子域名；适合静态站点、前端 Demo。 |
| Render | `service.onrender.com` | 免费 Web Service / Static Site 可用 | https://render.com/ | 每个 Web Service 有唯一 `onrender.com` 子域名；免费实例有休眠等限制。 |
| Koyeb | `app-org-hash.koyeb.app` | 免费账户可创建应用 | https://www.koyeb.com/ | 每个 App 自动获得 `koyeb.app` 子域名；实际可用资源以 Koyeb 免费计划为准。 |
| Railway | `service.up.railway.app` | 生成 Railway-provided domain | https://railway.com/ | 服务需手动 Generate Domain；免费/试用资源随账户政策变化。 |
| Replit | `subdomain.replit.app` | 静态部署可用 | https://replit.com/ | 发布应用后获得 `replit.app` 子域名；高级部署能力可能受套餐限制。 |
| Hugging Face Spaces | `space-subdomain.hf.space` | 免费创建公开 Space | https://huggingface.co/spaces | 每个 Space 有唯一 `hf.space` URL；自定义域名需要 Pro / Team / Enterprise。 |
| Firebase Hosting | `project.web.app`、`project.firebaseapp.com` | Firebase Spark 免费计划可用 | https://firebase.google.com/docs/hosting | 默认分配 Firebase 域名；适合静态站点、SPA、轻量 Web App。 |
| Surge | `project.surge.sh` | 免费发布静态站点 | https://surge.sh/ | 静态站点部署；支持免费自定义域名绑定。 |
| Neocities | `username.neocities.org` | 免费站点子域名 | https://neocities.org/ | 免费版含 1 GB 存储、200 GB 带宽；自定义域名需 Supporter。 |
| InfinityFree | `yourname.great-site.net`、`yourname.rf.gd` | 免费主机附带子域名 | https://www.infinityfree.com/ | 子域名通常只能用于 InfinityFree 托管环境。 |
| AwardSpace | 平台提供的免费子域名 | 免费主机可建最多 3 个免费子域名 | https://www.awardspace.com/free-hosting/ | 免费主机附带；适合 PHP/MySQL 小站点。 |
| Deno Deploy | Deno Deploy 默认项目域名 | 免费计划可用 | https://deno.com/deploy | 适合 Deno/Edge 应用；免费计划含请求、流量、CPU 时间限制。 |

## 3. 学生可领取的免费独立域名

| 平台 | 免费域名形式 | 免费额度 / 形式 | 访问网址 | 限制说明 |
|---|---|---:|---|---|
| Namecheap for GitHub Students | `.me` | GitHub 学生认证后免费 1 年 `.me` 域名 + 1 年 SSL | https://nc.me/landing/github | 需 GitHub Student Developer Pack；部分学校/地区可用性可能不同；续费按标准价格。 |
| Name.com for GitHub Students | `.rocks`、`.ninja`、`.games`、`.codes`、`.systems`、`.studio`、`.email`、`.works`、`.software`、`.engineer`、`.live`、`.app`、`.dev`、`.page`、`.foo` 等 | GitHub 学生认证后免费 1 年 | https://www.name.com/partner/github-students | 需要付款方式在档；免费期结束后按标准价格续费。 |
| .TECH Student Domain | `.tech` | GitHub Student Developer Pack 可领取赞助 `.tech` 域名 | https://get.tech/github-student-developer-pack | 需 GitHub 学生认证；通常为 1 年期，续费按注册商价格。 |

## 4. 快速选择

| 需求 | 可优先使用的资源 |
|---|---|
| 想要接近“独立域名”的长期免费资源 | EU.org、PP.UA |
| 想给个人项目一个开发者风格域名 | is-a.dev、JS.ORG |
| 家庭服务器 / NAS / 动态 IP 远程访问 | DuckDNS、Dynu、No-IP、deSEC、ClouDNS、dynv6、MyDNS.JP |
| 静态站点 / 前端 Demo | GitHub Pages、Cloudflare Pages、Vercel、Netlify、Surge、Firebase Hosting |
| ML Demo / Agent Web UI | Hugging Face Spaces、Render、Koyeb、Replit |
| 学生领取真实独立域名 | Namecheap `.me`、Name.com 多后缀、`.tech` |
