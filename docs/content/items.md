---
title: Contenus
---

Les contenus sont les éléments constitutifs du système Omeka. Dans Omeka S, les contenus peuvent être mis à votre disposition par l'administrateur système et vous pouvez ajouter des contenus à votre propre site. Les contenus sont répertoriés dans l'onglet Contenus (icône cube) de la navigation, à gauche du tableau de bord administratif.
![Vue de base de la page des contenus, montrant quelques ressources](/content/contentfiles/items_browse.png)

Chaque contenu apparaît sous forme de ligne, avec des colonnes pour:

- le titre*
- icônes pour * modifier * (crayon), * supprimer * (corbeille) ou * afficher les détails * (3 petits points)
- la classe*
- le * propriétaire * du contenu
- et la date à laquelle le contenu a été * créé *.

Les options de navigation et de création des contenus s'affichent au-dessus du tableau des contenus.

En haut à droite de la fenêtre Contenus se trouve le bouton * Ajouter un nouvel contenu *.

Sur le côté gauche se trouve un affichage du nombre de pages de contenus, avec les flèches avant et arrière. Le numéro de page actuel est un champ éditable. Entrez un numéro de page valide et appuyez sur la touche Entrée pour accéder à cette page.

En haut au centre se trouve un bouton [Recherche avancée](/search.md). 

Juste au-dessus du tableau de droite, vous trouverez des options pour trier le tableau des contenus, avec deux menus déroulants. Le premier vous permet de choisir entre *titre*, *identifiant*, *classe*, *propriétaire,* et *(date) créé*; la seconde vous permet de trier par ordre croissant ou décroissant. Pour executer ses actions, cliquez sur le bouton *Trier*.

Entre ceux-ci et le tableau, à gauche, se trouve un menu déroulant pour les actions par lot, y compris les opérations de modification des contenus sélectionnés, de tous les contenus, de suppression des contenus sélectionnés et de suppression de tous les contenus.

## Vue
Pour afficher rapidement les informations de base sur un contenu, cliquez sur le bouton *Afficher les détails* (3 petits points) dans la rangée du contenu, situé à côté des boutons Modifier et Supprimer. Cela ouvrira un onglet à la droite de la liste qui affiche le titre, la description et la visibilité du contenu.

Pour plus de détail sur un contenu, cliquez sur son titre.
 
Lorsque vous affichez un contenu, il existe des onglets pour les *métadonnées* et les *ressources liées* du contenu. Le côté droit de la page affiche le média, les *collections* auxquelles il appartient, sa date de création, son propriétaire et sa visibilité.

![Item browse view with details open for The Adventure of the Yellow Face. Links to item view page squared in blue](/content/contentfiles/items_detailview.png) The blue squares indicate where to click to open the full item view.

An item’s *linked resources* (shown below) are resources, which have been added as properties to the item. Note that this section only shows resources which have been linked *to* this item (which have it for a property); resources which are linked *from* this item will display in the property which they fill.

Linked items are grouped by the property for which they use the current item. In the example below, the item William Shakespeare is used for the properties "Creator," "References," and "list of authors" for the linked resources. 

You can filter linked resources to only display those referencing a specific property using the dropdown "Filter by property." It will only display properties actively in use.

![Item linked resources view for William Shakespeare, with six plays using Shakespeare as Creator, the item Folger Shakespeare Library listed as 'references' Shakespeare, and the Globe Theatre using Shakespeare for 'list of authors'. Each property cluster is in a separate rectangle, headed by the property being referenced.](/content/contentfiles/items_linked.png) 

## Adding an Item

To add a new item, begin by selecting the the *Add new item* button. 

Before creating items, site admins may want to create [Resource Templates](/content/resource-template.md), which will load specific fields for various item types.

### Values
The Values tab is where you enter metadata, such as title, description, etc.

![Basic view of add items page, with no content entered](/content/contentfiles/items_add.png)

You can select a resource template from the drop-down menu. Resource templates are defined by the site administrators and editors.

- If using a resource template, the class should automatically load.
- If not using a resource template, you may select a class from the dropdown menu (these are populated from the [Vocabularies](/content/vocabularies.md) in your installation).

Add information to the properties which load. If you do not select a resource template or class, the Dublin Core properties Title and Description will load automatically.

You may add text, a resource from the installation, or an external link in each field.  

Whether or not you use a resource template, you can add more properties to the item using the drawer on the right side of the screen. You can simply click open one of the vocabularies and click on the property you want to add, or you can use the “Filter properties” box to search for a specific property (this is helpful when you have multiple large vocabularies). 

![Close up of the right hand drawer with the text "date" entered into the filter properties box and a series of properties containing the word "date" loaded from Dublin Core and Bibliographic Ontology](/content/contentfiles/items_filterprop.png)

Clicking on the property label in the drawer will automatically add it to the Item. If you add a property by accident, leave it blank and it will be removed from the item when you save changes. 

You can set individual properties as Private or Publicly visible using the eye icon for each property. Note that properties set to private are still visible to Global Admins, Site Admins, and Editors will be able to see properties even when set to private. Authors will be able to see all properties on items they own, but will not see private properties created by other users.

In the image below, the first property (Title) is public as indicated by the open eye icon. The second property (Description) is private as indicated by the slashed-through eye icon. Clicking or hitting enter on the eye icon toggles between public and private. 

![As described](/content/contentfiles/item_propviz.png)

#### Text
Text fields allow for unformatted text entry.

![image of text input field with keyboard icon indicating text input, the globe icon for setting language, and a trashcan delete icon](/content/contentfiles/items_textedit.png)

You can indicate the language for the content of an input using the globe symbol above the input (see the red arrow in the image below). Click on the globe to activate a text field, then enter the [IETF Language tag](https://en.wikipedia.org/wiki/IETF_language_tag) code for the language in which the text is written.

![Red arrow points to the globe icon and a text entry field highlighted in blue](/content/contentfiles/item_lang.png)

#### Omeka Resource
Omeka Resource fields create an internal link between the resource you are creating and the resource which fills that field. 

When creating an item, you have the option to use either another item or an item set. 

Choosing a resource type will open a side drawer where you can browse all of those resources in the installation. You can use the search function at the top of the drawer to narrow down the list or to quickly find a specific item. 

Once you select an item or item set, detailed information will load, and you must click *select resource* to finish linking the resources. You can also click the *X* button in the upper right-hand corner to go back to the list of items or item sets.

![Select Item menu with list of items to link in edit item view](/content/contentfiles/items_addresource.png)

If you are using an Item resource for the property, you will have additional options for finding the item you want in the drawer. Open these options by clicking the triangle button next to the phrase "Filter search"

![Select Item drawer top options, with a red arrow around a gray triangle button to the right of the phrase "Filter search"](/content/contentfiles/items_filtersearch.png)

This will open a menu below the button with the following options to filter the items in the drawer:

- Filter by class: a dropdown where you can select any class provided by the vocabularies on the installation;
- Filter by item set: a dropdown where you can limit the items displayed in the drawer to only those associated with a particular item set
- Filter by item ID: a search field where you can input the ID of the item you want to use. You can find an item's ID in the url of it's edit page; if you are editing the item and the url is `admin/item/11547/edit` then the item's ID is 11547.

![options as above described](/content/contentfiles/item_addresItem.png)

Item resources also have an option for "Quick add". When this switch is flipped, all of the items in the drawer have a checkbox. You can use these checkboxes to add multiple items as a property at once. Note that you can only edit one property at a time, so all of the items must populate the same property (ex, Creator, Has Part). 

![a red arrow points to the slider button for "Quick add". The two items visible have an empty checkbox to the left of their representative thumbnail](/content/contentfiles/items_quickadd.png)

#### URI
URI fields link to an external website or online resource.

You may add other fields by selecting a property from the list on the right. Browse fields by vocabulary (Dublin Core, Bibliographic Ontology, etc), or search in the *filter properties* bar above the list of properties and vocabularies.

#### Language 
You can indicate the language for the content of an input using the globe symbol above the input (see the red arrow in the image below). Click on the globe to activate a text field, then enter the [IETF Language tag](https://en.wikipedia.org/wiki/IETF_language_tag) for the language in which the text is written.

![Red arrow points to the globe icon and a text entry field highlighted in blue](/content/contentfiles/item_lang.png)

### Media
Use the *Media* tab to add images, video, or other files.
Using the buttons on the *Add New Media* menu on the right side of the screen, select a media type (Upload, URL, oEmbed, YouTube, or HTML)

![“Add new media” drawer showing the options](/content/contentfiles/items_mediaadd2.png)

- *Upload*: select a file to upload from your computer.
- *URL*: import media via a uri.
- *HTML*: add html content as a media resource for your item.
- *IIIF*: Add an IIIF image via url.
- *oEmbed*: insert an embedded representation of an external URL. Note that this will only work with content from [existing oEmbed implementations](http://oembed.com/#section7) - use the url in your browser’s location bar.
- *YouTube*: add a link to embed a YouTube video. Use the url from your browser’s location bar (with `/watch/` in it) rather than the `youtu.be` link.

You can edit media later by going by editing an item, navigating to the *media* tab, and clicking the edit button (pencil) for a media when editing the item. 

You can delete any media instance from the item's edit page using the delete button (trashcan) on the upper right corner of the media block.

![Image shows a close up of a media item being removed - it is red and has an undo curling arrow at the right end of the block](/content/contentfiles/item_mediablockdelete.png)

If you have more than one media instance for an item, you can reorder them by dragging and drop each media instance block, using the icon of three lines in the upper left corner of the block as the anchor when dragging.

Omeka S uses the topmost media for an item to create thumbnail images for that item on browse and show pages. 

### Item Sets
You can only add items to existing item sets.

From the right-hand menu, click on the owner of an item set, then click the name of the item set to add the item to that set. 

You can also filter item sets using the text entry bar above the list of users.

To remove a connection between an item and item set, click the delete (trash can) button to the right of the item set title.

![item set tab with no item sets assigned](/content/contentfiles/items_itemset.png)

### Thumbnail
By default, Omeka S will use the topmost media to generate a thumbnail for the item. If you want to use a non-media image for the thumbnail for an item you can set it here.

![Thumbnail tab with no asset selected. The tab displays a message about thumbnail creation and a button to "select" an asset](/content/contentfiles/item_thumbnailtab.png)

When you use an asset thumbnail instead of uploading media, the asset thumbnail does not display on the item's public show page. This makes such thumbnails useful for items which have no media but which would benefit from a thumbnail for the browse view, or for items whose media does not render an elegant thumbnail, such as audio or visual files.

The assets you select from and upload as thumbnails in this tab are the same as those created for [site logos](../sites/site_theme/#settings-options). 

To assign an asset as a thumbnail, click on the Select button in the main work area of the tab. This will open a drawer on the right side. 

![Select drawer with upload option and two assets, both of which are images.](/content/contentfiles/item_thumbdrawer.png)

The drawer offers two options: upload a file using your browser, or select from existing assets. To select an existing asset, simply click on it and it will automatically be assigned to the item. 

![Add item open to Thumbnail tab, where an asset which is an image of a quill pen on a scrolled piece of paper is in the main work area. Below it are buttons for Select and Clear](/content/contentfiles/item_thumbnail.png)

To remove an asset which you have assigned as a thumbnail, click the "Clear" button below the image of the asset. To replace it, click select and either choose or upload a new thumbnail asset.

### Visibility
Use the *make public/private* button (eye icon) to set whether the item is visible to the public or only to users of the Omeka S system. 

![make public button showing an eye icon](/content/contentfiles/item_public.png) Public 

![make private button showing an eye icon with a diagonal slash through it](/content/contentfiles/item_private.png)  Private

Note that if an item is private, all the media attached is private, but an item which is public can have attached media which are set to be either public or private.

## Edit an item
Once you have created an item, you can edit it at any time, either by clicking the edit icon (pencil button) or clicking on the item's title and then clicking the Edit button in the upper right-hand corner of the screen.

To cancel out of editing, click the Cancel button in the upper right corner, between the Delete and Save buttons. 

![Detail view of the top row if information and buttons on an item edit view. A red arrow points to the Cancel button, on the far right](/content/contentfiles/items_cancel.png)

Editing options are the same as when creating a new item, with the addition of the ability to add any media which has been saved to an item as a property:

### Media as property 
Once you have created an item and added media to it, you will also have the option to use media *attached to that item* for a property. 

![A blue outline of a rectangle highlights resource options for Items, Item sets, and Media to be used as the input for the element "Description"](/content/contentfiles/items_addmediaresource.png)

To use a media resource for a property, select the media option for the element (1). The drawer which opens will display all media attached to the item. Select the media which you want to use(2); this will switch the drawer to just that media (second image). Click the *Select Resource* button at the bottom of the drawer to complete the process (3).

![Focus on the editing portion of a window for the item "Sense and Sensibility", with the elements Title and Description visible. On the right side of the window, a vertical rectangle (the drawer) is open on the right displaying five media which are attached to the item, including video, images, and text. This image contains steps 1 and 2.](/content/contentfiles/items_mediaresource1.png)

![The same window as before, but now the drawer on the right displays a thumbnail of the media "Sense and Sensibility DVD Trailer" with a dark gray button labeled "select resource" at the bottom of the drawer area. This image contains step 3](/content/contentfiles/items_mediaresource2.png)


## Batch editing

From the browse page of items (admin/item) you can batch edit items, using the dropdown menu on the left near the pagination buttons. You can select multiple items using the checkboxes on the left of each item's row.

![A red arrow points to the dropdown for batch editing and deleting options](/content/contentfiles/items_batch.png)

Batch actions are as follows:  

- Edit selected: edit only the items that are selected on the page
- Edit all: edit all the items returned by a search (default is all items)
- Delete selected: delete only the items that are selected on the page
- Delete all: delete all the items returned by a search (default is all items)

Choose one of these options and then click *Go*.

**Batch editing** items takes you to a new page. The items being edited will display on the right side in a drawer, while the batch edit form gives you the following options:  

- set visibility: a dropdown, select from public or not public.
- set template: a dropdown, select from the installation's resource templates.
- set class: a dropdown, select from classes of the installed vocabularies.
- add to item set: a dropdown, select from item sets on the installation. Add to an additional item set using the *add another item set* button.
- remove from item set: a dropdown, select from item sets on the installation. Remove from an additional item set using the *remove another item set* button.
- clear property values: a dropdown menu with all the properties in all vocabularies, selecting from this will remove any values in that property in the affected items. Clear additional properties using the *Clear another property* button.

![Batch edit items form, with options as described above. Everything is grayscale](/content/contentfiles/items_batchedit.png)

In addition,  you can use the bottoms at the bottom of the batch edit form to add properties to every item:

- add text value
- add resource value
- add URI value  

Selecting any of these will add a block to the form where you can select a property from the installed vocabularies and enter the value for that property.

![Image depicts only the Add text value block of the batch edit form, with a dropdown labeled "select property" above an empty text field](/content/contentfiles/items_beproperty.png)

For the **delete actions**, a drawer will open on the right side of the screen telling you the number of items which will be deleted. Nothing will be deleted unless you click the red *Confirm Delete* button. This action cannot be undone. To opt out of deleting the items, click the X in the upper right corner of the deletion drawer. To confirm delete, check the "Are you sure" checkbox and then click *Confirm Delete*

![Close up of the warning, with the text describing the number of items to be deleted in red.](/content/contentfiles/items_batchdelwarn.png)
