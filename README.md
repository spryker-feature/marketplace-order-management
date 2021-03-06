# Spryker Feature: Marketplace Order Management

With the Marketplace Order Management, default orders that contain additional information about the merchants are called Marketplace orders. In turn, every merchant can view and manage only the orders that are related to their items. Such orders are called merchant orders.

## Installation

```
composer require spryker-feature/marketplace-order-management
```

## Recommended feature dependencies
- [spryker-feature/marketplace-merchant](https://github.com/spryker-feature/marketplace-merchant)
- [spryker-feature/order-management](https://github.com/spryker-feature/order-management)
- [spryker-feature/shipment](https://github.com/spryker-feature/shipment)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [CartNoteMerchantPortalGui ^0.1.0](https://github.com/spryker/cart-note-merchant-portal-gui) (MP GUI)
- [CartNoteMerchantSalesOrderGui ^0.1.0](https://github.com/spryker/cart-note-merchant-sales-order-gui) (Connector)
- [MerchantSalesOrderExtension ^0.1.0](https://github.com/spryker/merchant-sales-order-extension) (Extension)
- [ProductOfferSalesRestApi ^0.1.0](https://github.com/spryker/product-offer-sales-rest-api) (Glue)
- [SalesMerchantPortalGui ^0.8.4](https://github.com/spryker/sales-merchant-portal-gui) (MP GUI)
- [SalesMerchantPortalGuiExtension ^0.1.0](https://github.com/spryker/sales-merchant-portal-gui-extension) (Extension)
