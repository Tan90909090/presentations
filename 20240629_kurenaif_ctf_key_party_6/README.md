# 20240629_kurenaif_ctf_key_party_6

[魔女のお茶会 #6(2024 夏) - connpass](https://witchskeyparty.connpass.com/event/320525/)で発表した資料を含むリポジトリです。

発表資料本体は[slide.pdf](slide.pdf)です。

## 備考
本発表で紹介している3問は、ブログでも解説しています:

1. TSG CTF 2023 "T the weakest":  [TSG CTF 2023 write-up](https://tan.hatenadiary.jp/entry/2023/11/05/211534#Reversing-easy-T-the-weakest-18-team-solved-215-points)
2. Ricerca CTF 2023 "RSLocker": [Ricerca CTF 2023 write-up (reversingジャンル全問)](https://tan.hatenadiary.jp/entry/2023/04/23/030022#reversing-RSLocker-4-solves-393-points)
3. LINE CTF 2024 "BrownFlagChecker": [LINE CTF 2024 write-up & Binary Ninja FreeとIDA Freeの比較](https://tan.hatenadiary.jp/entry/2024/03/25/221137#rev-BrownFlagChecker-17-teams-solved-221-points)

## スライド生成方法
1. VSCodeをインストールします。
2. VSCodeに[Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)をインストールします。
3. VSCodeで[slide.md](slide.md)を開きます。
4. VSCodeのコマンド一覧から `Marp: Export Slide Deck...` を選択して、[slide.html](slide.html)として保存します。なお、ここで直接PDFとして保存しなかった理由は、使われるフォントがどうにも思ったものではなかったためです。
5. Google Chromeで[slide.html](slide.html)を開き、印刷画面から[slide.pdf](slide.pdf)として保存します。
