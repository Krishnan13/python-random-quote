# Let's Write a Python Quote Bot!

This repository will get you started with building a quote bot in Python. It's meant to be used along with the [Learning Lab](https://lab.github.com) intro to Python.

When complete, you'll be able to grab random quotes from the command line, like this:

> **$** python get-quote.py
> 
> Keep it logically awesome
> 
> **$** python get-quote.py
> 
> Speak like a human

## Kannada Blog Interface

This repository now includes a simple blog interface for uploading blogs in Kannada.

### How to run

1. Install Flask:
   ```bash
   pip install flask
   ```

2. Initialize the database:
   ```bash
   python init_db.py
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Access the blog at `http://127.0.0.1:5000`.

### Features
- UI localized in Kannada.
- Upload blog posts with Kannada titles and content.
- SQLite database for storage.
