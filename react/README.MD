# React Note

### CERT_UNTRUSTED Error
~~~
npm ERR! Error: CERT_UNTRUSTED
~~~
~~~
before_install:
  - "npm config set strict-ssl false"
~~~
### React Command Not found Error
~~~
create-react-app: command not found
~~~
~~~
Need to install with -g flag to know react command 
npm install -g create-react-app
~~~

### NodeJS older version Error
~~~
Please update your version of Node.
~~~
~~~
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
~~~
### npm start - npm ERR! missing script ( not tested )
~~~
write a code in package.json file as below
"scripts": {
    "start": "node your-script.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
~~~

### Install Fetch ( whatwg-fetch )
~~~
npm WARN saveError ENOENT: no such file or directory, open '/home/y3myintoo/package.json'
npm WARN enoent ENOENT: no such file or directory, open '/home/y3myintoo/package.json'
~~~
npm install in uninitialized npm package directory,initialize package with npm init
