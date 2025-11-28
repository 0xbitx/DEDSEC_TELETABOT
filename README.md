
<p align="center">
<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGJoYXAzemhtcDdjMzQzdTYzZzl2aHg0czlmMGdycmw5bXJoemkwMCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/2lVtkuOqgKGeA/giphy.gif", width="300", height="300">
</p>

<h1 align="center">DEDSEC_TELETABOT</h1>

### DESCRIPTION

TELETABOT is an advanced intelligence-gathering tool designed to extract information from Telegram bots using the Telegram Bot API. It enables security researchers and investigators to monitor and analyze bot activities for threat intelligence and cybersecurity purposes.
With TELETABOT, you can:

   * Extract Bot Information: Retrieve comprehensive details about target bots including usernames and metadata
   * Monitor Message Traffic: Capture and forward bot messages to your own chat for analysis
   * Download Owner Profile Pictures: Extract and save profile images of bot operators for identification
   * Intercept Bot Communications: Automatically forward all messages from target bots to your controlled environment
   * Gather Threat Intelligence: Collect valuable data for security research and incident response

### Key Features:

   * Bot Information Extraction: Uses getMe API to retrieve bot details
   * Message Interception: Forwards messages from target bots to your account
   * Profile Picture Dumping: Downloads all profile photos of bot owners/operators
   * Real-time Monitoring: Captures and displays message content in formatted tables
   * Session Management: Stores Telegram credentials for persistent operations

### Technical Capabilities:

   * Supports multiple content types (text, images, documents, videos)
   * Handles bulk message forwarding through update tracking
   * Organizes extracted profile pictures in dedicated directories
   * Provides structured output with message IDs, types, and content
   * Maintains session persistence for repeated operations

Built for security researchers, penetration testers, and digital forensics experts, TELETABOT provides a powerful and efficient way to track bot communications while maintaining full control over the data flow.

### How to get Your telegram API
  * Visit [telegram](my.telegram.org/apps) and log in with your phone number.
  * Create a new application and get [APP api_id], [App api_hash] value


### INSTALLATION
    git clone https://github.com/0xbitx/DEDSEC_TELETABOT.git
    cd DEDSEC_TELETABOT
    python3 -m pip install telethon
    chmod +x dedsec_teletabot 
    ./dedsec_teletabot


### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.
