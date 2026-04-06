# Medicare 慢性病年度支出學術研究報告

**製作日期**：2026-04-04
**資料來源**：Firecrawl 學術搜尋 + 全文 scrape（5 次平行搜尋、5 篇全文抓取）

---

## 執行摘要

Medicare 慢性病支出呈現高度集中特性：少數多重慢性病患者佔據絕大多數費用。跨越 1987–2017 年的文獻一致顯示，慢性病條件數目是 Medicare 支出的最強預測因子，且平均每名受惠者的年度支出隨慢性病數目呈指數級上升。

**核心數字（跨研究彙整）**：

| 指標 | 數值 | 來源 / 年份 |
|------|------|------------|
| 全美醫療支出中慢性病比例 | 90%（共 $4.9 兆） | CDC, 2025 |
| 2017 年 Medicare FFS 總支出 | $347.9 億（每人 $6,359） | Matthews et al., 2021 |
| 2+ 慢性病患者佔 Part A 支出比例 | 86%（僅佔 36% 受惠者） | Erdem et al., 2013 |
| 2008 年平均 Part A 支出/人 | $2,945；2010 年 $3,070（+4.3%） | Erdem et al., 2013 |
| 2008 年平均 Part B 支出/人 | $3,640；2010 年 $4,015（+10.3%） | Erdem et al., 2013 |
| 65 歲患者年度增量支出（糖尿病） | +$1,930/年（相較無病者） | Joyce et al., 2005 |
| 心血管病自付費用超額 | +$317/年 | Pinares-Garcia et al., 2019 |

---

## 研究一：縣級慢性病濃度與 Medicare FFS 支出

**引用**
> Matthews KA, Gaglioti AH, Holt JB, McGuire LC, Greenlund KJ, et al.
> "County-Level Concentration of Selected Chronic Conditions Among Medicare Fee-for-Service Beneficiaries and Its Association with Medicare Spending in the United States, 2017."
> *Population Health Management*, 2020 Apr 1; 24(2):214–221.
> DOI: [10.1089/pop.2019.0231](https://doi.org/10.1089/pop.2019.0231)
> PMC: [PMC8488905](https://pmc.ncbi.nlm.nih.gov/articles/PMC8488905/)

**研究方法**

- **數據集**：CMS 縣級地理變異公開使用檔（Geographic Variation Public Use File）、CMS 多重慢性病流行率縣級資料（2017 年）
- **研究設計**：橫斷面生態研究，覆蓋全美 50 州 + DC 共 3,142 個縣
- **人群**：所有年齡層 Medicare FFS 受惠者（共 54,577,161 人）
- **慢性病定義**：16 種選定條件（含阿茲海默症、關節炎、氣喘、心房顫動、癌症、慢性腎病、COPD、憂鬱症、糖尿病、心臟衰竭、高血壓、缺血性心臟病、骨質疏鬆、類風濕性關節炎、中風、慢性藥物濫用）
- **統計方法**：Pearson 相關係數 + 普通最小二乘迴歸（OLS）

**關鍵發現**

- 2017 年 Medicare FFS 總支出約 **$347.9 億**，平均每位 FFS 受惠者 **$6,359**
- 最常見慢性病（全國流行率）：
  - 高血壓：37.3%（縣級中位數）
  - 糖尿病：28.2%
  - 慢性腎病：18.1%
  - 心臟衰竭：14.8%
  - COPD：11.2%（縣級範圍：4.7%–25.0%）
- 慢性病濃度（CCC）分數與縣級人均 Medicare 支出顯著正相關（Pearson R 顯著）
- 高慢性病濃度縣的人均支出顯著高於低濃度縣

**費用分布**

| CCC 分類 | 縣數 | FFS 受惠者（%） | 人均 FFS 支出（$） |
|---------|------|--------------|----------------|
| 低慢性病濃度縣 | 31.2% | 19.6% | 相對較低 |
| 中度（對照組） | 參考值 | 參考值 | ~$6,359 |
| 高慢性病濃度縣 | 部分縣 | 集中分布 | 顯著高於平均 |

---

## 研究二：慢性病條件對 Medicare 支出的影響程度

**引用**
> Erdem E, Prada SI, Haffer SC.
> "Medicare Payments: How Much Do Chronic Conditions Matter?"
> *Medicare & Medicaid Research Review*, 2013; 3(2):mmrr.003.02.b02.
> DOI: [10.5600/mmrr.003.02.b02](https://doi.org/10.5600/mmrr.003.02.b02)
> PMC: [PMC3983726](https://pmc.ncbi.nlm.nih.gov/articles/PMC3983726/)

**研究方法**

- **數據集**：CMS 慢性條件公開使用檔（Chronic Conditions Public Use Files, CC PUFs），2008 年與 2010 年版本；底層為 100% Medicare 受惠者摘要檔（100% Beneficiary Summary File）
- **慢性病定義**：來自 CMS 慢性條件數據倉庫（Chronic Condition Data Warehouse, CCW），使用 ICD-9/CPT4/HCPCS 碼的 peer-reviewed 臨床演算法識別 11 種條件
- **研究設計**：描述性分析，依慢性病數目、性別、年齡分層
- **11 種條件**：阿茲海默症、癌症、慢性心臟衰竭、慢性腎病、COPD、糖尿病、缺血性心臟病、憂鬱症、骨質疏鬆症、類風濕性關節炎、中風/短暫性腦缺血發作

**關鍵發現**

**Medicare Part A（住院）**

| 慢性病數目 | 2008 平均支出/人 | 2010 平均支出/人 | 佔 Part A 受惠者% | 佔 Part A 總支出% |
|---------|--------------|--------------|----------------|----------------|
| 0 種 | 基準值 | 基準值 | 64% | 14% |
| 1 種 | 基準值 × 5.3 | 基準值 × 5.4 | — | — |
| 2+ 種 | 最高 | 最高 | 36% | **86%** |
| 全體平均 | $2,945 | $3,070（+4.3%） | 100% | 100% |

- Part A 2008→2010 成長 5.2%；其中 **98%（$41 億）** 來自 2+ 慢性病患者
- Part B 2008→2010 成長 10.7%；其中 **76%（$92 億）** 來自 2+ 慢性病患者

**Medicare Part B（門診）**

| 慢性病數目 | 2008 平均支出/人 | 2010 平均支出/人 |
|---------|--------------|--------------|
| 0 種 | 基準值 | 基準值 |
| 1 種 | 基準值 × 2.35 | 基準值 × 2.35 |
| 全體平均 | $3,640 | $4,015（+10.3%） |

**各單一慢性病支出倍數（Part A，相對無病者）**

- 中風/TIA：最高（倍數最大）
- 慢性腎病：第二高
- 癌症（Part B 最貴）：3–9 倍
- 糖尿病：1.6–3.3 倍（最低）

---

## 研究三：老年人慢性病終生負擔

**引用**
> Joyce GF, Keeler EB, Shang B, Goldman DP.
> "The Lifetime Burden of Chronic Disease Among the Elderly."
> *Health Affairs (Millwood)*, 2005; 24(Suppl 2):W5R18–W5R29.
> DOI: [10.1377/hlthaff.w5.r18](https://doi.org/10.1377/hlthaff.w5.r18)
> PMC: [PMC6385883](https://pmc.ncbi.nlm.nih.gov/articles/PMC6385883/)
> PMID: 16186148

**研究方法**

- **數據集**：
  - Medicare 現任受惠者調查（Medicare Current Beneficiary Survey, MCBS），1992–1999 年旋轉追蹤面板
  - Medicare 申報資料（Claims），1991–1999 年，連結至 MCBS
  - 合計 28,482 名受惠者，73,260 人年資料
- **研究設計**：微模擬縱向研究（Future Elderly Model, FEM microsimulation）
- **7 種慢性條件**：高血壓、糖尿病、癌症（非皮膚）、COPD、急性心肌梗塞（AMI）、冠心病（CHD）、中風
- **費用分期**：初診年（Incident）、維持年（Maintenance）、終末年（Terminal）
- **貨幣基準**：1999 美元，折現率 3%

**關鍵發現（65 歲受惠者）**

**按健康狀態的終生支出（1999$）**

| 65 歲健康狀態 | 預期餘命（年） | 年均總費用（$） | 終生總費用（千$） | 年均 Medicare（$） | 終生 Medicare（千$） |
|------------|-----------|-------------|--------------|----------------|-----------------|
| 0 種共病 | 21.7 | 4,856 | 87.6 | 3,047 | 49.2 |
| 1–2 種共病 | 20.4 | 5,855 | 100.3 | 3,760 | 58.2 |
| 3+ 種共病 | 16.4 | 9,996 | 123.2 | 6,961 | 78.5 |
| **全體平均** | **19.4** | **6,984** | **105.1** | **4,644** | **62.9** |

**各慢性病對年度費用的增量影響（相對無病者）**

| 慢性病 | 壽命減少（年） | 年費用增加（1999$） | 終生費用增加（1999$） |
|------|------------|----------------|-----------------|
| 高血壓 | 0.3 | +$686 | +$9,648 |
| 糖尿病 | 3.1 | +$1,930 | +$13,032 |
| 癌症 | 2.1 | +$1,397 | +$12,279 |
| COPD | 2.8 | +$1,525 | +$6,158 |
| 急性心肌梗塞 | 2.3 | +$1,537 | +$13,737 |
| 冠心病 | 0.6 | +$843 | +$11,691 |
| 中風 | 3.0 | +$1,389 | +$3,807 |

**各病種年度醫療費用（按疾病分期）**

- 高血壓初診年：~$9,500（全因）；後續年減少約 10%
- 癌症/中風/冠心病初診年：$17,000–$19,000；後續減少 40–50%
- AMI 初診年：>$25,000；後續減少 60%
- 終末年（所有條件）：$25,000–$30,000（與疾病種類關聯性低）

**結論**：儘管慢性病增加年度費用，但由於縮短預期壽命，「累積 Medicare 支出」僅溫和增加（$3,807–$13,737）。10% 最高費用受惠者的年度費用為中位數的 3–6 倍。

---

## 研究四：Medicare 受惠者自付醫療費用中的慢性病影響

**引用**
> Pinares-Garcia GN, Prados-Torres A, Laguna-Berna C, Gimeno-Feliú LA, Clerencia-Sierra M, Ioakeim-Skoufa I.
> "Out-of-pocket health spending among Medicare beneficiaries."
> *PLOS ONE*, 2019; 14(9):e0222539.
> DOI: [10.1371/journal.pone.0222539](https://doi.org/10.1371/journal.pone.0222539)
> PMC: [PMC6754145](https://pmc.ncbi.nlm.nih.gov/articles/PMC6754145/)

**研究方法**

- **數據集**：2014 年健康與退休調查（Health and Retirement Study, HRS），代表 35,939,270 名 65 歲以上 Medicare 受惠者
- **研究設計**：橫斷面研究，廣義線性模型（GLM）
- **調整因子**：人口統計、社會經濟地位、生理健康、其他慢性條件
- **費用分解**：住院、非住院、處方藥

**關鍵發現**

各慢性病對 Medicare 受惠者**自付費用的年度增量影響**（調整後）：

| 慢性病 | 年度超額自付費用（$） | 主要費用驅動 |
|------|-----------------|-----------|
| 心血管疾病 | +**$317** | 處方藥 |
| 糖尿病 | +**$237** | 處方藥 |
| 高血壓 | +**$150** | 處方藥 |
| 癌症 | +**$144** | 非住院服務 |

- 心血管病、糖尿病、高血壓、癌症是超額自付費用的四大驅動因素
- 50–64 歲敏感性分析結果與主要分析方向一致

---

## 研究五：高需求高費用患者的費用軌跡

**引用**
> Trenaman L, Guh D, McGrail K, et al.
> "Longitudinal trajectories of healthcare costs among high-need high-cost patients: a population-based retrospective cohort study in British Columbia, Canada."
> *BMJ Open*, 2025; 15:e089693.
> DOI: [10.1136/bmjopen-2024-089693](https://doi.org/10.1136/bmjopen-2024-089693)
> PMC: [PMC12035471](https://pmc.ncbi.nlm.nih.gov/articles/PMC12035471/)

**研究方法**

- **數據集**：Population Data BC（卑詩省人口資料庫），2015–2019 年行政健康數據，5.4 百萬人
- **研究設計**：回顧性縱向佇列研究，群組軌跡建模（Group-Based Trajectory Modeling, GBTM）
- **HNHC 定義**：2017 年醫療費用前 5%（閾值：CA$7,968）
- **費用涵蓋**：住院、日間手術、醫師服務、處方藥、居家及社區照護

**關鍵發現**

HNHC 患者（2017 年，共 224,285 人）五年費用軌跡五群分類：

| 軌跡群組 | 比例 | 5 年平均總費用（CA$） | 主要特徵 |
|--------|------|-----------------|--------|
| 持續極高費用 | 44.0% | $124,622（SD=$92,700） | 多重共病、高齡 |
| 持續高費用 | 31.8% | $38,997（SD=$19,841） | — |
| 上升費用 | 10.3% | $43,140（SD=$17,426） | — |
| 下降費用 | 7.1% | $30,545（SD=$9,244） | — |
| 費用尖峰後回落 | 6.8% | $19,601（SD=$5,181） | 急性事件後恢復 |

- 75% 的 HNHC 患者維持持續高費用（3/4 軌跡）
- 持續極高費用者中，近 1/4 具有多重共病
- 低社經地位（SES）與持續極高費用軌跡顯著相關

**方法論意義**：此研究雖以加拿大資料為主，但 GBTM 方法與 Medicare 高費用患者分層研究高度相關，已被多篇 Medicare 研究引用。

---

## 補充資料：CDC 快速統計與個別疾病費用

**來源**：CDC National Center for Chronic Disease Prevention and Health Promotion
URL: https://www.cdc.gov/chronic-disease/data-research/facts-stats/index.html
（更新日期：2025 年 8 月 8 日）

| 慢性病 / 風險因子 | 年度費用 | 說明 |
|---------------|--------|------|
| 全美慢性病醫療支出 | **$4.9 兆的 90%** | 含心理健康條件 |
| 心臟病與中風 | $233.3 億/年 + $184.6 億生產力損失 | 預計 2050 年達 $2 兆 |
| 糖尿病（2022） | **$413 億**（醫療 + 生產力損失） | 3,800 萬美國人患病 |
| 阿茲海默症（2024） | **$360 億**（估計） | 預計 2050 年接近 $1 兆 |
| 慢性腎病 | **$95.7 億** Medicare 支出 | 佔 Medicare 總支出近 1/4 |
| 肥胖 | **$173 億/年** | 佔 40% 成人 |
| 癌症 | 預計 2030 年達 **$240 億** | — |

---

## 資料集總覽

| 數據集縮寫 | 全名 | 使用研究 |
|---------|------|--------|
| MCBS | Medicare Current Beneficiary Survey | Joyce et al. 2005 |
| CC PUF | CMS Chronic Conditions Public Use Files | Erdem et al. 2013 |
| CCW | Chronic Condition Data Warehouse | Erdem et al. 2013 |
| HRS | Health and Retirement Study | Pinares-Garcia et al. 2019 |
| CMS Geographic Variation PUF | CMS 縣級地理變異檔 | Matthews et al. 2021 |
| Medicare Claims (FFS) | Medicare 申報資料 | Joyce et al. 2005 |
| Population Data BC | 卑詩省行政健康資料庫 | Trenaman et al. 2025 |

---

## 費用趨勢與主要結論

### 費用集中趨勢

```
無慢性病者   ─────────────── 佔受惠者多數，但費用極低
1 種慢性病   ━━━━━━━━━━━━━━━ Part A 費用為無病者 5.3 倍
2+ 種慢性病  ████████████████ 佔 36% 受惠者 → 86% Part A 支出
3+ 種共病    ████████████████████ 年費用 $9,996（無病者 $4,856 的 2 倍）
```

### 跨年度費用成長（2008→2010）

- Part A 成長 5.2%，98% 由多重慢性病驅動
- Part B 成長 10.7%，76% 由多重慢性病驅動

### 重要政策含意

1. **集中介入**：2+ 種慢性病者（僅 36% 受惠者）消耗 86% Part A 支出，是費用管控的關鍵目標
2. **預防的悖論**（Joyce et al.）：減少 65 歲時慢性病流行率，雖可降低年費用，但因延長壽命，終生累積 Medicare 支出僅溫和減少（$3,807–$13,737/案例）
3. **地理差異**：慢性病濃度高的縣（多位於南部州）人均支出顯著較高，呈現系統性不平等
4. **費用持續性**：75% 高需求高費用患者維持持續高費用軌跡，有效分層是資源配置關鍵

---

## 參考文獻列表

1. Matthews KA, Gaglioti AH, Holt JB, McGuire LC, Greenlund KJ, Xu F. County-Level Concentration of Selected Chronic Conditions Among Medicare Fee-for-Service Beneficiaries and Its Association with Medicare Spending in the United States, 2017. *Popul Health Manag.* 2021;24(2):214-221. doi:10.1089/pop.2019.0231

2. Erdem E, Prada SI, Haffer SC. Medicare Payments: How Much Do Chronic Conditions Matter? *Medicare Medicaid Res Rev.* 2013;3(2):mmrr.003.02.b02. doi:10.5600/mmrr.003.02.b02

3. Joyce GF, Keeler EB, Shang B, Goldman DP. The Lifetime Burden Of Chronic Disease Among The Elderly. *Health Aff (Millwood).* 2005;24(Suppl 2):W5R18-W5R29. doi:10.1377/hlthaff.w5.r18

4. Pinares-Garcia GN, et al. Out-of-pocket health spending among Medicare beneficiaries. *PLOS ONE.* 2019;14(9):e0222539. doi:10.1371/journal.pone.0222539

5. Trenaman L, Guh D, McGrail K, et al. Longitudinal trajectories of healthcare costs among high-need high-cost patients: a population-based retrospective cohort study in British Columbia, Canada. *BMJ Open.* 2025;15:e089693. doi:10.1136/bmjopen-2024-089693

6. Thorpe KE, Ogden LL, Galactionova K. Chronic Conditions Account for Rise in Medicare Spending from 1987 to 2006. *Health Affairs.* 2010;29(4):718-724. doi:10.1377/hlthaff.2009.0474

7. CDC National Center for Chronic Disease Prevention and Health Promotion. Fast Facts: Health and Economic Costs of Chronic Conditions. Updated August 8, 2025. https://www.cdc.gov/chronic-disease/data-research/facts-stats/index.html

8. California Health Care Foundation (CHCF) / HHS Data. Medicare Enrollees with Multiple Chronic Conditions Drive Spending. September 2018. https://www.chcf.org/wp-content/uploads/2018/09/PDF-Politico-Medicare-Enrollees-Multiple-Chronic-Conditions.pdf
