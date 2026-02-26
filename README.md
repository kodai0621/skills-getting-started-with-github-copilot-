# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey kodai0621!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/kodai0621/skills-getting-started-with-github-copilot-/issues/2)

---

## Mergington High School Management System
## マージントン高校管理システム

### 📖 About / 概要

**English:**  
This is a web application for Mergington High School that allows students to view and sign up for extracurricular activities. The application is built with FastAPI (Python backend) and vanilla JavaScript (frontend).

**日本語:**  
このアプリケーションは、マージントン高校の生徒が課外活動を閲覧し、申し込むことができるWebアプリケーションです。FastAPI（Pythonバックエンド）とバニラJavaScript（フロントエンド）で構築されています。

### 🚀 Getting Started / 使い方

#### Prerequisites / 必要条件

**English:**
- Python 3.7 or higher
- pip (Python package manager)

**日本語:**
- Python 3.7以上
- pip（Pythonパッケージマネージャー）

#### Installation / インストール

**English:**

1. Clone this repository:
```bash
git clone https://github.com/kodai0621/skills-getting-started-with-github-copilot-.git
cd skills-getting-started-with-github-copilot-
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

**日本語:**

1. このリポジトリをクローンします：
```bash
git clone https://github.com/kodai0621/skills-getting-started-with-github-copilot-.git
cd skills-getting-started-with-github-copilot-
```

2. 必要な依存関係をインストールします：
```bash
pip install -r requirements.txt
```

#### Running the Application / アプリケーションの実行

**English:**

1. Navigate to the src directory:
```bash
cd src
```

2. Start the FastAPI server:
```bash
uvicorn app:app --reload
```

3. Open your web browser and navigate to:
```
http://localhost:8000
```

The application should now be running! 🎉

**日本語:**

1. srcディレクトリに移動します：
```bash
cd src
```

2. FastAPIサーバーを起動します：
```bash
uvicorn app:app --reload
```

3. Webブラウザを開き、以下のURLにアクセスします：
```
http://localhost:8000
```

アプリケーションが起動しました！🎉

### 💻 How to Use the Application / アプリケーションの使い方

**English:**

1. **View Activities**: When you open the application, you'll see a list of available extracurricular activities including:
   - Chess Club
   - Programming Class
   - Gym Class

2. **Sign Up for an Activity**:
   - Enter your student email address (e.g., yourname@mergington.edu)
   - Select an activity from the dropdown menu
   - Click the "Sign Up" button
   - You'll see a confirmation message

**日本語:**

1. **活動の閲覧**: アプリケーションを開くと、以下の課外活動のリストが表示されます：
   - チェスクラブ
   - プログラミングクラス
   - 体育クラス

2. **活動への申し込み**:
   - 生徒のメールアドレスを入力します（例：yourname@mergington.edu）
   - ドロップダウンメニューから活動を選択します
   - 「Sign Up」ボタンをクリックします
   - 確認メッセージが表示されます

### 🔧 API Documentation / APIドキュメント

**English:**

The application provides the following API endpoints:

- `GET /` - Redirects to the main page
- `GET /activities` - Returns list of all activities
- `POST /activities/{activity_name}/signup?email={email}` - Sign up for an activity

You can also view the interactive API documentation at:
```
http://localhost:8000/docs
```

**日本語:**

アプリケーションは以下のAPIエンドポイントを提供します：

- `GET /` - メインページにリダイレクト
- `GET /activities` - すべての活動のリストを返します
- `POST /activities/{activity_name}/signup?email={email}` - 活動に申し込みます

対話的なAPIドキュメントは以下で確認できます：
```
http://localhost:8000/docs
```

### 🧪 Running Tests / テストの実行

**English:**
```bash
pytest
```

**日本語:**
```bash
pytest
```

### 📁 Project Structure / プロジェクト構造

```
.
├── src/
│   ├── app.py              # FastAPI backend application
│   └── static/
│       ├── index.html      # Main HTML page
│       ├── app.js          # JavaScript frontend logic
│       └── styles.css      # CSS styling
├── requirements.txt        # Python dependencies
├── pytest.ini             # Pytest configuration
└── README.md              # This file
```

### 🛠️ Development / 開発

**English:**

To run the application in development mode with auto-reload:
```bash
cd src
uvicorn app:app --reload --host 0.0.0.0 --port 8000
```

**日本語:**

自動リロード機能付きの開発モードでアプリケーションを実行するには：
```bash
cd src
uvicorn app:app --reload --host 0.0.0.0 --port 8000
```

### ❓ Troubleshooting / トラブルシューティング

**English:**

**Problem**: Port 8000 is already in use  
**Solution**: Either stop the process using port 8000, or run the app on a different port:
```bash
uvicorn app:app --reload --port 8001
```

**Problem**: Module not found error  
**Solution**: Make sure you've installed the requirements:
```bash
pip install -r requirements.txt
```

**日本語:**

**問題**: ポート8000が既に使用されています  
**解決策**: ポート8000を使用しているプロセスを停止するか、別のポートでアプリを実行します：
```bash
uvicorn app:app --reload --port 8001
```

**問題**: モジュールが見つからないエラー  
**解決策**: requirements.txtをインストールしたか確認してください：
```bash
pip install -r requirements.txt
```

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

