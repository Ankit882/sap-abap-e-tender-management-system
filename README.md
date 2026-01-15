# SAP ABAP – E-Tender Management System

## Project Overview
The E-Tender Management System is an end-to-end procurement automation solution
developed using SAP ABAP and MM module.

It covers the complete lifecycle from Purchase Requisition to Tender,
Vendor Evaluation, Purchase Order, Goods Receipt, Invoice, and Certification clearance.

## Business Flow
PR → Tender → Vendor Mapping → Bid Evaluation (L1)
→ PO Creation → GR → Invoice → Certification Clearance

## Custom Tables
- ZTENDER_HDR – Tender Header
- ZTENDER_ITEM – Tender Items
- ZTENDER_VENDOR – Vendor Bids
- ZTENDER_AUDIT – Audit Log
- ZTENDER_GR – Goods Receipt
- ZTENDER_INVOICE – Invoice Data
- ZTENDER_CERT – Compliance Clearance

## ABAP Programs
- ZPR_TO_TENDER – Tender creation from PR
- ZTENDER_VENDOR_SELECT – Vendor mapping
- ZTENDER_BID_EVAL – L1 bid evaluation
- ZTENDER_PO_CREATE – PO creation using BAPI_PO_CREATE1
- ZTENDER_GR_CONFIRM – Goods receipt
- ZTENDER_INVOICE_CREATE – Invoice creation
- ZTENDER_CERT_CLEAR – Certification clearance

## Technologies Used
- SAP ABAP
- SAP MM
- Custom Z Tables
- ALV Reports
- BAPI_PO_CREATE1

## Audit & Validation
- Complete audit trail for every action
- Mandatory field validation
- BAPI return message handling

## Author
Ankit Raj  
SAP ABAP Developer (Fresher)
