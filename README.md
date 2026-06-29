# TDS GA2 combined FastAPI app

This one app implements Q1, Q2, Q3, Q5, Q6, Q8, Q9, and Q10.

Run locally:

```bash
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000
```

For deployment on most platforms, use this start command:

```bash
uvicorn main:app --host 0.0.0.0 --port $PORT
```

Submit URLs:

- Q1: `https://YOUR-HOST/stats` base URL should be `https://YOUR-HOST`
- Q2: `https://YOUR-HOST/verify`
- Q3: `https://YOUR-HOST/effective-config`
- Q5: `https://YOUR-HOST/analytics`
- Q6: base URL `https://YOUR-HOST`
- Q8: `https://YOUR-HOST/extract`
- Q9: base URL `https://YOUR-HOST`
- Q10: base URL `https://YOUR-HOST`
