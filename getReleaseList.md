そのリリースから追加されたマージ情報のみを取得する

```

git tag | tail -n [previous releases number] | head -n 1 | xargs -i git log --merges {}..

```