# New York State Broker License 完整研究報告

> 研究日期：2026-04-04 | 五輪自動研究 | 資料來源：NY DOS, NY DFS, FINRA, CBP, FMCSA, NFA 官方網站

---

## Cover Letter

本報告係針對紐約州所有類型 Broker License 的全面研究成果，涵蓋 12 種不同的經紀人執照類型，橫跨聯邦、州、市三個監管層級，由 6 個不同的政府機構管轄。

研究透過五輪自動化搜尋（每 3 分鐘一輪），系統性地從各官方網站（NY DOS, NY DFS, FINRA, SEC, CBP, FMCSA, NFA, NMLS）擷取第一手資料，並經由 Codex CLI（GPT-5.4）獨立交叉審查，確保事實準確性。

本報告適用對象包括：計畫在紐約州從事經紀業務的個人或企業、需要查驗經紀人資格的消費者、以及需要了解跨類型監管差異的法律從業人員。

**免責聲明**：本報告為研究草稿，資料基於 2026 年 4 月 4 日擷取的公開資訊。法規可能隨時變動，正式決策前請以各主管機關官方網站為準。部分 2025-2026 年的前瞻性變動尚未經官方最終確認。

---

## Abstract

本研究報告全面調查紐約州 12 種 Broker License 類型，涵蓋不動產經紀（Real Estate Broker）、保險經紀（Insurance Broker）、房貸仲介（Mortgage Broker/Banker）、證券經紀（Stockbroker）、報關行（Customs Broker）、貨運仲介（Freight Broker）、期貨仲介（Commodity Broker）、企業買賣仲介（Business Broker）、當鋪（Pawnbroker）、票券轉售商（Ticket Reseller）及遊艇經紀（Yacht Broker）。

研究發現：(1) 12 種 Broker 分屬 6 個不同監管機構，橫跨聯邦、州、市三個層級；(2) 初始費用從 $0（Business Broker，免照）到 $11,111（Freight Broker）不等；(3) 考試難度差異極大，Customs Broker 的 CBLE 通過率僅 12-30%，為全美最難；(4) 紐約不動產經紀執照與任何州均無全面 reciprocity，僅與 9 州/地區有 Mutual Recognition；(5) 2025-2026 年間有多項重大法規變動，包括 PCDS 新表、DFS 系統遷移、及 cybersecurity 執法加強。

報告同時整理了線上查驗工具、投訴流程、繼續教育要求、背景調查機制、以及常見違規案例與判例，為紐約州 Broker License 體系提供最完整的中文參考資料。

---

## 一、總覽比較表

| # | Broker 類型 | 主管機關 | 層級 | 年齡 | 教育時數 | 考試 | 初始費用 |
|---|------------|---------|------|------|---------|------|---------|
| 1 | Real Estate Broker | NY DOS | 州級 | 20+ | 152 hr | DOS 筆試 | ~$200 |
| 2 | Insurance Broker (P&C / Life) | NY DFS | 州級 | 18+ | Pre-licensing | NYS 保險考試 | ~$100-300 |
| 3 | Mortgage Broker | NY DFS | 州級 | — | — | — | ~$3,050+ |
| 4 | Mortgage Banker | NY DFS | 州級 | — | — | — | ~$5,555+ |
| 5 | Stockbroker / Broker-Dealer | FINRA + SEC + NY AG | 聯邦+州 | 18+ | — | SIE + Series 7 | ~$300-500 |
| 6 | Customs Broker | U.S. CBP | 聯邦 | 21+ | — | CBLE 考試 | ~$300-500 |
| 7 | Freight Broker | FMCSA | 聯邦 | — | — | 無 | $1,461-$11,111 |
| 8 | Commodity Broker (IB) | CFTC / NFA | 聯邦 | — | — | Series 3 | NFA 會員費 |
| 9 | Business Broker | 無需特別執照 | N/A | — | — | — | $0 |
| 10 | Pawnbroker | NYC DCWP | 市級 | — | — | — | NYC 許可費 |
| 11 | Ticket Reseller | NY DOS | 州級 | — | — | — | $5,000+/yr |
| 12 | Yacht Broker | NY DOS | 州級 | — | — | — | — |

---

## 二、各類型詳細說明

### 1. Real Estate Broker（不動產經紀人）

- **主管**：NY Department of State (DOS), Division of Licensing Services
- **法源**：Article 12-A of the Real Property Law
- **要求**：
  - 至少 20 歲
  - 持有 NYS photo driver's license 或 non-driver ID
  - 持牌 Salesperson 2 年以上，或不動產相關經驗 3 年以上，或兩者組合
  - 完成 152 小時教育（含 77hr Salesperson + 75hr Broker pre-licensing）
  - 通過 DOS 筆試
- **費用**：考試 $15 + 申請 $185 = ~$200
- **續期**：每 2 年 $185 + 22.5 hr CE 學分
- **申請方式**：透過 eAccessNY 線上系統排考；申請表可透過 Email 或紙本提交（官方正推進數位化）
- **申請系統**：eAccessNY（排考、查詢結果、申請管理）
- **官網**：https://dos.ny.gov/become-real-estate-broker

**4 步驟流程**：
1. 完成 75 小時 Broker pre-licensing 課程
2. 通過課程期末考（>=70%）
3. 通過 NYS Broker 筆試（多選題，2.5 小時，Pass/Fail）
4. 提交申請表 + $185

### 2. Insurance Broker（保險經紀人）

- **主管**：NY Department of Financial Services (DFS)
- **法源**：Insurance Law Article 21（§2101-2104，經紀人核心條文為 §2104；§2132 為繼續教育規定）
- **要求**：
  - 至少 18 歲
  - 完成 DFS 核准的 pre-licensing 課程
  - 通過 NYS 保險考試（>=70%，2 年內申請）
- **子類別**（主要 Broker/Agent 類型）：
  - Property & Casualty Broker
  - Life & Accident/Health Broker
  - Variable Life/Variable Annuity Agent/Broker
  - Excess Lines Broker
  - Life Settlement Broker
  - Title Insurance Agent
  - Bail Bond Agent
  - Consultant (General or Life)
  - Independent/Public Adjuster
  - Mortgage Guaranty Agent
  - Limited Agent（租車、無線通訊設備、自助倉儲）
  - Service Contract Provider
  - *注：DFS 官方列出 14 種申請類別，部分為 Agent 而非 Broker*
- **申請系統**：NY LINX（2026/2 遷移至 DFS ID + MFA）
- **非居民**：可透過 NIPR 申請
- **官網**：https://www.dfs.ny.gov/apps_and_licensing/agents_and_brokers/home

### 3. Mortgage Broker（房貸仲介）

- **主管**：NY DFS（透過 NMLS）
- **要求**：
  - Qualifying Individual：2 年可驗證經驗 + NY LO License
  - Surety Bond：$10,000
  - 無最低淨值要求
- **費用明細**：
  - 公司執照費 $1,500
  - 外州實體申請 $225
  - 註冊代理 $125
  - 指紋費 $105/人
  - Bond 費 ~$100
  - LO Bond 費 ~$1,000
- **續期**：$1,738 + 0.7% of NY 貸款毛收入
- **注意**：收到補件通知後 30 天未回覆 = 申請視為撤回

### 4. Mortgage Banker（房貸銀行）

- **主管**：NY DFS（透過 NMLS）
- **要求**（比 Broker 嚴格）：
  - Qualifying Individual：5 年可驗證經驗 + NY LO License
  - 最低淨值：$250,000（需審計）
  - Surety Bond：$50,000
  - $1,000,000 warehouse line of credit
  - 至少 3 位 executive officers
- **費用**：公司執照 $3,000 + Bond ~$500 + 其他 ≈ $5,555+
- **續期**：$4,108 + 0.7% of NY 貸款毛收入

### 5. Stockbroker / Broker-Dealer（證券經紀人）

- **主管**：FINRA + SEC + NY Attorney General
- **要求**：
  - 必須由 FINRA 會員公司 sponsor（無法個人自行申請）
  - 通過 SIE（Securities Industry Essentials）：75 題、1hr45min、70%
  - 通過 Series 7（General Securities Representative）：125 題、3hr45min、72%
- **NY 州層級**：Broker-Dealer 需向 NY AG 辦公室註冊，含指紋背景調查
- **背景調查**：Form U4 要求揭露所有 complaint/仲裁/刑事記錄；BrokerCheck 公開顯示大部分紀錄（部分可能因時間或申訴移除，並非全部永久可見）

### 6. Customs Broker（報關行）

- **主管**：U.S. Customs and Border Protection (CBP)
- **要求**：
  - 美國公民、>=21 歲
  - 不得為現任聯邦政府雇員
  - 品行良好（good moral character）
  - 通過 CBLE（Customs Broker License Examination）
- **CBLE 考試**：80 題、4.5 hr、75% 及格、一年僅 4 月和 10 月考
- **通過率**：歷史 15-30%（2025/10 僅 12%）——全美最難 Broker 考試
- **全美約 14,454 位持證 Customs Broker**

### 7. Freight Broker（貨運仲介）

- **主管**：FMCSA（聯邦層級）
- **NY 州不需額外州級執照**，僅需一般商業登記
- **聯邦要求**：
  - MC Number（Operating Authority）：申請費 $300
  - $75,000 Surety Bond（BMC-84）或 Trust Fund（BMC-85）
  - BOC-3 Process Agent 指定：$30-60
  - UCR 年費：$176
  - USDOT Number
- **無教育或考試要求**
- **中位年薪**（NY）：$54,800（高於全美平均 13%）

### 8. Commodity Broker / Introducing Broker（期貨商品仲介）

- **主管**：CFTC + NFA
- **要求**：NFA 會員註冊、通過 Series 3（120 題、2hr30min、70%）、背景調查

### 9. Business Broker（企業買賣仲介）

- **紐約州不需要特定執照**
- 涉及不動產的交易可能需要 Real Estate Broker License
- 涉及證券（如出售企業股份）可能觸發 Broker-Dealer 註冊要求
- 業界常見自願認證：CBI（Certified Business Intermediary）

### 10. Pawnbroker（當鋪）

- **主管**：NYC Department of Consumer and Worker Protection (DCWP)
- 需要 Pawnbroker License + Secondhand Dealer General License
- 官網：https://www.nyc.gov/site/dca/businesses/license-checklist-pawnbroker.page

### 11. Ticket Reseller（票券轉售商）

- **主管**：NY DOS
- **年費**：$5,000（執照期間 1/1-12/31）
- **Bond**：$25,000（可能需多張，依營業地點/平台）
- **2025 新規**：要求 "All-In Pricing"（票價必須含所有費用）

### 12. Yacht Broker（遊艇經紀）

- **主管**：NY DOS（15 NYCRR Section 104.7）
- 需向 Commissioner 提交認證

---

## 三、線上查驗工具

| Broker 類型 | 查驗系統 | 網址 |
|------------|---------|------|
| Real Estate | eAccessNY Public License Search | https://appext20.dos.ny.gov/nydos/selSearchType.do |
| Insurance | ALiS Producer Search | https://myportal.dfs.ny.gov/nylinxext/elsearch.alis |
| Mortgage | NMLS Consumer Access | https://www.nmlsconsumeraccess.org/ |
| Stockbroker | FINRA BrokerCheck | https://brokercheck.finra.org/ |
| Customs | CBP Broker Search | https://www.cbp.gov/trade/programs-administration/customs-brokers |
| Freight | FMCSA SAFER / Li-Public | https://li-public.fmcsa.dot.gov/LIVIEW/pkg_carrquery.prc_carrlist |
| Commodity | NFA BASIC | https://www.nfa.futures.org/basicnet/ |

---

## 四、投訴與懲戒機制

### Real Estate Broker（DOS）

- **投訴管道**：Preliminary Statement of Complaint 表格 -> Email 至 Complaints@dos.ny.gov 或郵寄至 Albany
- **懲戒措施**：reprimand（申誡）-> fine（罰款）-> suspension（停照）-> revocation（吊照）
- **法源**：Real Property Law Section 441-c
- **流程**：投訴 -> DOS 調查 -> 聽證 -> 判決（雙方全程通知）

### 常見違規類型

| 違規類型 | 法律分類 | 說明 | 法源 |
|---------|---------|------|------|
| Unlicensed Practice | Criminal Misdemeanor | 無照執業經紀 | Section 440-a |
| Deceptive Advertising | Administrative Fraud | 誇大面積、虛假描述 | Section 442-h |
| Market Collusion | Antitrust Violation | 聯合定價或抵制低價 | 反壟斷法 |
| License Lending | Professional Misconduct | 借照給無照人士 | Section 441-c |
| Commingling Funds | Fiduciary Breach | 混合客戶保證金與個人資金 | Section 441-c |
| Non-RE Misconduct | Cross-domain | 其他領域不誠信行為影響 RE 執照 | Eich v. Shaffer (1988) |

### 關鍵判例

- **Eich v. Shaffer (1988)**：保險經紀違規 -> DOS 據此吊銷其不動產執照（跨領域懲戒）
- **Fogel v. DOS (1994)**：刑事性犯罪前科 -> 拒絕發照
- **Stowell v. Cuomo (1981)**：純粹 broker-salesperson 佣金糾紛 -> DOS 無管轄權（需有公眾利益影響）
- **Gold v. Lomenzo (1972)**：賦予 Secretary of State 對「untrustworthiness」的廣泛裁量權

### Insurance Broker（DFS）

- DFS 每月發布 Disciplinary Actions Summary Report
- 2024-2025 重點：網路安全合規（8 家保險公司被罰 $19M+）

### Stockbroker（FINRA）

- BrokerCheck 可查看 employment history、certifications、violations、disciplinary history
- FINRA 每月公布 disciplinary actions
- Form U4 終身揭露機制

---

## 五、續期與繼續教育（CE）

### Real Estate Broker（DOS）

- 每 2 年續期，$185
- CE：22.5 小時（15 年豁免已廢除，所有 broker 均需 CE）

### Insurance Broker（DFS）

- 每 2 年續期（到期前線上續期，逾期即失效）
- 15 學分（Multi-Line 30 學分），必修包含：
  1. >=1 hr Insurance Law
  2. >=1 hr Ethics & Professionalism
  3. >=1 hr Diversity, Inclusion & Elimination of Bias（2021 新增）
  4. >=1 hr Flood Insurance（P&C 持照者）
  5. >=3 hr Enhanced Flood Insurance（NFIP 賣家）
- 非居民豁免：在 home state 合規即可

### Stockbroker（FINRA）

- Regulatory Element CE：首次註冊後定期完成（近年已從每 3 年改為年度制度，詳見 FINRA 最新規則）
- Firm Element CE：所在公司每年制定的內部培訓

### Freight Broker（FMCSA）

- MC Number 不過期，但 UCR 和 Surety Bond 需每年維持
- 無 CE 要求

---

## 六、考試通過率比較

| 考試 | 題數 | 時間 | 及格線 | 通過率 | 備註 |
|------|------|------|--------|--------|------|
| CBLE（Customs） | 80 題 | 4.5 hr | 75% | 12-30% | 全美最難，一年僅 4 月和 10 月 |
| NY RE Broker | 基於 152hr 課程 | 2.5 hr | Pass/Fail | ~60% | 31,200 位考生（2024） |
| Series 7 | 125 題 | 3hr45min | 72% | ~72% | 需公司 sponsor |
| SIE | 75 題 | 1hr45min | 70% | ~74% | 可自行報考 |
| NY Insurance | 依類別 | 依類別 | 70% | ~70-75% | P&C 和 Life 分開考 |
| Series 3（Commodity） | 120 題 | 2hr30min | 70% | ~55-60% | 聯邦期貨考試 |

---

## 七、背景調查

### 流程（以 Real Estate 為例）

1. IdentoGO 指紋（$35-56）
2. Criminal History Review（DOS 審查完整前科紀錄）
3. Application Hold（若有前科，審查時間延長）
4. Additional Documentation（DOS 可能要求補充文件）
5. Determination（DOS 最終裁定）

### 高度不利因素

- 金融犯罪（fraud, embezzlement, identity theft）
- 性犯罪（需登記或對未成年人）
- 暴力犯罪（assault, domestic violence）
- 近期重罪（時間遠近為考量因素之一，並非硬性 7 年門檻）

### DOS 考量因素（case-by-case）

- 重罪 vs 輕罪
- 犯罪性質（是否涉及誠信/金融）
- 距今時間（越久越有利，但無固定年限門檻）
- 更生努力和現況
- 單次 vs 多次犯罪

**關鍵**：前科不等於自動拒絕。NY Correction Law 提供 rehabilitation and licensing 保護。

### 跨類型嚴格度

| Broker 類型 | 指紋 | 背景調查嚴格度 |
|------------|------|--------------|
| Stockbroker | FINRA U4 | 最嚴（終身揭露） |
| Mortgage | FBI + State | 較嚴（金融犯罪零容忍） |
| Customs | CBP/DHS | 嚴格（good moral character） |
| Real Estate | IdentoGO | 中等（case-by-case） |
| Insurance | 依類別 | 中等 |
| Freight | 無 | N/A |

---

## 八、Reciprocity（州際互認）

### Real Estate Broker

- **Full Reciprocity**：無（紐約不與任何州全面互認）
- **Mutual Recognition**：MA, CT, CO, GA, MS, OK, PA, WV, Quebec（加拿大）
  - 減免部分課程，但仍需：通過 NY 考試 + 完成 NY 專屬課程 + 指紋背景調查
- **流程**：3-6 週，$200-350
- **無任何協議**：FL, NJ, CA, TX 等所有其他州（需完成完整 77hr 課程）

---

## 九、2025-2026 重大法規變動

### Real Estate（DOS）

| 日期 | 變動 |
|------|------|
| 2024/3/20 | PCDS 修正：賣方不再能用 $500 credit 代替填寫揭露 |
| 2025/7/1 | 新版 PCDS 表格上路（新增環境、結構揭露項目） |
| 2025 待議 | Bill S8729A：提議買方 10 天驗屋權 |

### Insurance（DFS）

| 日期 | 變動 |
|------|------|
| 2026/2 | DFS ID + MFA 遷移（NY LINX 新認證系統） |
| 2026/3 | Excess Line Broker 稅務寬限（30 天罰款免除至 4/14） |
| 2024-2025 | Cybersecurity 執法加強（8 家公司被罰 $19M+） |

---

## 十、實務常見陷阱

| 陷阱 | 類型 | 說明 |
|------|------|------|
| RE Broker 紙本申請延遲 | Real Estate | 官方說 4-6 週，實際可能 3+ 個月 |
| eAccessNY 帳號問題 | Real Estate | 系統老舊，密碼重設流程複雜 |
| DFS ID 遷移混亂 | Insurance | 2026/2 遷移後部分 producer 收不到邀請信 |
| NMLS 30 天補件時限 | Mortgage | 逾期未回覆 = 申請視為撤回 |
| Series 7 需 sponsor | Stockbroker | 無法個人報考，必須先被公司聘用 |
| CBLE 一年只考兩次 | Customs | 錯過 4 月 = 等到 10 月 |
| Bond 費用隨信用變化 | Freight/Mortgage | 信用差 -> Bond 年費可達面額 10%+ |

---

## 十一、費用全覽

| Broker 類型 | 初始費用 | 年化維持費 | Bond 要求 | 教育成本 |
|------------|---------|-----------|----------|---------|
| Real Estate | ~$200 | ~$93/yr | 無 | $300-600 |
| Insurance (P&C) | ~$100-300 | ~$75-150/yr | 無 | $200-500 |
| Mortgage Broker | ~$3,050 | $1,738+/yr | $10,000 | 含在申請中 |
| Mortgage Banker | ~$5,555 | $4,108+/yr | $50,000 | 含在申請中 |
| Stockbroker | ~$300-500 | 公司負擔 | 無（公司級） | $300-1,000 |
| Customs Broker | ~$300-500 | 依 CBP | 無 | $500-2,000 |
| Freight Broker | $1,461-$11,111 | $950+/yr | $75,000 | 選修 $500-2,000 |
| Commodity Broker | NFA 費用 | NFA 年費 | 依類別 | Series 3 prep |
| Ticket Reseller | $5,000+ | $5,000/yr | $25,000 x 多張 | 無 |
| Business Broker | $0 | $0 | 無 | 無 |

---

## 十二、申請時間線

| Broker 類型 | 預估時間 | 瓶頸 |
|------------|---------|------|
| Ticket Reseller | 2-4 週 | DOS 處理 |
| Insurance Broker | 2-4 週 | 考試排程 |
| Freight Broker | 4-6 週 | FMCSA 審核 |
| Real Estate Broker | 4-8 週（實際可能 3+ 月） | 紙本申請積壓 |
| Stockbroker | 4-8 週 | 需公司 sponsor |
| Mortgage Broker | 8-16 週 | DFS 審核 + Bond |
| Customs Broker | 3-6 個月 | CBLE 一年僅考 2 次 |

---

*報告完成。資料來源：NY DOS, NY DFS, FINRA, SEC, CBP, FMCSA, NFA, NMLS 官方網站及相關法律文獻。*
