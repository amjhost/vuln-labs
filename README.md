# Vulnerable Web Applications Environment

This repository contains a Docker Compose setup for running multiple intentionally vulnerable web applications. These applications are meant for educational and training purposes to help users understand various web security vulnerabilities and their mitigations.

## Prerequisites
You can manually instal these two 
-  Docker
- docker-compose
                - or-
cd into vuln-labs and run ```bash sudo ./prerequisites.sh```
## Applications Included

- **bWAPP**: Buggy Web Application
- **DVWA**: Damn Vulnerable Web Application
- **Mutillidae II**: OWASP Mutillidae II
- **WebGoat**: OWASP WebGoat
- **Juice Shop**: OWASP Juice Shop
- **Security Shepherd**: OWASP Security Shepherd

## Getting Started

To set up and run these vulnerable applications using Docker Compose, follow these steps:

1. Make sure you have Docker and Docker Compose installed on your system.
2. Clone this repository: `git clone https://github.com/amjhost/vulnerable-apps.git`
3. Navigate to the cloned directory: `cd vulnerable-apps`
4. Run the applications using Docker Compose: `docker-compose up`

Each application will be accessible through its designated port as mentioned in the `docker-compose.yml` file.

## Usage

Once the applications are up and running, you can access them using a web browser. For example:

- bWAPP: [http://localhost:80](http://localhost:80)
- DVWA: [http://localhost:81](http://localhost:81)
- WAMPI: [http://localhost:82](http://localhost:82)
- Mutillidae II: [http://localhost:83](http://localhost:83)
- WebGoat: [http://localhost:84](http://localhost:84)
- Juice Shop: [http://localhost:85](http://localhost:85)

Remember that these applications are intentionally vulnerable. Do not expose them to the public internet or use them for any malicious activities. They are meant for learning and testing purposes only.

## Contributing

Feel free to contribute to this repository by adding more vulnerable applications, improving documentation, or fixing issues. Create a pull request with your changes.

## Disclaimer

The authors of this repository do not endorse or encourage any illegal activities. The provided applications are intended for educational purposes only.

## License

This project is licensed under the [GNU General Public License (GPL)](LICENSE).
