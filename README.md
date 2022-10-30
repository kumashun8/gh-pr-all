## Usage

```shell
$ gh pr-all list [flags]
```

## Spec(TODO)

- from, to を指定して、自分が所属する全ての organization 内の repository に対して、その期間自分が出した PR 一覧を出す。出力形式は `gh pr list` に準ずる。
- 期間はデフォルトで実行時刻から一週間。個人的にその週のアウトプットをサクッと見たいという理由。
- target オプションで出力対象の repository や organization を指定できるようにする。
- exclude オプションで出力対象から除外したい repository や organization を指定できるようにする。
