# Linの一致相関係数：心拍出量モニターバリデーションにおける欠落指標

## Commentary

**投稿先候補**: Journal of Clinical Monitoring and Computing

---

**著者**: [著者名]

**所属**: [所属機関]

**責任著者**: [責任著者]

**語数**: 約2,400語（Commentary）

**キーワード**: 一致相関係数, 心拍出量, 方法比較, Bland-Altman, 血行動態モニタリング, バリデーション

---

## 抄録

心拍出量（CO）モニタリングデバイスのバリデーションは、Bland-Altman解析、パーセント誤差（PE）、およびポーラープロット評価からなる標準的な枠組みへと発展してきた。この3指標は、バイアス、一致限界、およびトレンド追従性を効果的に評価する一方で、絶対測定値の正確度と精度を同時に定量化する統合指標を提供しない。Linの一致相関係数（CCC）は、全体的な一致度を精度（Pearsonのr）と正確度（バイアス補正係数 C_b）に分解できることから、このギャップに対処しうる。他の生物医学的方法比較研究において確立された役割を有するにもかかわらず、CCCはCOモニターの標準バリデーション枠組みに組み込まれていない。本コメンタリーでは、CCCおよびその関連する一致性プロットが、現行の標準的分析手法では把握できない情報を提供する補完的指標として、COモニターバリデーション研究に採用されるべきであると論じる。

---

## 緒言

過去四半世紀にわたり、心拍出量（CO）モニタリングデバイスのバリデーションに関するコンセンサス枠組みが形成されてきた。その骨格をなすのは、バイアスおよび一致限界を評価するBland-Altmanプロット [1,2]、母集団間で正規化された比較を可能にするCritchley-Critchleyのパーセント誤差（PE）基準 [3]、そしてトレンド追従性を評価するポーラープロット [4,5] の3つの分析ツールである。方法論的ガイダンスは、Cecconi ら [6]、Saugel ら [7]、および Odor ら [8] によってさらに洗練され、方法比較研究のための段階的アプローチとチェックリストが確立されている。

この枠組みは当分野に十分貢献してきた。しかし、批判的に検討すると重要なギャップが浮かび上がる。これらのツールのいずれも、45度完全一致線に対するCO絶対測定値の正確度（真値への近さ）と精度（再現性）を同時に捉える統合的な単一値指標を提供しない。Bland-Altmanプロットは差のバイアスとばらつきを評価するが、一致線との直接的な一致度は定量化しない。PEは一致限界を正規化するが、同じ限界を継承する。ポーラープロットは変化の方向と大きさのみを評価し、絶対値は評価しない。

Linの一致相関係数（CCC）は1989年に導入され [9]、まさに方法比較研究におけるこの役割を果たすために設計された。検査医学、画像診断、肺機能検査など他の生物医学分野で広く採用されているにもかかわらず、CCCはCOモニタリングのバリデーション文献に系統的に組み込まれていない。本コメンタリーでは、CCCをCOモニターの標準バリデーションツールキットに追加すべきことを提案し、既存手法を超える診断的情報について説明する。

## 現行の枠組みとその限界

### Bland-Altman解析

Bland-Altmanプロットは、COモニターバリデーションの礎石であり続けている [1,2]。2つの手法の差をその平均に対してプロットすることにより、バイアス（平均差）と精度（一致限界、LoA = バイアス ± 1.96 SD）の視覚的評価を提供する。しかし、Odor ら [8] が認めたように、Bland-Altmanプロットには固有の限界がある。散布図上にデータが広く分散していても一貫したバイアスがないように見えるだけであり、「隠れたまたは一貫性のないバイアス（hidden or inconsistent bias）」を排除することはできない。さらに、LoAは純粋に統計的な境界であり、95%の差がこの範囲に収まることを記述するものであって、新しいデバイスの読み値が個々の測定レベルでリファレンスと互換性があるかどうかを直接示すものではない。

特に重要な限界は、デバイスが比例バイアス（proportional bias）を示す場合に生じる。すなわち、不一致の大きさがCOのレベルに応じて系統的に変動する場合である。このような場合、単一のLoAセットは誤解を招く可能性がある。回帰ベースのアプローチはこの問題に対処できるが [2]、複雑性が増し、適用に一貫性がない。

### パーセント誤差

Critchley-Critchley基準のPE ≤ ±30% [3] は、肺動脈カテーテル（PAC）熱希釈法リファレンスの既知の精度（±20%）から導かれた客観的な許容閾値を提供する。これは、研究間および母集団間の標準化された比較を可能にした画期的な貢献であった。しかし、PEはLoAを平均COで割って算出されるため、Bland-Altman解析の限界を継承する。さらに、30%閾値は特定のリファレンス手法精度を前提としており、リファレンス手法が異なる場合（例：経食道心エコー、経肺熱希釈法）には理論的に再計算すべきだが [6]、実際にはこの調整が行われることはまれである。

### ポーラープロット

Critchley ら [4] が導入したポーラープロットは、COのペア変化量間の一致を放射軸からの角度偏差として表現することにより、トレンド追従性を評価する。角度バイアス、放射方向の一致限界、および極座標一致率が、デバイスが動的変化をどの程度追従するかを記述する。これは目標指向型治療において絶対精度よりもトレンド追従性がより臨床的に重要となりうるため、臨床的に重要である。しかし、ポーラープロットは変化の方向一致のみを明示的に評価し、絶対値の一致に関する情報は提供しない。

### ギャップ

まとめると、現行の3指標は以下を評価する：
- **バイアスとばらつき**（Bland-Altman）— ただし一致線との統合的一致度は評価しない
- **正規化された一致度**（PE）— ただしBland-Altmanの限界を継承する
- **トレンド追従性**（ポーラープロット）— ただし変化のみで、絶対値は評価しない

欠落しているのは、以下の問いに直接答える指標である：*「2つの手法からの対応する測定値は、45度完全一致線上にどの程度近く分布しているか？」* これはまさにLinのCCCが定量化するものである。

## Linの一致相関係数

### 定義と分解

LinのCCC（ρ_c）は、観測値のペアが45度完全一致線上にどの程度位置するかを評価する [9,10]。定義は以下の通りである：

    ρ_c = (2 × σ₁₂) / (σ₁² + σ₂² + (μ₁ - μ₂)²)

ここで σ₁₂ は共分散、σ₁² および σ₂² は分散、μ₁ および μ₂ は2つの測定値の平均である。

決定的に重要なのは、CCCが2つの解釈可能な成分に分解できることである：

    ρ_c = r × C_b

ここで：
- **r**（Pearsonの相関係数）は**精度（precision）**を測定する — データが最良適合線の周囲にどれだけ緊密に分布しているか
- **C_b**（バイアス補正係数）は**正確度（accuracy）**を測定する — 最良適合線が45度一致線からどれだけ乖離しているか

この分解は診断的に強力である。高いrだが低いC_bを持つデバイスは、精度は高いが正確度が低い（一貫したスケールまたはオフセットエラー — 再較正により補正可能な可能性がある）。低いrだが高いC_bを持つデバイスは、平均的な正確度は良好だが精度が低い（固有の測定ノイズ — 較正では補正不可能）。この区別はデバイス開発および臨床的意思決定に直接的な含意を持つが、Bland-Altmanプロットやパーセント誤差からは抽出できない。

### 一致性プロット（Concordance Plot）

一致性プロット — 手法1 vs 手法2の散布図に45度一致線を重ねたもの — は、全体的な一致度の即座の視覚的評価を提供する。差を平均に対してプロットすることにより実際の測定スケールを不明瞭にするBland-Altmanプロットとは異なり、一致性プロットは臨床的測定スケール（COではL/min）を両軸に保持する。これにより以下の直接的な視覚的同定が可能になる：

1. **スケールエラー**（傾き ≠ 1）：最良適合線が一致線から乖離する
2. **オフセットエラー**（切片 ≠ 0）：低値または高値域で系統的なずれが見える
3. **範囲依存的な不一致**：不均一分散を示す扇状パターン
4. **外れ値**：一致線から遠い個別測定値

## 数値的例示

2つの仮想的な非侵襲COモニターを考える。いずれもPAC熱希釈法に対して120組のペア測定（真のCO範囲：2.0–9.0 L/min、平均約5.0 L/min）で比較された（Figure 1）：

**デバイスA**（比例バイアス、高精度）：
- Bland-Altman：バイアス = +0.15 L/min、LoA = [-1.44, +1.75] L/min、PE = 30.5%
- 関係式：CO_A = 1.21 × CO_ref - 0.92（傾き > 1、補償的オフセット）
- CCC = 0.867（r = 0.907、C_b = 0.956）

**デバイスB**（系統的バイアスなし、低精度）：
- Bland-Altman：バイアス = +0.12 L/min、LoA = [-1.70, +1.93] L/min、PE = 34.9%
- 関係式：CO_B = 0.83 × CO_ref + 1.00 + ランダムノイズ（SD = 1.10）
- CCC = 0.778（r = 0.782、C_b = 0.995）

Bland-Altman解析のみでは、デバイスAとBは概ね類似して見える：同程度のバイアス（約0.1 L/min）、重複するLoA範囲、そしていずれもCritchley-Critchley閾値付近の30–35%範囲のPE値。従来型の評価では、両デバイスとも境界的に許容可能な一致度を有すると結論づけうる。しかし、CCC分解は根本的に異なるエラープロファイルを明らかにする（Figure 2）：

- **デバイスA**：高精度（r = 0.907）だが正確度が低下（C_b = 0.956） — 系統的なスケールエラー（傾き = 1.21）であり、ゲインファクターのアルゴリズム再較正により補正可能な可能性がある
- **デバイスB**：高正確度（C_b = 0.995）だが低精度（r = 0.782） — 固有の測定変動性であり、較正では補正不可能

この区別は臨床的にもデバイス開発においても重要である。デバイスAでは、アルゴリズムのゲインファクターを調整するファームウェアアップデートにより一致度が大幅に改善され、PEを30%以下に引き下げられる可能性がある。デバイスBでは、エラーが系統的ではなく確率的であるため、根本的なハードウェアまたは信号処理の改善が必要となる。Bland-Altman解析のみではこれらのシナリオを区別できないが、CCC分解は各デバイスの限界の性質と適切な是正戦略を即座に同定する。

## なぜ今なのか？ Odor et al.から8年後

2017年のOdor ら [8] の出版以降のいくつかの進展が、CCCの導入を裏付ける：

1. **非侵襲デバイスの増加**：非侵襲COモニターの市場は大幅に拡大し、フィンガーカフ（ClearSight/VitaWave）、バイオインピーダンス/バイオリアクタンス（NICOM/Starling）、電気式心拍計測（ICON）、およびパルス分解解析（VitalStream）デバイスがすべて規制当局の承認を取得している [11-13]。測定原理の多様性により、標準化された包括的バリデーションはかつてないほど重要になっている。

2. **規制上の含意**：これらのデバイスに対するFDA 510(k)経路は実質的同等性の実証を要求するが、バリデーションのための具体的な統計手法は規定されていない [14]。公表されたバリデーション研究は圧倒的にBA解析とPEに依存し、トレンド評価にはポーラープロットを用いている。CCCを含めるコンセンサス推奨は、研究デザインと規制上の期待の両方に影響を与えうる。

3. **方法論的不一致の持続**：最近のメタアナリシスおよびシステマティックレビューは、バリデーション結果の報告方法が研究間で一貫していないことを引き続き指摘している [15]。確立されたベンチマーク（例：不良 < 0.90、中程度 0.90–0.95、良好 0.95–0.99、優秀 > 0.99、McBride [16] より改変）を持つ標準化された指標としてCCCを追加することは、研究間比較を促進するだろう。

4. **計算上のアクセス性**：CCCは広く利用可能な統計ソフトウェア（Rパッケージ `epiR`、Python `pingouin`、Stata `concord`）を用いて生のペアデータから容易に計算できる。Bland-Altman解析に既に必要とされるもの以上の追加データ収集は不要である。

## 提案する拡張バリデーション枠組み

COモニターの標準バリデーション枠組みを3指標から4指標に拡張することを提案する：

| 指標 | 評価対象 | 臨床的問い |
|------|---------|-----------|
| **Bland-Altmanプロット** | バイアス、LoA | 系統誤差と差のばらつきはどの程度か？ |
| **パーセント誤差** | 正規化されたLoA | リファレンスに対して一致度は臨床的に許容可能か？ |
| **ポーラープロット** | トレンド追従性 | デバイスは変化を正しい方向に追従するか？ |
| **CCC + 一致性プロット** | 統合された正確度×精度 | 測定値は完全一致線上にどの程度近く分布し、エラーはバイアスによるものかノイズによるものか？ |

CCCはその分解（rおよびC_b）とともに報告されるべきである。個々の成分が実行可能な診断情報を提供するためである。一致性プロットは、45度一致線、最良適合回帰線、およびCCC値を注釈した形で提示されるべきである。

CCCは既存手法の代替としてではなく、特定の分析的ギャップを埋める補完として提案されることを強調する。提案する4指標の各々は異なる臨床的問いに答え、総合してデバイス性能の包括的な特性評価を提供する。

## 結論

COモニターバリデーションの現行標準枠組み — Bland-Altman解析、パーセント誤差、ポーラープロット — は20年以上にわたり当分野に貢献してきた。しかし、正確度と精度を同時に捉える絶対的測定一致度の統合指標が欠落している。Linの一致相関係数は、精度と正確度の成分への解釈可能な分解を伴い、このギャップを埋める。非侵襲COモニタリング技術の増加と標準化されたバリデーション方法論の重要性の高まりを考慮し、CCCおよび一致性プロットがCOモニターバリデーション研究の定常的な構成要素として採用されることを推奨する。

---

## 引用文献

1. Bland JM, Altman DG. Statistical methods for assessing agreement between two methods of clinical measurement. Lancet. 1986;327(8476):307-310. doi:10.1016/S0140-6736(86)90837-8

2. Bland JM, Altman DG. Measuring agreement in method comparison studies. Stat Methods Med Res. 1999;8(2):135-160. doi:10.1177/096228029900800204

3. Critchley LAH, Critchley JAJH. A meta-analysis of studies using bias and precision statistics to compare cardiac output measurement techniques. J Clin Monit Comput. 1999;15(2):85-91. doi:10.1023/A:1009982611386

4. Critchley LA, Lee A, Ho AM-H. A critical review of the ability of continuous cardiac output monitors to measure trends in cardiac output. Anesth Analg. 2010;111(5):1180-1192. doi:10.1213/ANE.0b013e3181f08a5b

5. Critchley LA, Yang XX, Lee A. Assessment of trending ability of cardiac output monitors by polar plot methodology. J Cardiothorac Vasc Anesth. 2011;25(3):536-546. doi:10.1053/j.jvca.2011.01.003

6. Cecconi M, Rhodes A, Poloniecki J, Della Rocca G, Grounds RM. Bench-to-bedside review: the importance of the precision of the reference technique in method comparison studies---with specific reference to the measurement of cardiac output. Crit Care. 2009;13(1):201. doi:10.1186/cc7129

7. Saugel B, Grothe O, Wagner JY. Tracking changes in cardiac output: statistical considerations on the 4-quadrant plot and the polar plot methodology. Anesth Analg. 2015;121(2):514-524. doi:10.1213/ANE.0000000000000725

8. Odor PM, Bampoe S, Cecconi M. Cardiac output monitoring: validation studies---how results should be presented. Curr Anesthesiol Rep. 2017;7(4):410-415. doi:10.1007/s40140-017-0239-0

9. Lin LI. A concordance correlation coefficient to evaluate reproducibility. Biometrics. 1989;45(1):255-268. doi:10.2307/2532051

10. Lin LI. A note on the concordance correlation coefficient. Biometrics. 2000;56(1):324-325. doi:10.1111/j.0006-341X.2000.00324.x

11. Ameloot K, Palmers PJ, Malbrain MLNG. The accuracy of noninvasive cardiac output and pressure measurements with finger cuff: a concise review. Curr Opin Crit Care. 2015;21(3):232-239. doi:10.1097/MCC.0000000000000198

12. Squara P, Denjean D, Estagnasie P, Brusset A, Dib JC, Dubois C. Noninvasive cardiac output monitoring (NICOM): a clinical validation. Intensive Care Med. 2007;33(7):1191-1194. doi:10.1007/s00134-007-0640-0

13. Song W, Guo J, Cao D, et al. Comparison of noninvasive electrical cardiometry and transpulmonary thermodilution for cardiac output measurement in critically ill patients: a prospective observational study. BMC Anesthesiol. 2025;25:123. doi:10.1186/s12871-025-03005-1

14. U.S. Food and Drug Administration. Premarket Notification 510(k). https://www.fda.gov/medical-devices/premarket-submissions-selecting-and-preparing-correct-submission/premarket-notification-510k. Accessed March 2026.

15. Joosten A, Desebbe O, Suehiro K, et al. Accuracy and precision of non-invasive cardiac output monitoring devices in perioperative medicine: a systematic review and meta-analysis. Br J Anaesth. 2017;118(3):298-310. doi:10.1093/bja/aew461

16. McBride GB. A proposal for strength-of-agreement criteria for Lin's concordance correlation coefficient. NIWA Client Report HAM2005-062. 2005.

---

## 補足：ソフトウェア実装

CCCは一般的な統計環境で計算可能である：

**R**:
```r
library(epiR)
result <- epi.ccc(method1, method2, ci = "z-transform", conf.level = 0.95)
# 返値: rho.c (CCC), s.shift (scale shift), l.shift (location shift),
#       C.b (bias correction factor), r (Pearson r)
```

**Python**:
```python
import numpy as np

def concordance_cc(y1, y2):
    """LinのCCCと分解成分を計算"""
    mean1, mean2 = np.mean(y1), np.mean(y2)
    var1, var2 = np.var(y1, ddof=1), np.var(y2, ddof=1)
    sd1, sd2 = np.std(y1, ddof=1), np.std(y2, ddof=1)
    cor = np.corrcoef(y1, y2)[0, 1]  # Pearson r（精度）
    # バイアス補正係数（正確度）
    c_b = (2 * sd1 * sd2) / (var1 + var2 + (mean1 - mean2)**2)
    # CCC = r × C_b
    ccc = cor * c_b
    return {'ccc': ccc, 'pearson_r': cor, 'C_b': c_b}
```

**Stata**:
```stata
concord method1 method2, summary
```

---

*利益相反*: [記載予定]

*資金*: [記載予定]
