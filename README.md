# CodeIgniter User Friendly Url
CodeIgniter User Friendly Url
Library ini dibuat untuk memudahkan mendapatkan url yang SEO Freindly, 
Sangat cocok sekali digunakan untuk website Portal, Blog, maupun Toko Online.

# Usage

load library ini pada controller anda.

      $this->load->library('seo_url', $config);

atau menambahkan pada autolod.php

      $autoload['libraries'] = array('seo_url');

**Paramaters**

* $replacement - (dash atau underscore)

Hanya memanggil method create_url :

      echo $this->slug->create_slug('Blog Vicky Nitinegoro');
      
akan menjadi :

      blog-vicky-nitinegoro
