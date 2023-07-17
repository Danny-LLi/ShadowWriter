# ShadowWriter
ShadowWriter is a Python keylogger that discreetly captures keystrokes and sends them to a specified email address. It operates silently in the background, logging keystrokes into a file and then attaching and sending that file via email.

## Prerequisites

Before running the ShadowWriter keylogger, ensure that you have the following prerequisites:

- Python 3.x installed on your system.
- The `email` and `pynput` libraries installed. If not, you can install them by running the following command:
  ```shell
  pip install email pynput
  ```

## Usage

1. Clone the repository to your local machine:
   ```shell
   git clone https://github.com/your-username/shadow-writer.git
   ```

2. Open the `shadow_writer.py` file in a text editor.

3. Modify the following variables in the script with your own information:
   - `email_address`: Enter your email address.
   - `password`: Enter your email password.
   - `toaddr`: Enter the recipient's email address.
   - `file_path`: Specify the desired file path where the log file will be stored.

4. Save the changes.

5. Run the script:
   ```shell
   python shadow_writer.py
   ```

6. The ShadowWriter keylogger will now run silently in the background, capturing keystrokes.

7. To stop the keylogger, press the `Esc` key.

## Notes

- **Use responsibly:** ShadowWriter is intended for educational purposes only. Ensure you have proper authorization before utilizing it. Unauthorized use may violate privacy laws and is strictly prohibited.

- **Antivirus and security software:** Many antivirus and security software programs may classify keyloggers as potentially harmful. Running this script may trigger security alerts or be blocked. It is recommended to use it on your own system or with explicit consent and awareness.

- **Email configuration:** ShadowWriter is preconfigured to send emails using a Gmail account. If you're using a different email provider, you will need to modify the SMTP server and port settings accordingly.

- **Logging frequency:** By default, ShadowWriter logs keystrokes and sends an email when the log file reaches a size of either 40 or 80 characters. You can adjust this behavior by modifying the `number_of_Character` function.


## License
ShadowWriter is licensed under the GNU General Public License, Version 3. For more information, see the [LICENSE](LICENSE) file.