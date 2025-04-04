<p align="center">
  <img src="https://img.shields.io/badge/d9c-PyPI-red" alt="Version Badge">
  <img src="https://img.shields.io/badge/our.-8A4B295" alt="Description Badge">
  <br>
  <a href="https://github.com/kkkik">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?logo=github" alt="GitHub Profile">
  </a>
  <a href="https://t.me/pyd9c">
    <img src="https://img.shields.io/badge/Report%20Issues-Telegram-blue?logo=telegram" alt="Report Issues">
  </a>
</p>
<div align="center" style="background-color: #f2f2f2; padding: 30px; border-radius: 12px;">
  <a href="https://badge.fury.io/py/our">
    <img src="https://badge.fury.io/py/our.svg" alt="PyPI version" />
  </a>

</div>
# **Our** - Simple Paste Management

**Our** is a minimalistic Python library for uploading and retrieving pastes with ease. Perfect for storing and sharing your code, notes, or any content.

## **Features**

- ✨ **Easy Upload**: Upload content and get a unique paste ID.
- ⚡ **Fast Retrieval**: Access your pastes quickly using the paste ID.
- 📝 **Customizable**: Add descriptions, extensions, and owner details.
- 🔒 **Error Handling**: Handles errors gracefully.

## **Installation**

Install via pip:

```bash
pip install our
```
__Usage__

Upload a Paste:
```python
from our import upload

paste_id = upload("This is a test paste", description="Test description", owner="user123")
print(f"Your paste ID: {paste_id}")

Retrieve a Paste:

from our import get

content = get(paste_id)
print(f"Content: {content}")
```
##API

POST `/api/pastes`: Upload content and get a paste ID.

GET `/api/pastes?id={paste_id}`: Retrieve content by paste ID.


License

MIT License.


---

Built with simplicity and ease.

### Key Points:
- **Concise and Easy**: Straight to the point with a clean structure.
- **Simple Examples**: Provides just the necessary code for quick integration.
- **Professional Yet Minimal**: The language is direct and professional while remaining simple and elegant.
