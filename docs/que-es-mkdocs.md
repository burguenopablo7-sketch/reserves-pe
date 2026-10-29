# **Què és MkDocs?**

### **Què és mkdocs.yml?**

És l'arxiu de configuració la web. Defineix l'estructura, el disseny, el nom del lloc, els menús de navegació i els complements (plugins) que utilitza MkDocs per generar les pàgines a partir d'arxius Markdown.

Funció principal: Controlar què es mostra a la web i com es veu.

### **Què és deploy.yml?**

És un arxiu de flux de treball (workflow) de GitHub Actions. S'executa automàticament als servidors de GitHub cada vegada que puges canvis (un push) al teu repositori.

Funció principal: Controlar com es publica la web de manera automatitzada (normalment a GitHub Pages). S'encarrega d'instal·lar el programari necessari, compilar els arxius de MkDocs i pujar-los al servidor final.

### **Exemple Pràctic: Afegir la funció de "Cerca Avançada" i "Mode Fosc"**

Imagina que vols fer dos canvis a la teva web:

- Activar el mode fosc i el cercador a la interfície (mkdocs.yml).
- Actualitzar el procés de publicació automatitzada perquè instal·li les dependències necessàries d'aquest nou tema visual (deploy.yml).

### **Canvis a mkdocs.yml (Disseny de la web)**

Al nostre mkdocs.yml, hem configurat el tema avançat material en idioma català (ca), afegint característiques de navegació fluida i extensions de Markdown per millorar el contingut:

### **Canvis a deploy.yml**

El nostre arxiu deploy.yml utilitza un contenidor Docker oficial (squidfunk/mkdocs-material). Això empaqueta automàticament MkDocs i totes les seves extensions (pymdownx, admonition, etc.) per compilar la nostra web de manera ràpida i segura a GitHub Pages sense necessitat de gestionar comandes pip.

## **Resum**

El canvi a mkdocs.yml transforma visualment la web afegint botons de disseny com el mode fosc i activa extensions de text. El canvi a deploy.yml garanteix que el servidor de GitHub utilitzi un contenidor Docker oficial que ja té totes aquestes eines extres preinstal·lades, permetent processar i compilar correctament el disseny de la web.
