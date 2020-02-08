# fish-aws-vault-chrome
A Fish function for aws-vault that opens a temporary Chrome profile when logging in to the AWS Console 

## Installation
`fisher add adamsimp/fish-aws-vault-chrome`

## Usage
`awschrome profile-name`

Replace _profile-name_ with the name of the aws-vault profile you wish to log in to. This will open the AWS Console for that account in a completely independent Chrome instance. You can open as many as you want with this.

Thanks to Ben Bridts for writing this function. https://www.cloudar.be/awsblog/using-aws-vault-with-mulitple-browser-windows/
