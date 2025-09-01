# Shopify Custom PDP & Product Media Slider

This repository contains custom code for a Shopify store, focusing on the Product Detail Page (PDP) and product media slider functionalities.

## File Structure

### Liquid Files

- **product-media-slider-custom.liquid**  
  Main product media slider section. Displays product images in a carousel using Flickity slider integration.

- **product-details-custom.liquid** *(snippet)*  
  Handles product descriptions, accordion sections, and basic product information.

- **product-image-custom.liquid** *(snippet)*  
  Renders individual product images and supports image zoom/gallery functionality.

- **custom-tabbing-pdp.liquid** *(snippet)*  
  Implements custom tabbing within the PDP accordion for organized product details.

- **related-products.liquid**  
  Displays the related/recommended products section. Loops through products and renders product cards.

- **card-product-related.liquid** *(snippet)*  
  Renders a single related product card. Handles variant selection and quick add-to-cart functionality.

### CSS

- **custom.css**  
  Contains all custom styles for the PDP, slider, related products, tabs, and variant boxes.

## Features

- Custom Flickity product media slider
- Accordion + tabbing system for product details
- Related products section with quick add-to-cart
- Variant selection with open/close toggle
- Smooth animations and overflow handling
- Toggles body class `variant-active` when variant box is open

## Theme Preview
https://quickstart-f5e76180.myshopify.com/products/ocean-blue-shirt
password : nilesh
