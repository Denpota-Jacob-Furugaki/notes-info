# notes-info
improtant info
   py -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload
clean up test files in powershell
Kill All Python Processes

Terminate all running python.exe processes (record PIDs).

Check for py.exe processes and close if any.

Clear All Caches

Delete __pycache__ directories.

Delete .pytest_cache directories.

Verify Environment

Confirm port 8000 is free (netstat check).

Confirm correct Python version (py --version → 3.13.7).

Confirm correct OpenAI API version (1.107.1).

Start Server

Run: py -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload.

Confirm server starts cleanly (note new PID).

Regex Fix

Add fallback regex pattern for company name extraction.

Test extraction manually.

Current Status (✅ Done)

Server running on port 8000 (PID confirmed).

All cache cleared.

Using correct Python + OpenA
