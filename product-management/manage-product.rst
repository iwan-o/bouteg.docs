.. include:: /incudes/images.rst
.. include:: /incudes/dictionary.rst

.. _product-management_manage-product:

Créer & modifier des produits
=============================

Vous allez pouvoir voir ici comment saisir les fiches d'identification de vos produits dans votre catalogue.

Créer un nouveau produit
------------------------

A partir du menu latéral cliquez sur la rubrique "Produits", puis cliquez sur le bouton "Créer" en haut à droite. 
Il existe trois types de produits différents dans Bouteg :

- :ref:`product-management_manage-product_product-standard`
- :ref:`product-management_manage-product_product-quantite`
- :ref:`product-management_manage-product_product-variante`

Si votre produit se vend au kilo, au litre ou via une autre mesure le mode :ref:`product-management_manage-product_product-quantite` est adapté.
Si votre produit présente des variantes, telles que la taille, vous pouvez ajouter chaque déclinaison via la création d’un :ref:`product-management_manage-product_product-variante`.
Pour les autres type de produits le mode :ref:`product-management_manage-product_product-standard` est préconisé. 


.. _product-management_manage-product_product-standard:

Produit standard
~~~~~~~~~~~~~~~~~~~~~~

Une fois sur le formulaire de création d'un nouveau produit, il vous faut saisir les informations minimum obligatoires pour que le produit puisse être publié.

C'est informations sont résumées dans l'onglet "Générale" :  

.. image:: /_static/images/product-management/create-product.png
    :alt: Nouveau produit
    :class: img-capture-bordered

* Nom
    Nom du produit

* Slug
    Le slug [#f1]_ sera généré automatiquement à partir du nom du produit.

* Référence
    Référence produit, elle doit être unique et peut uniquement être constitué de lettres, chiffres, tirets et tirets bas. 

* Prix de vente
    Prix client renseignés en HT, comme dans le reste de la solution le TTC est calculé automatiquement en prenant en compte le taux de taxe renseigné.

* Catégorie
    Affilier votre produit à une catégorie principale. Par exemple le produit "carottes" peut être rangés dans la catégorie « Légumes ». Voir la section :ref:`product-management_manage-categorys` pour plus d'information sur la création de catégories. 

* Catégorie de taxe
    La TVA à apliquer à votre produit. De manière général le taux réduit (5,5%) concerne l'essentiel des produits alimentaires. Pour plus d'informations vous pouvez vous référer au `site du ministère de l'économie <https://www.economie.gouv.fr/cedef/taux-tva-france-et-union-europeenne>`_ 

Une fois toutes les valeurs saisient, cliquez sur le bouton |image btn create| pour valider la création de votre nouveau produit.

.. _product-management_manage-product_product-quantite:

Produit par quantité (gr, kg, cl...) 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Une fois sur le formulaire de création d'un nouveau produit, vous allez retrouver exactement les même champs 
que pour un produit standard. Vous pouvez donc vous référer à la marche à suivre décrite ci-dessus dans :ref:`product-management_manage-product_product-standard` .

Deux champs apparaisent en complément : 

* Option
    Cela correspond à l'unité de mesure pour votre produit. Exemple : grammes, kilogrammes, litres... 

* Valeur de définition des tranches
    Cette valeur correspond à la tranches de quantité à laquelle un client pourrat acheter le produit. Exemple si vous indiquez 250 gr, le client pourra acheter le porduit en 250 gr, 500 gr, 750 gr, 1000 gr...

.. image:: /_static/images/product-management/create-product-measure.png
    :alt: Nouveau produit par quantité
    :class: img-capture-bordered

.. caution:: Le prix de vente doit être le  prix du produit pour la quantité de tranche indiquée ci-dessus. 

Une fois toutes les valeurs saisient, cliquez sur le bouton |image btn create| pour valider la création de votre nouveau produit.

.. _product-management_manage-product_product-variante:

Produit avec variantes
~~~~~~~~~~~~~~~~~~~~~~

Une fois sur le formulaire de création d'un nouveau produit, vous allez retrouver les même champs 
que pour un produit standard sans la partie tarification. 
Vous pouvez donc vous référer à la marche à suivre décrite ci-dessus dans :ref:`product-management_manage-product_product-standard` .

Une nouvelle section "Méthode de sélection de variante" apparait dans l'onglet "Générale" avec deux champs : 

* Choix de variante
    Conserver la valeur "Choix de variante", nous ne détaillerons pas ici la seconde option. 

* Options
    Sélectionner ici la ou les valeurs corespondant afin de déclinner toutes les combinaisons existant de votre produit.

.. image:: /_static/images/product-management/create-product-variantes.png
    :alt: Nouveau produit par variante
    :class: img-capture-bordered

Une fois toutes les valeurs saisient, cliquez sur le bouton |image btn create| pour valider la création de votre nouveau produit.

.. note:: Il est possible de créer des options personnnalisées (comme la couleur de votre produit : rouge, noir, blanc...) via la création d'une nouvelle "Options de produit"
    Pour cela à partir du menu latéral cliquez sur la rubrique "paramétrages" puis ""Options de produit" et enfin "Créer" 

Créer une variante de produit
*****************************

Une fois le produit créée un nouveau bouton "Gérer les varaintes" vas apparaitre en haut à droite de la page d'édition du produit.
Cliquez sur "Créer" afin d'accéder au formulaire.

.. image:: /_static/images/product-management/manage-variante.png
    :alt: Gérer les varaintes
    :class: img-capture-bordered


Une fois sur le formulaire de création d'une nouvelle variante, il vous faut saisir les informations obligatoires pour que la variante puisse être publiée.

.. image:: /_static/images/product-management/create-variante.png
    :alt: Nouveau produit
    :class: img-capture-bordered

* Référence
    Référence  de la vairante produit, tout comme pour le produit elle doit être unique et peut uniquement être constitué de lettres, chiffres, tirets et tirets bas. 

* Prix de vente
    Prix client renseignés en HT, comme dans le reste de la solution le TTC est calculé automatiquement en prenant en compte le taux de taxe renseigné.

* Options
    Sélectionner les valeurs correpondant à la combinaison que vous souhaitez créer. Par exemple : Taille = petite taille & Couleur = rouge

Une fois toutes les valeurs saisient, cliquez sur le bouton |image btn create| pour valider la création de votre nouvelle variante.

.. rubric:: Notes

.. [#f1] |dictionary field slug| 