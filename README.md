# pg-dev2-web
Web application for PostgreSQL DEV2 course

1. Clone the repo
```
git clone https://github.com/i-bash/pg-dev2app.git
```

2. Install NodeJS 9 and server packages
```
curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -
sudo apt install -y nodejs

cd pg-dev2app/server
npm install
```
3. Start server in terminal
```
./wspg-server <port>
```
4. Open http://localhost:port in web browser.
Make sure you don't run an ancient version of the browser. Firefox 75+ will work.
