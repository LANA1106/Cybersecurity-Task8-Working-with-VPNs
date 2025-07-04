# VPN Setup Guide

## Step 1: Choose a Reputable Free VPN Service

For this task, we'll use **ProtonVPN** (free tier) as it's highly recommended for security and privacy.

### Why ProtonVPN?
- Swiss-based company with strong privacy laws
- No-logs policy
- Strong encryption (AES-256)
- Free tier includes 3 server locations
- Unlimited bandwidth on free plan
- Open-source applications

### Alternative: Windscribe
- 10GB monthly data limit on free plan
- Multiple server locations
- Strong encryption
- No-logs policy

## Step 2: Sign Up Process

### ProtonVPN Registration:
1. Visit https://protonvpn.com/
2. Click "Get ProtonVPN Free"
3. Create account with email and secure password
4. Verify email address
5. Complete account setup

### Account Security Tips:
- Use a strong, unique password
- Enable two-factor authentication if available
- Use a secure email address

## Step 3: Download and Install VPN Client

### For Windows:
1. Log into ProtonVPN account
2. Go to "Downloads" section
3. Download Windows application
4. Run installer as administrator
5. Follow installation wizard
6. Launch application and log in

### System Requirements:
- Windows 10/11 (64-bit)
- At least 100MB free space
- Administrator privileges for installation

## Step 4: VPN Client Configuration

### Initial Setup:
1. Open ProtonVPN application
2. Log in with your credentials
3. Review connection settings:
   - Protocol: OpenVPN (recommended)
   - Kill Switch: Enable for security
   - Auto-connect: Configure as needed

### Security Settings:
- **Kill Switch**: Blocks internet if VPN disconnects
- **Secure Core**: Routes traffic through multiple servers
- **NetShield**: Blocks ads and malware
- **Always-on VPN**: Maintains connection automatically

## Step 5: Connect to VPN Server

### Server Selection:
1. Choose server location (free tier options):
   - Netherlands
   - Japan  
   - United States
2. Consider factors:
   - Geographic proximity for speed
   - Server load (lower is better)
   - Specific geo-restrictions if needed

### Connection Process:
1. Click on desired server location
2. Wait for connection establishment
3. Verify connection status (green indicator)
4. Note the virtual IP address assigned

## Step 6: Verify VPN Connection

### IP Address Verification:
1. Before connecting: Visit whatismyipaddress.com
2. Note your real IP address and location (e.g., 203.122.45.178 - Mumbai, India)
3. Connect to VPN
4. Refresh whatismyipaddress.com
5. Verify IP address has changed to VPN server location (e.g., 185.159.158.234 - Amsterdam, Netherlands)

### Additional Verification Methods:
- Use ipleak.net for comprehensive leak testing
- Check DNS leak protection
- Verify WebRTC leak protection
- Test IPv6 leak protection

## Step 7: Test Browsing and Encryption

### Browsing Test:
1. Visit various websites while connected
2. Check if any sites are blocked/restricted
3. Note any speed differences
4. Test video streaming performance

### Encryption Verification:
1. Use tools like Wireshark to monitor traffic
2. Verify that traffic is encrypted
3. Check for DNS leaks
4. Test kill switch functionality

## Step 8: Performance Comparison

### Speed Testing:
1. **Without VPN**: Run speed test (speedtest.net)
   - Example: 89.45 Mbps down, 42.18 Mbps up, 24ms ping
2. **With VPN**: Connect and run same test
   - Example: 76.12 Mbps down, 34.58 Mbps up, 69ms ping
3. Compare results:
   - Download speed reduction (~15%)
   - Upload speed reduction (~18%)
   - Ping/latency increase (+45ms)
   - Overall performance impact

### Expected Performance Impact:
- Speed reduction: 10-50% (depends on server distance)
- Latency increase: 20-100ms additional
- Slight increase in CPU usage

## Step 9: Disconnect and Compare

### Disconnection Process:
1. Click disconnect in VPN application
2. Wait for disconnection confirmation
3. Verify return to original IP address
4. Compare browsing speed and experience

## Troubleshooting Common Issues

### Connection Problems:
- Check internet connectivity
- Try different server locations
- Restart VPN application
- Disable firewall temporarily
- Check for software updates

### Performance Issues:
- Switch to different server
- Change VPN protocol (OpenVPN vs IKEv2)
- Adjust MTU settings
- Close unnecessary applications

### Security Concerns:
- Verify kill switch is working
- Check for DNS leaks regularly
- Monitor for IP leaks
- Keep VPN software updated

## Security Best Practices

1. **Always use Kill Switch**: Prevents data leaks
2. **Regular Leak Testing**: Check for DNS/IP leaks
3. **Keep Software Updated**: Install security patches
4. **Use Strong Authentication**: Enable 2FA when available
5. **Monitor Connection Status**: Verify VPN is active
6. **Understand Limitations**: VPN doesn't make you anonymous

## Next Steps

After completing the setup:
1. Take screenshots of connection status
2. Document IP address changes
3. Record performance metrics
4. Research VPN protocols and encryption
5. Prepare comprehensive report

---
*This guide provides a foundation for secure VPN usage and privacy protection.*
