# sstpoffload
PowerShell script to enable TLS offload for SSTP VPN connections on Windows Server Routing and Remote Access (RRAS) servers.

If the public SSL certificate used by VPN clients is installed on the VPN server before enabling TLS offloading, this script is not required. However, if the public SSL certificate cannot be installed on the VPN server, the Enable-SstpOffload.ps1 script will be required to ensure proper operation of SSTP.
