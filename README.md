# 🛒 Featured Collection Grid – BlackBytt 

## Overview  
This custom Shopify section, `featured-collection-grid.liquid`, displays a dynamic product grid from a merchant-selected collection. It highlights products in a **responsive 3-column layout** with hover interactions, badges, and customizable settings. The section is designed for **clean code reuse, scalability, and a polished shopping experience.**  

---

## Features  
- **Dynamic Collection Selection** – Merchant can select any collection via the theme editor.  
- **Responsive Product Grid** –  
  - Desktop: 3 columns  
  - Tablet: 2 columns  
  - Mobile: 1 column  
- **Reusable Product Card Snippet** – Extracted into `product-card-custom.liquid` for maintainability.  
- **Hover Interactions** – Product card scales slightly with a “Quick View” overlay.  
- **Badges** – Improves UX by displaying:  
  - 🏷️ **Sale** – when discounted  
  - ⚡ **Low stock** – when inventory < 5  
  - 🆕 **New** – products added within the last 30 days  
- **Customizable Section Settings:**  
  - Background color picker  
  - Toggle product title visibility  
  - Number of products to display (3, 6, 9, 12)  
  - Padding controls (top/bottom)  
- **Price Formatting** – Correct handling of regular vs. sale prices.  
- **Responsive Design** – Optimized for mobile-first browsing.  

---

## Code Structure  

- `sections/featured-collection-grid.liquid` – Main section logic and schema.  
- `snippets/product-card-custom.liquid` – Reusable snippet for product cards.  
- **Liquid Logic:**  
  - Variant and product price comparisons to determine sale status  
  - Badge conditions for low stock and new products  
  - Conditional rendering for product titles  
- **Scoped CSS:** Styles for layout, hover animations, badges, and responsiveness.  
- **Schema:** Defines all customizable options accessible via the Shopify theme editor.  

---

## How to Use  

1. Add the `featured-collection-grid` section to your theme.  
2. From the Shopify theme editor, insert the **Featured Collection Grid** section into any page.  
3. Select the desired collection.  
4. Configure section options:  
   - Number of products (3, 6, 9, 12)  
   - Toggle product titles  
   - Adjust padding & background color  
5. Save and preview. The collection will render with responsive design, hover states, badges, and add-to-cart functionality.  

---

## Key Considerations  

-⚡**Scalability** – Snippet-based architecture supports reuse and future enhancements.  
-⚡**Merchant Usability** – All key display options are configurable without editing code.  
-⚡**Best Practices** – Clean Liquid syntax, schema-driven customization, and separation of concerns.  
-⚡**User Experience** – Subtle hover animations, clear pricing, and helpful badges create a polished storefront section.  

## Developer

[![GitHub](https://img.shields.io/badge/GitHub-thesakshijaiswal-181717?style=for-the-badge&logo=github)](https://github.com/thesakshijaiswal)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
