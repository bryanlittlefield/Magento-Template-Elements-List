Magento-Template-Elements-List
==============================

Default Template Elements used in Magento


#####Quick Search
---------------------

Reference the Block to the Correct Location

```xml
<reference name="header"> 
<block type="core/template" name="top.search" as="topSearch" template="catalogsearch/form.mini.phtml"/> 
</reference> 
```

Add This to The Desired Location of Your Template
```php
<?php echo $this->getChildHtml('topSearch') ?>
```
