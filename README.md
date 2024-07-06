## 概要

Next.js と Supabase を使用した掲示板アプリケーション

## 技術スタック

- **Next.js**: 14.2.4
- **React**: 18
- **TypeScript**: 5
- **Tailwind CSS**: 3.4.1
- **Prisma**: 5.16.1
- **Supabase**: データベースとして使用

## 主な使用ライブラリ

- **@hookform/resolvers**: 3.8.0
- **@prisma/client**: 5.16.1
- **@radix-ui/react-label**: 2.1.0
- **@radix-ui/react-slot**: 1.1.0
- **class-variance-authority**: 0.7.0
- **clsx**: 2.1.1
- **lucide-react**: 0.400.0
- **react-hook-form**: 7.52.1
- **tailwind-merge**: 2.3.0
- **tailwindcss-animate**: 1.0.7
- **zod**: 3.23.8

## 実装機能

- **投稿作成**: ユーザーはフォームを使用して新しい投稿を作成できます。
- **投稿一覧表示**: すべての投稿を一覧で表示します。
- **投稿詳細表示**: 各投稿の詳細を表示します。

## コメント

このプロジェクトは、Next.js14 と Supabase を活用して、掲示板アプリケーションを構築しています。  
今回データの取得方法は、Prisma を使用して ORM で SQL 操作を簡潔化しています。  
投稿フォームには、React Hook Form と Zod を使用してフォームのバリデーションを行っています。

## 著者

[SakuTech blog](https://github.com/n-sakuma39/)
# next-bbs-supabase-app
