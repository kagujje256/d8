# D8 Online PC

GitHub Actions-powered online PC. Access via SSH through Ngrok or Tailscale.

## How to use
1. Trigger the workflow: `gh workflow run "D8 Online PC"`
2. Check the run logs for connection info
3. SSH: `ssh root@{ngrok-hostname} -p {port}` password: `D8RunnerPass!`
