# E.NEXT Product Media

Public product media repository for E.NEXT Bulgaria and shop.enext.bg.

## Purpose

This repository stores optimized product images used by the E.NEXT Bulgaria online store.

Images are prepared by the ENEXT Media Manager and are intended to be accessed through direct public URLs for product imports and website content.

## Image format

- Format: WebP
- Main image: `{SKU}_main.webp`
- Gallery images: `{SKU}_1.webp`, `{SKU}_2.webp`, `{SKU}_3.webp`, etc.
- Existing transparency is preserved during conversion.

## Repository structure

    products/
      p00/
      p01/
      p02/
      ...

    manifests/
    docs/

Product images are grouped by SKU prefix to avoid storing thousands of files in a single directory.

## Example

SKU:

    p008017

Files:

    products/p00/p008017_main.webp
    products/p00/p008017_1.webp
    products/p00/p008017_2.webp

Direct image URL:

    https://raw.githubusercontent.com/ElectroStore/01-enext-product-media/main/products/p00/p008017_main.webp

## Directories

### products

Contains production product images.

### manifests

Contains generated media reports and image indexes.

### docs

Contains documentation about naming conventions, synchronization and media management.

## Important

This repository contains public product media only.

Do not store:

- passwords
- API keys or access tokens
- customer information
- ERP exports containing confidential information
- internal commercial information
- credentials or configuration secrets

## Managed by

ElectroStore / ENEXT Media Manager
