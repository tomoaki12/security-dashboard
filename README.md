# 🌐 Security Dashboard Global

> 世界主要機関のセキュリティ情報を一画面で確認できる、個人用ダッシュボードツール  
> A personal dashboard to monitor security advisories from major organizations worldwide.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://tomoaki12.github.io/security-dashboard/)
![個人利用](https://img.shields.io/badge/用途-個人利用専用-blue)
![言語](https://img.shields.io/badge/言語-HTML%20%2F%20JavaScript-yellow)

---

## 📋 概要 / Overview

**日本語**  
IPA・JVN・JPCERT/CC（国内）および CISA・NVD・Krebs on Security・The Hacker News・Bleeping Computer・ENISA（海外）から、最新のセキュリティ脆弱性情報・注意喚起をリアルタイムで収集・表示するブラウザベースのダッシュボードです。

**English**  
A browser-based security dashboard that aggregates real-time vulnerability advisories and alerts from major domestic (IPA, JVN, JPCERT/CC) and international (CISA, NVD, Krebs on Security, The Hacker News, Bleeping Computer, ENISA) sources.

---

## ✨ 機能 / Features

| 機能 | 説明 / Description |
|---|---|
| 🔄 自動取得 | ページ読み込み時に最新情報を自動取得 / Auto-fetch on page load |
| 🎨 重要度別カラー | 緊急・重要・警告・注意で色分け表示 / Color-coded by severity |
| 🌍 ソース別フィルター | 国・機関ごとに絞り込み可能 / Filter by source organization |
| 🔍 キーワード検索 | CVE番号・製品名などで検索 / Search by CVE ID, product name, etc. |
| ✅ 既読管理 | 確認済み情報を既読としてマーク / Mark items as read |
| 📝 メモ機能 | 各情報にメモを追加可能 / Add personal notes to each item |
| 💾 ローカル保存 | 既読・メモはブラウザに自動保存 / Auto-saved in browser storage |

---

## 📡 情報ソース / Data Sources

### 🇯🇵 国内 / Japan
| 機関 | 内容 |
|---|---|
| [IPA](https://www.ipa.go.jp/security/) | 重要なセキュリティ情報 |
| [JVN](https://jvndb.jvn.jp/) | 脆弱性情報データベース |
| [JPCERT/CC](https://www.jpcert.or.jp/) | 注意喚起・インシデント情報 |

### 🇺🇸 米国 / United States
| Organization | Content |
|---|---|
| [CISA](https://www.cisa.gov/) | Cybersecurity advisories & alerts |
| [NVD](https://nvd.nist.gov/) | National Vulnerability Database |
| [Krebs on Security](https://krebsonsecurity.com/) | In-depth security news & analysis |
| [The Hacker News](https://thehackernews.com/) | Latest cybersecurity news |
| [Bleeping Computer](https://www.bleepingcomputer.com/) | Malware & ransomware news |

### 🇪🇺 欧州 / Europe
| Organization | Content |
|---|---|
| [ENISA](https://www.enisa.europa.eu/) | EU cybersecurity threat landscape |

---

## 🚀 使い方 / How to Use

**日本語**
1. [こちらのURL](https://tomoaki12.github.io/security-dashboard/) をブラウザで開く
2. ページ読み込み時に自動で最新情報を取得
3. 重要度・ソース・キーワードで絞り込む
4. 確認した情報は「既読にする」ボタンでマーク
5. 気になる情報には「メモ」を残しておく

**English**
1. Open [this URL](https://tomoaki12.github.io/security-dashboard/) in your browser
2. Latest advisories are fetched automatically on page load
3. Filter by severity, source, or keyword
4. Mark reviewed items as "read"
5. Add personal notes to items of interest

---

## ⚠️ 注意事項 / Notes

**日本語**
- 本ツールは**個人利用専用**です
- 既読・メモのデータはブラウザのローカルストレージに保存されます（外部送信なし）
- 情報の取得には外部のRSSプロキシサービス（rss2json.com）を利用しています
- 職場のPCで使用する場合は、所属組織のセキュリティポリシーを必ず確認してください
- 本ツールの情報は参考情報であり、正確性・完全性を保証するものではありません

**English**
- This tool is for **personal use only**
- Read/memo data is stored in browser localStorage only (no external transmission)
- RSS feeds are fetched via rss2json.com as a CORS proxy
- If using on a work PC, please check your organization's security policy
- Information provided is for reference only; accuracy and completeness are not guaranteed

---

## 🛠️ 技術構成 / Tech Stack

- **Frontend**: HTML5 / CSS3 / Vanilla JavaScript
- **Hosting**: GitHub Pages
- **RSS Proxy**: rss2json.com API
- **Fonts**: Google Fonts（Noto Sans JP / JetBrains Mono）
- **Storage**: Browser localStorage

---

## 📄 ライセンス / License

個人利用専用 / For personal use only

---

*Last updated: 2026-02*

