# AR OptionSim

AR OptionSim is an app that lets you simulate and visualize option prices and Greeks in augmented reality. The program implements the Black-Scholes model and supports both one-asset vanilla and two-asset basket European call/put, with and without barrier(s).

The Black-Scholes partial differential equation is solved using the finite element method with implicit Euler time integration. The simulation algorithm also leverages GPU acceleration with Metal Shading Language. Please see details below for information on settings and supported option types.

[**App Download Link**](https://apps.apple.com/app/id1579196058?fbclid=IwAR2J-ffo_5wl3yuQnVLBLe_OnJ7-Capv0C_nuJAM7RGLd1nSkJKTu8rAB04)

[**App Demo Video**](https://www.youtube.com/watch?v=nHFGQzNHW_s)

---

### Settings
- One-Asset Mode
    - **K:** Option Strike Price (A range of underlying asset prices are automatically calculated based on the option’s strike price)
    - **B1:** Lower Knock-out Barrier Price (Optional)
    - **B2:** Upper Knock-out Barrier Price (Optional)
    - **T:** Time to Expiration
    - **σ:** Volatility
    - **δ:** Dividend Yield
    - **r:** Risk-free Interest Rate
    - **Steps:** Number of Simulation Timesteps (Increase the number of timesteps to increase simulation accuracy and stability)

<br />

- Two-Asset Mode
    - **K:** Option Strike Price (A range of underlying assets prices are automatically calculated based on the option’s strike price)
    - **B1:** Lower Knock-out Barrier Price (Optional)
    - **B2:** Upper Knock-out Barrier Price (Optional)
    - **T:** Time to Expiration
    - **σ1:** Volatility of Underlying Asset 1
    - **σ2:** Volatility of Underlying Asset 2
    - **δ1:** Dividend Yield of Underlying Asset 1
    - **δ2:** Dividend Yield of Underlying Asset 2
    - **ρ:** Correlation Coefficient Between Underlying Asset 1 And Underlying Asset 2
    - **r:** Risk-free Interest Rate
    - **Steps:** Number of Simulation Timesteps (Increase the number of timesteps to increase simulation accuracy and stability)

<br />

- Color Mode
    - **Normal:** Heat map based on the option prices on the simulated price surface
    - **Curvature:** Heat map based on the mean curvature of the simulated price surface

<br />

### Interaction
- Drag on the plot with one finger to see prices and Greeks
- Move, rotate, or scale the plot with two fingers

<br />

### Supported Option Types
- Vanilla European Call/Put (One-Asset)
- Down-and-out European Call/Put (One-Asset)
- Up-and-out European Call/Put (One-Asset)
- Double-Barrier European Call/Put (One-Asset)
- Basket European Call/Put (Two-Asset)
- Down-and-out Basket European Call/Put (Two-Asset)
- Up-and-out Basket European Call/Put (Two-Asset)
- Double-Barrier Basket European Call/Put (Two-Asset)

<br />

### Supported Greeks for Interactive Visualization
- One-Asset: Delta and Theta (Δ & Θ)
- Two-Asset: Deltas with respect to the two underlying assets (Δ1 & Δ2)

<br />

**This app features work from patent pending inventions.**

**For more information and ad placements, please contact Jiecong Lu at <aroptionsim@gmail.com>.**

---

### Disclaimer
This app is designed for informational and educational purposes only. It is not intended to be the basis of your trading decisions and should not be considered as a substitute for any financial service or investment advice. The simulation results presented in this app are hypothetical and may not represent the actual properties or performance of your investment. Please note that the information shown in this app may not be 100% accurate, correct, or complete; and we are not responsible for any direct or indirect loss or damage as consequences of any decisions or actions taken based on the information provided in this app.

---

### Privacy Policy

The AR OptionSim app is an Ad Supported app. This SERVICE is provided at no cost to you and is intended for your use as is.

This privacy policy relates to the collection, use, and disclosure of Personally Identifiable Information (PII) when using the AR OptionSim app.

By using the AR OptionSim app, you agree to the collection and use of certain personally identifiable information in relation to this privacy policy.  The personally identifiable information may be used for providing and improving the AR OptionSim app. 

The terms used in this Privacy Policy have the same meanings as in our Terms and Conditions, which is accessible at AR OptionSim unless otherwise defined in this Privacy Policy.

### Information Collection and Use

For a better experience, while using the AR OptionSim app, we may collect certain PII.

We may use the information we collect from you when you register, download the app, or use certain other app features in the following ways: 
- To personalize your experience. 
- To improve our app in order to better serve you. 
- To allow us to better service you in responding to your customer service requests. 
- To administer a contest, promotion, survey or other site feature. 
- To follow up with them after correspondence (live chat, email or phone inquiries).

### Log Data

Whenever you use the AR OptionSim app, we collect data and information (through third party products) on your device called Log Data. This Log Data may include information such as your device Internet Protocol (“IP”) address, device name, operating system version, the configuration of the app when utilizing our Service, the time and date of your use of the Service, and other statistics.  in a case of an error in the app, we use the log data to improve your user experience.

### Cookies

Cookies are files with a small amount of data that are commonly used as anonymous unique identifiers. These are sent to your browser from the websites that you visit and are stored on your device's internal memory.  Cookies enable the app to recognize your device and capture and remember certain information. We use cookies to: 
- Understand and save user's preferences for future visits. 
- Keep track of advertisements. 
- Compile aggregate data about app traffic and interactions in order to offer better app experiences and tools in the future. 
- We may also use trusted third-party services that track this information on our behalf.

You have the option to either accept or refuse these cookies and know when a cookie is being sent to your device. If you choose to refuse cookies, some features may be disabled.

### Service Providers

We may employ third-party companies and individuals due to the following reasons:

- To facilitate our Service;
- To provide the Service on our behalf;
- To perform Service-related services; or
- To assist us in analyzing how our Service is used.

We want to inform users of this Service that these third parties may have access to your Personal Information. The reason is to perform the tasks assigned to them on our behalf. However, they are obligated not to disclose or use the information for any other purpose.

### Third-party disclosure 

We do not sell, trade, or otherwise transfer to outside parties your Personally Identifiable Information unless we provide users with advance notice. This does not include application hosting partners and other parties who assist us in operating our app, conducting our business, or serving our users, so long as those parties agree to keep this information confidential. We may also release information when its release is appropriate to comply with the law, enforce our site policies, or protect ours or others' rights, property or safety. However, non-personally identifiable visitor information may be provided to other parties for marketing, advertising, or other uses.

### Third-party links 

Occasionally, at our discretion, we may include or offer third-party products or services on our website and app. These third-party sites have separate and independent privacy policies. We therefore have no responsibility or liability for the content and activities of these linked sites. Nonetheless, we seek to protect the integrity of our site and welcome any feedback about these sites. 

### Security

We value your trust in providing us your Personal Information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and we cannot guarantee its absolute security.  We implement a variety of security measures when a user enters, submits, or accesses their information to maintain the safety of your personal information.  Only us, the services we use, and trusted third-party applications may have access to your personal data. Government agencies may also be recipients of your personal data, exclusively to meet legal obligations.

### Children’s Privacy

The AR OptionSim app is not directed to children under the age of 13 and we do not knowingly collect personally identifiable information from children under 13 years of age. Should we learn that a child under 13 has provided us with their personally identifiable information, we will delete that information from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact us at <aroptionsim@gmail.com> so that we can take any necessary actions.

### Fair Information Practices 

The Fair Information Practices Principles form the backbone of privacy law in the United States and the concepts they include have played a significant role in the development of data protection laws around the globe. Understanding the Fair Information Practice Principles and how they should be implemented is critical to comply with the various privacy laws that protect personal information. In order to be in line with Fair Information Practices we will take the following responsive action, should a data breach occur: 
- We will notify you via email within 7 business days. 
- We will notify the users via in-site notification within 7 business days. 
- We also agree to the Individual Redress Principle which requires that individuals have the right to legally pursue enforceable rights against data collectors and processors who fail to adhere to the law. This principle requires not only that individuals have enforceable rights against data users, but also that individuals have recourse to courts or government agencies to investigate and/or prosecute non-compliance by data processors.

### CAN SPAM Act 

The CAN-SPAM Act is a law that sets the rules for commercial email, establishes requirements for commercial messages, gives recipients the right to have emails stopped from being sent to them, and spells out tough penalties for violations. 

We may collect your email address in order to: 
- Send information, respond to inquiries, and/or other requests or questions 
- Market to our mailing list or continue to send emails to our clients after the original transaction has occurred. 

To be in accordance with CANSPAM, we agree to the following: 
- Not use false or misleading subjects or email addresses. 
- Identify the message as an advertisement in some reasonable way. 
- Include the physical address of our business or site headquarters. 
- Monitor third-party email marketing services for compliance, if one is used. 
- Honor opt-out/unsubscribe requests quickly. 
- Allow users to unsubscribe by using the link at the bottom of each email. 

If at any time you would like to unsubscribe from receiving future emails, you can follow the instructions at the bottom of each email and we will promptly remove you from ALL correspondence.


### Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page.

This policy is effective as of 2021-09-10

### Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at <aroptionsim@gmail.com>.

---

### Terms and Conditions

By downloading or using the AR OptionSim app, these terms will automatically apply to you – you should make sure therefore that you read them carefully before using the app. You are prohibited from copying, or modifying the app, any part of the app, or our trademarks in any way. You are prohibited from attempting to extract the source code of the app, attempting to translate the app into other languages, and/or making derivative versions of the app. The app itself, and all the trade marks, copyright, database rights and other intellectual property rights related to it, belong to Jiecong Lu.

We are committed to ensuring that the app is as useful and efficient as possible. For that reason, we reserve the right to make changes to the app or to charge for its services, at any time and for any reason. We will never charge you for the app or its services without making it very clear to you exactly what you’re paying for.

The AR OptionSim app stores and processes personal data that you have provided to us, in order to provide our Service. It is your responsibility to keep your device and access to the app secure. We therefore recommend that you do not jailbreak or root your device, which is the process of removing software restrictions and limitations imposed by the official operating system of your device. It could make your device vulnerable to malware/viruses/malicious programs, compromise your device’s security features and it could mean that the AR OptionSim app will not work properly or at all.

You should be aware that there are certain things that we are not responsible for. Certain functions of the app will require the app to have an active internet connection. The internet connection can be Wi-Fi, or provided by your mobile network provider, but we cannot take responsibility for the app not working at full functionality if you do not have access to Wi-Fi, and you do not have any of your data allowance left.

If you are using the app outside of an area with Wi-Fi, you should remember that your terms of the agreement with your mobile network provider will still apply. As a result, you may be charged by your mobile provider for the cost of data for the duration of the connection while accessing the app, or other third party charges. In using the app, you are accepting responsibility for any such charges, including roaming data charges if you use the app outside of your home territory (i.e. region or country) without turning off data roaming. If you are not the bill payer for the device on which you are using the app, please be aware that we assume that you have received permission from the bill payer for using the app.

We are not responsible for the way you use the app.  You should ensure that your device stays charged.  If your device runs out of battery and you cannot turn it on to access the AR OptionSim app, we cannot accept responsibility.

Although we endeavour to ensure that it is updated and correct at all times, we do rely on third parties to provide information to us so that we can make it available to you.  We accept no liability for any loss, direct or indirect, you experience as a result of relying wholly on this functionality of the app.

At some point, we may wish to update the app.  The app is currently available on iOS – the requirements for system (and for any additional systems we decide to extend the availability of the app to) may change, and you’ll need to download the updates if you want to keep using the app.  We do not promise that we will always update the app so that it is relevant to you and/or works with the iOS version that you have installed on your device.  However, you promise to always accept updates to the application when offered to you.  We may also wish to stop providing the app, and may terminate use of it at any time without giving notice of termination to you.  Unless we tell you otherwise, upon any termination, (a) the rights and licenses granted to you in these terms will end; (b) you must stop using the app, and (if needed) delete it from your device.

### Changes to This Terms and Conditions

We may update our Terms and Conditions from time to time.  Thus, you are advised to review this page periodically for any changes. We will notify you of any changes to the terms and conditions by posting the new Terms and Conditions on this page.

These terms and conditions are effective as of 2021-09-10

### Contact Us

If you have any questions or suggestions about our Terms and Conditions, do not hesitate to contact us at <aroptionsim@gmail.com>.