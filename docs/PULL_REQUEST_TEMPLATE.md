## Scope of PR
- *Here comes what the reviewee would like the reviewer to focus on.*
- ...

## Major changes in codes/documents
- *Here comes list of major changes.*
- ...

## How to run the code
*The reviewer might need some specific data that I should prepare for her/him, etc. 
Add instruction here. ("See `README`" can be OK in some cases)*


## What to be reviewed
- [ ] Is the code reproducible?
  - [ ] Can you reproduce the result with the instructions in `README.md`?
    - [ ] Does it have a link to the necessary files (training data/trained model)?
    - [ ] Is a virtual environment (such as`poetry`/`docker`) set up?
    - [ ] Is the version of all the dependencies specified? (`requirements.txt` often has this issue)
- [ ] Does the code have docstring/type annotation?
  - [ ] Are there docstring in all the methods/class?
  - [ ] Are the docstring written in appropriate format (which can be used by `mkdocs/sphinx`)?
  - [ ] Are all the methods type annotated?
- [ ] Is the code comprehensive?
  - [ ] Is the code comprehensive/clear?
  - [ ] Is the logic correct/as intended?
- [ ] Are the names for variable/method/class appropriate?
  - [ ] Is variable/method/class name meaningful? (as it is a short comment)
  - [ ] Are the names following [pep8](https://realpython.com/python-pep8/#naming-conventions)?
- [ ] Is coverage rate high enough? (if there is unittest)

## Requested deadline for review
Can you please review this PR by `YYYY/MM/DD` ?

---
## PRのscope
- *ここにreviewerに注目して欲しい、PRの主眼が入る*
- ...

## code/documentsの主な変更点
- *ここに主な変更点のリストが入る*
- ...

## コードの動かし方
*動かすためのデータなどが必要な場合は、取得方法などを明示してください。("`README`を見ろ"というのでもOKな場合はあると思います)*

## レビューすべき点
- [ ] 結果は再現可能か?
  - [ ] `README.md`のインストラクションに従って結果を再現できるか?
    - [ ] 必要なファイル（学習用データ/学習済モデルなど）へのリンクはあるか?
    - [ ] 仮想環境 (`poetry`/`docker`など)の構築ができるようになっているか?
    - [ ] 全てのdependencyのversionは固定されているか？(`requirements.txt`ではよくこういう問題が起こる)
- [ ] docstring/type annotationはされているか?
  - [ ] 全てのmethod/classにdocstringはあるか？
  - [ ] docstringは適切なformatで書かれているか？(`mkdocs/sphinx`で使用可能なもの)
  - [ ] 全てのmethodにtype annotationはあるか?
- [ ] コードは理解可能か?
  - [ ] コードは理解可能/明快か?
  - [ ] 実装された論理は正しい/意図された通りか?
- [ ] 変数/method/classの名前は適切か?
  - [ ] 変数/method/classの名前は意味があるものになっているか？(これらの名前は短いコメント文としての役割を持つので）
  - [ ] 名前は[pep8](https://realpython.com/python-pep8/#naming-conventions)に従っているか?
- [ ] coverage rateは十分高いか? (unittestがある場合)

## 希望するreviewの締切
このPRを`YYYY/MM/DD`までにreviewしてもらえますか?
