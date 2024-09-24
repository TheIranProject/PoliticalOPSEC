
# Networking Best Practices

## What?

1. **Never Connect to Any App/Website with Your Real IP Address.**  
   Always use Tor, or, if that is not possible, a reputable VPN to hide your IP address. If you are in an authoritarian country such as Iran and using solutions like Starlink, remember that you still need to use Tor or a VPN.

2. **Using Tor is the Best Option.**  
   If a website you are trying to access has blocked access from Tor, consider using Tor gateways. Use a VPN only if you cannot use Tor.

3. **Never Use Free VPNs or Free Proxy Servers.**  
   Ensure that your VPN is reputable and has a no-logs policy. Among reputable VPNs, Mullvad and ProtonVPN are considered some of the most secure options.

4. **Using VPN/Proxy/SSH with Tor:**  
   Most of the time, Tor is sufficient for achieving anonymity. However, setting up a VPN/Proxy/SSH in conjunction with Tor can add complexity to your setup and may even compromise your anonymity. Nevertheless, there are certain scenarios where using a VPN/Proxy/SSH might be advisable:
   1. **Tor is blocked in your country:** In this case, using Tor bridges may be a better option. Consider using a bridge first, and only resort to a VPN/Proxy/SSH before Tor as a last measure.
   2. **Your traffic is being monitored:** In some countries or specific situations, using Tor may raise suspicion from the government or those monitoring your traffic. In these cases, employing a VPN/Proxy/SSH before Tor can be beneficial.
   3. **The website you want to visit has blocked Tor:** If a website has blocked Tor, using a VPN/Proxy/SSH after Tor may help you access it.

   In all cases, if the VPN/Proxy/SSH is compromised or is logging your activities, your real identity will be exposed. Therefore, if you must use a VPN, ensure that you choose a reputable and secure VPN provider that has a strict no-logs policy and a proven track record of protecting user privacy.

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
