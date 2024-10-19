# FAZ3A SMS Sender

**FAZ3A SMS Sender** is a multi-provider SMS sending tool that allows users to send SMS messages through various SMS providers like Vonage, Twilio, Plivo, and Nexmo. This tool provides an easy-to-use graphical interface for sending bulk SMS messages, managing accounts, and tracking delivery status. The tool is perfect for businesses or individuals who need to send messages to large contact lists efficiently.

## Features

- **Multiple SMS Providers**: Send SMS through Vonage, Twilio, Plivo, and Nexmo.
- **API Credentials Management**: Easily manage API keys and secrets for different providers.
- **Custom Sender ID**: Specify your sender ID for branding purposes.
- **Bulk SMS**: Upload recipient numbers from CSV, TXT, or Excel files, or paste them directly.
- **Number Verification**: Verify the validity of phone numbers before sending.
- **Progress Tracking**: Visual progress bar for monitoring the status of message delivery.
- **Multi-language Support**: Send messages in different languages by simply typing in the message box.
- **Reports and Logs**: View detailed reports and logs of sent messages and delivery status.

## Prerequisites

To use FAZ3A SMS Sender, you will need:

- Python 3.x installed on your system.
- API credentials from one or more of the following SMS providers:
  - Vonage
  - Twilio
  - Plivo
  - Nexmo

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/FAZ3ATOOLS/faz3a-sms-sender.git
   cd faz3a-sms-sender
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## How to Use

1. **Choose SMS Provider**: Select one of the supported SMS providers (Vonage, Twilio, Plivo, or Nexmo).
   
2. **Enter API Credentials**: Provide the necessary API key and secret for the selected SMS provider.

3. **Enter Sender ID**: Specify the sender ID that will appear to the recipients.

4. **Compose Your Message**: Write the message you want to send in the text box.

5. **Upload Recipient Numbers**: You can upload phone numbers via CSV, TXT, or Excel files, or paste them directly.

6. **Verify Numbers**: Optionally, click the "Verify Numbers" button to ensure all numbers are valid.

7. **Send Message**: Click the "Send" button to send your SMS message to the uploaded recipients.

## File Formats

- **CSV/TXT Files**: Files should contain phone numbers in the first column.
- **Excel Files (XLSX)**: The tool accepts Excel files with phone numbers in the first column.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Troubleshooting

- **Invalid API Credentials**: Make sure the API key and secret are correctly entered.
- **Failed to Send SMS**: Ensure your internet connection is stable and that the phone numbers are valid.


##CONTACT
🔗 **FAZ3A SMS SENDER Developed By**: [@faz3ateamjo](https://t.me/faz3ateamjo)  
📢 **Stay Updated**: [@FAZ3ATEAMJOchannel](https://t.me/FAZ3ATEAMJOchannel)
