 # Node.js via Homebrew (OS X)

### Properly install node.js and npm so as to coexist with Homebrew. 

Reference https://github.com/Homebrew/homebrew/issues/22408

Install node without npm.
`brew install node --without-npm`

Install npm straight from the source.
`curl https://www.npmjs.org/install.sh | sh`

 When you want to update npm.
 `npm update npm -g`
