# KryptoJobs2Go Application

![alt=""](Images/application-image.png)
KryptoJobs2Go is a disruptive application that allows customers to find fintech professionals from a list of candidates, hire them, and pay them instantly using cryptocurrency. This application integrates the Ethereum blockchain network, enabling secure and transparent transactions.

## Getting Started
To use the KryptoJobs2Go application, follow the steps below:

## Prerequisites
Python 3.x installed
Ganache or a local Ethereum development network set up
Metamask or a compatible Ethereum wallet installed

## Installation
Clone the GitHub repository:

shell
Copy code
git clone https://github.com/your-username/kryptojobs2go.git
Navigate to the project directory:

shell
Copy code
cd kryptojobs2go
Install the required dependencies:

shell
Copy code
pip install -r requirements.txt

## Usage
Set up your Ethereum wallet and account information:

Open the .env file and add your mnemonic seed phrase (provided by Ganache).
Rename the file to .env.
Start Ganache or your local Ethereum development network.

Run the application:

shell
Copy code
streamlit run fintech_finder.py
Access the application in your web browser at http://localhost:8501.

Select a fintech professional candidate from the drop-down menu.

Enter the number of hours to hire the candidate.

Click the "Send Transaction" button to initiate the payment transaction.

Screenshots
Sender's Address Balance and History in Ganache
Sender Balance and History

### Transaction Details in Ganache
Transaction Details

### Recipient's Address Balance and History in Ganache
Recipient Balance and History

## Contributing
Contributions to the KryptoJobs2Go application are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License
This project is licensed under the MIT License.



