---
lab:
  title: 自然言語処理のシナリオを調べる
  description: AI の自然言語処理機能を使用して、話し言葉や書き言葉のテキストを書き起こし、分析する方法を示すアプリケーションを確認します。
---

# 自然言語処理のシナリオを調べる

この演習では、AI 搭載の社会史プロジェクト サイトとソーシャル メディア分析サイトをシミュレートするアプリケーションを確認します。

この演習の所要時間は約 **15** 分です。

## 記録されたインタビューを分析する

*StoryBridge* アプリケーションの目標は、オーディオ録音に基づいて一般の人々の個人的な思い出を収集し、カタログ化することです。 世界各地の人々から、人生の思い出深い瞬間について短いエピソードを録音したものが送信されました。 あなたはこれらの録音を書き起こして分析し、*StoryBridge* 社会史プロジェクトの一環としてカタログ化する必要があります。

1. Web ブラウザーで、[StoryBridge アプリ](https://aka.ms/story-bridge){:target="_blank"} アプリ (`https://aka.ms/story-bridge`) を開きます。
1. **[Upload File]** ボタンを使用して **story-1.wav** を開きます。 ファイルが開いたら、メディア プレーヤーで再生できます。 数秒すると、アプリによって録音エピソードの文字起しと分析が行われ、メンションされている主要なエンティティ (名前、場所、日付など) が特定され、エピソードの全体的な "センチメント" が評価されます。**
1. ストーリー 2 と 3 に対してこのプロセスを繰り返し、生成された分析を確認します。
1. **story-4.wav** を開いて録音を聞き、分析を表示します。
1. アプリによってエピソードが英語に翻訳されることに注目してください。

## ソーシャル メディアの投稿を分析する

Blue Yonder Airlines は、ハッシュタグ *#BlueYonderAirlines* を使用して同社をメンションしているソーシャル メディアの投稿を分析したいと考えています。 このアプリケーションでは、ソーシャル メディアの投稿を取り込み、そこに含まれるセンチメントやキー フレーズを分析する方法を確認します。

1. Web ブラウザーで、[Blue Yonder Airlines ソーシャル メディア アナライザー](https://aka.ms/blue_yonder_social){:target="_blank"} アプリ (`https://aka.ms/blue_yonder_social`) を開きます。
1. **[Start capturing]** ボタンを使用して、タグ *#BlueYonderAirlines* をメンションしているソーシャル メディア メッセージの取り込みを開始します。
1. 各投稿が取り込まれたら、それを選択して **[Post Details]** ペインで詳細を表示します。 投稿のセンチメントとキー フレーズは AI を使用して判断されていることに注目してください。
1. ページの上部を見ると、ソーシャル メディア投稿のセンチメントのメトリックが、AI 分析によって継続的にリアルタイムで計測されていることがわかります。
1. **[Stop capturing]** ボタンを使用して、ソーシャル メディアの投稿の取り込みを停止します。

> **注**:この演習で使用されているアプリケーションは "シミュレーション" です。背後に実際の AI 音声や言語サービスはありません。** ただし、[Azure AI Foundry](https://azure.microsoft.com/products/ai-foundry/){:target="_blank"}、特に [Azure AI 音声](https://azure.microsoft.com/products/ai-services/ai-speech/){:target="_blank"}、[Azure AI Language](https://azure.microsoft.com/products/ai-services/ai-language){:target="_blank"}、[Azure AI Translator](https://azure.microsoft.com/products/ai-services/ai-translator){:target="_blank"}サービスを使用して実装できる実際の機能に基づいています。
