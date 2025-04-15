# IEDS
Causal Discovery System Using Multivariate Post-nonlinear Models

[English]

This code is used in our study and our paper "Understanding of parameter dependence among the radiative collapse data in LHD plasmas with a causal discovery approach" (2025) by A. Anzai *et al*.

In terms of physics, the causal discovery method of this code would show not "causality" but "dependence", because the method does not use information of time.

[日本語]

このコードは作成者を含む共同研究による論文"Understanding of parameter dependence among the radiative collapse data in LHD plasmas with a causal discovery approach" (2025) by A. Anzai *et al*. 中で使用されたものである．

物理学の観点からは，本手法は時間の情報を使用せずタイムスライスを用いるため，推定される関係性は「因果」関係というよりも「依存」関係であると考える方がより妥当だと思われる．

**Our paper / 研究論文**<br>
"Understanding of parameter dependence among the radiative collapse data in LHD plasmas with a causal discovery approach" (2025):
https://pubs.aip.org/aip/pop/article/32/3/033903/3340255/Understanding-of-parameter-dependence-among-the

------------------------------------------------------------------------
# Acknowledgements / 謝辞

A.A. would like to thank Dr. Uemura Kento of the Artificial Intelligence Laboratory, Fujitsu Ltd. for his advice and for answering many questions concerning his paper.

------------------------------------------------------------------------
# Base paper and code / 先行研究ならびに参考にしたコード

[English]

IEDS is created based on the papaer by Dr. Uemura Kento *et al*., and also based on the code "AbPNL" in the github repository of RIKEN AIP-FUJITSU Collaboration Center (RAFCC).

[日本語]

IEDSを作成するにあたり，富士通上村健人研究員と理化学研究所の共同研究の成果であるAuto-encoder based Post-nonlinear Model(AbPNL)を参考にしている．

**The paper and the code by K. Uemura *et al*./上村健人研究員らの先行研究ならびにAbPNLコード** <br>
"A Multivariate Causal Discovery based on Post-Nonlinear Model" (2022): <br>
https://proceedings.mlr.press/v177/uemura22a.html

AbPNL: https://github.com/rafcc/abpnl

-------------------------------------------------------------------------
# How to use IEDS ? / 使用方法

[English]

Once you read csv or table formatted data by Pandas Data Frame in python liblary, you just do use the "causal_detection()" method!

For more details, check sample programs, please.

[日本語]

-------------------------------------------------------------------------
# Requirements

numpy

torch

pandas

psutil

scipy

-------------------------------------------------------------------------
# Mathematical assumptions

-------------------------------------------------------------------------
# About the name of IEDS
IEDS (Instant Effect Detection System/ お手軽効果特定システム/ 瞬時効果特定システム 等) is named for "Aizu (会津)", which is the name of the district in the Fukushima prefecture in Japan (Wikipedia: https://en.wikipedia.org/wiki/Aizu).

Named by Dr. Murakami Sadayoshi (ORCiD: https://orcid.org/0000-0002-2526-7137).

------------------------------------------------------------------------
# About availability / 使用に関しての注意他

[English]

Now preparing for beeing publicly available.

[日本語]

現在プログラムを公開に向け調整中
