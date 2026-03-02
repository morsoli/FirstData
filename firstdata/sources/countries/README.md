# Countries Data Sources - 各国官方数据源

## 概览 Overview

本目录包含全球各国政府官方数据源的元数据。涵盖北美、欧洲、亚洲、大洋洲、南美洲、非洲等六大洲，42个国家和地区的200+个官方数据源。

This directory contains metadata for official government data sources from countries around the world, covering 42 countries and regions across six continents with 200+ official data sources.

## 当前状态 Current Status

**目录结构**: ✅ 已完成
**JSON文件**: 27个数据源已创建
**完成度**: 27/200+ (13.5%)

```
总目标: 200+ 个各国数据源
当前完成: 27 个
完成度: ██░░░░░░░░░░░░░░░░░░ 13.5%
```

## 目录结构 Directory Structure

```
sources/countries/
├── north-america/              # 北美洲 (3国，目标30个)
│   ├── usa/                   # 🇺🇸 美国 (目标15个，已完成8个)
│   ├── canada/                # 🇨🇦 加拿大 (目标10个，已完成5个)
│   └── mexico/                # 🇲🇽 墨西哥 (目标5个，已完成2个)
│
├── europe/                     # 欧洲 (15国，目标50个，已完成2个)
│   ├── eu/                    # 🇪🇺 欧盟 (目标5个)
│   ├── uk/                    # 🇬🇧 英国 (目标5个，已完成2个)
│   ├── germany/               # 🇩🇪 德国 (目标4个)
│   ├── france/                # 🇫🇷 法国 (目标4个)
│   ├── italy/                 # 🇮🇹 意大利 (目标3个)
│   ├── spain/                 # 🇪🇸 西班牙 (目标3个)
│   ├── netherlands/           # 🇳🇱 荷兰 (目标3个)
│   ├── sweden/                # 🇸🇪 瑞典 (目标3个)
│   ├── switzerland/           # 🇨🇭 瑞士 (目标3个)
│   ├── norway/                # 🇳🇴 挪威 (目标2个)
│   ├── denmark/               # 🇩🇰 丹麦 (目标2个)
│   ├── finland/               # 🇫🇮 芬兰 (目标2个)
│   ├── poland/                # 🇵🇱 波兰 (目标2个)
│   ├── russia/                # 🇷🇺 俄罗斯 (目标2个)
│   └── turkey/                # 🇹🇷 土耳其 (目标2个)
│
├── asia/                       # 亚洲 (14国，目标50个，已完成3个)
│   ├── japan/                 # 🇯🇵 日本 (目标8个，已完成1个)
│   ├── korea/                 # 🇰🇷 韩国 (目标5个，已完成1个)
│   ├── india/                 # 🇮🇳 印度 (目标5个，已完成1个)
│   ├── singapore/             # 🇸🇬 新加坡 (目标3个)
│   ├── malaysia/              # 🇲🇾 马来西亚 (目标2个)
│   ├── thailand/              # 🇹🇭 泰国 (目标2个)
│   ├── indonesia/             # 🇮🇩 印度尼西亚 (目标2个)
│   ├── philippines/           # 🇵🇭 菲律宾 (目标2个)
│   ├── vietnam/               # 🇻🇳 越南 (目标2个)
│   ├── pakistan/              # 🇵🇰 巴基斯坦 (目标2个)
│   ├── bangladesh/            # 🇧🇩 孟加拉国 (目标2个)
│   ├── israel/                # 🇮🇱 以色列 (目标2个)
│   ├── saudi-arabia/          # 🇸🇦 沙特阿拉伯 (目标2个)
│   └── uae/                   # 🇦🇪 阿联酋 (目标2个)
│
├── oceania/                    # 大洋洲 (2国，目标10个，已完成3个)
│   ├── australia/             # 🇦🇺 澳大利亚 (目标6个，已完成3个)
│   └── new-zealand/           # 🇳🇿 新西兰 (目标4个)
│
├── south-america/              # 南美洲 (4国，目标15个，已完成1个)
│   ├── brazil/                # 🇧🇷 巴西 (目标5个，已完成1个)
│   ├── argentina/             # 🇦🇷 阿根廷 (目标2个)
│   ├── chile/                 # 🇨🇱 智利 (目标2个)
│   └── colombia/              # 🇨🇴 哥伦比亚 (目标2个)
│
└── africa/                     # 非洲 (4国，目标15个)
    ├── south-africa/          # 🇿🇦 南非 (目标4个)
    ├── nigeria/               # 🇳🇬 尼日利亚 (目标4个)
    ├── egypt/                 # 🇪🇬 埃及 (目标4个)
    └── kenya/                 # 🇰🇪 肯尼亚 (目标3个)

总计: 42个国家和地区，目标200+个数据源，已完成24个
```

## 已收录数据源 Current Data Sources

### 🌎 北美洲 North America

**已完成**: 11/30 (37%)

#### 🇺🇸 美国 United States (6/15)

1. **US Census Bureau** (`census-bureau`) ⭐💎
   - 权威等级：government
   - 类型：人口统计、经济普查、社会调查
   - 数据格式：CSV, JSON, Excel, XML
   - 访问类型：开放
   - **文件**: [census-bureau.json](north-america/usa/census-bureau.json)

2. **NOAA Climate Data Online (CDO)** (`noaa-cdo`) ⭐
   - 权威等级：government
   - 类型：气候数据、气象观测、历史天气
   - 数据格式：CSV, JSON, XML, NetCDF, PDF
   - 访问类型：需注册（免费）
   - **文件**: [noaa-cdo.json](north-america/usa/noaa-cdo.json)

3. **USGS EarthExplorer** (`usgs-earthexplorer`) ⭐💎
   - 权威等级：government
   - 类型：卫星影像、地球观测、地质数据
   - 数据格式：GeoTIFF, HDF, NetCDF, JPEG2000, LAS, LAZ, Shapefile, KML
   - 访问类型：需注册（免费）
   - **文件**: [usgs-earthexplorer.json](north-america/usa/usgs-earthexplorer.json)

4. **Bureau of Economic Analysis** (`us-bea`) ⭐💎
   - 权威等级：government
   - 类型：GDP、国民收入、国际收支
   - 数据格式：CSV, Excel, JSON, XML, PDF
   - 访问类型：开放
   - **文件**: [us-bea.json](north-america/usa/us-bea.json)

5. **Bureau of Labor Statistics** (`us-bls`) ⭐💎
   - 权威等级：government
   - 类型：就业、失业、工资、CPI
   - 数据格式：CSV, Excel, JSON, XML, PDF, TXT, API
   - 访问类型：开放
   - **文件**: [us-bls.json](north-america/usa/us-bls.json)

6. **Centers for Disease Control and Prevention** (`us-cdc`) ⭐💎
   - 权威等级：government
   - 类型：疾病监测、健康统计、流行病学
   - 数据格式：CSV, Excel, XML, Text, PDF, Interactive Query
   - 访问类型：开放
   - **文件**: [us-cdc.json](north-america/usa/us-cdc.json)

7. **Data.gov** (`us-data-gov`) ⭐💎
   - 权威等级：government
   - 类型：综合开放数据门户
   - 数据格式：CSV, JSON, XML, Excel, PDF, Shapefile, KML, RDF
   - 访问类型：开放
   - **文件**: [us-data-gov.json](north-america/usa/us-data-gov.json)

8. **U.S. Energy Information Administration** (`usa-eia`) ⭐💎
   - 权威等级：government
   - 类型：能源统计、石油、天然气、电力
   - 数据格式：CSV, Excel, JSON, XML, PDF, API
   - 访问类型：开放
   - **文件**: [eia.json](north-america/usa/eia.json)

#### 🇨🇦 加拿大 Canada (4/10)

1. **Statistics Canada** (`statcan`) ⭐💎
   - 权威等级：government
   - 类型：国家统计、人口普查、经济数据
   - 数据格式：CSV, JSON, XML, Excel, SDMX, HTML, PDF
   - 访问类型：开放
   - **文件**: [statcan.json](north-america/canada/statcan.json)

2. **Bank of Canada** (`canada-boc`) ⭐💎
   - 权威等级：government
   - 类型：货币政策、汇率、金融市场
   - 数据格式：CSV, JSON, XML, Excel, RSS
   - 访问类型：开放
   - **文件**: [canada-boc.json](north-america/canada/canada-boc.json)

3. **Canadian Institute for Health Information** (`canada-cihi`) ⭐💎
   - 权威等级：government
   - 类型：医疗卫生、健康统计
   - 数据格式：Excel, CSV, PDF, HTML, JSON
   - 访问类型：开放
   - **文件**: [canada-cihi.json](north-america/canada/canada-cihi.json)

4. **Canada Energy Regulator** (`canada-energy-regulator`) ⭐💎
   - 权威等级：government
   - 类型：能源监管、石油天然气
   - 数据格式：CSV, JSON, XML, Excel, Interactive Dashboards
   - 访问类型：开放
   - **文件**: [canada-energy-regulator.json](north-america/canada/canada-energy-regulator.json)

5. **Agriculture and Agri-Food Canada** (`aafc`) ⭐💎
   - 权威等级：government
   - 类型：农业统计、作物、土地利用
   - 数据格式：GeoTIF, FGDB, GDB, CSV, Shapefile, JSON, REST API
   - 访问类型：开放
   - **文件**: [aafc.json](north-america/canada/aafc.json)

#### 🇲🇽 墨西哥 Mexico (1/5)

1. **Bank of Mexico Economic Information System** (`banxico`) ⭐💎
   - 权威等级：government
   - 类型：经济指标、汇率、通货膨胀
   - 数据格式：JSON, XML, JSONP, Excel, CSV
   - 访问类型：开放
   - **文件**: [banxico.json](north-america/mexico/banxico.json)

2. **National Council for the Evaluation of Social Development Policy** (`coneval`) ⭐💎
   - 权威等级：government
   - 类型：贫困测量、社会政策评估
   - 数据格式：Excel, CSV, PDF
   - 访问类型：开放
   - **文件**: [coneval.json](north-america/mexico/coneval.json)

---

### 🌍 欧洲 Europe

**已完成**: 2/50 (4%)

#### 🇬🇧 英国 United Kingdom (2/5)

1. **Bank of England Statistical Interactive Database** (`bank-of-england`) ⭐💎
   - 权威等级：government
   - 类型：货币政策、金融统计
   - 数据格式：CSV, Excel, XML, PDF
   - 访问类型：开放
   - **文件**: [bank-of-england.json](europe/uk/bank-of-england.json)

2. **Data.gov.uk** (`uk-data-gov`) ⭐💎
   - 权威等级：government
   - 类型：综合开放数据门户
   - 数据格式：CSV, JSON, XML, Excel, PDF, RDF, Shapefile, GeoJSON
   - 访问类型：开放
   - **文件**: [uk-data-gov.json](europe/uk/uk-data-gov.json)

---

### 🌏 亚洲 Asia (除中国)

**已完成**: 3/50 (6%)

#### 🇯🇵 日本 Japan (1/8)

1. **Bank of Japan Statistics** (`boj-statistics`) ⭐💎
   - 权威等级：government
   - 类型：货币政策、金融统计、经济指标
   - 数据格式：CSV, Excel, PDF
   - 访问类型：开放
   - **文件**: [boj-statistics.json](asia/japan/boj-statistics.json)

#### 🇰🇷 韩国 South Korea (1/5)

1. **Bank of Korea** (`korea-bok`) ⭐💎
   - 权威等级：government
   - 类型：货币政策、经济统计
   - 数据格式：Excel, CSV, PDF
   - 访问类型：开放
   - **文件**: [korea-bok.json](asia/korea/korea-bok.json)

#### 🇮🇳 印度 India (1/5)

1. **Directorate General of Commercial Intelligence and Statistics** (`india-dgcis`) ⭐💎
   - 权威等级：government
   - 类型：贸易统计、进出口数据
   - 数据格式：Text, Excel, PDF
   - 访问类型：开放
   - **文件**: [india-dgcis.json](asia/india/india-dgcis.json)

---

### 🌏 大洋洲 Oceania

**已完成**: 3/10 (30%)

#### 🇦🇺 澳大利亚 Australia (3/6)

1. **Australian Bureau of Statistics** (`abs`) ⭐💎
   - 权威等级：government
   - 类型：国家统计、人口普查、经济数据
   - 数据格式：CSV, Excel, JSON, XML, API
   - 访问类型：开放
   - **文件**: [abs.json](oceania/australia/abs.json)

2. **Australian Institute of Health and Welfare** (`aihw`) ⭐💎
   - 权威等级：government
   - 类型：健康与福利统计
   - 数据格式：CSV, Excel, JSON, PDF, Interactive dashboards
   - 访问类型：开放
   - **文件**: [aihw.json](oceania/australia/aihw.json)

3. **Bureau of Meteorology** (`bureau-of-meteorology`) ⭐💎
   - 权威等级：government
   - 类型：气象数据、气候监测
   - 数据格式：CSV, JSON, XML, NetCDF, GeoTIFF, GRIB2, HTML, PDF
   - 访问类型：需注册（免费）
   - **文件**: [bureau-of-meteorology.json](oceania/australia/bureau-of-meteorology.json)

---

### 🌎 南美洲 South America

**已完成**: 2/15 (13%)

#### 🇧🇷 巴西 Brazil (2/5)

1. **Central Bank of Brazil** (`brazil-bcb`) ⭐💎
   - 权威等级：government
   - 类型：货币政策、金融统计、经济指标
   - 数据格式：JSON, CSV, XML, WSDL, OData, HTML, PDF
   - 访问类型：开放
   - **文件**: [brazil-bcb.json](south-america/brazil/brazil-bcb.json)

2. **Brazilian Institute of Geography and Statistics** (`brazil-ibge`) ⭐💎
   - 权威等级：government
   - 类型：国家统计、人口普查、经济和社会数据
   - 数据格式：CSV, Excel, JSON, API
   - 访问类型：开放
   - **文件**: [brazil-ibge.json](south-america/brazil-ibge.json)

3. **Brazilian Coffee Exporters Council** (`brazil-cecafe`)
   - 权威等级：market
   - 类型：咖啡出口统计、贸易数据、市场分析
   - 数据格式：PDF, Excel
   - 访问类型：需注册
   - 涵盖：巴西咖啡出口月度统计，包括出口量、目的地国家、外汇收入、平均价格
   - 特色：按咖啡类型（阿拉比卡、罗布斯塔/科尼隆、速溶、烘焙）分类、港口数据、特色咖啡
   - **文件**: [brazil-cecafe.json](south-america/brazil-cecafe.json)

4. **National Supply Company (CONAB)** (`brazil-conab`) ⭐💎
   - 权威等级：government
   - 类型：农业生产、粮食供应、市场信息
   - 数据格式：PDF, Excel
   - 访问类型：需注册
   - 涵盖：咖啡产量预测、粮食作物收成、种植面积、生产力估算
   - 特色：季度咖啡收成公报、按州和品种的产量数据、仓储设施信息、农产品定价
   - **文件**: [brazil-conab.json](south-america/brazil-conab.json)

---

### 🌍 非洲 Africa

**已完成**: 0/15 (0%)

*待添加*

---

## 区域统计 Regional Statistics

| 区域 | 计划国家数 | 计划数据源 | 已完成 | 进度 |
|------|----------|-----------|--------|------|
| 北美洲 | 3 | 30 | 11 | 37% |
| 欧洲 | 15 | 50 | 2 | 4% |
| 亚洲（除中国） | 14 | 50 | 3 | 6% |
| 大洋洲 | 2 | 10 | 3 | 30% |
| 南美洲 | 4 | 15 | 1 | 7% |
| 非洲 | 4 | 15 | 0 | 0% |
| **总计** | **42** | **200+** | **24** | **12%** |

## 分类规则 Classification Rules

### 目录结构规范
- **路径格式**: `sources/countries/{continent}/{country}/{id}.json`
  - continent: 大洲英文名（小写，连字符分隔）
  - country: 国家英文名（小写，连字符分隔，可选）
  - id: 数据源ID

### 命名规范
- **大洲代码**: `north-america`, `europe`, `asia`, `oceania`, `south-america`, `africa`
- **国家代码**: 使用英文小写国家名称，如 `usa`, `canada`, `uk`, `japan`
- **文件命名**: 直接使用数据源ID作为文件名

## 使用说明 Usage Guide

每个JSON文件遵循FirstData标准元数据Schema，包含：

- **基本信息**: ID、名称（中英文）、描述
- **访问信息**: website、data_url、api_url（如有）
- **权威等级**: government/international/research/market等
- **覆盖范围**: 地理范围、领域、更新频率
- **数据内容**: 可用数据类型和内容描述
- **搜索标签**: 中英文关键词、同义词

