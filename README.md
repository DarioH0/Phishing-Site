# What is this?
This is a phishing site designed to deceive victims into sending sensitive files to an attacker's server. It is intended for educational purposes and to raise awareness of such attacks, although it is a unique phishing tactic that has not been seen before as of the time of writing this.

# Features:
1. Multilingual Support: The phishing page supports 8 languages: English, Greek, German, Russian, French, Romanian, Albanian, and Arabic. It automatically detects the user's language based on their IP address and translates the page accordingly.

2. Webhook Integration: Once files are selected, they are sent to a Discord webhook in batches of 10 to avoid embed limitations. This allows attackers to collect the selected files remotely. To list your webhook, find the `wURL` variable in the javascript section and insert your webhook. To avoid detection, it may help to obfuscate the URL.<br> ![webhook](https://github.com/DarioH0/Phishing-Site/assets/123750271/4a1ea2f6-e4ec-4bc0-87d1-7f12c173c41d)


3. Dynamic Background: The background of the phishing page changes dynamically based on the website listed in the URL. It applies a blur effect to simulate a real website environment, enhancing the deception. For example, `localhost:8080/index.html/#youtube.com`. If no site is listed then the background will remain white.<br> ![site](https://github.com/DarioH0/Phishing-Site/assets/123750271/1d31bf4e-79c8-4e1c-bc06-87e43d88bb35)


# Disclaimer
This project is meant to raise awareness about phishing attacks and educate individuals on how to recognize and avoid them. It should only be used for educational purposes and ethical demonstrations. Any misuse or illegal activities conducted using this project are the sole responsibility of the user, and the developer or contributors of this project bear no liability for such actions.

# Usage
To use this project:

1. Clone the repository to your local machine.
2. Set up a web server to host the phishing page.
3. Configure the Discord webhook URL to receive the selected files.
4. Access the phishing page from a web browser.
5. Test the phishing page to understand how it works and educate yourself on phishing tactics.

# Contributing
Contributions to this project are welcome. If you have any suggestions for improvements or additional features, feel free to open an issue or submit a pull request.
