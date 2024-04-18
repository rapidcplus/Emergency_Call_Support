# Emergency_Call_Support （1分以内で会得しなッ！）

---

### **サービス概要**
　このWebアプリは、消防の指令員（オペレーター）が119番通報の受付時に、通報者に対して迅速かつ的確な口頭指導を可能にするプラットフォームサービスです。オペレーターは、事前に説明動画を用意しておくことで、簡単に通報者へ動画URLをSMS送信することができます。

---

### **このサービスへの思い・作りたい理由**

 私は現役消防士として、119番通報を受け付け、通報内容に応じて消防車両を出動させる業務に従事している通信指令室の指令員（オペレーター）です。日々、さまざまな通報を受け付けるなかで、応急手当て等の口頭指導を行ったり、初期消火の協力を依頼したりすることがあります。

 しかし、私自身、声のみの説明で慌てている通報者にきちんと伝わっているか不安を覚えていましたし、一方で、通報者の方も普段やり慣れていない初期消火や応急手当ての説明を電話越しに受けても、その理解は難しいようでした。そこで、オペレーターが要点を絞った説明動画を簡単にSNS送信でき、また通報者がその動画をスマートフォンで見ることができれば、オペレーター業務の改善が図れると考えたのがきっかけです。

 現状はそのような説明動画を準備しておいたとしても、簡単にリンクを送る方法はありません。そのため、事前に用意した説明動画を一覧で管理し、そのリンクを簡単にSMS送信できるWebアプリ（プラットフォーム）を開発しようと決意しました。

**口頭指導とは？**

　119番通報を受付けた際、オペレーターが傷病者の状態を聞き取り、救急車が到着するまでの間に何らかの応急手当てが必要だと判断した場合、通報者を含めた救急現場に居合わせた方々に対して電話越しに応急手当ての協力を要請し、その実践方法を説明・指導するものです。特に、心肺停止状態の方に対して行う胸骨圧迫（心臓マッサージ）やAEDを使った救命活動は、その後の生存率に直結するため、現場に居合わせた方々の適切で迅速な行動が重要となります。

**過去の事例**

　救急隊が現場に駆けつけると、オペレーターの「心臓マッサージはできますか？」の尋ねに「できます！」と即答したはずの通報者が、一心不乱に傷病者の胸をさすっていた...。という事例がありました。現場を見ることができないオペレーターにとっても、慌てていて適切な行動ができていない通報者にとっても、電話口での確認だけではお互いの誤解に気がつくことができません。

---

### **ユーザー層について**

**対象ユーザー**

- 指令員（オペレーター）

**※ユーザー選定の理由（補足）**

　このプラットフォームは、オペレーターの業務改善Webアプリです。したがって対象ユーザーは、消防指令員たちに限ります。一方で、通報者や現場に居合わせた協力者が、このWebアプリにるサービス受益者です。送信されてきた動画を視聴することで、初期消火や応急手当てのやり方を視覚的に確認することが可能になり、電話越しの声だけの説明を受けるより、理解度の向上が予測できます。
---

### **サービスの利用イメージ**

1. 事前に用意しておいた動画一覧の中から、通報内容に応じた適切な説明動画を選択
2. 動画URLを通報者・協力者のスマートフォンにSMS送信
3. 通報者・協力者が受信したSMSのURLから説明動画にアクセスし、視聴
4. 動画の内容に基づいて、適切な初期消火・応急手当てを実施

**※3について**
　固定電話やフィーチャーフォン（ガラケー）からの通報も想定されるため、場合によってはスマートフォンを持っている協力者の電話番号宛にSMS送信することも考慮しています。

---

### **サービスの差別化ポイント・推しポイント**

- **動画による分かりやすい説明：** 声だけの説明と比較して、動画を見ながらの方が内容をイメージしやすく、適切な応急手当てや初期消火などの対応を実践しやすいです。

- **事前準備された動画：** 状況に合わせた動画を事前に準備することで、指令員は迅速かつ的確な動画選択が可能になります。

- **SMS送信による利便性：** 動画を検索してもらう煩わしさがなく、指令員も手軽に動画リンクを共有できます。

- **直接SMS送信：** 動画リンクを**通報者の電話に直接SMS送信**することで、スムーズな情報共有を実現します。

- **オペレーターの負担軽減:** 口頭指導をしないことで指令員の負担が軽減され、一方で、新たな119番通報へ迅速に応対することができます。

- **公平な住民サービス:** 動画による説明は、指令員個人の説明力やコミュニケーション能力に依存しないため、常に一定した水準の市民サービスを提供できます。

---

### **機能候補**

**MVPリリース時**

- 説明動画一覧画面: 様々な説明動画のサムネイルを表示
- 動画選択機能: ユーザーが状況に合った動画を選択
- SMS送信機能: 選択した動画のURLをSMSで送信

**本リリースまで**

- 検索機能
- カテゴリ分類機能
- ユーザー管理機能

---

### **本リリース後のユーザーの獲得について**

- 消防署への説明
- 他消防本部への横展開

---
### **機能の実装方針予定**

**説明動画一覧画面**

[画面遷移図](https://www.figma.com/file/b2eg08fgpCZsViWha4ok0T/Emergency_Call_Support(Flow-Diagram)?type=whiteboard&node-id=0%3A1&t=87TxCsT2z5kEfRZS-1)

[ER図](https://drive.google.com/file/d/1T4_LI3SraHF1XoAFl2yyrew9va6pUNoo/view?usp=sharing)
