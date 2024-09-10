
# Networking Best Practices

## What?

1. **Never Connect to Any App/Website with Your Real IP Address.**  
   Always use Tor, or, if that is not possible, a reputable VPN to hide your IP address. If you are in an authoritarian country such as Iran and using solutions like Starlink, remember that you still need to use Tor or a VPN.

2. **Using Tor is the Best Option.**  
   If a website you are trying to access has blocked access from Tor, consider using Tor gateways. Use a VPN only if you cannot use Tor.

3. **Never Use Free VPNs or Free Proxy Servers.**  
   Ensure that your VPN is reputable and has a no-logs policy. Among reputable VPNs, Mullvad and ProtonVPN are considered some of the most secure options.

4. **Do Not Use VPN Before Tor.**  
   If you are using both Tor and a VPN, if possible, try to connect to Tor first and then use the VPN.

## Why?

1. **Data Privacy Concerns.**  
   In many jurisdictions, businesses are required to cooperate with authorities and provide any user information upon request. This data includes your IP address and any other personal information you have provided to that website, which can directly lead to your arrest or worse. Even if a business refuses to cooperate with your government, data breaches remain a significant risk. A security failure on any website you use could expose your real IP address to authorities.

2. **Tor's Decentralization and Security.**  
   Tor is decentralized and offers a high level of security. While it is not perfect and may have vulnerabilities, no one has been caught due to a security failure within Tor itself. Users who have been apprehended typically made mistakes in protecting their identities. Tor effectively hides your IP address, but the responsibility for maintaining your anonymity ultimately lies with you. Despite its imperfections, Tor remains one of the best options available for privacy.

3. **Risks of Free VPNs.**  
   Many free VPNs monetize their services by selling user data. If you live in an authoritarian country, these services might even be managed by the government. For paid VPNs, while most claim to have a "no-logs policy," this cannot be independently verified by regular users. Therefore, it is impossible to know for certain whether they are storing your data.

4. **Tor before VPN**
   When you connect to a VPN first, your internet traffic is routed through the VPN server before reaching the Tor network. This means that the VPN provider can see your original IP address and the websites you visit, which undermines the anonymity that Tor provides. Additionally, if the VPN is compromised or logs user data, it could expose your identity. For maximum privacy, it is generally recommended to connect directly to the Tor network first, as it is designed to anonymize your traffic.

## Additional Suggestions:

- **Consider Using Bridges with Tor.**  
  If you are in a country where Tor is blocked, consider using Tor bridges to access the network. Bridges are private Tor relays that help users connect to the Tor network without being detected.

- **Stay Informed About VPN and Tor Updates.**  
  Regularly check for updates and security advisories related to the VPN and Tor software you use. Keeping your software up to date is crucial for maintaining security.
