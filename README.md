# Business-management-application
業務管理アプリケーション

# 概要
下請業者との業務内容を共有する為の管理システム

# 背景
現在、電気設備工事の現場監督（サブゼネコン）として働いています。建築（ゼネコン）との業務管理はアプリケーションで管理しておりますが、サブゼネコンとの下請け業者とは口頭でのやり取りによる管理をしています。※図参照

![業務管理体制](https://user-images.githubusercontent.com/90845405/197956867-5e2f7fb5-2304-4661-b943-a199945303c8.jpg)

口頭で管理するので聞き漏れや聞き忘れ等が発生や何十社と電話で確認をするのに時間がかかります。※図参照

![analog](https://user-images.githubusercontent.com/90845405/197953637-df706a90-57e0-4cfa-b8be-838ff5170d64.jpg)

そこで、対策としてGoogle Apps Script（GAS）+　Google Forms　＋　Lineを連携した簡易なシステムを開発し運用してました。

![line](https://user-images.githubusercontent.com/90845405/197954691-cb1dbcda-2167-4ea3-898a-2f76a6a079bd.jpg)

上記のシステムにより、電話をする時間から解放され、どこの会社が何の業務をしているかを共有化できました。
しかし、運用していて以下のでデメリットがありました。

* 業務内容の更新・削除ができない
* 下請業者が多くなるとLineをスクロールして確認するのが大変
* 過去の業務を確認はできるが探すのが大変



