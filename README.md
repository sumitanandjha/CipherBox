# CipherBox
-----------
CipherBox is an open-source web application designed to empower users with the ability to encrypt and decrypt strings using state-of-the-art cryptographic techniques. With an intuitive user interface, our application ensures data security and privacy by enabling users to safeguard their sensitive information effortlessly. Join us in advancing data security in the digital realm and contribute to this project.
<hr>

## Project Structure
```
- /css
  - styles.css        # CSS styles for the application
- /js
  - app.js            # JavaScript logic for the application
- /images             # Image assets 
- /crypto             # Folder for cryptographic algorithm modules
  - aes.js            # Example: AES encryption module
  - rsa.js            # Example: RSA encryption module
- README.md           # Project documentation
- /public
  - index.html        # Main HTML file for the web application
- LICENSE             # License file 
```
- **crypto**: Contains JavaScript files for each algorithm. Each file must contain a function for Encryption and Decryption each. For eg. aes.js conatins aesEncrypt, aesDecrypt.
- **app.js**: imports each function from the respective JavaScript file.
   
<hr>
#### Before contributing look into [CONTRIBUTING GUIDELINES]([./CONTRIBUTING.md](https://github.com/gdsc-jssstu/CipherBox/blob/main/CODE_OF_CONDUCT.md))
#### Our Code of Conduct:   [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)
<hr>

## Project setup instructions:
- **Fork the repository** to your GitHub account by clicking the "Fork" button at the top-right corner of this page. This will create a copy of the repository under your account.
- **Clone your forked repository** to your local machine using Git. Replace `your-username` with your GitHub username:

   ```
   git clone https://github.com/your-username/CipherBox.git
   cd CipherBox
   ```
- **Create a new branch** for your contribution. Replace *'feature/your-feature-name'* with a descriptive branch name related to your contribution.
- Commit your changes with a descriptive commit message:
  ```
  git commit -m "Add your descriptive message here"
  ```
  - Push your changes to your forked repository on GitHub:
  ```
  git push origin feature/your-feature-name
  ```
  <hr>
  ## Getting started with contributions

- ### Create a Pull Request (PR)

Visit the [CipherBox](https://github.com/gdsc-jssstu/CipherBox) repository on GitHub.
Click the "Compare & pull request" button next to your recently pushed branch.
Follow the PR template and guidelines. Provide details about your changes.
Submit the PR.

- ### Review and Merge

The maintainers will review your PR and may request changes or provide feedback.
Once your PR is approved, it will be merged into the main repository.

<hr>
