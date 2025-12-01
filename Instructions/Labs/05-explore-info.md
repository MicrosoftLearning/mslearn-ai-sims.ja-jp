---
lab:
  title: AI 情報抽出のシナリオを調べる
  description: AI を使用して複数の形式のコンテンツから情報を抽出する方法を示すアプリケーションを確認します。
---

# AI 情報抽出のシナリオを調べる

この演習では、AI を使用して複数の形式のコンテンツから情報を抽出する方法を示すアプリケーションを確認します。

この演習の所要時間は約 **15** 分です。

## レシートからフィールドを抽出する

ある組織が経費申請処理を自動化する必要があるとします。 このようなアプリケーションの要件の 1 つは、スタイルやレイアウトが異なる可能性のあるスキャンされたレシートから、重要な情報を特定して抽出することです。

1. Web ブラウザーで、[Receipt Analyzer](https://aka.ms/receipt-analyzer){:target="_blank"} アプリ (`https://aka.ms/receipt-analyzer`) を開きます。
1. **[Upload Receipt]** ボタンを使用して、**receipt-1.png** を開きます。 画像が開いたら、分析が完了するまで待って、レシートから抽出された情報 (ベンダー名、取引日、合計金額など) を確認します。
1. アプリにより、フィールド値と、レシート内のその位置が抽出され、画像上にマークされていることに注目してください。
1. このプロセスを繰り返してレシート 2 と 3 を分析します。レシートのレイアウト、スタイル、数字や日付の書式設定が異なっていても、正しい情報が抽出されることに注目してください。

## 電話の通話から情報を抽出する

次に、別のシナリオを見てみましょう。 コーヒーの自動販売機と消耗品を販売している中小企業の経営者が、顧客から寄せられたボイスメール メッセージに返信する必要があるとします。 AI を使用して通話から情報を抽出することで、重要な詳細をすばやく確認し、タスクの優先順位付けに役立てることができます。

1. Web ブラウザーで、[Voicemail Analyzer](https://aka.ms/voicemail){:target="_blank"} アプリ (`https://aka.ms/voicemail`) を開きます。
1. 左側の各メッセージを順番に選択し、右側のメッセージで AI によって抽出された情報を確認します。 メッセージを再生して聞くこともできます。

> **注**:この演習で使用されているアプリケーションは "シミュレーション" です。背後に実際の AI モデルやサービスはありません。** ただし、[Azure AI Foundry](https://azure.microsoft.com/products/ai-foundry/){:target="_blank"}、特に [Azure AI Document Intelligence](https://azure.microsoft.com/products/ai-services/ai-document-intelligence/){:target="_blank"}、[Azure AI Content Understanding](https://azure.microsoft.com/products/ai-services/ai-content-understanding){:target="_blank"} サービスを使用して実装できる実際の機能に基づいています。
