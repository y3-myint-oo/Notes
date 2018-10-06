# React Note
~~~
npm ERR! Error: CERT_UNTRUSTED
~~~
Solution
~~~
before_install:
  - "npm config set strict-ssl false"
~~~
