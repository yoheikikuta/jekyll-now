---
layout: post
title: 確定申告の提出書類を作成した
categories: ['雑談']
---
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>


### TL;DR
- 平成29年分の確定申告の提出書類を作成した
- 検討の結果、会計ソフトなどは何も使わずに全て自分で作成した
- 作ったのは確定申告書Bと青色申告決算書と医療費控除の明細書

確定申告の季節だ。  
確定申告は何度かしたことがあるが、個人事業主としても仕事をしながら確定申告書と青色申告決算書を作るのは初めてなので、備忘録を兼ねて記事にしておく。

とはいえ細かい情報は手元に控えを残してるので、この記事は単なる日記として書くくらいの気持ちで、誰かの役に立つほど有用な情報をまとめるつもりはない。


## 全部自分でやった理由
まず、クラウドの会計ソフトは一ヶ月無料というものも多いので、以前に試したことがあった。  
これらは機能が充実していて中小企業では有用かもしれないが、自分には必要ないものが多過ぎた。
自分が使う仕分けは相当限定的なので、毎月お金を払う気にはなれないし、確定申告の作業をする月だけお金を払ってソフトを使うのも{ソフトに慣れるのにコストが掛かる、お金を払わなくなると過去データが見直せない}などの理由でイマイチだなと思った。

ということで全部自分でやってみることにした。
青色申告の申請をしているので複式簿記が要求されるが、まあちょっと勉強すれば大丈夫だろうという呑気な気持ちで進めることにした。


## 使ったツール
- Google docs : 単なるメモ用として
- Google spreadsheets : 仕分け帳や総勘定元帳の作成

基本的にはこれだけ。まあそれはそうだろう、別に特別なツールが必要な作業でもないし。  
あとは国税庁のHPと郵送されてくる確定申告の手引とウェブ上の情報で必要な知識は得た。


## 手元に残している書類
複式簿記では取引の情報を記録しておく上で必ず作成しなければならない主要簿（仕訳帳、総勘定元帳）があり、必須ではないが勘定科目毎に詳しい情報を残しておくための補助簿がある。  
自分の場合は取引の数が多いわけではなく、補助簿を残さないと把握できないというものでもないので、主要簿のみ作ることにした。

- 仕訳帳  
  全ての取引を記録したもの。貸方や借方の意味や勘定科目として何を使うか、は自分の場合は15~20パターンくらいググッて調べてそれに倣って書けば大体網羅できるものだった。  
  これはレシートやカードの使用記録に基づいて、日付順に spreadsheets に地道に打ち込んでいった。自分の場合は取引が多くないので、一年に一回これくらいを手作業でやるのはまあ耐えられるレベル。
- 総勘定元帳  
  仕訳帳を勘定科目毎に分けてまとめたもの。こいつは spreadsheets で仕訳帳を作っておけばフィルタリングしてコピペして、くらいの作業で作れるので大した作業量ではない。  
  これも一年に一回これくらいの作業量なら、まあ粛々とやればいいのではという気がする。
- レシート（領収証）  
  青色申告だと7年の保存義務がある。長い...　無くさずに持ってられるというのはなかなか難しい要求だが、これは愚直にファイリングして手元に持っている。


## 申告用に作った書類
- 確定申告書B  
  事業収入と給与収入があるのでこれが税務署から送られてくる。
  基本的には{源泉徴収票、所得税青色申告決算書、医療費控除の明細書｝に基づいて、「確定申告の手引」で必要なところを埋めていくことで書くべき金額を明らかにし、それを転記するということで作成。
- 所得税青色申告決算書  
  総勘定元帳に基づいて作成。
  青色申告では貸借対照表が必要だが、自分の場合は複雑ではないのでちょっと調べれば疑問は解決し、大きな問題もなく作成。
- 医療費控除の明細書  
  平成29年度からはこの明細書を作ることで申告ができるとのこと。
  これまでは領収証送ってたのか...ﾋｴ~  
  作るのは難しくなく、ちょっと調べながら書いてすんなり作成。


## 所感
- ちょうどよいまとめ情報がなかった。兼業なら自分と同じような確定申告をする人が結構いるかなと思っていたが、「大体一緒だから真似しておこう」となる情報がなかった。結局必要な部分の情報を適宜探して進めた。
- 事業用にクレジットカードを作って経費とかをまとめられればもうちょっと楽になりそうだが、地代家賃の按分とかで完全分離できないので、自分としてはイマイチ乗り気になれなかった（営業性個人口座は使っている）。
- 会社員としても働いている場合、社会保険料は会社で強制加入の分で完結しているので、新たにやるべきことはないと知った。
- 印税は源泉徴収されていて、その辺りをどう仕分けで取り扱うかはちょっと混乱した。売掛金回収時に事業主貸で取り扱うと学んだ。
- 銀行口座の利息、生活上は negligible だけど仕分上はちょっと注意を要するものだったので、これ何とかならないものかね。
- 所得税...結構な金額ですなぁ...有意義に使ってください。


## まとめ
確定申告用の提出書類を作成した。全部自分でやってみたところ、そこそこ勉強になるし現実的な作業量で可能だったので、良い判断だったのではないかと思う。

---
---
<br>
