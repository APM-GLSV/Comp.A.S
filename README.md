# Modulos
Para ejecutar localmente es necesario realizar los siguientes pasos:  
1. Instalar Ruby [Documentación](https://www.ruby-lang.org/en/documentation/installation/). Se recomienda instalar la version con DevKit es la que mejor ha funcionado [Instalador](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-3.1.2-1/rubyinstaller-devkit-3.1.2-1-x64.exe)  
2. Instalar Bundler [Sitio Web](https://bundler.io/) para esto se debe ejecutar el comando,  despues de completar el paso 1:
``` ruby
gem install bundler 
```  
3. Ejecutar en terminal desde VS Code
``` ruby
bundle install
``` 
4. Ejecutar en terminal desde VS Code para ver la pagina localmente
``` ruby
bundle exec jekyll serve
``` 
5. En el navegador abrir la URL: http://127.0.0.1:4000/Comp.A.S/  
6. Revisar los cambios realizados.  

Más información en: [Documentacion de GitHub Pages](https://docs.github.com/es/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
