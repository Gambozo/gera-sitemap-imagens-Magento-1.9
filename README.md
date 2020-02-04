### sitemap-imagens-Magento-1.9
Script PHP para gerar XML de Imagens - Magento

##COMO USAR:
Colocar na raiz do Magento (não é necessário configurar quaisquer opções).

##OBS:
O script salva o XML para ser usado na raíz do site:
https://www.seusite.com/sitemap-image.xml

Caso haja necessidade de atualizar em períodos de tempo, recomendo configurar um CRON para executá-lo.

O script gera uma estrutura como esta:
```
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:image="http://www.google.com/schemas/sitemap-image/1.1">
   <url>
     <loc>
          httpX://www.seusite.com/seu-produto.html
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
