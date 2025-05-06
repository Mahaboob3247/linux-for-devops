# 📡 Port Listening

Check which ports your system is listening to.

### Example:
```bash
ss -tuln | grep :80
```

### Use Case:
Ensure web servers like Nginx or Apache are listening on the expected ports.