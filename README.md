# Spryker Feature: Marketplace Order Management

With the Marketplace Order Management, default orders that contain additional information about the merchants are called Marketplace orders. In turn, every merchant can view and manage only the orders that are related to their items. Such orders are called merchant orders.

## Installation

```
composer require spryker-feature/marketplace-order-management
```

## Recommended feature dependencies
- [spryker-feature/marketplace-merchant](https://github.com/spryker-feature/marketplace-merchant)
- [spryker-feature/order-management](https://github.com/spryker-feature/order-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [MerchantSalesOrderExtension ^1.0.0](https://github.com/spryker/merchant-sales-order-extension) (Extension)
- [MerchantSalesOrderThresholdGui ^1.0.0](https://github.com/spryker/merchant-sales-order-threshold-gui) (Connector)
- [ProductOfferSalesRestApi ^1.0.0](https://github.com/spryker/product-offer-sales-rest-api) (Glue)
- [SalesMerchantPortalGui ^1.9.0](https://github.com/spryker/sales-merchant-portal-gui) (MP GUI)
- [SalesMerchantPortalGuiExtension ^1.0.0](https://github.com/spryker/sales-merchant-portal-gui-extension) (Extension)
