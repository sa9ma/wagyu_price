# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリは、ネット上にあり、複数人で共有するためのリポジトリ
- ローカルリポジトリは、個人のPC上にあり、個人で作業するためのリポジトリ

## プッシュとマージの違いは何でしょうか？

- プッシュは、ローカルリポジトリからリモートリポジトリに反映させるもの
- マージは、作業用のブランチを幹ブランチに変更履歴を取り込むためのもの

## コミットとプッシュの違い

- コミットは、変更履歴を任意の名前でローカルリポジトリに保存するもの
- プッシュは、保存したものをローカルリポジトリからリモートリポジトリに反映させるもの

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- 一目で変更した内容についてわかるように記載する。各チーム独自のルールがある場合はそれに従う。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- プルリクエストする場合は、バグの発生を抑えるためにほかの人からコードレビューが必要なとき
- ローカルでのマージは、複数のコミットメッセージをまとめたり、不要なコミットを統合するために行う

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

- 先にマージされた変更内容を取り込む、後にマージしようとしている変更内容を取り込む、どちらの変更内容も取り込む、以上の3通りの方法で変更を取り込む必要がある。手動で修正を行う。