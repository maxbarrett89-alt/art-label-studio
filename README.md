# Art Label & Barcode Studio

Turns an art catalog spreadsheet into:

- **Printable label sheets (PDF)** for Avery 5160, 5163, 5167 and 22806, with a Code 128 barcode, QR code, title and price
- **POS-scannable barcodes** (Code 128) that work with any standard USB or Bluetooth barcode scanner
- **Phone-scannable QR codes**
- **Barcode and QR images (ZIP)**, as PNG and SVG files named by SKU
- **Online store import files (CSV)** for Shopify, plus a general format for WooCommerce, Etsy, Big Cartel and similar stores

Everything runs in your browser. Your catalog is never uploaded anywhere. The app remembers it only on the device you load it on.

## How to use

1. In the Art Catalog spreadsheet, download the **Catalog** tab as a **CSV** file.
2. Open the app and load that file on **1 · Load catalog**.
3. Check the pieces you want, then use:
   - **2 · Print labels** to download the PDF, or open it to print. Always print at **100% / Actual size**.
   - **3 · Barcode images** to download a ZIP of barcode and QR images.
   - **4 · Online store file** to download a store import CSV. Shopify products come in as **Draft** by default.
   - **Quick barcode** to make a one-off barcode for any text.

## SKU format

`TYPE-MEDIUM-####`. For example, `WP-PAS-0001` is a work on paper in soft pastel, item 1. The spreadsheet builds the SKU automatically from Item #, Type and Medium.

## Files

- `index.html`: the whole app
- `lib/`: bundled libraries (JsBarcode, qrcode-generator, jsPDF, JSZip), so the app works offline

## Hosting

The app is published with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
