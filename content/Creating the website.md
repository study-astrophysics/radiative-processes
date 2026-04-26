
# Prerequisites

## Node.js

``` bash
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.4/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 24

# Verify the Node.js version:
node -v # Should print "v24.15.0".

# Verify npm version:
npm -v # Should print "11.12.1".
```

## Git

``` bash
brew install git
```

## GitHub Account: study.astrophysics@gmail.com


# Quartz Setup

## Download

``` bash
git clone https://github.com/jackyzha0/quartz.git
cd quartz
```

## Install the required dependencies

``` bash
(base) ➜  quartz git:(v4) npm i

added 485 packages, and audited 486 packages in 1m

176 packages are looking for funding
  run `npm fund` for details

8 vulnerabilities (2 moderate, 6 high)

To address all issues, run:
  npm audit fix

Run `npm audit` for details.
```

``` bash
(base) ➜  quartz git:(v4) npm audit fix

added 2 packages, removed 2 packages, changed 10 packages, and audited 486 packages in 1s

176 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```


## 