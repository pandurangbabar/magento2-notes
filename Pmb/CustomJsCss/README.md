# Add custom js anc css file using layout file

Sample code used to add custom js and css file in Magento 2 module.
 ```
<page xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" layout="1column" 
    xsi:noNamespaceSchemaLocation="urn:magento:framework:View/Layout/etc/page_configuration.xsd">
    <head>
        <link src="Pmb_CustomJsCss::js/custom.js"/>
        <css src="Pmb_CustomJsCss::css/custom.css" rel="stylesheet" type="text/css"/>
    </head>
    <body>
        <referenceContainer name="content">
            <block class="Pmb\CustomJsCss\Block\CustomJsCss" name="CustomJsCss" 
                template="Pmb_CustomJsCss::customjscss.phtml"/>
        </referenceContainer>
    </body>
</page>
 ```
Feel free to contact me for Magento 2 development help..

* Email - pandurangmbabar5@gamil.com
* Skype - live:pandurang.babar
