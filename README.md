# curriculum-vitae

最終更新日 2026/02/17

## 基本情報

| Name | Shogo Tanaka |
|  ----  |  ----  |
|  Speaker Deck  |  https://speakerdeck.com/shogo452 |
|  note  |  https://note.com/shogo452 |
| Qiita |https://qiita.com/shogo452 |
|  Zenn  |  https://zenn.dev/shogo452  |

## 概要

* SRE
* インフラ、バックエンド開発がメイン
* 現職はnote株式会社

## スキル

* 言語
  * Ruby
  * HTML/CSS/JavaScript
  * 日本語
    * ネイティブ
  * 英語
    * 日常会話レベル 
* フレームワーク
  * Rails
* インフラ
  * AWS
    * EKS, EC2, ECS, RDS, CloudWatch, S3, Route53, CloudFormation, Athena, Lambda, QuickSight, EventBridge, CostExplorer, IAM, ACM, CodeDeploy, CodeBuild, OpenSeach Service, ElastiCache, WAF, CloudTrail, Glue, Elemental MediaConvert, Systems Manager, SNS, SES
  * Docker
  * Kubernetes
  * Terraform
  * Terragrunt
* ツール、その他
  * Slack
  * Backlog
  * Docbase/Notion
  * Bugsnag
  * Sentry
  * Sendgrid
  * Datadog
  * Github
  * CI/CD(CircleCI, Github Actions)
  * Figma
  * Bytebase

## 職歴

### note株式会社：2024/6 ~ 現在(正社員)

SREとして入社し、[note](https://note.com/), [noteマネー](https://money.note.com/), [tales](https://tales.note.com/)のインフラの新規構築・運用業務に従事。

#### 技術関連の記事の投稿

* [Bytebaseで実現するデータベース管理の効率化](https://note.com/shogo452/n/n7ae4857b47ae)
* [How note.com Implements Just-in-Time (JIT) Database Access Control with Bytebase](https://www.bytebase.com/blog/note-case-study/)
  * Bytebase社との共同執筆 
* [CodeBuild-hosted GitHub Actions Runnerの設定例とTips](https://note.com/shogo452/n/n58e294605494)
* [AWS Cost Explorer MCP Server と Claude Code Actionを用いたインフラコスト分析の自動化](https://note.com/shogo452/n/ne56fb11ea902)
* [複数のTerraform管理リポジトリに対するClaude CodeおよびCursorの設定の共通化](https://note.com/shogo452/n/ne56fb11ea902)

### 株式会社東雲火山：2024/1 ~ 2025/6(業務委託)

* 体験型ゲームの管理サーバーのインフラ構築・運用に従事。
  * API Gateway + Lambda(serverless-express)の構築、CI・CD環境の構築
  * ECSを用いた非同期処理サーバーの構築、CI/CD環境の構築
  * CloudFront+S3による静的サイトのホスティング、デプロイ環境の構築
* ライブ配信アプリのインフラ運用に従事。

### 株式会社スタメン：2021/2 ~ 2024/5 (正社員)

バックエンドエンジニアとして入社し、エンゲージメント経営プラットフォームサービス「[TUNAG](https://biz.tunag.jp/)」の機能改善、新機能開発に従事。

#### 概要

* 入社後は主にRuby/Railsを用いたバックエンドの機能実装をメインに担当。 
* バックエンド開発と並行してSRE業務にも従事。2023年7月からSREとしてインフラメインで業務に従事。
  * 監視・障害対応
    * CloudWatchやBugsnagのアラート対応、メトリクス監視
    * Athenaによるアクセスログの集計及びRDSのパフォーマンスインサイト・DataDogを用いたパフォーマンス監視
    * 障害対応
    * CI/CD周りのトラブルシュート
  * インフラコスト管理
    * コスト管理・削減
    * SaaSの契約更新に伴う社外調整
  * 脆弱性診断の推進
    * 診断業者との社外調整
  * 基盤整備
    * Aurora MySQLのバージョンアップ
    * 監視アラートの見直し
    * Sentryの導入

#### その他

* 会社の技術ブログへの投稿
  * [RailsのActiveRecord::AttributeMethods::Dirtyを使ってみた](https://tech.stmn.co.jp/entry/2021/04/22/100133)
  * [名前空間を用いたQuickSight上でのマルチテナントの実現](https://tech.stmn.co.jp/entry/2022/04/18/135545)
  * [QuickSightを利用してカスタマイズしたダッシュボードを埋め込む](https://tech.stmn.co.jp/entry/2022/08/03/122204)
  * [QuickSight SPICEデータのLambda関数を用いた自動更新処理](https://tech.stmn.co.jp/entry/2022/08/05/091212)
  * [QuickSightのSPICEデータ使用量をLambdaで監視している話](https://tech.stmn.co.jp/entry/2022/08/08/090850)
  * [Rubyを用いたAWS LambdaからSlackに通知する仕組みを作った話](https://zenn.dev/stmn_inc/articles/6869d707b3af70)
  * [TUNAGのDBをAurora MySQL v3にアップグレードしました](https://tech.stmn.co.jp/entry/2023/11/30/115509)
  * [SentryでRailsアプリケーションのエラー監視を始めました](https://tech.stmn.co.jp/entry/2024/02/13/093103)
* 社内表彰の受賞
  * 2022年12月：ベストプロダクト賞
  * 2023年12月：ベストプロダクト賞 & 全社MVP   

### 三菱重工業株式会社：2013/4 ~ 2021/1:正社員

* 航空宇宙部品の品質管理業務に従事。
  * [技報「複合材の最新非破壊検査技術」](https://www.mhi.co.jp/technology/review/jp/abstractj-54-4-24.html)

## 学歴

* 2013年3月 豊田工業高等専門学校 電気・電子システム工学科卒
* 研究内容：Bi系超伝導体の結晶構造の解析

## 資格

| 資格名  |  取得時期  |
| ---- | ---- |
|  AWS Certified Solutions Architect - Associate  | 2021年8月 |
|  MOS Office Excel 2016 Expert  | 2019年05月 | 
|  TOEIC スコア810  | 2018年12月 | 
| STEP BULATS SPEAKING B2, WRITING B2  | 2013年4月 | 

## 業務外活動

|  Date  |  Event/Comunity  | Details |
| ---- | ---- |---- |
| 2022/12〜2023/12 | JAWS-UG 名古屋支部 | 運営スタッフ |

## 登壇歴(社外)

|  Date  |  Event  | Slide |
| ---- | ---- |---- |
|  2022/9/26  | [BigData-JAWS 勉強会#21](https://jawsug-bigdata.connpass.com/event/257903/) |  [マルチテナントSaaSにおけるAmazon QuickSightの活用例](https://speakerdeck.com/shogo452/marutitenantosaasniokeruamazon-quicksightnohuo-yong-li)  |
|  2022/12/23  | [JAWS-UG 名古屋 2022年 "re:Invent"の復習 -忘年会-](https://jawsug-nagoya.doorkeeper.jp/events/146962) |  [Amazon QuickSightのアップデート -re:Invent 2022の復習&2022年ハイライト-](https://speakerdeck.com/shogo452/amazon-quicksightnoatupudeto-re-invent-2022nofu-xi-and-2022nian-hairaito)  |
|  2023/1/21  | [NGK2023S](https://ngk2022s.connpass.com/event/265837/) |  [5分で分かるドラッカー風エクササイズ](https://speakerdeck.com/shogo452/5fen-defen-karudoratukafeng-ekusasaizu)  |
|  2023/3/24  | [【LT会】この技術書がすごい in 名古屋](https://nagoya-it.connpass.com/event/274872/) |  [モブプログラミングの理解を深めた話](https://speakerdeck.com/shogo452/mobupuroguramingunoli-jie-woshen-metahua)  |
|  2023/5/23  | [JAWS-UG朝会 #45](https://jawsug-asa.connpass.com/event/274687/) |  [Amazon EventBridge Schedulerを用いて Amazon QuickSightの運用を改善した話](https://speakerdeck.com/shogo452/amazon-eventbridge-schedulerwoyong-ite-amazon-quicksightnoyun-yong-wogai-shan-sitahua)  |
|  2023/11/22  | [【ハイブリッド開催】BtoB SaaSのSRE奮闘事例秋まつり](https://stmn.connpass.com/event/298576/) |  [SREチーム立ち上げまでの変遷と取り組み事例](https://speakerdeck.com/shogo452/sretimuli-tishang-gemadenobian-qian-toqu-rizu-mishi-li) |
|  2023/12/18  | [JAWS-UG 名古屋 2023年 AWS re:Inventの復習](https://jawsug-nagoya.doorkeeper.jp/events/165969) |  [Amazon QuickSightのアップデート - re:Invent 2023 & 2023年ハイライト -](https://speakerdeck.com/shogo452/amazon-quicksightnoatupudeto-re-invent-2023-and-2023nian-hairaito) |
|  2024/2/21  | [ゆるSRE勉強会 #4](https://yuru-sre.connpass.com/event/306649/) |  [SentryでRailsアプリケーションの エラー監視を始めた話](https://speakerdeck.com/shogo452/sentryderailsapurikesiyonno-erajian-shi-woshi-metahua)
|  2024/11/29  | [ゆるSRE勉強会 #8](https://yuru-sre.connpass.com/event/332731/) |  [Bytebaseで実現する データベース管理の効率化](https://speakerdeck.com/shogo452/bytebasedeshi-xian-suru-detabesuguan-li-noxiao-lu-hua)

