# 美国州 · 中英文对照与地区归属

美国 51 个州及特区（50 州 + 华盛顿特区）的中英文名称对照，以及跨境物流常用的四分区归属。

## 在线访问

https://linhf123.github.io/us-state-regions/

## 分区规则

| 分区 | 州数 | 范围 |
|---|---|---|
| 美西 West | 13 | 太平洋沿岸 + 山地西侧，含 AK / HI |
| 美中 Central | 13 | 五大湖 + 中西部平原，含 KY |
| 美南 South | 7 | 墨西哥湾沿岸 + 德州 + 田纳西 |
| 美东 East | 18 | 东北 + 东南沿海，含 DC |

具体归属：

- **美西**：AK AZ CA CO HI ID MT NM NV OR UT WA WY
- **美中**：IA IL IN KS KY MI MN MO ND NE OH SD WI
- **美南**：AL AR LA MS OK TN TX
- **美东**：CT DC DE FL GA MA MD ME NC NH NJ NY PA RI SC VA VT WV

## 几点说明

- **AK / HI 归美西**：离西海岸最近，通常经加州或华盛顿州中转。
- **TX 归美南**：德州体量大、位置居中，单列后不与其他区混。
- **KY 归美中**：虽然地理上偏东南，但走辛辛那提 / 路易斯维尔枢纽，跟中西部网络更顺。
- **不设美北**：北部各州与中西部高度重合，单列后与美中难以区分。

## 文件

- `index.html` — 可交互页面，支持按分区筛选、按州代码/中文/英文搜索
- `states.csv` — 同源数据，UTF-8 BOM 编码，Excel / WPS 可直接打开

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```
