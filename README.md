


# DomainDossier

Are you interested in web security and want to test your skills against potential domain information gathering? If so, you've come to the right place! This project is a comprehensive Python script, meticulously designed for the purpose of probing domain information. Whether you're a beginner or an expert, this tool will help you discover new ways to gather domain information and access restricted resources.

## Features

1. **Domain Information Retrieval**: It retrieves and displays detailed information about a specific domain. The information includes:
   - Nameservers
   - Creation date
   - Expiration date
   - HTTP status code
   - IP address
   - Web server
   - Hosting provider
   - Real hostname

2. **Single Domain or Wordlist Input**: The script allows you to input either a single domain or a wordlist file containing multiple domains. This is useful for batch processing of multiple domains.

3. **Pretty Output**: The script uses the PrettyTable library to format the output in a neat, tabular structure, making it easy to read and understand.

4. **Output to File**: The script provides an option to save the output to a file. This is useful for record-keeping and future reference.

5. **Error Handling**: The script includes error handling mechanisms to manage exceptions and provide useful feedback when an error occurs.

## Installation

To install this tool, simply follow these steps:

```
git clone https://github.com/diiablo00/DomainDossier
```
```
cd DomainDossier
```
```
pip install -r requirements.txt
```

## Usage

To use this tool, simply run the script with the appropriate options. For example:

```
python DomainDossier.py -d yourdomain.com
```
```
python DomainDossier.py -w wordlist.txt -o output.txt
```

You can also view the help menu of the script by using the `-h` option.

## Demo

Here is a screenshot of the tool:
![Screenshot_2023-11-02_16_19_57](https://github.com/diiablo00/DomainDossier/assets/140319882/a3c24445-d4ee-4723-8e84-7dfdf7fb1f6b)
![Screenshot_2023-11-02_16_24_35](https://github.com/diiablo00/DomainDossier/assets/140319882/c63d5736-c36f-47ed-a256-313b86f816c8)

## Contribution

If you want to contribute to this project, feel free to fork it and submit a pull request. You can also report any issues or suggestions on the [Issues](https://github.com/diiablo00/DomainDossier/issues) page.

## Contact

If you have any questions or feedback, you can follow me on:
- Twitter: [diablo0_diablo](https://twitter.com/diablo0_diablo)
- Instagram: [diablo0_diablo](https://www.instagram.com/diablo0_diablo)
- Facebook: [Mahmoud Salah](https://www.facebook.com/profile.php?id=100044106499352)

I'd love to hear from you!
