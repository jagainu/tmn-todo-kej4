# tmn-todo-kej4

> **Status**: 🎨 DESIGNING

## 概要

ユーザーがタスクを作成、編集、削除、完了状態を切り替えることができるシンプルなTODOアプリ

## 機能

- [ ] タスク追加
- [ ] タスク編集
- [ ] タスク削除
- [ ] タスク完了状態切り替え
- [ ] タスクリスト表示

## 画面

| パス | 画面名 | 説明 |
|------|--------|------|
| `/` | TODOリストページ | すべてのTODOタスクを表示し、新規タスクの追加や既存タスクの管理を行うメインページ |

## データ

### Todo

| フィールド | 型 | 説明 |
|-----------|-----|------|
| id | string | 一意のタスク識別子 |
| title | string | タスクのタイトル |
| completed | boolean | タスクの完了状態 |
| createdAt | string | タスク作成日時 |

## 認証

なし

---

## Tech Stack

- Framework: Next.js 14 (App Router)
- Styling: Tailwind CSS + shadcn/ui
- Database: localStorage (ブラウザストレージ)
- Hosting: Vercel
