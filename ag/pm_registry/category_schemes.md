---
layout: page
title: Category Schemes
description: Define your own custom category schemes that align with your specific business requirements, a prerequisite to defining a category hierarchy.
product: ag
category: learn
sub-nav-class: Registry
weight: 05
type: page
nav-title: Category Schemes
---


## Category Schemes
The **Configure > Registry > Category Schemes** section of the *Management Console* provides the ability to define your own custom category schemes that align with your specific business requirements. The Policy Manager default installation includes a set  of default identifier schemes that include industry specific and custom category schemes. Configuring category schemes is a prerequisite to defining a category hierarchy. This is because category schemes are used to build the category hierarchy.

To view the category schemes summary, in the *Management Console*, go to **Configure > Registry** and then click the **Category Schemes** tab.

<a href="registry_toc.html" class="button secondary">Registry (Home)</a> <a href="categories.html" class="button secondary">Categories</a> <a href="identifier_schemes.html" class="button secondary">Identifier Schemes</a> <a href="schema.html" class="button secondary">Schema</a> <a href="interfaces.html" class="button secondary">Interfaces</a> <a href="tmodels.html" class="button secondary">tModels</a> <a href="subscriptions.html" class="button secondary">Subscriptions</a> <br><br> <a href="replications.html" class="button secondary">Replications</a> <a href="registry_reference.html" class="button secondary">Registry Reference</a>
<h5 class="stamp">Supported Platforms: 7.0 and greater.</h5>


<h3 style="color: gray;">Table of Contents</h3>
<div id="toc-marker"></div>
* [About Category Schemes Types](#about-category-schemes-types)
* [Add Category Scheme](#add-category-scheme)
* [Modify Category Scheme](#modify-category-scheme)
* [Delete Category Scheme](#delete-category-scheme)



## About Category Schemes Types

Categories Schemes (also referred to as Category tModels) are a set of classification codes that represent different aspects of a web service (e.g., products, services, technical specifications). Within UDDI, a categorization tModel is used for structuring category content. This category structure is referred to as an "information taxonomy." Each category scheme contains Key Names and Key Values for each category item.  Key Names are typically defined as a physical description of the category item, and Key Values are internal reference numbers for that category item. The use of categorization tModels enhances the search process by providing a broader scope of choices for targeting information.

The "Registry" provides a Category Hierarchy that includes WSDL Entity Type tModels, UDDI Category tModels, Policy Manager Category tModels, and a series of industry standard category schemes referred to as Business Taxonomy tModels. You can navigate the tiers of the Category Hierarchy by clicking the main hyperlink of a specific category scheme, and continuing with this same approach to perform additional drill-downs.

When you register a service with Policy Manager using the *Create Physical Service* Wizard, a default set of category schemes are added to the service and access points categories section. Category tModels added to the **Registry > Category Schemes** section include tModels that comprise a wsdl:service. Category tModels added to the **Workbench > Services > Access Points** section include tModels that comprise a wsdl:port. This section can also include tModels associated with the wsdl:binding extensions.

The following  category schemes comprise the category hierarchy:

* WSDL Entity Type tModels
* UDDI Category tModels
* Policy Manager Category tModels
* Business Taxonomy tModels

The *Category Schemes Summary* screen allows you to view current category schemes, assign and unassign categories to the baseline of Categories Schemes that can be utilized when performing service management activities.

<a href="#top">back to top</a> 




## Add Category Scheme

The process of adding a category scheme involves defining the "Name" and "Description" of the category scheme and assigning an optional "Key." The category scheme naming convention must conform to one of the Uniform Resource Identifier (URI) Schemes.

1. Go to **Configure > Registry** and click the **Category Schemes** tab.  
The *Category Schemes Summary* screen displays.
2. Click **Add Category Scheme**.  
The *Add Category Scheme* screen displays.
3. Enter the following **Details**:  
  * **Key** - (Optional) Key name that is system-generated by the Registry Manager Subsystem.
  * **Name** - Name of the new category scheme. The naming convention used must conform to any Uniform Resource Identifier Scheme.
  * **Description** - Description of the new category scheme. Will be displayed for the new category definition on the *Category Schemes Summary* screen.
4. Click **Apply**.  
The system saves the new definition and you are returned to the *Category Schemes Summary* screen.
5. (Optional) Click **Cancel** to exit the *Add Category Scheme* screen without saving.

<a href="#top">back to top</a>


## Modify Category Scheme

The process of modifying a category scheme involves selecting the category scheme line item from the *Category Scheme Summary* screen, and clicking **Modify Category Scheme**.  From there, follow steps #3 - #5 as outlined in the [Add Category Scheme](#add-category-scheme) section of this page.

**Notes:**  

* *Updates to the category schema name must conform to one of the Uniform Resource Identifier (URI) Schemes.*
* *Changing the underlying properties of a category scheme after it has been used to associate a category with an entity will "automatically" update the associations.*

<a href="#top">back to top</a>


## Delete Category Scheme

1. Go to **Configure > Registry** and click the **Category Schemes** tab.  
The *Category Schemes Summary* screen displays.
2. Click **Add Category Scheme**.  
The *Add Category Scheme* screen displays.
3. Click on the line item for the category scheme you would like to delete.
4. Click **Delete Category Scheme**.  
The following message is displayed:  
"Are you sure you want to delete this category scheme?"
5. Click **OK** to delete the Category Scheme.  
The Category Scheme is permanently removed from the system.
6. (Optional) Click **Cancel** to cancel the delete operation.

<a href="#top">back to top</a>