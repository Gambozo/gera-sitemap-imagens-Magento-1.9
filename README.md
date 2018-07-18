### sitemap-imagens-Magento-1.9
Script PHP para gerar XML de Imagens - Magento

##COMO USAR:
Colocar na raiz do Magento (não é necessário configurar quaisquer opções).

##OBS:
O script salva o XML para ser usado na raíz do site:
https://www.seusite.com/sitemap-image.xml

O script gera uma estrutura como esta:
```
<urlset xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:image="http://www.google.com/schemas/sitemap-image/1.1" xmlns:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd" xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
   <url>
     <loc>
          httpX://www.seusite.com/media/catalog/product/x/p/xproduto.jpg
     </loc>
     <lastmod>2017-09-01</lastmod>
     <changefreq>daily</changefreq>
     <priority>0.5</priority>
     <image:image>
     <image:loc>
          httpX://www.seusite.com/media/catalog/product/x/p/xproduto.jpg
     </image:loc>
     </image:image>
   </url>
</urlset>
```
O link da imagem é definido inicialmente pela URL Base p/ Mídia.
