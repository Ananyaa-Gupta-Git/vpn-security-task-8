# Task 8: VPN Setup and Analysis

## Objective
Understand the role of VPNs in protecting privacy and secure communication through hands-on experience.

## Tools Used
- **VPN Service**: ProtonVPN Free Tier
- **IP Checking**: whatismyipaddress.com
- **Speed Testing**: speedtest.net

## Task Completion Steps

### 1. Initial Setup
- Signed up for free VPN account
- Downloaded and installed VPN client
- Verified installation

### 2. Pre-VPN Testing
- Checked original IP address: `122.161.74.146`
- Original location: `Noida, Uttar Pradesh, India`
- Original internet speed: `37.82 Mbps download, 38.79 Mbps upload, 9ms ping`

### 3. VPN Connection
- Connected to VPN server in: `United States (Miami, Florida)`
- New IP address: `138.199.50.137`
- New apparent location: `Miami, Florida, USA`
- VPN-connected speed: `14.91-26.87 Mbps download, 10.56-36.45 Mbps upload, variable ping`

### 4. Verification and Testing
- Confirmed IP address change
- Tested website browsing functionality
- Verified encrypted traffic flow

## Screenshots
- `before_vpn.png` - Original IP address and location
- `vpn_connected.png` - VPN client showing active connection
- `after_vpn.png` - New IP address after VPN connection
- `speed_comparison.png` - Speed test results comparison

## Key Findings

### VPN Benefits
1. **Privacy Protection**: Masks real IP address and location
2. **Traffic Encryption**: Secures data transmission
3. **Bypass Restrictions**: Can access geo-blocked content
4. **Public WiFi Security**: Protects on unsecured networks

### VPN Limitations
1. **Speed Reduction**: 21-61% speed reduction observed
2. **Server Reliability**: Variable performance depending on server load
3. **Trust Factor**: Must trust VPN provider with data
4. **Free Service Limits**: Bandwidth/server restrictions, fewer server options

## Technical Analysis

### Encryption Methods
- **Protocol Used**: WireGuard (TCP)
- **Encryption Standard**: AES-256 (ChaCha20 for WireGuard)
- **Authentication**: Poly1305 authenticator

### Network Impact
- **Latency Increase**: Variable (9ms to 561ms depending on server)
- **Bandwidth Reduction**: 21-61% reduction observed
- **Connection Stability**: Generally stable with occasional fluctuations

## Interview Questions Preparation

### 1. What is a VPN?
A Virtual Private Network (VPN) creates a secure, encrypted connection between your device and a remote server, masking your IP address and encrypting your internet traffic.

### 2. How does a VPN protect privacy?
- Encrypts all data transmission
- Masks real IP address
- Routes traffic through secure servers
- Prevents ISP monitoring

### 3. Difference between VPN and proxy?
- **VPN**: Encrypts all traffic, works at OS level, more secure
- **Proxy**: Only routes specific traffic, no encryption, application-level

### 4. What is encryption in VPN?
VPN encryption converts readable data into coded format using algorithms like AES-256, making it unreadable to interceptors.

### 5. Can VPN guarantee complete anonymity?
No, VPNs provide privacy but not complete anonymity. Factors like DNS leaks, browser fingerprinting, and VPN logs can compromise anonymity.

### 6. What protocols do VPNs use?
- **OpenVPN**: Open-source, highly secure
- **WireGuard**: Modern, fast, lightweight
- **IKEv2**: Good for mobile devices
- **L2TP/IPSec**: Older but compatible

### 7. What are some VPN limitations?
- Speed reduction due to encryption overhead
- Dependence on VPN provider trustworthiness
- Potential IP/DNS leaks
- Some websites block VPN traffic

### 8. How does a VPN affect network speed?
VPNs typically reduce speed by 10-50% due to:
- Encryption/decryption overhead
- Distance to VPN server
- Server load and capacity
- Quality of VPN infrastructure

## Conclusion
This hands-on experience demonstrated both the benefits and limitations of VPN technology. While VPNs provide significant privacy and security improvements, users must understand their limitations and choose reputable providers.

## Files in Repository
- `README.md` - This documentation
- `screenshots/` - All captured screenshots
- `vpn_analysis_report.md` - Detailed technical analysis
- `speed_test_results.txt` - Speed comparison data
