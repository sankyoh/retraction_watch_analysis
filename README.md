# Retraction Watch DB analysis
論文撤回データベースを独自の視点で解析することで、論文撤回の動向について明らかにする。
データは、Crossrefの[gitlabサイト](https://gitlab.com/crossref/retraction-watch-data)から取得する。

#  JEA & JEAWPR 2026（2026年1月29日）での発表
Title: Did the Launch of ChatGPT Affect Retraction Trends? Evidence from an Interrupted Time Series Study

poster -> [260129Poster_sankyoh.pdf](https://github.com/sankyoh/retraction_watch_analysis/blob/main/260129Poster_sankyoh.pdf)

## 要旨（日本語版）
はじめに：ChatGPTなどの生成AIの最近の普及は、研究の誠実性に関する懸念を引き起こしている。AI生成コンテンツが科学文献を損なう可能性については議論されているが、撤回件数への定量的影響は依然不明確である。本研究は、他の重要な事象を考慮に入れつつ、この影響を評価することを目的とする。

方法：Retraction Watchデータベースを用い、生物医学論文に焦点を当てた中断時系列分析を実施した。分析対象は2012年1月から2023年7月までに発表され、データ抽出時点（2025年8月）までに撤回された論文とした。介入事象はChatGPTの公開（カットオフ：2023年3月1日、3ヶ月遅れ）とした。「コンピュータ支援コンテンツ」の月次撤回率を、COVID-19パンデミックと2022年10月のHindawi社による大量撤回の影響を調整した負の二項回帰モデルで推定した。感度分析では0ヶ月および6ヶ月の遅延期間を用いた。

結果：COVID-19パンデミックとHindawi社の大量撤回を調整後、ChatGPTのリリースはコンピュータ支援コンテンツの撤回傾向の顕著な加速と関連していた。介入後の傾向は月あたり68.8%増加した（発生率比［IRR］：1.688、95%信頼区間［CI］：1.351-2.110）。撤回レベルの即時変化は統計的に有意ではなかった（IRR: 2.298, 95% CI: 0.875-6.031）。感度分析でも同様の結論が得られた。

考察： 本結果は、ChatGPTのリリースがコンピュータ支援コンテンツの撤回加速と関連していることを示唆している。これはCOVID-19パンデミックの影響や出版社固有の大量撤回事象を考慮した後でも同様である。パンデミックは全体的な増加と関連し、出版社の取り締まりは一時的な減少と関連したが、ChatGPT以降の時代には明確かつ有意な上昇傾向が認められる。生成AI時代においては、継続的な監視と研究倫理方針の更新が不可欠である。

## Abstract（English version）
Introduction: The recent proliferation of generative AI, such as ChatGPT, has raised concerns about research integrity. While the potential for AI-generated content to undermine scientific literature is discussed, its quantitative impact on retractions remains unclear. This study aims to evaluate this impact while accounting for other significant events.

Methods: I conducted an interrupted time series analysis using the Retraction Watch Database, focusing on biomedical papers. The analysis included papers published from January 2012 to July 2023 and that had been retracted by the time of data extraction (August 2025). The intervention was the public release of ChatGPT (cutoff: March 1, 2023, with a 3-month lag). I modeled the monthly rate of retractions for "Computer-Aided Content" using a negative binomial regression, adjusting for the effects of the COVID-19 pandemic and Hindawi's mass retraction in October 2022. Sensitivity analyses used 0- and 6-month lags.

Results: After adjusting for COVID-19 pandemic and Hindawi's mass retraction, the release of ChatGPT was associated with a significant acceleration in the trend of retractions for computer-aided content. The post-intervention trend increased by 68.8% per month (Incidence Rate Ratio [IRR]: 1.688, 95% Confidence Interval [CI]: 1.351-2.110). The immediate change in retraction level was not statistically significant (IRR: 2.298, 95% CI: 0.875-6.031). Sensitivity analyses yielded similar conclusions.

Discussion: The findings suggest that the release of ChatGPT is associated with an accelerated increase in retractions for computer-aided content, even after accounting for the effects of the COVID-19 pandemic and publisher-specific mass retraction events. While the pandemic was linked to a general rise and publisher crackdowns to a temporary fall, the post-ChatGPT era shows a distinct and significant upward trend. Continuous monitoring and updated research integrity policies are essential in the age of generative AI.

