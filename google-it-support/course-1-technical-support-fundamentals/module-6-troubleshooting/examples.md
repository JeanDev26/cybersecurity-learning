# 🧪 Examples — Module 6 Troubleshooting


## Example 1: 404 Not Found
When trying to visit `https://example.com/oldpage`, you receive:
```
404 Not Found
The requested URL was not found on this server.
```
➡️ This means the page has been moved or deleted.

---

## Example 2: Permission Denied
On Linux, if you try to access a protected file without privileges:
```bash
cat /etc/shadow
```
Output:
```
cat: /etc/shadow: Permission denied
```
➡️ Solution: use `sudo` if you have administrator rights.

---

## Example 3: Root Cause Analysis
A user reports slow Internet. Investigation shows:  
- Router overloaded  
- Too many background downloads  
➡️ **Root cause** = Router overload.

---

## Example 4: General Troubleshooting
1. Identify the issue → Computer won’t boot.  
2. Isolate → Test power supply, cables, and battery.  
3. Root cause → Faulty power supply.  
4. Resolution → Replace the power supply.
