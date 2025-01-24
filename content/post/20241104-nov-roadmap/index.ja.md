---
title: 2024年11月指針
description: 2024年休止計画の終焉と次期計画
slug: 20241104-nov-roadmap
date: 2024-11-04 16:51:00+0900
categories:
    - Guide Line
    - Develop
---

霜秋の候となり寒い日々が続きますが、いかがお過ごしでしょうか。私はついに現実活動での大きな節目を迎え、こちらの活動についても再開できる目処がついた次第でございます。

この休止期間中にいくつかの次期計画の構想ができており、どの選択をするかはかなりの悩みどころです。この記事を書いている現在も、まだ完全な決定としては決めかねている状況です。

ともかく、この記事ではこれからの大まかな予定や構想、直面している問題などを整理し、今年の残り2ヶ月及び来年前期の優先順位を記載します。

## 課題

本組織は私 Lemon73 が単独で運営しているため、とにかく時間が不足しています。また資金に関しても不足しているため、利益を確保できる事業の早期開業が望まれます。立ち絵や 3D の素材や、後述するゲーム開発により、ある程度の資金獲得を達成したいと考えていますが、これらが LRA 全体を支える資金源になるとはあまり思えないため、その他の事業を考える必要があります。現時点では特に思いついていないため、この資料への明示的な記載は行えません。

## 今年の活動

今年の大半が休止期間だったこともあり、あまり目立った活動はありません。小規模な活動としては、数年前から継続している KDE の翻訳や、Blog の更新などが行われていました。

直近では Alice Novel が v0.9.3 のリリースを迎え、本アプリケーションの安定性向上や機能追加が行われました。

## 次期計画

### ウェブサイトの刷新と Blog の統合

- 担当: LRA 本部

現在の LRA を始めとしたウェブサイトはかなり簡素な作りとなっており、開発者としてよりデザインが凝ったウェブサイトを作成することを考慮していました。また、ウェブサイトはすべて HTML で作成されており、記事の更新などを簡単に行うことができませんでした。

次期計画では、Hugo によりウェブサイトを構築し、記事を更新する際は Markdown だけの変更とすることで、更新の手間を減らします。また、ホームページは凝ったデザインとし、優れた UX を提供します。更に、ウェブサイトのデザインに関しては、開発者らしさではなく、デザイナーやイラストレーターのような可愛らしさを全面的に出すデザインにすることを重要項目とする予定です。

Lemon73 の顔とも言える、重要な役割を担うウェブサイトの開発を第一優先の開発対象として選出しました。

### ゲーム開発

ゲーム関係は複雑なので別資料で記載します。

ゲーム開発は A-RPG 以来となる悲願の計画ですが、困難が伴うことが予想されます。以前より認知していましたが、ゲーム開発はグラフィック (イラスト)、コーディング (プログラム)、トラックメイク (音楽) など様々な要素を複合した総合開発であり、それ以外の開発と比較し、成果を出すのにかなりの時間がかかります。ゲーム開発は他の開発と比較しても莫大な時間が必要であるため、LRA の金策として期待していますが、すでにある多くの競合の中で売れるのはかなり難しいと考えます。しかし、1つのゲームを作成すれば、次のゲームではある程度システムの流用を行えるため、長期的に考えるとよい計画かもしれません。現状は開発を前向きに検討しています。

#### 宗教と13人の儀式

- 担当: Ivy Cafeteria

#### 世界の終焉の前に。

- 担当: Ivy Cafeteria

### ゲームエンジン開発

現時点では計画は立っていますが、開発を積極的に進める理由が不足しており、あまり価値を感じられないというのが一通りの見解となります。一応、ゲームエンジンもゲームと同様に、別資料の頒布を行う可能性があります。

#### Alice Project (継続)

- 担当: Alice Project

LRA 及び小組織の開発の中で現状一番の計画です。この計画資料を頒布する前に、すでに開発が再開しつつあります。

(その一大発表として v0.9.3 の発表が先日行われました)

#### CR 計画

- 担当: Ivy Cafeteria

> Crystal Rabbit 計画

本計画では内部内[^inside-of-inside]ツールである Crystal a Live (Live x[^live-x]) の開発提案について議論します。

[^inside-of-inside]: 内部向けの内部公開のみ (外部公開なし)
[^live-x]: x はバージョン。バージョンが3なら Live 3

#### Anov Syntax

- 担当: Alice Project

Alice Project 側としては **A**lice **Nov**el の略として、CR 計画側としては **A**dvanced **Nov**el Script の略として **Anov** 構文が利用されています。

Anov 構文の最終的な目標は、ノベルゲーム作成だけでなく、資料作成や動画作成などの幅広い分野で利用できる汎用的なスクリプト言語です。

### Alienor Protocol

- 担当: Alienor Protocol (新規)

動画系 SNS の開発を行います。

この開発自体はある程度の価値を認めることができ、積極的な開発が望まれます。しかし、動画配信プラットフォームであるということもあり、データサーバーを支えるための莫大な資金が必要になるという資金面や、動画の違法転載の取締などの法律的な観点から開発を進めること自体が困難であると認知しています。いくら優れたアプリケーションであっても、サーバー (インスタンス) がなければ意味がないです。これらの懸念点を考慮し、開発を行うかどうかの最終的な評価を行う必要があります。現時点では小規模での開発を前向きに検討しています。

### 外部活動

#### KDE

- 担当: Lemon73

翻訳を主に行います。開発は C++, Python の学習コストの観点から、行う予定はありません。翻訳に関しては、今まではマイナーなアプリケーションやウェブサイトを中心に行っていましたが、これからはメジャーな基本アプリケーションなどを中心に行うことを検討しています。

#### .NET MAUI (maui-linux)

- 担当: Lemon73

MAUI の Linux 実装を進めることを考えています。しかし、開発が難航しており、成果が出せるかどうかは微妙です。

### その他

#### 記事の更新頻度

- 担当: LRA 本部

今まで Blog や Qiita, Zenn などでの記事の作成はあまり行っていませんでしたが、広報活動としての役割を担えると考え、記事の更新の頻度を上げることを推奨します。

毎週資料を書くことを強制する案も考えましたが、強制することにより記事の品質が低くなる可能性があるため、あくまで推奨事項とします。

#### 開発水準

休止期間のうち、特に7月-9月は GitHub のコミット数が50程度まで停滞しましたが、11月の目標は休止以前の昨年12月-今年4月あたりの200-250コミット程度まで開発水準を戻す予定です。(もちろん開発水準とコミット数が一致するわけではないので、あくまでコミット数は参考程度です)

## 最後に

現時点でもまだ未確定な部分が多いため、今後の調整などにより決定していきます。

ひとまず、ウェブサイトの構築を進めていく予定です。

## 公開

- [Lemon73 Blog (ここ)](./) (2024/11/4)