# 🖥️ Reset a Forgotten Windows Password

If a user forgets their Windows password, follow these steps:

---

### 🔄 Option 1: Safe Mode with Command Prompt

1. Restart the PC and press `F8` before Windows loads.
2. Select **Safe Mode with Command Prompt**.
3. Enter the following command:
   net user USERNAME NEWPASSWORD
   Example: net user JohnDoe NewPassword123

---

### 🔄 Option 2: Using Windows Recovery

1. Hold **Shift** and click **Restart**.
2. Go to **Troubleshoot > Advanced Options > Command Prompt**.
3. Type:
   net user
   Then:
   net user USERNAME NEWPASSWORD

---

✅ You’ve successfully reset the password!
