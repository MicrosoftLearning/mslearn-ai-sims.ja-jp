---
title: ホーム
permalink: index.html
layout: home
---

以下の演習では、さまざまなアプリケーションにおける一般的な人工知能のワークロードについて確認します。 これらの演習の目標は、AI の機能の一部を経験し、AI によって可能になるソリューションの種類について学ぶことです。 開発者や技術の専門家である必要はありません。 セットアップ要件はありません。 必要なのはモダン Web ブラウザーだけです。AI で実現できるすばらしい機能をすぐに体験できます。

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %} {% for activity in labs  %}
<hr>
### [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})

{{activity.lab.description}}

{% endfor %}

<hr>

## AI アプリケーション

記載されているラボ手順を実行せずに、アプリケーションを自分で調べる場合は、以下のリンク先を参照してください。

- [Home Rental Predictor (機械学習 - 回帰)](https://aka.ms/rent-predictor){:target="_blank"}
- [Wheat Seed Identifier (機械学習 - 分類)](https://aka.ms/seed-identifier){:target="_blank"}
- [Customer Segmentation (機械学習 - クラスタリング)](https://aka.ms/customer-segmentation){:target="_blank"}
- [Expenses Chat Assistant (生成 AI エージェント)](https://aka.ms/expenses-agent){:target="_blank"}
- [Recruiter Dashboard (生成 AI エージェント)](https://aka.ms/resume-app){:target="_blank"}
- [StoryBridge 社会史プロジェクト (自然言語処理)](https://aka.ms/story-bridge){:target="_blank"}
- [Blue Yonder Airlines ソーシャル メディア アナライザー (自然言語処理)](https://aka.ms/blue_yonder_social){:target="_blank"}
- [Photo Tagger (コンピューター ビジョン)](https://aka.ms/photo-tagger){:target="_blank"}
- [Doorbell Photo Viewer (コンピューター ビジョン)](https://aka.ms/doorbell){:target="_blank"}
- [Receipt Analyzer (情報抽出)](https://aka.ms/receipt-analyzer){:target="_blank"}
- [Voicemail Analyzer (情報抽出)](https://aka.ms/voicemail){:target="_blank"}

> **注**:これらのアプリケーションは "シミュレーション" です。モデルは単純であり、背後に Azure AI サービスはありません。** ただし、[Microsoft Azure AI テクノロジ](https://azure.microsoft.com/solutions/ai/){:target="_blank"}を使用して実装できる実際の機能に基づいています。
