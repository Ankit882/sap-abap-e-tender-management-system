# SAP ABAP – E-Tender Management System

## Overview
This project is an end-to-end E-Tender Management System developed using
SAP ABAP and SAP MM module to automate the procurement lifecycle.

The solution covers Purchase Requisition to Tender creation, Vendor
evaluation, Purchase Order creation, Goods Receipt, Invoice processing,
and Certification clearance with complete audit tracking.

## Business Process Flow
PR → Tender → Vendor Mapping → Bid Evaluation (L1)
→ PO Creation → GR → Invoice → Certification Clearance

## Custom Tables
- ZTENDER_HDR – Tender header data
- ZTENDER_ITEM – Tender line items
- ZTENDER_VENDOR – Vendor participation & bids
- ZTENDER_AUDIT – Audit trail
- ZTENDER_GR – Goods receipt confirmation
- ZTENDER_INVOICE – Invoice records
- ZTENDER_CERT – Certification clearance

## ABAP Programs
- ZPR_TO_TENDER – Create Tender from PR
- ZTENDER_VENDOR_SELECT – Vendor mapping
- ZTENDER_BID_EVAL – Bid evaluation and L1 selection
- ZTENDER_PO_CREATE – PO creation using BAPI_PO_CREATE1
- ZTENDER_GR_CONFIRM – Goods receipt confirmation
- ZTENDER_INVOICE_CREATE – Invoice creation
- ZTENDER_CERT_CLEAR – Compliance certification clearance

## Key Features
- End-to-end procurement automation
- Vendor bid evaluation with ALV reporting
- Purchase Order creation via standard BAPI
- Complete audit logging
- Validation and error handling

## Technologies Used
- SAP ABAP
- SAP MM
- Custom Z Tables
- ALV Reports
- BAPI_PO_CREATE1

## Author
Ankit Raj  
SAP ABAP Developer (Fresher)
