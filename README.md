# mini-blog

Flaskr & Test-Driven Deplyment (TDD)

A mini blog website, built using Flask and hosted on Render.

Created from: https://github.com/shuruizUofT/flaskr-tdd

<img width="1050" height="789" alt="image" src="https://github.com/user-attachments/assets/128b5c3b-1a12-4a01-8d0d-ac1ac37805ce" />

Instructions to deploy:

1. Create a Render Web Service
2. Go to Render Dashboard
3. Click New → Web Service.
4. Connect your repo.
5. Set Environment to Python 3.
6. Set the Start Command to: gunicorn app:app

7. Configure Settings
8. Region: pick closest.
9. Instance type: Free tier is enough to test.
10. Environment Variables: Add any secrets (API keys, etc.).

11. Deploy
12. Render will install dependencies from requirements.txt.
13. It will then run the start command.
14. After a few minutes, you’ll get a live URL
