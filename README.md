# [practice] Todo-Application

## 課題
以下、要件を満たすWebアプリケーションを作成する。

## 画面について
1ページで完結のtodoアプリケーションの作成。（画面遷移はしない）
使用するライブラリ、フレームワークは自由。

## 要件項目
用途は1日のタスクを管理するアプリケーションと考える。  

- TODOの追加ができる(動的にviewに反映させる)
  - 項目1：タイトル (空文字はNG) *必須*
  - 項目2：期限 （数字のみの入力としてバリデーションも行う事） *必須*
- 各TODOが完了・未完了のステータスを持ち、何らかのイベントで変更ができる
- 各TODOを削除ができる
- 既存の各TODOのタイトル、期限を編集できる（編集で空文字にさせて終了したら削除）
- TODOを状態ごとにフィルタリングできること（一覧・完了・未完了）
- TODO一覧をタイトルでフィルタリングできること(部分一致)

上記条件を満たしていればUI/UXに関しては基本的に自由。
また、今回はフロントエンドのみの実装となるため、リロードで初期化される仕様で良い。

## 参考
今回の要件とは異なる部分があるが
http://todomvc.com/examples/angularjs
このような形をイメージ。

## 上記実装ができたら挑戦してほしい追加実装
### 追加実装1
項目3としてラベルを追加する（カテゴリ分けのようなもの）
また、既存するラベルの選択形式でラベルでのフィルタリングができる
  
### 追加実装2
ソートでTODOの順番を入れ替えるができる
追加順の昇順・降順
期限の昇順・降順
の4項目のソート機能の持つ
またソートした後はその状態を維持し、これまで通りフィルタリング機能も併用できる

### 追加実装3
ドラッグアンドドロップでのタスクの並べ替え。
もちろんこれまでの機能はそのまま使える。
 
**追加実装については課題の要件外であるがロジック面では工夫が必要なものとなっており1〜3で順に難易度も上がっているので挑戦すると力がつくと思います。**
 
### データの保持やデータのviewへの反映など、これまでの研修で行っていたものとは設計概念から異なり、難易度も高いものとなるためこの実装ができるころには超レベルアップしてるはず。
