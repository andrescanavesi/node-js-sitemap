# Node.js sitemap XML
A simple webapp that exposes and endpoint that prints a sitemap.xml like this:

```
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
   <url>
      <loc>https://javaniceday.com/</loc>
      <lastmod>2019-11-18</lastmod>
      <changefreq>monthly</changefreq>
      <priority>0.8</priority>
   </url>
</urlset> 
```

Just run the classic steps

`npm install`

`npm start`

Open your browser at: http://localhost:3000/sitemap.xml

See the step by step here:
[https://javaniceday.com/2019/11/19/how-to-build-a-sitemap-xml-in-node-js-using-express/](https://javaniceday.com/2019/11/19/how-to-build-a-sitemap-xml-in-node-js-using-express/)
