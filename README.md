# OverrideAttributeSet

In Default Magento ver. 2.3.0 have issue in "Attribute Sets"

when we delete any of the "Attribute Sets" It will redirect to the "404 Error Page not found" page.

So, Fix that issue I have create module "Ktpl_OverrideAttributeSet" and Override this controller
Magento\Catalog\Controller\Adminhtml\Product\Set\Delete.php

Changes for fix the issue:
HttpGetActionInterface Instead of HttpPostActionInterface

Done.
