# 先進計算機構成論

東京大学大学院 情報理工学系研究科 創造情報学専攻で行っている「先進計算機構成論」の講義の資料です．

* パワーポイントと PDF でファイルを置いていますが，アニメーションを結構使っているためパワーポイントで正しく見れる方はそちらの方がおすすめです．
* パワーポイントで表示がずれる方は PDF 版を参照してください．
* 質問や間違いの指摘などは，github の issue に投げていただければと思います．

## 講義資料

0. [イントロ](./aco-shioya-00.pptx?raw=true) （[PDF版](./aco-shioya-00.pdf)）
1. [コンピュータの基本](./aco-shioya-01.pptx?raw=true) （[PDF版](./aco-shioya-01.pdf)）
    * コンピュータの基本
        * 命令やプログラム，機械語とはなにか
        * 単純な CPU の構造と動作
    * C 言語で書かれたプログラムの実行を考える
        * C 言語と機械語の対応
    * 命令セットの例：RISC-V
2. [回路と遅延](./aco-shioya-02.pptx?raw=true) （[PDF版](./aco-shioya-02.pdf)）
    * (RISC-V についての続き
    * 論理回路の復習
    * 回路の遅延
3. [回路の消費電力と命令パイプラインの基本](./aco-shioya-03.pptx?raw=true) （[PDF版](./aco-shioya-03.pdf)）
    * 回路の消費電力
    * 命令パイプライン
4. [命令パイプラインの詳細](./aco-shioya-04.pptx?raw=true) （[PDF版](./aco-shioya-04.pdf)）
    * パイプラインの詳細
    * 各種のハザードと解消方法
        * 構造ハザード
        * 非構造ハザード
5. [命令パイプラインと性能，分岐予測](./aco-shioya-05.pptx?raw=true) （[PDF版](./aco-shioya-05.pdf)）
    * 命令パイプラインと性能
    * 分岐予測の基本
6. [分岐予測](./aco-shioya-06.pptx?raw=true) （[PDF版](./aco-shioya-06.pdf)）
    * 各種分岐予測器の構成について
7. [分岐予測とメモリについて](./aco-shioya-07.pptx?raw=true) （[PDF版](./aco-shioya-07.pdf)）
    * 高度な分岐予測器
        * パーセプトロン予測器と TAGE 予測器
    * 間接分岐予測
    * メモリの基本
    * SRAM や DRAM の構造
8. [命令の並列実行](./aco-shioya-08.pptx?raw=true) （[PDF版](./aco-shioya-08.pdf)）
    * 命令の並列実行
    * データ依存
    * 静的命令スケジューリングと VLIW
9. [動的命令スケジューリング](./aco-shioya-09.pptx?raw=true) （[PDF版](./aco-shioya-09.pdf)）
    * in-order 発行/in-order 完了
    * in-order 発行/out-of-order 完了
    * out-of-order 発行/out-of-order 完了
10. [動的命令スケジューリングの続き，GPU の概要](./aco-shioya-10.pptx?raw=true) （[PDF版](./aco-shioya-10.pdf)）
    * 例外への対処，ロード/ストアのスケジューリング
    * GPU の概要
11. [キャッシュ](./aco-shioya-11.pptx?raw=true) （[PDF版](./aco-shioya-11.pdf)）
    * 基本原理
    * 容量と性能の関係
    * 詳細な構造
    * 行列積での性能の変化の例
12. [保護機構とアタック](./aco-shioya-12.pptx?raw=true) （[PDF版](./aco-shioya-12.pdf)）
    * 保護機構
        * 仮想メモリ
        * 特権モード
    * 脆弱性とアタック
        * バッファ・オーバーフロー
        * Return Oriented Programming
        * マイクロアーキテクチャ面の脆弱性

## 付録

* [付録1:分岐予測の詳細](./aco-shioya-appendix-bpred.pptx?raw=true) （[PDF版](./aco-shioya-appendix-bpred.pdf)）
    * パーセプトロン予測器や TAGE 予測器の詳細
    * 間接分岐予測器
    * 複数命令同時フェッチ時の予測の実装方法
* [付録2:高性能CPUの研究・開発動向](./aco-shioya-appendix-processor.pptx?raw=true) （[PDF版](./aco-shioya-appendix-processor.pdf)）
    * プログラムの複雑化とシングルスレッド性能の向上
    * 「現代の」Out-of-order スーパスカラ・プロセッサの構造
    * 最近の研究

* 謝辞
    * 付録の一部を作るのを手伝ってくれた情報理工学系研究科 電子情報学専攻の小泉くんに感謝します．
