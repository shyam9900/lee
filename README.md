# FREE-RDP
FREE LIFETIME WINDOWS10 RDP 7GB RAM >> 2CORES >> 900-1200 MBPS INTERNET SPEED

# USAGE
1. Assume Windows Runners cannot listen to ports. I didn't bother trying and ngrok worked anyway. So, signup for an ngrok account.
2. Get the tunnel auth token at: https://dashboard.ngrok.com/auth .
3. Under the repository's settings, make a secret called NGROK_AUTH_TOKEN and set it to the tunnel auth token from ngrok.
4. Trigger a build somehow. Maybe make a spurious commit or edit and commit the README or something.
5. Wait until the last step which will hang forever as it connects to ngrok and sets up the reverse tunnel.
6. Visit ngrok's dashboard. https://dashboard.ngrok.com/
7. Note the active tunnel's public host and port.
8. Connect to the host and port combination with your RDP client of choice.
9. Use the username KENLIEPLAYS and the password ken@lor23.
10. Enjoy! ☕
11. When you're done introspecting, cancel the job.
