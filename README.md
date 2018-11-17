# Awesome Burp Extensions  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome Burp Extensions

# Contributing

[Please refer to the contributing guide for details](CONTRIBUTING.md).


# How to Use
Awesome burp extensions is an amazing list for people who wants to spice up their Burp instance with awesome plugins. The best ways to use are:
 - Simply press command + F to search for a keyword
 - Go through our Content Menu

# Content
- [Scanners](#scanners)
- [Beautifiers and Decoders](#beautifiers-and-decoders)
- [Cloud Security](#cloud-security)
- [Scripting](#scripting)
- [OAuth and SSO](#oauth-and-sso)
- [Information Gathering](#information-gathering)
- [Vulnerability Specific](#vulnerability-specific)
    - [Cross-site scripting](#cross-site-scripting)
    - [Broken Access Control](#broken-access-control)
    - [Cross-Site Request Forgery](#cross-site-request-forgery)
    - [Deserialization](#deserialization)
    - [Sensitive Data Exposure](#sensitive-data-exposure)
    - [SQL Injection](#sql-injection)
    - [XXE](#xxe)
    - [Insecure File Uploads](#insecure-file-uploads)
    - [Directory Traversal](#directory-traversal)
    - [Session Management](#session-management)
    - [Command Injection](#command-injection)
- [Web Application Firewall Evasion](#web-application-firewall-evasion)
- [Logging and Notes](#logging-and-notes)
- [Payload Generator/Fuzzers](#payload-generator/fuzzers)
- [Cryptography](#cryptography)
- [Traffic Analysis](#traffic-analysis)
- [Mobile Security](#mobile-security)
- [Misc](#misc)
- [Tool Integration](#tool-integration)
- [Burp Extension Training Resources](#burp-extension-training-resources)

## Scanners

*Passive and Active scan plugins*

* [ActiveScan++](https://github.com/albinowax/ActiveScanPlusPlus)
* [Burp Vulners Scanner](https://github.com/vulnersCom/burp-vulners-scanner)
* [Additional Scanner checks](https://github.com/portswigger/additional-scanner-checks)
* [CSRF Scanner](https://github.com/ah8r/csrf)
* [HTML5 Auditor](https://github.com/PortSwigger/html5-auditor)
* [Software Version Reporter](https://github.com/augustd/burp-suite-software-version-checks)
* [J2EEScan](https://github.com/ilmila/J2EEScan)
* [Java-Deserialization-Scanner](https://github.com/federicodotta/Java-Deserialization-Scanner)
* [CSP-Bypass](https://github.com/moloch--/CSP-Bypass)
* [Burp Sentinel](https://github.com/dobin/BurpSentinel)
* [Backslash Powered Scanner](https://github.com/PortSwigger/backslash-powered-scanner)
* [Collaborator Everywhere](https://github.com/PortSwigger/collaborator-everywhere)
* [Distribute Damage](https://github.com/PortSwigger/distribute-damage)
* [Burp Molly Pack](https://github.com/yandex/burp-molly-pack)
* [Noopener Burp Extension](https://github.com/snoopysecurity/Noopener-Burp-Extension)
* [ActiveScan3Plus](https://github.com/silentsignal/ActiveScan3Plus)
* [Burp Image Size](https://github.com/silentsignal/burp-image-size)
* [UUID issues for Burp Suite](https://github.com/silentsignal/burp-uuid)
* [JSON array issues for Burp Suite](https://github.com/silentsignal/burp-json-array)
* [Burp Retire JS](https://github.com/h3xstream/burp-retire-js)
* [SOMEtime](https://github.com/linkedin/sometime)
* [HTTPoxy Scanner](https://github.com/PortSwigger/httpoxy-scanner)
* [ParrotNG](https://github.com/ikkisoft/ParrotNG)
* [Error Message Checks](https://github.com/augustd/burp-suite-error-message-checks)
* [Identity Crisis](https://github.com/EnableSecurity/Identity-Crisis)
* [CSP-Auditor](https://github.com/GoSecure/csp-auditor)
* [Burp Suite GWT Scan](https://github.com/augustd/burp-suite-gwt-scan)
* [Minesweeper](https://github.com/codingo/Minesweeper)
* [Add & Track Custom Issues](https://github.com/JAMESM0RR1S/Add-And-Track-Custom-Issues)
* [Yara](https://portswigger.net/bappstore/11e2ec6923f2497db9c18ec92492c63a)
* [WordPress Scanner](https://portswigger.net/bappstore/77a12b2966844f04bba032de5744cd35)
* [Web Cache Deception Burp Extension](https://portswigger.net/bappstore/7c1ca94a61474d9e897d307c858d52f0)
* [UUID Detector](https://portswigger.net/bappstore/65f32f209a72480ea5f1a0dac4f38248)
* [SSL Scanner](https://portswigger.net/bappstore/474b3c575a1a4584aa44dfefc70f269d)
* [Software Vulnerability Scanner](https://portswigger.net/bappstore/c9fb79369b56407792a7104e3c4352fb)
* [Scan Check Builder](https://portswigger.net/bappstore/ca7ee4e746b54514a0ca5059329e926f)
* [Scan manual insertion point](https://portswigger.net/bappstore/ca7ee4e746b54514a0ca5059329e926f)
* [Reverse Proxy Detector](https://portswigger.net/bappstore/a112997070354d249b64b4cf68eabc04)
* [SRI Check](https://github.com/bellma101/sri-check)
* [Reflected File Download Checker](https://portswigger.net/bappstore/34cd4392e7e04999b9ca0cc91f58886c)
* [Length Extension Attacks](https://portswigger.net/bappstore/f156669cae8d4c10a3cd9d0b5270bcf6)
* [Headers Analyzer](https://portswigger.net/bappstore/8b4fe2571ec54983b6d6c21fbfe17cb2)
* [Heartbleed](https://portswigger.net/bappstore/d405150b57e54887b1dcfa563b7c0b6f)
* [HTTPoxy Scanner](https://portswigger.net/bappstore/9c9877825cbd428bab27a25d0ea17178)
* [Image Size Issues](https://portswigger.net/bappstore/1b602a9ae78a4ba4bc9f7b2c405a2b4e)
* [CMS Scanner](https://portswigger.net/bappstore/1bf95d0be40c447b94981f5696b1a18e)
* [Distribute Damage](https://portswigger.net/bappstore/543ab7a08d954390bd1a5f4253d3763b)
* [Detect Dynamic JS](https://portswigger.net/bappstore/4a657674ebe3410b92280613aa512304)

## Beautifiers and Decoders

* [.NET Beautifier](https://github.com/allfro/dotNetBeautifier) 
* [JS Beautifier](https://github.com/irsdl/BurpSuiteJSBeautifier) 
* [Burp ASN1 Toolbox](https://github.com/silentsignal/burp-asn1)
* [JSON JTree viewer for Burp Suite](https://github.com/silentsignal/burp-json-jtree)
* [JSON Beautifier](https://github.com/NetSPI/JSONBeautifier)
* [Browser Repeater](https://github.com/allfro/browserRepeater)
* [GQL Parser](https://github.com/br3akp0int/GQLParser)
* [XChromeLogger Decoder](https://portswigger.net/bappstore/a68f0a880362410baaf884ddb383fe4c)
* [WebSphere Portlet State Decoder](https://portswigger.net/bappstore/49e9917c721e4abfa4c2540b07f35eb7)
* [PDF Viewer](https://portswigger.net/bappstore/4b0cbd1e44da4212881cc1480ba1bc68)
* [NTLM Challenge Decoder](https://portswigger.net/bappstore/30d095e075e64a109b8d12fc8281b5e3)
* [JCryption Handler](https://portswigger.net/bappstore/fe2a5a42985b4ac8b1801a09b670758f)
* [JSWS Parser](https://portswigger.net/bappstore/1d1b8fd9be354c64a5887f25fc271e56)
* [JSON Decoder](https://portswigger.net/bappstore/ceed5b1568ba4b92abecce0dff1e1f2c)
* [MessagePack](https://portswigger.net/bappstore/c199ec3330864d548ff7d6bf761960ba)
* [Fast Infoset Tester](https://portswigger.net/bappstore/2f640c88e0394bb09e788378f1bcc80f)

## Cloud Security

*Plugins related to Cloud Security*

* [AWS Security Checks](https://github.com/PortSwigger/aws-security-checks)
* [AWS Extender](https://github.com/VirtueSecurity/aws-extender.)
* [Cloud Storage Tester](https://github.com/PortSwigger/cloud-storage-tester)

## Scripting
* [Python Scripter](https://github.com/portswigger/python-scripter)
* [Burpkit](https://github.com/allfro/BurpKit)
* [Burp Requests](https://github.com/silentsignal/burp-requests)
* [Burpy](https://github.com/debasishm89/burpy)
* [Buby](https://github.com/tduehr/buby)
* [Burpee](https://github.com/GDSSecurity/burpee)
* [Burp Jython Tab](https://github.com/mwielgoszewski/burp-jython-tab)
* [Reissue Request Scripter](https://portswigger.net/bappstore/6e0b53d8c801471c9dc614a016d8a20d)
* [Burp Buddy](https://github.com/tomsteele/burpbuddy)
* [Copy As Python-Requests](https://portswigger.net/bappstore/b324647b6efa4b6a8f346389730df160)
* [Copy as PowerShell Requests](https://portswigger.net/bappstore/4da25d602db04f5ca7c4b668e4611cfe)
* [Copy as Node Request](https://portswigger.net/bappstore/e170472f83ef4da1bca5897203b6b33d)

## OAuth and SSO
* [SAML Raider](https://github.com/SAMLRaider/SAMLRaider)
* [Burp OAuth](https://github.com/dnet/burp-oauth)
* [EsPReSSO](https://github.com/RUB-NDS/BurpSSOExtension)
* [SAML Encoder/Decoder](https://portswigger.net/bappstore/9ff11c976383491b976389ce23091ee3)
* [SAML Editor](https://portswigger.net/bappstore/32c38cd10ef44c1cbca9d54483f78e88)
* [PeopleSoft Token Extractor](https://portswigger.net/bappstore/df04d7d1af004ed6b50c555c4920232d)
* [JSON Web Token Attacker](https://portswigger.net/bappstore/82d6c60490b540369d6d5d01822bdf61)
* [JSON Web Tokens](https://portswigger.net/bappstore/f923cbf91698420890354c1d8958fee6)
* [AuthHeader Updater](https://github.com/sampsonc/AuthHeaderUpdater)

## Information Gathering

* [Google Hack](https://portswigger.net/bappstore/a00a906943de49159092e329cc4f95f4)
* [PwnBack](https://github.com/P3GLEG/PwnBack)
* [Directory File Listing Parser Importer](https://github.com/SmeegeSec/Directory_File_Listing_Parser_Importer)
* [Wayback Machine](https://portswigger.net/bappstore/5c7c516c690345c19fbf55b2b2ebeb76)
* [Site Map Extractor](https://portswigger.net/bappstore/f991b67d4ef94f3c8692c3edca06583e)
* [Site Map Fetcher](https://portswigger.net/bappstore/93bbecc3da434ef7ba5a5b2b98265169)
* [Burp CSJ](https://portswigger.net/bappstore/371cebe47d8d4049a92dc03b66e1105f)
* [Attack Surface Detector](https://portswigger.net/bappstore/47027b96525d4353aea5844781894fb1)

## Vulnerability Specific

### Cross-site scripting
* [XSS Validator](https://github.com/nVisium/xssValidator)
* [burp-xss-sql-plugin](https://github.com/attackercan/burp-xss-sql-plugin)
* [Burp Hunter](https://github.com/mystech7/Burp-Hunter)

### Broken Access Control
* [Burplay](https://github.com/SpiderLabs/burplay)
* [AuthMatrix](https://github.com/SecurityInnovation/AuthMatrix)
* [Autorize](https://github.com/Quitten/Autorize)
* [AutoRepeater](https://github.com/nccgroup/AutoRepeater)
* [UUID issues for Burp Suite](https://github.com/silentsignal/burp-uuid)
* [Authz](https://github.com/wuntee/BurpAuthzPlugin)
* [Paramalyzer](https://github.com/JGillam/burp-paramalyzer)
* [Burp SessionAuth](https://github.com/thomaspatzke/Burp-SessionAuthTool)
* [Multi Session Replay](https://portswigger.net/bappstore/47319d00cae2447e8319db423913e19c)
* [Auto Repeater](https://portswigger.net/bappstore/f89f2837c22c4ab4b772f31522647ed8)

### Cross-Site Request Forgery
* [CSRF Scanner](https://github.com/ah8r/csrf)
* [CSurfer](https://github.com/asaafan/CSurfer)
* [Additional CSRF Checks/EasyCSRF](https://github.com/0ang3el/EasyCSRF)
* [Match/Replace Session Action](https://portswigger.net/bappstore/9b5c532966ca4d5eb13c09c72ba7aac2)
* [Token Extractor](https://portswigger.net/bappstore/f24211fa6fcd4bbea6b21f99c5cad27a)
* [CSRF Token Tracker](https://portswigger.net/bappstore/61ddd8a0464544218dfd94114c910548)

### Deserialization
* [Java-Deserialization-Scanner](https://github.com/federicodotta/Java-Deserialization-Scanner)
* [Java Serial Killer](https://github.com/NetSPI/JavaSerialKiller)
* [BurpJDSer-ng](https://github.com/IOActive/BurpJDSer-ng)
* [PHP Object Injection Check](https://portswigger.net/bappstore/24dab228311049d89a27a4d721e17ef7)
* [Java Serialized Payloads](https://portswigger.net/bappstore/bc737909a5d742eab91544705c14d34f)
* [Freddy, Deserialization Bug Finder](https://portswigger.net/bappstore/ae1cce0c6d6c47528b4af35faebc3ab3)
* [CustomDeserializer](https://portswigger.net/bappstore/84ff4dceaae14e84990c6f3f7fe999bd)

### Sensitive Data Exposure
* [Burp Smart Buster](https://github.com/pathetiq/BurpSmartBuster)
* [PDF Metadata](https://github.com/luh2/PDFMetadata)
* [SpyDir](https://github.com/aur3lius-dev/SpyDir)
* [Burp Hash](https://github.com/burp-hash/burp-hash)
* [Param Miner](https://portswigger.net/bappstore/17d2949a985c4b7ca092728dba871943)
* [MindMap Exporter](https://portswigger.net/bappstore/676b2e91c5a347289fca66fa67cca545)
* [Image Location & Privacy Scanner](https://portswigger.net/bappstore/f3aec37088aa494c81962d965219be46)
* [Image Metadata](https://portswigger.net/bappstore/3996aa01e0474b1a990db586a7f14ab7)
* [ExifTool Scanner](https://portswigger.net/bappstore/858352a27e6e4a6caa802e61fdeb7dd4)

### SQL Injection
* [CO2](https://github.com/JGillam/burp-co2)
* [SQLiPy](https://github.com/codewatchorg/sqlipy)
* [burp-xss-sql-plugin](https://github.com/attackercan/burp-xss-sql-plugin)
* [SQLiPy Sqlmap Integration](https://portswigger.net/bappstore/f154175126a04bfe8edc6056f340f52e)

### XXE
* [Office OpenXML Editor](https://github.com/PortSwigger/office-open-xml-editor)
* [Content Type Converter](https://github.com/NetSPI/Burp-Extensions/tree/master/ContentTypeConverter)

### Insecure File Uploads
* [HTTP file upload scanner](https://github.com/modzero/mod0BurpUploadScanner)
* [ZIP File Raider](https://github.com/destine21/ZIPFileRaider)
* [Upload Scanner](https://portswigger.net/bappstore/b2244cbb6953442cb3c82fa0a0d908fa)
* [File Upload Traverser](https://portswigger.net/bappstore/5f46fe766e9c435992c610160bb53cba)

### Directory Traversal
* [Uploader](https://github.com/thec00n/Uploader)

### Session Management
* [Session Timeout Test](https://github.com/augustd/burp-suite-session-timeout-test)
* [WAFDetect](https://portswigger.net/bappstore/12bef6b7607e46cf965c16f76e905a4c)
* [TokenJar](https://portswigger.net/bappstore/d9e05bf81c8f4bae8a5b0b01955c5578)
* [Token Incrementor](https://portswigger.net/bappstore/ae166662024149f981bb6920cf3c8960)
* [Token Extractor](https://portswigger.net/bappstore/f24211fa6fcd4bbea6b21f99c5cad27a)
* [Session Auth](https://portswigger.net/bappstore/9cbdeea2d3744e5ab0f2d08632438985)
* [Session Timeout Test](https://portswigger.net/bappstore/c4bfd29882974712a1d69c6d8f05874e)
* [Session Tracking Checks](https://portswigger.net/bappstore/1ab99dc6b61b45469759fdc38f371278)
* [ExtendedMacro](https://portswigger.net/bappstore/33839d04fdaa4e3b80292fbed115db13)
* [AuthHeader Updater](https://github.com/sampsonc/AuthHeaderUpdater)

### Command Injection

* [Command Injection Attacker/Shelling](https://github.com/portswigger/command-injection-attacker)

## Web Application Firewall Evasion
* [Bypass Waf](https://github.com/codewatchorg/bypasswaf)
* [Random IP Address Header](https://github.com/PortSwigger/random-ip-address-header)
* [Burp Suite HTTP Smuggler](https://github.com/nccgroup/BurpSuiteHTTPSmuggler/)
* [What-The-WAF](https://portswigger.net/bappstore/5da470c526ea4661a82187ec3e0f94aa)
* [WAF Cookie Fetcher](https://portswigger.net/bappstore/0f6ce51c1cb349689ecb4025e8db060a)
* [WAFDetect](https://portswigger.net/bappstore/12bef6b7607e46cf965c16f76e905a4c)
* [LightBulb WAF Auditing Framework](https://portswigger.net/bappstore/3144e67e904a4fdf91ea96cf4c694c39)

## Logging and Notes
* [Burp Notes](https://github.com/SpiderLabs/BurpNotesExtension)
* [Logger++](https://github.com/nccgroup/BurpSuiteLoggerPlusPlus)
* [Burp Dump](https://github.com/crashgrindrips/burp-dump)
* [Burp SQLite logger](https://github.com/silentsignal/burp-sqlite-logger)
* [Burp Git Version](https://github.com/silentsignal/burp-git-version)
* [Burp Commentator](https://github.com/silentsignal/burp-commentator)
* [Burp Suite Importer](https://github.com/SmeegeSec/Burp-Importer)
* [Burp Replicator](https://github.com/portswigger/replicator)
* [Notes](https://portswigger.net/bappstore/b150353ea3d54f61bdc482a4a8470356)
* [Log Requests to SQLite](https://portswigger.net/bappstore/d916d94506734f3490e49391595d8747)
* [Flow](https://portswigger.net/bappstore/ee1c45f4cc084304b2af4b7e92c0a49d)
* [Custom Logger](https://portswigger.net/bappstore/f5ca4f46dc37424c9666845a6ad0ecef)
* [Log Requests to SQLite](https://github.com/righettod/log-requests-to-sqlite)

## Payload Generator/Fuzzers

* [CO2](https://github.com/JGillam/burp-co2)
* [Bradamsa](https://github.com/ikkisoft/bradamsa)
* [Payload Parser](https://github.com/infodel/burp.extension-payloadparser)
* [Burp Luhn Payload Processor](https://github.com/EnableSecurity/burp-luhn-payload-processor)
* [Gather Contacts](https://github.com/clr2of8/GatherContacts)
* [Blazer](https://github.com/ikkisoft/blazer)
* [Wordlist Extractor](https://portswigger.net/bappstore/21df56baa03d499c8439018fe075d3d7)
* [PsychoPATH](https://portswigger.net/bappstore/554059e593ce446585574b92344b9675)
* [Meth0dMan](https://portswigger.net/bappstore/8ba6e98e367e40c79824f562f22d2221)
* [Intruder File Payload Generator](https://portswigger.net/bappstore/880cf2cf689b4067afd9db8e2aefb8ba)
* [Intruder Time Payloads](https://portswigger.net/bappstore/ad5f51b515d14490ae8842ce61f60df5)

## Cryptography

* [WhatsApp Protocol Decryption Burp Tool](https://github.com/romanzaikin/BurpExtension-WhatsApp-Decryption-CheckPoint)
* [AES Burp](https://github.com/lgrangeia/aesburp)
* [Crypto Attackeer](https://github.com/PortSwigger/crypto-attacker)
* [AES Payloads](https://github.com/PortSwigger/aes-payloads)
* [Length Extension Attacks](https://portswigger.net/bappstore/f156669cae8d4c10a3cd9d0b5270bcf6)

## Web Services

* [WCF-Binary-SOAP-Plug-In](https://github.com/GDSSecurity/WCF-Binary-SOAP-Plug-In)
* [WSDL Wizard](https://github.com/SmeegeSec/WSDLWizard)
* [BurpWCFDSer](https://github.com/NetSPI/Burp-Extensions/tree/master/BurpWCFDser)
* [JSWS](https://github.com/NetSPI/JSWS)
* [JSON Decoder](https://github.com/PortSwigger/json-decoder)
* [WSDLer](https://github.com/NetSPI/Wsdler)
* [POST2JSON](https://github.com/cyberisltd/POST2JSON/tree/3d6109a4749352849e5e7f27737e5384f78c4552)
* [WCF Deserializer](https://portswigger.net/bappstore/1ddd8919e946459f9c1bb47eedb19376)
* [Postman Integration](https://portswigger.net/bappstore/6ae9ede3630949748842a43518e840a7)
* [OpenAPI Parser](https://portswigger.net/bappstore/6bf7574b632847faaaa4eb5e42f1757c)
* [Content Type Converter](https://github.com/NetSPI/Burp-Extensions/tree/master/ContentTypeConverter)

## Traffic Analysis

* [Burp Non HTTP Extension](https://github.com/summitt/Burp-Non-HTTP-Extension)
* [Burp Suite GWT wrapper](https://github.com/dnet/burp-gwt-wrapper)
* [BurpJDSer](https://github.com/NetSPI/Burp-Extensions/tree/master/BurpJDSer)
* [BurpAMFDSer](https://github.com/NetSPI/Burp-Extensions/tree/master/BurpAMFDSer)
* [Deflate Burp Plugin](https://github.com/GDSSecurity/Deflate-Burp-Plugin)
* [Brida](https://github.com/federicodotta/Brida)
* [burp-protobuf-decoder](https://github.com/mwielgoszewski/burp-protobuf-decoder)
* [Pcap Importer](https://portswigger.net/bappstore/01da4fdd9f6e4e12b0622fbdaa2dd26d)
* [Proxy Auto Config](https://portswigger.net/bappstore/7b3eae07aa724196ab85a8b64cd095d1)
* [Proxy Action Rules](https://portswigger.net/bappstore/01376d8325c846b988730e9417016039)

## Mobile Security

* [CFURL Cache inspector for Burp Suite](https://github.com/silentsignal/burp-cfurl-cache)
* [Brida](https://github.com/federicodotta/Brida)

## Misc

* [Burp Rest API](https://github.com/vmware/burp-rest-api)
* [Burpa](https://github.com/0x4D31/burpa)
* [CVSS Calculator](https://portswigger.net/bappstore/e2209cdad8474342a695b2e279c294f0)
* [Burp Uniqueness](https://github.com/silentsignal/burp-uniqueness)
* [Sample Burp Suite extension: custom scanner checks](https://github.com/PortSwigger/example-scanner-checks)
* [Decoder Pro](https://github.com/Matanatr96/DecoderProBurpSuite)
* [Decoder Improved](https://portswigger.net/bappstore/0a05afd37da44adca514acef1cdde3b9)
* [Burp Bing translator](https://github.com/yehgdotnet/burp-extention-bing-translator)
* [Similar Request Excluder](https://github.com/tijme/similar-request-excluder)
* [jython-burp-api](https://github.com/mwielgoszewski/jython-burp-api)
* [Jython Burp Extensions](https://github.com/mwielgoszewski/jython-burp-extensions)
* [Add Custom Header](https://github.com/lorenzog/burpAddCustomHeader)
* [ThreadFix](https://portswigger.net/bappstore/0b0100a98b1c4a0e927f34eac9d01afe)
* [Target Redirector](https://portswigger.net/bappstore/d938ed20acbe4cd9889aa06bd23ba7e1)
* [Similar Request Excluder](https://portswigger.net/bappstore/9ecd51851baf4ae6b69c6a951257387a)
* [Request Highlighter](https://portswigger.net/bappstore/11729a617d8d4d3b87c82e34b71885c3)
* [Request Minimizer](https://portswigger.net/bappstore/cc16f37549ff416b990d4312490f5fd1)
* [Request Randomizer](https://portswigger.net/bappstore/36d6d7e35dac489b976c2f120ce34ae2)
* [Request Timer](https://portswigger.net/bappstore/56675bcf2a804d3096465b2868ec1d65)
* [Response Clusterer](https://portswigger.net/bappstore/e63f09f290ad4d9ea20031e84767b303)
* [Hackbar](https://github.com/d3vilbug/HackBar)
* [Hackvertor](https://github.com/hackvertor/hackvertor)
* [HUNT](https://github.com/bugcrowd/HUNT)
* [Replicator](https://portswigger.net/bappstore/56cf924977874104ac35e52962a9a553)
* [Kerberos Authentication](https://portswigger.net/bappstore/94135ed444c84cc095c72e6520bcc583)
* [JVM Property Editor](https://portswigger.net/bappstore/150c653f60b54b4eb556ca289a6aa800)
* [Lair](https://portswigger.net/bappstore/16ac195454f8429baac1c5357b0d3952)
* [Multi-Browser Highlighting](https://portswigger.net/bappstore/29fb77b2611d4c27a9a0b8bc504d8ca2)
* [Manual Scan Issues](https://portswigger.net/bappstore/3ebca77f69434faea1e3e97e0269fe17)
* [Google Authenticator](https://portswigger.net/bappstore/fb3685f958f8424493945c6c60c0920c)
* [GWT Insertion Points](https://portswigger.net/bappstore/a0740678763a4c748bbe7c79151cbe00)
* [Handy Collaborator](https://portswigger.net/bappstore/dcf7c44cdc7b4698bba86d94c692fb7f)
* [Headless Burp](https://portswigger.net/bappstore/d54b11f7af3c4dfeb6b81fb5db72e381)
* [HTTP Mock](https://portswigger.net/bappstore/42680f96fc214513bc5211b3f25fd98b)
* [Carbonator](https://portswigger.net/bappstore/e3a26fff8e1d401dade52f3a8d42d06b)
* [Burp Chat](https://portswigger.net/bappstore/1d0986521ace4b2dbf0b70836efa999d)
* [Batch Scan Report Generator](https://portswigger.net/bappstore/bc4ad87282e64fc4b35e9b9b05bac1dd)
* [Decompressor](https://portswigger.net/bappstore/ef36a66ebeb04412a52ffc17c2f5e15e)
* [Custom Parameter Handler](https://portswigger.net/bappstore/a0c0cd68ab7c4928b3bf0a9ad48ec8c7)

## Tool Integration
* [Report To Elastic Search](https://portswigger.net/bappstore/8493f7ae00aa4e01b6ffbbd1b8381ccc)
* [Qualys WAS](https://portswigger.net/bappstore/3b0105b95e4645a7929faa0cbda1df28)
* [NMAP Parser](https://portswigger.net/bappstore/0780c0a9f12e47848a94ac3e43dccbd9)
* [WebInspect Connector](https://github.com/portswigger/webinspect-connector)
* [Faraday](https://portswigger.net/bappstore/82f3cbaea46c4f158fd85bbccc90c31c)
* [Git Bridge](https://portswigger.net/bappstore/ae94d3ff6007497d863313fdded20daa)
* [Issue Poster](https://portswigger.net/bappstore/5e1ec745965b4e768d1f4908cc5cf22d)
* [Code Dx](https://portswigger.net/bappstore/03b096411fed48e49ccf585659650348)
* [ElasticBurp](https://portswigger.net/bappstore/67f5c31f93d04ad3a3b0a1808b3648fa)
* [Dradis Framework](https://portswigger.net/bappstore/c1be8787ebdd45f58c091f6ae30f1af2)

## Burp Extension Training Resources

* [Burp plugin development for java n00bs - Marc Wickenden](https://www.slideshare.net/marcwickenden/burp-plugin-development-for-java-n00bs-44-con)
* [Developing Burp Suite Extensions - Doyensec](https://github.com/doyensec/burpdeveltraining)
* [Writing your first Burp Suite extension - Portswigger](https://portswigger.net/burp/extender/writing-your-first-burp-suite-extension)
* [Burp Extension Writing - Sanoop Thomas](https://devilslab.in/files/Burp%20Extension%20Writing%20Workshop.pdf)
* [Extending Burp with Python](https://www.owasp.org/images/9/9f/Extending-Burp-with-Python.pptx)
* [Creating Burp Extensions in Python](https://blog.stalkr.net/2015/04/creating-burp-extensions-in-python.html)
* [Burp Extensions in Python and Pentesting Custom Webservices - Neohapsis](https://labs.neohapsis.com/2013/09/16/burp-extensions-in-python-pentesting-custom-web-services/)
* [Writing Burp Suite Marcos and Plugins - Pluralsight](https://www.pluralsight.com/courses/writing-burp-suite-macros-plugins)
* [Extending Burp with Extensions - Chris Bush](http://blog.opensecurityresearch.com/2014/03/extending-burp.html)
* [Burp Suite Extension Development series - Prakhar Prasad](https://prakharprasad.com/burp-suite-extension-development-series/)
