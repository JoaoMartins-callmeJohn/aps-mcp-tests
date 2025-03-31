# aps-mcp-tests
Repo to test mcp server with claude

## Prerequisites

Python 3 installed
Claude Desktop downloaded

You can start following the tutorial from the video: https://www.youtube.com/watch?app=desktop&v=wa_A0qY0anA

## Steps

1. First open the terminal in the root folder and spin a new environment with the code below:
```py
python -m venv .venv
```
2. Then you activate the environment:
```py
On Windows
.venv/Scripts/activate

On a MAC
.venv/bin/activate
```

3. Install mcp
```py
pip install mcp
```

4. Now you can run the server
```py
python server.py
```