# ai-labo-analytics - Legal Pages

TikTok Developer App「ai-labo-analytics」の利用規約・プライバシーポリシーページです。

## セットアップ手順

### 1. GitHubにリポジトリを作成

```bash
# 新しいリポジトリを作成（GitHub上で `ai-labo-legal` 等の名前で作成）
git init
git add .
git commit -m "Add terms and privacy policy"
git branch -M main
git remote add origin https://github.com/<あなたのユーザー名>/ai-labo-legal.git
git push -u origin main
```

### 2. GitHub Pagesを有効化

1. GitHubリポジトリの **Settings** タブを開く
2. 左メニューの **Pages** をクリック
3. **Source** で `Deploy from a branch` を選択
4. **Branch** で `main` / `/ (root)` を選択して **Save**

### 3. URLを確認

数分後に以下のURLでアクセスできるようになります：

- 利用規約: `https://<ユーザー名>.github.io/ai-labo-legal/terms.html`
- プライバシーポリシー: `https://<ユーザー名>.github.io/ai-labo-legal/privacy.html`

### 4. TikTok Developer Portalに入力

上記のURLをそれぞれ以下のフィールドに入力：

- **Terms of Service URL** → `https://<ユーザー名>.github.io/ai-labo-legal/terms.html`
- **Privacy Policy URL** → `https://<ユーザー名>.github.io/ai-labo-legal/privacy.html`
