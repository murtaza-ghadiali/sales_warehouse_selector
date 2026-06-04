<div align="center">

<h1>Sales Warehouse Selector</h1>

Quickly select the best warehouse while creating Sales Invoices and Sales Orders in ERPNext.

<br><br>

## Demo Video

![Quick Preview](https://github.com/murtaza-ghadiali/sales_warehouse_selector/blob/main/Readme%20images/warehouse_popup.gif)

<!-- ![image](https://github.com/murtaza-ghadiali/sales_warehouse_selector/blob/main/Readme%20images/image.png) -->

</div>

---

## Introduction

**Sales Warehouse Selector** is a custom ERPNext app designed to improve the Sales Invoice and Sales Order workflow.

By default, ERPNext automatically selects a warehouse when an item is added. In real-world usage, items are often available in multiple warehouses, and users must manually check stock and change the warehouse every time.

This app solves that problem.

When an item is selected in a Sales Invoice or Sales Order, a popup appears showing all warehouses where the item is available along with their stock quantity. The warehouse with the highest stock is clearly marked as **Recommended**, and users can select the desired warehouse with a single click.

The result is a faster, cleaner, and more reliable workflow.

---

## Features

- Compatible with Frappe **v15 and v16**
- Automatically opens a **warehouse selection popup** when an item is selected.
- Lists **all warehouses** where the item is available.
- Shows **available quantity** for each warehouse.
- Highlights the **recommended warehouse** (highest stock).
- One-click **Use** button for each warehouse.
- Popup appears neatly at the **bottom-right** corner.
- Modern, clean UI that matches ERPNext design.
- No ERPNext core changes.
- Upgrade-safe and production-ready.

---

## How It Works

1. User selects an item in the **Sales Invoice or Sales Order Items** table.
2. ERPNext default warehouse is cleared automatically.
3. The app fetches live stock data from the Bin table.
4. A popup appears listing available warehouses and quantities.
5. The recommended warehouse is highlighted.
6. User clicks **Use** on any warehouse.
7. The warehouse field is set instantly for that item row.

---

## Usage

1. Open a **Sales Invoice** or **Sales Order** and add a new item row.
2. Select an item in the **Item Code** field.
3. A popup appears in the bottom-right corner listing all warehouses that have stock for the selected item.
4. Each row shows the **warehouse name** and its **available quantity**. The warehouse with the highest stock is highlighted and marked as **Recommended**.
5. Click **Use** on any warehouse row to apply it to the item line.
6. The popup closes automatically and the warehouse field is updated instantly.

If the item has no stock in any warehouse, a message is shown and no popup appears.

## Contributions and Community

There are many ways you can contribute even if you don't code:

1. You can start by giving a star to this repository!
2. If you find any issues, even if it is a typo, you can [raise an issue](https://github.com/murtaza-ghadiali/sales_warehouse_selector/issues/new) to inform us.

## License

Sales Warehouse Selector is released under the [MIT License.](https://github.com/murtaza-ghadiali/sales_warehouse_selector/blob/main/license.txt)
