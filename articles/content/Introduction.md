You can add *title* and *sort* at the top of each article. By default
it will take your filename as the title.

Authorization is enabled by default, login as "admin" and "password" by
<http://localhost:3000/login>

Main file changed:

* mkdir articles
* Makefile  #for new directory articles/
* package.json #replace examples/ with articles/
* customize a local theme raneto.css and layout.html, both under themes/local

After check out git, do:

* npm install
* npm start
* google-chrome http://localhost:3000/login (admin/password)
