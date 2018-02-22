# Backend

Install Wordpress, please be sure rewrite mode  is ON and wp .htacess is acceptable with apache
Input some sample content , some sample category
Expect you finish your installation, and have accessible URL http://localhost/wordpress 

# Frontend 

Edit line 54 in index.html, change

```
const RESTURL = 'https://wordpress.org/news/wp-json/'
```

Into

```
const RESTURL = 'https://localhost/wordpress/wp-json/'
```

If don’t change RESTURL, the data will be loaded from wordpress news ( wordpress.org )
Open index.html with web browser to see the demo
