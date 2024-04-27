# Julia の仮想環境

## Julia の仮想環境の作り方

1. julia の Pkg mode に入る

2. 仮想環境の作成

> [!Tip]
> 　 `Pkg mode`で以下を実行する

```julia
generate <仮想環境名>
```

## 仮想環境に入る

> [!Tip]
> `Pkg mode`で以下を実行する

> [!Tip]
> 　 package を追加する場合は、仮想環境に入ってから、`add <package名>`を実行する

※ サンプルで作成した`myenvironment`という仮想環境に`Plots`という package を追加している。

```julia
activate <仮想環境名>
```

仮想環境のプロジェクトのパスで、`Pkg mode`に入った場合は、以下を実行する

```julia
activate .
```

## 仮想環境から抜ける

> [!Tip]
> `Pkg mode`で以下を実行する

```julia
activate
```

## プログラムファイルの実行

> [!Tip]
> コマンドプロンプトで以下を実行する

```shell
julia --project <相対パス>
```

実行例

```shell
julia --project ./src/myenvironment.jl
```
