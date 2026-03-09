# 技術英語学習プラン（記憶力補助付き）

## 学習方針
- 目標：技術文を翻訳なしで 130語/分で読解できるようになる
- 精神状態や記憶力低下を考慮し、短時間・小単位・外部記憶に依存する学習
- ツール：Anki、Neovim（Markdownプレビュー可）、Googleスプレッドシート、Krita

---

## 毎日の学習ステップ（20〜40分目安）

1. **技術文読解**
   - Rust公式ドキュメント、GitHub Issue / PR、CS論文の段落を読む
   - 10分程度、Markdown にコピーして管理

2. **SVOC振り**
   - 文ごとに SVOC を Markdown に記録
   - 関係節・修飾関係は Krita で図解 → PNG化して保存
   - 10分程度

3. **単語整理**
   - 不明単語・フレーズを Googleスプレッドシートに登録
   - 意味・用法・例文もメモ
   - 5分程度

4. **音読 / シャドーイング**
   - 文のリズム・意味を確認しながら声に出して読む
   - 慣れたら黙読でスピード重視
   - 5〜10分

> 学習量は調子に合わせて柔軟に。1日1〜2段落でもOK。

---

## リポジトリ構成例

english_learning_repo/
├─ README.md                     # 学習方針・進捗管理
├─ docs/
│   └─ images/                   # 複雑な関係節・修飾関係の図スクショ
│       ├─ sentence_001.png
│       ├─ sentence_002.png
│       └─ ...
├─ practice/
│   └─ reading_materials/
│       ├─ rust_docs/            # Rust公式ドキュメントの原文コピー
│       ├─ github_issues/        # GitHub Issue / PR例文
│       └─ cs_papers/            # CS論文抜粋
└─ svoc/
    ├─ sentence_001.md           # 文ごとの SVOC Markdown
    ├─ sentence_002.md
    └─ ...

---

- **Markdown + Krita図解で外部記憶を最大化**
- **Googleスプレッドシートで単語・フレーズ・文章を管理**
- **Ankiと連携して反復復習可能**
