git init
git add .
git commit -m "from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "مرحبًا بك في مشروعنا!"

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000)"
git branch -M main
git remote add origin https://github.com/اسم_المستخدم/اسم_المستودع.git
git push -u origin main

